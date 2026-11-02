---
layout: post
title: "Learn the migration, not the platform"
subtitle: "A$485 million of Commonwealth VMware contracts expire across 2027 and 2028. Four alternatives all end the cost. What separates them is whether anyone can be found to do the work."
date: 2026-11-02
slug: learn-the-migration
image: /assets/og/learn-the-migration.png
image_alt: "Learn the migration, not the platform. A$485m of Commonwealth VMware contracts expiring 2027-2028, four alternatives ending the licence cost, three bringing the tools to move."
description: "Nineteen Commonwealth VMware contracts worth A$485m expire across 2027 and 2028. The destination platforms are commoditised; the capacity to move is not. What that means for infrastructure skills."
---

If your work touches virtualisation and you are weighing what to learn next, most of the advice
going round amounts to "learn the new thing". There is a published calendar that says something
more specific than that, and what it points to is not the obvious answer.

Nineteen Commonwealth contracts with VMware, worth A$485.3 million, expire across 2027 and 2028.
Broadcom, which bought VMware, has repriced it, and those buyers are weighing whether to renew or
leave. The usual question is *which platform do we move to*. Having gone through the register and
the alternatives, I think that is the wrong question — and that the answer tells you which skills
are worth your evenings.

These are Commonwealth contracts because those are the ones published. The same repricing reaches
banks, insurers and large private employers, whose contracts are not public — so what follows is
the part of the market that can be counted, not the whole of it. The skills question does not
change with the sector.

*If this is not your field: virtualisation software lets one physical server run many separate
computers. VMware has been the default for twenty years, so a large organisation may run
thousands of systems on it. Leaving means moving every one of them.*

Everything here is from AusTender — the Commonwealth's public register of government contracts —
plus vendor documentation and job counts taken on a stated day. Method and full tables at the
foot.

## When the work lands

<figure>
  <svg viewBox="0 0 640 162" role="img" aria-label="The deadline is 2028. The hiring is 2027.. 2027: A$106.0m · 6. 2028: A$379.3m · 13.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">The deadline is 2028. The hiring is 2027.</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Commonwealth VMware contracts by year of expiry</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">2027</text>
  <rect x="190" y="58" width="83.8" height="17" rx="4" fill="var(--s1)"/>
  <text x="282.8" y="71" font-size="12.5" font-weight="600" fill="var(--text)">A$106.0m · 6</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">2028</text>
  <rect x="190" y="92" width="300.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="499.0" y="105" font-size="12.5" font-weight="600" fill="var(--text)">A$379.3m · 13</text>
  <text x="0" y="150" font-size="11.5" fill="var(--muted)">19 contracts, 11 agencies. Migration hiring precedes cutover, so it precedes these dates.</text>
  </svg>
  <figcaption>Published contract value and count by year of expiry. AusTender notices, read 2 November 2026.</figcaption>
</figure>

