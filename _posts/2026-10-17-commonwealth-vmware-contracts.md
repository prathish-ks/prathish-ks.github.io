---
layout: post
title: "Commonwealth VMware contracts: A$485 million expiring across 2027 and 2028"
subtitle: "Eleven agencies, when each contract comes up, and what the evidence says about migration"
date: 2026-10-17
slug: commonwealth-vmware-contracts
---

Eleven Australian Commonwealth agencies have roughly **A$485 million** in published contracts
naming VMware as supplier, expiring across 2027 and 2028. All were signed after Broadcom
completed its acquisition, and 79% by value was signed in 2025 or later.

The number matters less than what happens next. Each of those agencies will face the same
decision: renew, move some workloads, or move the lot. I wanted to know what the public record
could tell a buyer approaching that choice — and, just as usefully, what it couldn't.

Three things came out of it. Contract consolidation makes published values badly misleading if
you compare them the obvious way. The expiries cluster hard in 2028. And the Australian hiring
market shows far more demand for VMware skills than for any alternative — which says something
about how practical a migration threat is as a negotiating position, though less than you might
first think.

## When the contracts expire

<figure>
  <svg viewBox="0 0 640 214" role="img" aria-label="Four-fifths of the value expires in 2028. 2027 H1: A$104m  (5). 2027 H2: A$1.5m  (1). 2028 H1: A$184m  (6). 2028 H2: A$195m  (7).">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">Four-fifths of the value expires in 2028</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Commonwealth VMware contract value by expiry half-year</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">2027 H1</text>
  <rect x="190" y="58" width="203.1" height="17" rx="4" fill="var(--s1)"/>
  <text x="402.1" y="71" font-size="12.5" font-weight="600" fill="var(--text)">A$104m  (5)</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">2027 H2</text>
  <rect x="190" y="92" width="2.9" height="17" rx="4" fill="var(--s1)"/>
  <text x="201.9" y="105" font-size="12.5" font-weight="600" fill="var(--text)">A$1.5m  (1)</text>
  <text x="178" y="138" font-size="12.5" text-anchor="end" fill="var(--text)">2028 H1</text>
  <rect x="190" y="126" width="358.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="557.0" y="139" font-size="12.5" font-weight="600" fill="var(--text)">A$184m  (6)</text>
  <text x="178" y="172" font-size="12.5" text-anchor="end" fill="var(--text)">2028 H2</text>
  <rect x="190" y="160" width="380.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="579.0" y="173" font-size="12.5" font-weight="600" fill="var(--text)">A$195m  (7)</text>
  <text x="0" y="208" font-size="11.5" fill="var(--muted)">Contract count in brackets. Source: AusTender.</text>
  </svg>
  <figcaption>Source: AusTender contract notices, end dates 2027–2028, value A$500,000 and above.</figcaption>
</figure>

Nearly four-fifths of the value sits in 2028. For a vendor, that is when this market moves. For
a buyer, it means a substantial number of organisations will reach the same decision at roughly
the same time — which affects how much attention any one of them can expect to command.

## What has happened to annualised contracted value

Comparing individual contracts across periods produces misleading results, because the structure
of these agreements has changed. The meaningful comparison is **total annualised contracted value per
agency** — every contract an agency held, normalised by duration.

<figure>
  <svg viewBox="0 0 640 224" role="img" aria-label="The largest buyer's contracted value is slightly lower. Dept of Defence: 0.9x. Services Australia: 2.5x. Foreign Affairs &amp; Trade: 2.0x. Combined, these three: 1.2x.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">The largest buyer's contracted value is slightly lower</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Change in annualised VMware contracted value, earlier contracts to current</text>
  <line x1="332.3" y1="50" x2="332.3" y2="190" stroke="var(--muted)" stroke-width="1.5" stroke-dasharray="3 3"/>
  <text x="332.3" y="206" font-size="11.5" text-anchor="middle" fill="var(--muted)">no change (1.0x)</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">Dept of Defence</text>
  <rect x="318.1" y="58" width="14.2" height="17" rx="4" fill="var(--s2)"/>
  <text x="309.1" y="71" font-size="12.5" font-weight="600" text-anchor="end" fill="var(--text)">0.9x</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">Services Australia</text>
  <rect x="332.3" y="92" width="213.5" height="17" rx="4" fill="var(--s1)"/>
  <text x="554.8" y="105" font-size="12.5" font-weight="600" text-anchor="start" fill="var(--text)">2.5x</text>
  <text x="178" y="138" font-size="12.5" text-anchor="end" fill="var(--text)">Foreign Affairs &amp; Trade</text>
  <rect x="332.3" y="126" width="142.3" height="17" rx="4" fill="var(--s1)"/>
  <text x="483.6" y="139" font-size="12.5" font-weight="600" text-anchor="start" fill="var(--text)">2.0x</text>
  <text x="178" y="172" font-size="12.5" text-anchor="end" fill="var(--text)">Combined, these three</text>
  <rect x="332.3" y="160" width="28.5" height="17" rx="4" fill="var(--s1)"/>
  <text x="369.8" y="173" font-size="12.5" font-weight="600" text-anchor="start" fill="var(--text)">1.2x</text>
  <text x="0" y="218" font-size="11.5" fill="var(--muted)">Employment &amp; Workplace Relations excluded: earlier base of A$229k is too small to carry meaning.</text>
  </svg>
  <figcaption>Annualised = contract value ÷ duration × 365.25, summed across every contract an agency held in each period.</figcaption>
