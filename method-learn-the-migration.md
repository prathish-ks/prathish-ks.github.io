---
layout: page
title: "Method: leaving VMware"
permalink: /2026/11/learn-the-migration/method/
image: /assets/og/learn-the-migration.png
image_alt: "Method and sources for the VMware contract and skills analysis"
---

Sources, scope and the full tables behind
[Learn the migration, not the platform](/2026/11/learn-the-migration/). Everything here can be
checked independently of me.

**Contract data.** The [AusTender OCDS API](https://api.tenders.gov.au), the Commonwealth's
contract notice register, read 2 November 2026. Scope: contract notices with end dates between
1 January 2027 and 31 December 2028 where the supplier is VMware Australia Pty Ltd or VMware
International Unlimited Company — 19 notices, A$485.3 million published value, 11 agencies. A
third entity, VMWARE USER GROUP INC, appears in the register and is excluded: it is a user group,
not the vendor.

**What this excludes.** Commonwealth contracts only — no state or territory government, no
private sector, and no contract whose supplier is a reseller rather than VMware itself. Published
value is contracted value, not expenditure. An agency may hold entitlement through arrangements
that produce no contract notice at all.

<div class="table-scroll">
<table class="contracts">
  <thead><tr><th>Year of expiry</th><th>Contracts</th><th>Published value</th></tr></thead>
  <tbody>
    <tr><td data-l="Year">2027</td><td data-l="Contracts">6</td><td data-l="Value">A$106.0m</td></tr>
    <tr><td data-l="Year">2028</td><td data-l="Contracts">13</td><td data-l="Value">A$379.3m</td></tr>
    <tr><td data-l="Year"><b>Total</b></td><td data-l="Contracts"><b>19</b></td><td data-l="Value"><b>A$485.3m</b></td></tr>
  </tbody>
</table>
</div>

Largest single notice: `CN4211096`, Department of Defence, A$178.1 million, 12 December 2025 to
11 December 2028.

**Platform comparison.** Read from each vendor's own published documentation. Nothing here has
been trialled, benchmarked or reference-checked.

<div class="table-scroll">
<table class="contracts">
  <thead><tr><th>Platform</th><th>What ends the VMware licence</th><th>First-party tools to move systems across</th></tr></thead>
  <tbody>
    <tr><td data-l="Platform">Nutanix AHV</td><td data-l="Licence">Bundled with a paid Nutanix Cloud Infrastructure licence</td><td data-l="Tools">Nutanix Move, included</td></tr>
    <tr><td data-l="Platform">Red Hat OpenShift Virtualization</td><td data-l="Licence">Under an OpenShift subscription</td><td data-l="Tools">Migration Toolkit for Virtualization, included</td></tr>
    <tr><td data-l="Platform">Proxmox VE</td><td data-l="Licence">Free to run; a subscription buys the enterprise repository and support</td><td data-l="Tools">Built-in ESXi importer</td></tr>
    <tr><td data-l="Platform">Microsoft Hyper-V</td><td data-l="Licence">Included in Windows Server licensing</td><td data-l="Tools"><a href="https://learn.microsoft.com/en-us/system-center/vmm/vm-convert-vmware?view=sc-vmm-2025">System Center VMM conversion</a> (requires System Center licensing), and the free <a href="https://learn.microsoft.com/en-us/windows-server/manage/windows-admin-center/use/vm-conversion-extension-overview">Windows Admin Center VM Conversion extension</a>, in public preview and limited to ten machines per batch</td></tr>
  </tbody>
</table>
</div>

<p>All four ship first-party conversion tooling. They differ in maturity, in batch size, and in
whether the tool itself carries a licence cost. Capability is read from each vendor's published
documentation; nothing here has been trialled or benchmarked. The Microsoft standalone converter
(MVMC) reached end of support in 2017 and is not a current option.</p>

**Job counts.** Exact-phrase searches on Seek, Australia-wide. Measured 2 November 2026: VMware
239, Hyper-V 102, Nutanix 14, Proxmox 9. The same four searches on 14 October 2026 returned 239,
117, 14 and 12. Seek normalises the query, so "Hyper-V" is searched as *hyper v*; both readings
use the same form. These are measurements on single days rather than standing facts.
Recruitment is also an indirect signal: a migration
delivered by an integrator, an offshore team or redeployed internal staff produces no
advertisement, and vacancies are often written as "infrastructure modernisation" without naming a
destination.

**Defence's direction.** [Reported by iTnews](https://www.itnews.com.au/news/defence-mandates-move-off-vmware-629929)
on 30 October 2026, by Ry Crozier. The report states the "mandate" was issued around September
2025, months before the A$178.1 million renewal was revealed; that its formality is unclear and
Defence declined to comment on its scope; that it applies to all parts of Defence with VMware
exposure; and that cost is not the only driver, with sovereignty also a concern. It rests on
unnamed sources. Nothing in it is independently verified here, and the reading of the renewal as
runway for a transition is my inference, not the report's.

---

[Back to the article](/2026/11/learn-the-migration/)
