---
layout: post
title: "Learn the migration, not the platform"
subtitle: "A$485 million of Commonwealth VMware contracts expire across 2027 and 2028. Choosing a destination is the easy part — and that is what decides which skills are worth learning."
date: 2026-11-02
slug: learn-the-migration
image: /assets/og/learn-the-migration.png
image_alt: "Learn the migration, not the platform. A$485m of Commonwealth VMware contracts expiring 2027-2028 across 19 contracts and 11 agencies; four alternatives all ending the licence cost. The finding: the platform is not the hard part, the people are."
description: "Nineteen Commonwealth VMware contracts worth A$485m expire across 2027 and 2028. The alternatives differ in cost and tooling, but the scarce thing is the capacity to move a large estate safely. What contract records, vendor documentation and Australian job advertisements show."
---

If your work touches virtualisation and you are weighing what to learn next, most of the advice
going round amounts to "learn the new thing". There is a published calendar that says something
more specific.

Nineteen Commonwealth contracts with VMware, worth A$485.3 million, expire across 2027 and 2028.
Broadcom, which bought VMware, has repriced it, and those buyers are weighing whether to renew or
leave. The obvious advice is to learn whichever platform they move to. Having gone through the
register, the alternatives, and what one of these programmes looks like from inside, I think that
is the wrong lesson.

These are Commonwealth contracts because those are the ones published. The same repricing reaches
banks, insurers and large private employers, whose contracts are not public — so what follows is
the part of the market that can be counted, not the whole of it. The skills question does not
change with the sector.

*If this is not your field: virtualisation software lets one physical server run many separate
computers. VMware has been the default for twenty years, so a large organisation may run
thousands of systems on it. Leaving means moving every one of them.*

## When the contracts land

<figure>
  <svg viewBox="0 0 640 162" role="img" aria-label="Most of the value expires in 2028. 2027: A$106.0m · 6. 2028: A$379.3m · 13.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">Most of the value expires in 2028</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Published value of Commonwealth VMware contracts, by year of expiry</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">2027</text>
  <rect x="190" y="58" width="83.8" height="17" rx="4" fill="var(--s1)"/>
  <text x="282.8" y="71" font-size="12.5" font-weight="600" fill="var(--text)">A$106.0m · 6</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">2028</text>
  <rect x="190" y="92" width="300.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="499.0" y="105" font-size="12.5" font-weight="600" fill="var(--text)">A$379.3m · 13</text>
  <text x="0" y="150" font-size="11.5" fill="var(--muted)">19 contracts, 11 agencies. Contract end dates, not a schedule of work.</text>
  </svg>
  <div class="chart-mobile" aria-hidden="true">
    <p class="cm-title">Most of the value expires in 2028</p>
    <p class="cm-sub">Published value of Commonwealth VMware contracts, by year of expiry</p>
    <div class="cm-row"><span class="cm-name">2027</span><span class="cm-val">A$106.0m · 6</span></div>
    <div class="cm-bar"><i style="width:27.9%"></i></div>
    <div class="cm-row"><span class="cm-name">2028</span><span class="cm-val">A$379.3m · 13</span></div>
    <div class="cm-bar"><i style="width:100.0%"></i></div>
    <p class="cm-note">19 contracts, 11 agencies. Contract end dates, not a schedule of work.</p>
  </div>
  <figcaption>Published contract value and count by year of expiry. AusTender notices, read 2 November 2026.</figcaption>
</figure>

The largest is the Department of Defence: A$178.1 million, to 11 December 2028. The sequence
there is not the one you would guess.