</figure>

**This is a four-agency matched cohort, not a Commonwealth-wide figure.** Only four of the eleven
agencies have earlier VMware contracts visible in the data — they account for 70% of current
value, but the remaining seven are simply absent from the comparison. The Employment and
Workplace Relations ratio also rests on an earlier base of A$229,000 across two contracts, too
small to carry weight.

Within that cohort, annualised contracted value rose about 20%, and the largest buyer sits
slightly below where it was. **It does not support a conclusion about Commonwealth VMware cost
inflation generally**, and I would not use it that way.

## Why single-contract comparisons mislead

Defence illustrates the problem, and the mechanism is worth understanding because anyone
benchmarking a renewal will encounter it.

**Twenty-seven Defence VMware contracts ended on 11 December 2025**, with a combined published
value of A$95.9 million. **One contract worth A$178 million began on 12 December 2025**, running
three years.

Set against Defence's largest earlier contract — A$14.07 million — the new agreement looks like a
twelvefold increase. Set against all 47 of the contracts it replaced, annualised contracted value was slightly
lower.

The consolidation is the story, not the headline number. Whether it reflects Broadcom's packaging,
Defence's own procurement strategy, or both, is not determinable from published data.

**If you are benchmarking your own position, compare total annualised contracted value across all
agreements, not contract against contract.** The published values invite the wrong comparison.

## The migration question

Renewal under high switching costs is not evidence of satisfaction. Migrating a production
virtualisation estate is difficult, carries real risk, and competes for people who are already
committed elsewhere. Renewing in those circumstances is frequently the rational decision.

It is, however, testable — because migrations require people well before they require contracts.
Advertised roles in Australia, exact-phrase, as at 14 October 2026:

<figure>
  <svg viewBox="0 0 640 214" role="img" aria-label="Microsoft is the larger alternative in Australia. VMware: 239. Hyper-V: 117. Nutanix: 14. Proxmox: 12.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">Microsoft is the larger alternative in Australia</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Advertised roles naming each platform, Australia, October 2026</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">VMware</text>
  <rect x="190" y="58" width="380.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="579.0" y="71" font-size="12.5" font-weight="600" fill="var(--text)">239</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">Hyper-V</text>
  <rect x="190" y="92" width="186.0" height="17" rx="4" fill="var(--s1)"/>
  <text x="385.0" y="105" font-size="12.5" font-weight="600" fill="var(--text)">117</text>
  <text x="178" y="138" font-size="12.5" text-anchor="end" fill="var(--text)">Nutanix</text>
  <rect x="190" y="126" width="22.3" height="17" rx="4" fill="var(--s1)"/>
  <text x="221.3" y="139" font-size="12.5" font-weight="600" fill="var(--text)">14</text>
  <text x="178" y="172" font-size="12.5" text-anchor="end" fill="var(--text)">Proxmox</text>
  <rect x="190" y="160" width="19.1" height="17" rx="4" fill="var(--s1)"/>
  <text x="218.1" y="173" font-size="12.5" font-weight="600" fill="var(--text)">12</text>
  <text x="0" y="208" font-size="11.5" fill="var(--muted)">Exact-phrase search, Seek, Australia-wide.</text>
  </svg>
  <figcaption>Exact-phrase searches on Seek, Australia-wide, 14 October 2026.</figcaption>
</figure>

