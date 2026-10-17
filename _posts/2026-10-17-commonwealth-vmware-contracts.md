---
layout: post
title: "Commonwealth VMware contracts: A$485 million expiring across 2027 and 2028"
subtitle: "Eleven agencies, when each contract comes up, and what the evidence says about migration"
date: 2026-10-17
slug: commonwealth-vmware-contracts
---

Eleven Australian Commonwealth agencies hold **A$485 million** in contracts where VMware is the
named supplier, expiring between March 2027 and December 2028. All were signed after Broadcom
completed its acquisition of VMware, and 79% by value was signed in 2025 or later.

Across the agencies where both periods can be compared, annualised spend has risen about 20%.
The largest buyer's has fallen slightly. And by the clearest available leading indicator —
hiring — there is little sign of migration away from the platform in this market.

This is what the public record shows, where it is ambiguous, and what it is useful for if you
are approaching a renewal of your own.

## When the contracts expire

<svg viewBox="0 0 680 300" role="img" aria-label="Commonwealth VMware contract value by expiry half-year. 2027 H1: A$104 million across 5 contracts. 2027 H2: A$1.5 million, 1 contract. 2028 H1: A$184 million, 6 contracts. 2028 H2: A$195 million, 7 contracts." style="max-width:100%;height:auto">
  <text x="0" y="18" font-size="15" font-weight="600" fill="currentColor">Four-fifths of the value expires in 2028</text>
  <text x="0" y="38" font-size="12" fill="currentColor" opacity="0.6">Commonwealth VMware contract value by expiry half-year</text>
  <g fill="currentColor" opacity="0.2">
    <rect x="60" y="208" width="120" height="54" rx="2"/>
    <rect x="210" y="260" width="120" height="2" rx="1"/>
    <rect x="360" y="167" width="120" height="95" rx="2"/>
    <rect x="510" y="161" width="120" height="101" rx="2"/>
  </g>
  <g font-size="13" font-weight="600" fill="currentColor" text-anchor="middle">
    <text x="120" y="200">A$104m</text>
    <text x="270" y="252">A$1.5m</text>
    <text x="420" y="159">A$184m</text>
    <text x="570" y="153">A$195m</text>
  </g>
  <g font-size="12" fill="currentColor" opacity="0.6" text-anchor="middle">
    <text x="120" y="281">2027 H1</text>
    <text x="270" y="281">2027 H2</text>
    <text x="420" y="281">2028 H1</text>
    <text x="570" y="281">2028 H2</text>
    <text x="120" y="296">5 contracts</text>
    <text x="270" y="296">1 contract</text>
    <text x="420" y="296">6 contracts</text>
    <text x="570" y="296">7 contracts</text>
  </g>
  <line x1="40" y1="262" x2="650" y2="262" stroke="currentColor" stroke-opacity="0.25"/>
</svg>

Nearly four-fifths of the value sits in 2028. For a vendor, that is when this market moves. For
a buyer, it means a substantial number of organisations will reach the same decision at roughly
the same time — which affects how much attention any one of them can expect to command.

## What has happened to annualised spend

Comparing individual contracts across periods produces misleading results, because the structure
of these agreements has changed. The meaningful comparison is **total annualised spend per
agency** — every contract an agency held, normalised by duration.

| Agency | Earlier (A$/yr) | Current (A$/yr) | Change |
| --- | --- | --- | --- |
| Department of Defence | 77,531,795 | 70,513,296 | **0.9×** |
| Services Australia | 12,957,820 | 32,788,120 | 2.5× |
| Foreign Affairs and Trade | 3,089,896 | 6,057,326 | 2.0× |
| Employment and Workplace Relations | 229,015 | 3,795,757 | 16.6× |
| **Combined** | **93.8m** | **113.2m** | **1.2×** |

Two cautions on reading this. The Employment and Workplace Relations ratio rests on an earlier
base of A$229,000 across two contracts — too small to carry weight. And only four of the eleven
agencies have both periods visible in the data.

With those caveats, the aggregate picture is a roughly 20% increase in annualised spend, and the
largest buyer is slightly below where it was.

## Why single-contract comparisons mislead

Defence illustrates the problem, and the mechanism is worth understanding because anyone
benchmarking a renewal will encounter it.

**Twenty-seven Defence VMware contracts ended on 11 December 2025**, with a combined published
value of A$95.9 million. **One contract worth A$178 million began on 12 December 2025**, running
three years.

Set against Defence's largest earlier contract — A$14.07 million — the new agreement looks like a
twelvefold increase. Set against all 47 of the contracts it replaced, annualised spend went
slightly down.

The consolidation is the story, not the headline number. Whether it reflects Broadcom's packaging,
Defence's own procurement strategy, or both, is not determinable from published data.

**If you are benchmarking your own position, compare total annualised spend across all agreements,
not contract against contract.** The published values invite the wrong comparison.

## The migration question

Renewal under high switching costs is not evidence of satisfaction. Migrating a production
virtualisation estate is difficult, carries real risk, and competes for people who are already
committed elsewhere. Renewing in those circumstances is frequently the rational decision.

It is, however, testable — because migrations require people well before they require contracts.
Advertised roles in Australia, exact-phrase, as at 14 October 2026:

| Term | Jobs advertised |
| --- | --- |
| VMware | 239 |
| Hyper-V | 117 |
| Nutanix | 14 |
| Proxmox | 12 |

VMware exceeds Nutanix by seventeen to one. No migration-programme hiring was found in Australia.
The VMware roles being advertised are predominantly administrators for VMware Cloud Foundation —
positions that support continued operation rather than exit.

## Microsoft is the larger alternative, by a factor of eight