Defence was reportedly told to reduce its VMware use under a "mandate" issued around September
2025 — and then, months later, signed the A$178.1 million renewal. [iTnews reported this on 30
October 2026](https://www.itnews.com.au/news/defence-mandates-move-off-vmware-629929), noting the
formality of the mandate is unclear and that Defence declined to comment on its scope. Cost is
understood not to be the only driver; sovereignty is also a concern.

If the reported mandate reflects Defence's direction, the intention to reduce VMware use came
before the renewal rather than after it. Read that way the contract is runway rather than
reversal — you keep paying for what you are still running while you move off it — and it says
something about pace: a department that had decided to move signed for three more years.

## The platform is not the hard part

Every credible alternative ends the VMware subscription. Nutanix bundles the software with its
own platform licence, Microsoft includes it in Windows Server licensing, Proxmox is free to run,
Red Hat includes it in an OpenShift subscription.

They are not interchangeable. Each replaces a VMware bill with a different bill, and the storage,
networking, backup and support requirements differ with it. Ending one subscription is not the
same as ending the cost.

All four also ship first-party tools for moving existing systems across — Nutanix Move, Red Hat's
Migration Toolkit, Proxmox's importer, and from Microsoft both a long-standing capability in
System Center and a free Windows Admin Center extension now in public preview. They differ in
maturity, batch size, and whether the tool itself costs anything. [The full comparison is
here](/2026/11/learn-the-migration/method/).

What none of them does is make the move easy. From the reporting on Defence, by someone inside
it:

> "They've spent their entire careers with one style of design and we've now made them shift and
> it's been quite a challenge. [It's been about] the training, the experience and making people
> understand why we're going through this change — [that] it's not change for change's sake."

That is the constraint as described from inside the largest of these contracts. Not the licence,
not the tooling. The same report notes why: the software is embedded
in IT operations, and for many administrators it is an ecosystem they know better than any
alternative.

At that scale, moving means working out what depends on what, rebuilding backup and recovery
around the new platform, re-certifying secure environments, retraining operators, and running old
and new side by side until the switchover is safe. A conversion tool moves a system. It does not
tell you what order to move things in, what will break, or how to get back if it does.

None of that is bought in a licence. It is bought in people.

## Which is why the hiring figures read oddly

<figure>
  <svg viewBox="0 0 640 230" role="img" aria-label="The alternatives are barely advertised yet. VMware: 239. Hyper-V: 102. Nutanix: 14. Proxmox: 9.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">The alternatives are barely advertised yet</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Advertised Australian roles naming each platform, 2 November 2026</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">VMware</text>
  <rect x="190" y="58" width="300.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="499.0" y="71" font-size="12.5" font-weight="600" fill="var(--text)">239</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">Hyper-V</text>
  <rect x="190" y="92" width="128.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="327.0" y="105" font-size="12.5" font-weight="600" fill="var(--text)">102</text>
  <text x="178" y="138" font-size="12.5" text-anchor="end" fill="var(--text)">Nutanix</text>
  <rect x="190" y="126" width="17.6" height="17" rx="4" fill="var(--s1)"/>
  <text x="216.6" y="139" font-size="12.5" font-weight="600" fill="var(--text)">14</text>
  <text x="178" y="172" font-size="12.5" text-anchor="end" fill="var(--text)">Proxmox</text>
  <rect x="190" y="160" width="11.3" height="17" rx="4" fill="var(--s1)"/>
  <text x="210.3" y="173" font-size="12.5" font-weight="600" fill="var(--text)">9</text>
  <text x="0" y="218" font-size="11.5" fill="var(--muted)">Nutanix plus Proxmox = 9.6% of VMware roles. The forecast below turns on that ratio.</text>
  </svg>
  <div class="chart-mobile" aria-hidden="true">
    <p class="cm-title">The alternatives are barely advertised yet</p>
    <p class="cm-sub">Advertised Australian roles naming each platform, 2 November 2026</p>
    <div class="cm-row"><span class="cm-name">VMware</span><span class="cm-val">239</span></div>
    <div class="cm-bar"><i style="width:100.0%"></i></div>
    <div class="cm-row"><span class="cm-name">Hyper-V</span><span class="cm-val">102</span></div>
    <div class="cm-bar"><i style="width:42.7%"></i></div>
    <div class="cm-row"><span class="cm-name">Nutanix</span><span class="cm-val">14</span></div>
    <div class="cm-bar"><i style="width:5.9%"></i></div>
    <div class="cm-row"><span class="cm-name">Proxmox</span><span class="cm-val">9</span></div>
    <div class="cm-bar"><i style="width:3.8%"></i></div>
    <p class="cm-note">Nutanix plus Proxmox = 9.6% of VMware roles. The forecast below turns on that ratio.</p>
  </div>
  <figcaption>Exact-phrase searches on Seek, Australia-wide, 2 November 2026. A measurement on one day, not a standing fact.</figcaption>