VMware exceeds Nutanix by seventeen to one, and the VMware roles being advertised are
predominantly administrators for VMware Cloud Foundation — positions that support continued
operation rather than an exit.

**That is weaker evidence than it first appears, and worth being careful with.** I found no
advertisements naming a migration programme, but recruitment is an indirect signal. A migration
may be delivered by a systems integrator, an existing partner, an offshore team or redeployed
internal staff, none of which produce a public advertisement. Vacancies are also often written
as "infrastructure modernisation" without naming a destination platform.

So the honest reading is narrower than "nobody is migrating": Australian advertisements show
substantially more demand for VMware skills than for the alternatives, which is consistent with
continued VMware dependence. It does not establish whether migration programmes are under way.

## Microsoft is the larger alternative, by a factor of eight

The most practically significant figure above is Hyper-V at 117 roles, against 14 for Nutanix and 12 for Proxmox. Most migration commentary treats Nutanix as the default destination. The
Australian skills market does not reflect that.

This matters more than platform comparison for anyone planning an exit. A migration needs people
who have done one before, and in this market those people are considerably more likely to have
Hyper-V experience. Twenty-six advertised roles across Nutanix and Proxmox combined is a narrow
base from which to staff a multi-year programme.

That is an observation about skills availability, not a recommendation. Which platform suits a
given estate depends on workloads, existing licensing position and cloud strategy — none of which
this data addresses.

## Is Australia behind?

The hiring ratio only means something against a benchmark, so I measured the same terms in two
other markets.

<figure>
  <svg viewBox="0 0 640 180" role="img" aria-label="Australia lags both comparison markets. Australia  (Seek): 10.9%. United Kingdom  (Reed): 18.9%. United States  (Dice): 17.3%.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">Australia lags both comparison markets</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">Nutanix + Proxmox roles as a share of VMware roles</text>
  <text x="178" y="70" font-size="12.5" text-anchor="end" fill="var(--text)">Australia  (Seek)</text>
  <rect x="190" y="58" width="188.3" height="17" rx="4" fill="var(--s2)"/>
  <text x="387.3" y="71" font-size="12.5" font-weight="600" fill="var(--text)">10.9%</text>
  <text x="178" y="104" font-size="12.5" text-anchor="end" fill="var(--text)">United Kingdom  (Reed)</text>
  <rect x="190" y="92" width="326.5" height="17" rx="4" fill="var(--s1)"/>
  <text x="525.5" y="105" font-size="12.5" font-weight="600" fill="var(--text)">18.9%</text>
  <text x="178" y="138" font-size="12.5" text-anchor="end" fill="var(--text)">United States  (Dice)</text>
  <rect x="190" y="126" width="298.8" height="17" rx="4" fill="var(--s1)"/>
  <text x="497.8" y="139" font-size="12.5" font-weight="600" fill="var(--text)">17.3%</text>
  <text x="0" y="174" font-size="11.5" fill="var(--muted)">Ratios within a market only; boards differ in coverage, so absolute counts are not comparable.</text>
  </svg>
  <figcaption>Australia 10.9%, United Kingdom 18.9%, United States 17.3%. Underlying counts in the method note.</figcaption>
</figure>

Australia's alternative-platform share is roughly **40% below** the UK and US figures, which sit
close to each other at 17–19%.

Two observations worth drawing out. Proxmox outnumbers Nutanix in the UK, and the US has
twenty-three times Australia's Nutanix count against ten times the VMware base — so the gap is
not simply a function of market size.

**But these are three different job boards with different employer populations**, and a similar
ratio does not establish a similar market. Seek dominates Australian general recruitment; Dice is
a United States technology specialist; Reed is a British generalist. The comparison is suggestive
of a thinner Australian alternative-platform market. It is not a measurement of one.

**One cross-market measure does not survive scrutiny, and it is worth saying so.** Hyper-V as a
share of VMware ranges from 23% in the US to 49% in Australia to 75% in the UK. That spread is
too wide to reflect real differences in adoption; it more likely reflects what each board covers —
Dice is a specialist technology board, Reed is a general one. Absolute counts are not comparable
across markets. The Nutanix-plus-Proxmox ratio is more defensible because it sits within the same
band in both comparison markets, but it should still be read as indicative rather than precise.

For a buyer, the practical reading is this: if the migration skills market in the UK and US is
thin, Australia's is thinner. An exit plan that assumes you can hire locally is making a stronger
assumption here than the same plan would make elsewhere.

