---
layout: page
title: Projects
permalink: /projects/
image: /assets/og/site.png
image_alt: "Open-source projects by Prathish Kumar Srinivasan"
---

Open-source work, written outside my day job. Each one started with a problem I could not find a
good answer to.

## Splitstick

**The problem.** When an AI agent does something consequential, the record of it is written by the
operator, who also holds the only key and the only copy. So after a bad outcome, the journal can
be edited and the runtime's own verifier will not notice. We measured that rather than asserting
it: against a real run record from a widely used runtime containing a €2,000,000 transfer, most of
our alterations passed its verifier — including changing the amount to €25, and deleting the
transfer outright.

**What it does.** Records are hash-chained, signed with Ed25519 and countersigned by independent
witnesses, so a later edit, deletion or renumbering contradicts a signature someone else holds.
Anyone with the bytes and a public key can verify it offline. It builds on existing standards
rather than a format of its own — Merkle-tree transparency logs (RFC 6962), canonical JSON
(RFC 8785), timestamping (RFC 3161).

**What it does not do**, and this is the part I would want to read first. It cannot establish that
the record is *complete*. An operator who patches the collector before the fact, so an action is
never captured, defeats it — and no witness discharges that, because a witness attests only to
what it was shown. What changes is the cost: an opportunistic edit after a bad outcome becomes a
premeditated compromise of the build, committed to in advance. That limit is run as an attack in
the test suite rather than described in a paragraph, and the verifier reports `INCONCLUSIVE`
rather than `ok` whenever a check could not be answered.

[github.com/splitstick/splitstick](https://github.com/splitstick/splitstick)

## Isthmus

**The problem.** An AI-agent host runs with broad access to a machine. Most hardening for that is
documentation — a list of settings you are trusted to have applied.

**What it does.** A Go trust kernel that enforces the boundaries instead of describing them, with
behavioural regression contracts so a security property that silently stops holding fails a test.
Built with fuzzing and race testing throughout.

Building it turned up a high-severity flaw in the upstream project itself —
[GHSA-vwj5-j44r-v364](https://github.com/advisories/GHSA-vwj5-j44r-v364), CVSS 7.8 — which I
reported and am credited for.

[github.com/prathish-ks/isthmus](https://github.com/prathish-ks/isthmus)

## Isthmus Scan

**The problem.** Before changing anything, you want to know whether the installation you already
have is hardened, and which controls are missing.

**What it does.** A free, read-only scanner that checks a running installation against the
controls Isthmus enforces, and changes nothing.

[github.com/prathish-ks/isthmus-scan](https://github.com/prathish-ks/isthmus-scan)

## Clawnap

**The problem.** Idle agent containers hold memory you are paying for. Shutting them down costs a
cold start on the next request, so most people leave them running.

**What it does.** A Go daemon that hibernates idle containers and wakes them on their first
request, reclaiming their memory in between through cgroup v2, with signed webhook ingress and
Prometheus metrics. In the reference setup that held 100 healthy cells on a 16 GB host.

[github.com/prathish-ks/clawnap](https://github.com/prathish-ks/clawnap)