</figure>

The obvious reading is that VMware is in decline and its skills are a liability. Against the
contract calendar, that is at best incomplete.

VMware expertise stays relevant whether an organisation renews or leaves. A large installed base
needs people to run it, and a move needs people who understand what is being replaced. The counts
cannot tell you how much of the demand is which, and anyone citing them owes you the reading they
mean. What they do show is that the alternatives are barely advertised yet — which is different
from their never being.

## So, what would I learn

You can get hands-on with each alternative in weeks, so a certificate in one is worth less than
it looks — though being trusted with production takes considerably longer. What is scarce is the
ability to move a large estate safely: a different skill, and a slower one to acquire.

**Learn migration engineering rather than a platform badge.** The work listed above — sequencing,
dependencies, switchover and the way back — is what every one of these programmes needs,
whichever destination wins. Conversion tooling is one part of it, not the whole.

**Keep your VMware depth, and say so.** On a CV, "moved N systems across, including the ones that
would not go" beats any certificate. The failures are where the judgement shows, and the people
reading your CV know it.

**Add one alternative, picked from what the organisations you want to work for already run.** On
the figures above, Hyper-V is advertised about seven times as often as Nutanix, so for most
readers it will be the one within reach.

**Spend nothing yet.** Hyper-V ships in Windows Pro and Windows Server, Proxmox is free, Nutanix has a free edition.
Build something small on hardware you own and move a real system onto it — then move one that
does not go cleanly. A certificate is worth something after you can do the thing.

And if you are deciding a renewal rather than preparing for one, the same finding points the
other way: the threat to leave is only as good as your ability to carry it out, which is a
question about people and months rather than products. Worth knowing too that the cheapest
responses are not moves at all — an entitlement audit, or third-party support, can cut the bill
without touching the platform.

## What would make this wrong

**Broadcom could discount materially on renewals in this region.** If the price pressure goes, so
does the wave.

**The work might not be hired locally.** If it goes to offshore delivery centres and global
integrators rather than Australian hiring, the role counts stay flat however much money expires.
I think this is the likelier of the two, and it is why I would weight migration skills — which
travel — over platform badges, which do not.

**And the honest limit.** A contract register records what was bought and when, never intent.
Nothing here establishes that any agency will leave — only what each committed to, and until
when. The Defence reporting rests on unnamed sources and a department that declined to comment.

## Forecast

A prediction that cannot be settled objectively is not worth making, so here is the rule
alongside the call.

> Advertised Australian roles naming **Nutanix or Proxmox**, as a share of advertised roles naming
> **VMware**, will exceed **15%** — up from **9.6%** at this measurement.
> **Confidence: 40%. Resolves: 29 July 2028**, on a single measurement taken that day by
> re-running the same four exact-phrase searches on the same job board, with the counts and the
> search URLs published alongside the result.

The resolution date is arithmetic: the last 2027 contract expires 29 July 2027, and a
twelve-month window for hiring to become visible runs to 29 July 2028.

Below even odds deliberately: I think this work is more likely to be delivered by teams Australia
does not advertise for. It is also a narrow instrument — one job board's advertised counts, not
migration activity. If that board materially changes its search coverage, query handling or how
it counts results before 2028, I will document the change and may record the forecast as
inconclusive rather than settle it on a measurement that is no longer comparable.

## One thing I cannot answer

If the alternatives all end the licence cost, and the capacity to move is the scarce thing, then
the rational move for a large buyer is to secure that capacity rather than to choose a platform.
In the records I searched I did not find it — no panel, no framework, no advertised programme. Either buyers do not see it that way, or they are doing it through channels that leave
no public record. I would like to know which.

*[Sources, scope and the full tables](/2026/11/learn-the-migration/method/) are set out
separately, so this piece can be read without them and checked with them.*

---

*These are my personal views, based on the public evidence cited. They are not the views of my
employer, and no part of this analysis uses non-public information.*