The largest is the Department of Defence: A$178.1 million, to 11 December 2028. Defence signed it
in December 2025 and, ten months later, told its groups to move off VMware ahead of a licence
bill reported to double — [reported by iTnews on 30 October
2026](https://www.itnews.com.au/news/defence-mandates-move-off-vmware-629929). Not a
contradiction: the contract is the runway.

So this is not a 2026 story. It is a 2027 story about securing people, with a 2028 deadline.

## Four alternatives, and one real difference

Every credible alternative ends the VMware subscription rather than renegotiating it, and each
does it the same way: the software either comes bundled with something the organisation already
buys, or costs nothing. Nutanix bundles it. Microsoft includes it in a Windows Server licence
many large organisations already hold. Proxmox is open source and free. Red Hat includes it in an
OpenShift subscription.

On cost, then, these are close to interchangeable — and each can be learned hands-on in weeks.
That part is commoditised.

<figure>
  <svg viewBox="0 0 640 250" role="img" aria-label="All four remove the licence cost. Only three bring the move with them.. Nutanix: Licence cost ends yes, Tools to move across yes. Red Hat: Licence cost ends yes, Tools to move across yes. Proxmox: Licence cost ends yes, Tools to move across yes. Microsoft Hyper-V: Licence cost ends yes, Tools to move across no.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">All four remove the licence cost. Only three bring the move with them.</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">What each alternative includes, from its own published documentation</text>
  <text x="250" y="66" font-size="11.5" font-weight="600" fill="var(--muted)">Licence cost ends</text>
  <text x="420" y="66" font-size="11.5" font-weight="600" fill="var(--muted)">Tools to move across</text>
  <text x="0" y="97" font-size="12.5" fill="var(--text)">Nutanix</text>
  <circle cx="257" cy="92" r="7" fill="var(--s1)"/>
  <text x="272" y="97" font-size="12" fill="var(--text)">yes</text>
  <circle cx="427" cy="92" r="7" fill="var(--s1)"/>
  <text x="442" y="97" font-size="12" fill="var(--text)">yes</text>
  <line x1="0" y1="108" x2="600" y2="108" stroke="var(--line)" stroke-width="1"/>
  <text x="0" y="131" font-size="12.5" fill="var(--text)">Red Hat</text>
  <circle cx="257" cy="126" r="7" fill="var(--s1)"/>
  <text x="272" y="131" font-size="12" fill="var(--text)">yes</text>
  <circle cx="427" cy="126" r="7" fill="var(--s1)"/>
  <text x="442" y="131" font-size="12" fill="var(--text)">yes</text>
  <line x1="0" y1="142" x2="600" y2="142" stroke="var(--line)" stroke-width="1"/>
  <text x="0" y="165" font-size="12.5" fill="var(--text)">Proxmox</text>
  <circle cx="257" cy="160" r="7" fill="var(--s1)"/>
  <text x="272" y="165" font-size="12" fill="var(--text)">yes</text>
  <circle cx="427" cy="160" r="7" fill="var(--s1)"/>
  <text x="442" y="165" font-size="12" fill="var(--text)">yes</text>
  <line x1="0" y1="176" x2="600" y2="176" stroke="var(--line)" stroke-width="1"/>
  <text x="0" y="199" font-size="12.5" fill="var(--text)">Microsoft Hyper-V</text>
  <circle cx="257" cy="194" r="7" fill="var(--s1)"/>
  <text x="272" y="199" font-size="12" fill="var(--text)">yes</text>
  <circle cx="427" cy="194" r="7" fill="none" stroke="var(--s2)" stroke-width="2"/>
  <text x="442" y="199" font-size="12" font-weight="600" fill="var(--s2)">no</text>
  <line x1="0" y1="210" x2="600" y2="210" stroke="var(--line)" stroke-width="1"/>
  <text x="0" y="240" font-size="11.5" fill="var(--muted)">Read from vendor documentation. Nothing trialled or benchmarked.</text>
  </svg>
  <figcaption>Whether the licence cost ends, and whether the vendor supplies tools to move existing systems across.</figcaption>
</figure>

What actually separates them is whether the vendor supplies the tools to move existing systems
across. Nutanix and Red Hat both ship purpose-built ones. Proxmox has a built-in importer.
Microsoft has none of its own, and the job depends on third-party tools.

That gap is the difference between a decision and a programme. At the scale of a Defence estate
it means moving every system, rebuilding backup and recovery around them, re-certifying secure
environments, retraining operators, and running old and new side by side until the switchover is
safe. None of that is bought in a licence. It is bought in people.

## Which is why the hiring figures matter

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
  <figcaption>Exact-phrase searches on Seek, Australia-wide, 2 November 2026. A measurement on one day, not a standing fact.</figcaption>
</figure>

The obvious reading is that VMware is in decline and its skills a liability. Read against the
contract calendar, it says close to the opposite.

**There are 239 VMware roles because leaving VMware requires knowing VMware.** You cannot work
out what depends on what, plan a safe switchover, or confirm a moved system still behaves, on a
platform you do not understand. That expertise is the qualification for this work, not the thing
to move on from.

And there are 14 Nutanix roles because the demand has not arrived yet — which is different from
it not coming.

That figure is worth handling carefully, because it supports two readings that point opposite
ways and the count alone cannot separate them. High VMware demand is consistent with
organisations **staying put**. It is equally consistent with organisations **leaving**, because a
move needs more of that expertise while it runs, not less. Anyone citing it owes you the reading
they mean.

## So, what would I learn

The platforms are commoditised and each can be learned in weeks, so a certificate in one is worth
less than it looks on a job board. What is scarce is the work of moving: the tools that carry
systems across, working out what depends on what, planning the switchover and the way back.

**Learn the moving tools rather than a platform badge.** They are the part every one of these
programmes needs, whichever destination wins, and the part that transfers when the next vendor
reprices something.

**Keep your VMware depth, and say so.** On a CV, "moved N systems across, including the ones that
would not go" beats any certificate. The failures are where the judgement shows, and the people
reading your CV know it.

**Add one alternative, picked from what the organisations you want to work for already run.** On
the figures above, Hyper-V is advertised about seven times as often as Nutanix, so for most
readers it will be the one within reach — and it is also the one with no tools of its own, which
is where the gap is widest.

**Spend nothing yet.** Hyper-V comes with Windows, Proxmox is free, Nutanix has a free edition.
Build something small on hardware you own and move a real system onto it. A certificate is worth
something after you can do the thing.

Timing matters more than the choice. Hiring comes before the work, so 2027 is the window — about
a year to become credible, which is enough but not generous.

And if you are the one deciding a renewal rather than preparing for one, the same finding points
the other way round: the threat to leave is only as good as your ability to carry it out, and
that is a question about people and months rather than about products. An alternative nobody can
staff is a weaker card across the table than it looks on a slide. Worth knowing too that the
cheapest responses are not moves at all — an entitlement audit, or third-party support, can cut
the bill without touching the platform.

## What would make this wrong

**Broadcom could discount materially on renewals in this region.** If the price pressure goes, so
does the wave.

**The work might not be hired locally.** If it goes to offshore delivery centres and global
integrators rather than Australian hiring, the role counts stay flat however much money expires.
I think this is the likelier of the two, and it is why I would weight the moving skills — which
travel — over platform badges, which do not.

**And the honest limit.** A contract register records what was bought and when, never intent.
Nothing here establishes that any agency will leave — only what each committed to, and until
when.

## Forecast

A prediction that cannot be settled objectively is not worth making, so here is the rule
alongside the call.

> Advertised Australian roles naming **Nutanix or Proxmox**, as a share of advertised roles naming
> **VMware**, will exceed **15%** — up from **9.6%** at this measurement.
> **Confidence: 40%. Resolves: 29 July 2028**, by re-running the same four searches on the same
> job board and publishing the counts.

The resolution date is arithmetic, not preference: the last 2027 contract expires 29 July 2027,
and a twelve-month window for hiring to become visible runs to 29 July 2028. Hiring for the
larger 2028 group comes before switchovers ending that December, so it should be visible by
then.

Below even odds deliberately: I think this work is more likely to be delivered by teams Australia
does not advertise for. Forty rather than forty-five because the base moved — 15% from 9.6% is a
56% relative rise, where from October's 10.9% it was 38%.

## One thing I cannot answer

If the alternatives really are interchangeable on cost, and the capacity to move really is the
scarce thing, then the rational move for a large buyer is to secure that capacity rather than to
choose a platform. I can find no public evidence of anyone doing that — no panel for it, no
framework, no advertised programme. Either buyers do not see it that way, or they are doing it
through channels that leave no public record. I would like to know which.

*[Sources, scope and the full tables](/2026/11/learn-the-migration/method/) are set out
separately, so this piece can be read without them and checked with them.*

---

*These are my personal views, based on the public evidence cited. They are not the views of my
employer, and no part of this analysis uses non-public information.*