## Three ways this decision usually goes

A renewal decision of this kind generally resolves into one of three paths. The evidence here
does not tell you which to take — that depends on your estate — but it does say something about
the constraints on each.

**Renew and optimise.** Stay, and attack the bill through rationalisation: consolidate
agreements, reclaim unused entitlement, right-size the estate, negotiate term and uplift caps.
The Defence pattern below is the clearest public example of consolidation changing a commercial
position, and the contract data gives you comparables to argue from.

**Selective migration.** Move the workloads that move cheaply, keep the ones that don't, and
reduce dependency over time rather than at once. This is the path the skills data bears on most
directly: a smaller programme can be staffed from a thin market, where a full transition cannot.

**Full platform transition.** Replace across the estate. The public evidence is least encouraging
here — not because the alternatives are weak, but because the Australian delivery capacity to
execute at that scale is hard to see in the recruitment market, and the expiry cluster in 2028
means many organisations may be competing for the same scarce people at once.

What the data genuinely supports is narrower than a recommendation:

**Comparative pricing.** Eleven large Australian buyers, what each contracted, and when each
comes up. Procurement teams frequently negotiate without visibility of what comparable
organisations pay. This is a floor of public fact, free, and reproducible from the dataset below.

**A realistic view of leverage.** If a negotiating position rests on a credible threat to
migrate, that threat needs people behind it. The local market for alternative-platform skills is
visibly thinner than for the incumbent. An alternative you cannot staff is a weaker card than it
looks across a table.

## What this data cannot establish

**It is not a price comparison.** Published contract values do not disclose cores, sockets,
virtual machines or licence counts. No unit rate can be derived, and the table above should not
be read as one agency negotiating better terms than another.

**Scope is not constant.** Estates grow and requirements change. One earlier Defence contract is
described as "Computer Equipment". A larger figure may reflect a larger purchase.

**This is a supplier-identified subset, not all Commonwealth VMware procurement.** It captures
contract notices where VMware is the *named supplier* — two entities, VMware Australia Pty Ltd
(12 contracts, A$247.0m) and VMware International Unlimited Company (7 contracts, A$238.3m).
Licences bought through a reseller, or bundled inside a larger systems-integration contract, do
not appear. The real figure is therefore higher than A$485 million by an unknown margin.

**Some contracts bundle other products from the same vendor group.** The Taxation Office's
largest is described as "CA Mainframe and VMware software licences"; the Reserve Bank's as
"Software licensing and support — CA Broadcom". These cannot be read as pure virtualisation
spending, and whether bundling represents better or worse value than separate licensing is not
determinable from published values.

**Published contract value is not expenditure.** The Department of Finance is explicit that
AusTender values are contracted amounts rather than money actually spent, and that they change
through amendment. Everything here is contracted value.

**Seven of eleven agencies have no earlier contract visible**, including the Australian Taxation
Office, the second-largest current buyer at A$39.3 million a year. Earlier purchases may have
been made through a reseller, or fall outside the search window used. This is a gap in the data
rather than a finding about those agencies.

**This is public-sector data only.** Commonwealth agencies must publish contracts above A$10,000.
Private companies publish nothing comparable, so **none of this can be extrapolated to them.**
Whether private Australian organisations are behaving similarly is not determinable from public
sources.

## Forecast

A prediction that cannot be settled objectively is not worth making, so here is the resolution
rule as well as the call.

> Of the **19 contracts listed in the dataset below**, more than half by count will be followed,
> within 12 months of their expiry, by a new AusTender contract notice from the same agency
> naming VMware or its successor entity as supplier.
> **Confidence: 65%. Resolves: 30 June 2029**, from AusTender records.

Counting contracts rather than agencies or dollars is deliberate: it is the measure least
sensitive to one large renewal dominating the result, and it is settleable from the same public
source anyone can check.

The indicator I will track alongside it is Nutanix plus Proxmox as a share of advertised VMware
roles in Australia, currently 11%. If that rises durably above 15% I will treat the forecast as
weakening — though as an indirect measure it would be evidence, not proof. It is recorded in
[the registry](/registry/) and will be scored there whichever way it resolves.

One matter remains unresolved. A$379 million concentrated in 2028, across a small number of
agencies, is either an artefact of contract terms or reflects something more deliberate in how
these agreements were structured. The data does not distinguish between those explanations.

**For readers who have been through one of these renewals — was migration seriously evaluated,
or was it not realistically on the table?** That is the question public records cannot answer.