The most practically significant figure above is Hyper-V at 117 roles, against 14 for Nutanix and
12 for Proxmox. Most migration commentary treats Nutanix as the default destination. The
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

| Market | VMware | Hyper-V | Nutanix | Proxmox | Nutanix + Proxmox as % of VMware |
| --- | --- | --- | --- | --- | --- |
| Australia (Seek) | 239 | 117 | 14 | 12 | **10.9%** |
| United Kingdom (Reed) | 212 | 158 | 16 | 24 | **18.9%** |
| United States (Dice) | 2,412 | 554 | 322 | 96 | **17.3%** |

Australia's alternative-platform share is roughly **40% below** the UK and US figures, which sit
close to each other at 17–19%.

Two observations worth drawing out. Proxmox outnumbers Nutanix in the UK, and the US has
twenty-three times Australia's Nutanix count against ten times the VMware base — so the gap is
not simply a function of market size. Australia appears to be genuinely further behind on
alternative-platform skills than either comparison market.

**One measure in that table does not survive scrutiny, and it is worth saying so.** Hyper-V as a
share of VMware ranges from 23% in the US to 49% in Australia to 75% in the UK. That spread is
too wide to reflect real differences in adoption; it more likely reflects what each board covers —
Dice is a specialist technology board, Reed is a general one. Absolute counts are not comparable
across markets. The Nutanix-plus-Proxmox ratio is more defensible because it sits within the same
band in both comparison markets, but it should still be read as indicative rather than precise.

For a buyer, the practical reading is this: if the migration skills market in the UK and US is
thin, Australia's is thinner. An exit plan that assumes you can hire locally is making a stronger
assumption here than the same plan would make elsewhere.

## What this is useful for

**Comparative pricing.** Eleven large Australian buyers, what each signed, and when each comes up
again. Procurement teams frequently negotiate without visibility of what comparable organisations
pay. This is a floor of public fact, available at no cost.

**A realistic view of leverage.** If a negotiating position depends on a credible threat to
migrate, the local skills market is thinner than the commentary suggests. An alternative that
cannot be staffed is not a genuine alternative.

## What this data cannot establish

**It is not a price comparison.** Published contract values do not disclose cores, sockets,
virtual machines or licence counts. No unit rate can be derived, and the table above should not
be read as one agency negotiating better terms than another.

**Scope is not constant.** Estates grow and requirements change. One earlier Defence contract is
described as "Computer Equipment". A larger figure may reflect a larger purchase.

**Seven of eleven agencies have no earlier contract visible**, including the Australian Taxation
Office, the second-largest current buyer at A$39.3 million a year. Earlier purchases may have
been made through a reseller, or fall outside the search window used. This is a gap in the data
rather than a finding about those agencies.

**This is public-sector data only.** Commonwealth agencies must publish contracts above A$10,000.
Private companies publish nothing comparable, so **none of this can be extrapolated to them.**
Whether private Australian organisations are behaving similarly is not determinable from public
sources.

## Forecast

> Despite changes to VMware's commercial packaging, the majority of Australian Commonwealth
> VMware contracts expiring in 2027–2028 will be renewed with VMware rather than migrated to an
> alternative hypervisor. **Confidence: 65%. Resolves: 30 June 2029.**

The leading indicator is Nutanix plus Proxmox as a share of advertised VMware roles, currently
11%. **Sustained movement above 15% would weaken this forecast.** It is recorded in
[the registry](/registry/) and will be scored there whichever way it resolves.

One matter remains unresolved: A$379 million concentrated in 2028, across a small number of
agencies, is either an artefact of contract terms or reflects something more deliberate in how
these agreements were structured. The data does not distinguish between those explanations.

**For readers who have been through one of these renewals — was migration seriously evaluated, or
was it not realistically on the table?** That question cannot be answered from public records.

---

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

Job counts: exact-phrase searches, 14–17 October 2026. Australia via Seek, United Kingdom via
Reed, United States via Dice. Each board has different coverage and employer mix, so absolute
counts are not comparable across markets — only ratios within a market, and those only
indicatively. A single measurement indicates position rather than direction; these figures will
be re-measured monthly and published as a series.

The supplier entity on these notices is VMware International Unlimited Company. Some contracts
bundle other products from the same vendor group — the Taxation Office's largest is described as
"CA Mainframe and VMware software licences", the Reserve Bank's as "Software licensing and
support — CA Broadcom". Whether bundling represents better or worse value than separate licensing
cannot be determined from published contract values.

### Contract detail

| Agency | Value | Contracts | First expiry |
| --- | --- | --- | --- |
| Department of Defence | A$211,218,116 | 5 | 2027-03-09 |
| Australian Taxation Office | A$111,650,003 | 2 | 2027-06-29 |
| Services Australia | A$98,456,045 | 3 | 2027-06-22 |
| Reserve Bank of Australia | A$18,324,640 | 1 | 2028-04-28 |
| Department of Foreign Affairs and Trade | A$18,142,957 | 1 | 2028-02-12 |
| Bureau of Meteorology | A$12,193,449 | 1 | 2028-12-21 |
| Dept of Employment and Workplace Relations | A$11,379,478 | 2 | 2028-05-11 |
| Geoscience Australia | A$1,378,982 | 1 | 2028-08-17 |
| AUSTRAC | A$997,955 | 1 | 2028-07-13 |
| Federal Court of Australia | A$903,870 | 1 | 2028-07-15 |
| Australian Criminal Intelligence Commission | A$646,309 | 1 | 2028-07-25 |

---

*These are my personal views, based on the public evidence cited. They are not the views of my
employer, and no part of this analysis uses non-public information.*