## Method

Contract data: the [AusTender OCDS API](https://api.tenders.gov.au), the Commonwealth's contract
notice register. Current contracts: end dates 1 January 2027 to 31 December 2028, UNSPSC families
4322/4323 and 81111/81112, value A$500,000 and above — 1,050 contracts totalling A$4.57 billion,
of which the VMware-supplied subset is reported here. Earlier contracts: searching the
approximately 110 days before each current contract's start returned 92 VMware contracts, of
which the 77 ending before 2026 (A$232 million, 10 buyers, 18 December 2023 to 14 December 2025)
are treated as predecessors.

Annualised figures are contract value ÷ duration × 365.25, summed per agency. Where terms
overlap, this slightly overstates spend in any single month.

Job counts: exact-phrase searches, 14–17 October 2026. Australia via Seek (VMware 239, Hyper-V
117, Nutanix 14, Proxmox 12), United Kingdom via Reed (212 / 158 / 16 / 24), United States via
Dice (2,412 / 554 / 322 / 96). Each board has different coverage and employer mix, so absolute
counts are not comparable across markets — only ratios within a market, and those only
indicatively. A single measurement indicates position rather than direction; these figures will
be re-measured monthly and published as a series.

Supplier matching is on the name recorded in the contract notice, which covers two entities:
**VMware Australia Pty Ltd** (12 contracts) and **VMware International Unlimited Company** (7).
One earlier record naming "VMware User Group Inc" — a training membership, not the vendor — was
excluded.

The API returns a single release per contract notice reflecting its current state; amendment
history is not exposed. A value shown here may therefore have been revised since the notice was
first published, and no amendment lineage could be reconstructed.

### Contract detail

Every contract behind this analysis, by notice number, so any figure here can be checked against
the source record.

| Notice | Agency | Value | Start | Expiry |
| --- | --- | --- | --- | --- |
| CN4211096 | Department of Defence | A$178,086,240 | 2025-12-12 | 2028-12-11 |
| CN4142919 | Australian Taxation Office | A$108,625,000 | 2025-03-22 | 2028-03-21 |
| CN4071834 | Services Australia | A$93,973,803 | 2024-06-13 | 2027-06-22 |
| CN4175970 | Department of Defence | A$27,564,423 | 2025-06-30 | 2028-06-29 |
| CN4154952 | Reserve Bank of Australia | A$18,324,640 | 2025-04-29 | 2028-04-28 |
| CN4137626 | Department of Foreign Affairs and Trade | A$18,142,957 | 2025-02-13 | 2028-02-12 |
| CN4215000 | Bureau of Meteorology | A$12,193,449 | 2025-12-22 | 2028-12-21 |
| CN4150499 | Department of Employment and Workplace Relations | A$9,790,528 | 2025-05-12 | 2028-05-11 |
| CN4075434 | Services Australia | A$3,960,000 | 2024-06-23 | 2027-06-22 |
| CN4260252 | Australian Taxation Office | A$3,025,003 | 2026-06-30 | 2027-06-29 |
| CN4042775 | Department of Defence | A$2,964,192 | 2024-03-10 | 2027-03-09 |
| CN4150498 | Department of Employment and Workplace Relations | A$1,588,950 | 2025-05-12 | 2028-05-11 |
| CN4086032 | Department of Defence | A$1,505,556 | 2024-07-30 | 2027-07-29 |
| CN4180119 | Geoscience Australia | A$1,378,982 | 2025-08-18 | 2028-08-17 |
| CN4236283 | Department of Defence | A$1,097,704 | 2026-05-10 | 2028-12-11 |
| CN4175583 | Australian Transaction Reports and Analysis Centre | A$997,955 | 2025-07-29 | 2028-07-13 |
| CN4181064 | Federal Court of Australia | A$903,870 | 2025-07-16 | 2028-07-15 |
| CN4172594 | Australian Criminal Intelligence Commission | A$646,309 | 2025-07-26 | 2028-07-25 |
| CN4224787 | Services Australia | A$522,243 | 2026-01-30 | 2027-06-22 |

Downloadable: [current contracts (CSV)](/assets/data/commonwealth-vmware-contracts-2027-2028.csv)
· [earlier contracts (CSV)](/assets/data/commonwealth-vmware-predecessors.csv)


---

*These are my personal views, based on the public evidence cited. They are not the views of my
employer, and no part of this analysis uses non-public information.*
