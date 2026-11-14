---
layout: post
title: "One vendor credential, many customers"
subtitle: "A stolen credential belonging to a Microsoft 365 backup service allowed unauthorised access to customer environments. It raises a wider question: how much access do we give trusted software providers, and what happens when their credentials are stolen?"
date: 2026-11-14
slug: one-vendor-credential-many-customers
image: /assets/og/one-vendor-credential.png
image_alt: "One vendor credential, many customers. One stolen credential belonging to the vendor; 2,250+ customer environments with attempted sign-ins; 162 environments with confirmed sign-ins; 2 where follow-on activity was seen. Not how a vendor stores credentials — how far one can act for you."
description: "A stolen credential belonging to a Microsoft 365 backup service allowed unauthorised access to customer environments. What investigators confirmed, what remains unknown, and the four properties of a credential that decide the consequences."
---

ConnectWise sells software to IT service providers — the firms that run technology for other
businesses. One of its products, ConnectWise Cloud Backup, backs up a customer's Microsoft 365
email, files and Teams conversations.

To do that, the customer authorises the application to read all of it. That authorisation is
given once, by each customer, and it persists. It is how the product works.

In October, a credential belonging to that application was stolen.

A credential of this kind is not a password belonging to a person. It identifies the
application itself, and it is issued by the vendor, not the customer. The same credential
authenticates the application into every customer environment that has authorised it — each
organisation's separate Microsoft 365 environment, what Microsoft calls a tenant.

So one stolen credential potentially reached a great many organisations at once. What
investigators could confirm it actually did was a much smaller number, and the distance between
those two things is what makes the incident worth reading about.

<figure>
  <svg viewBox="0 0 640 282" role="img" aria-label="What was actually observed, and when. 10,000+: Tenants with the apps whose sign-in logs Huntress could review, 19 Oct. ~1,000: Tenants with sign-in activity from the attacker's address, 17 Oct. 300+: Of those, sign-ins that succeeded, 17 Oct. 162: Tenants with confirmed unauthorised sign-ins, at 19:00 UTC, 16 Oct. 2: Tenants where Huntress identified post-compromise activity, 19 Oct.">
  <text x="0" y="20" font-size="15.5" font-weight="600" fill="var(--text)">What was actually observed, and when</text>
  <text x="0" y="40" font-size="12" fill="var(--muted)">ConnectWise Cloud Backup, October 2026. Five figures from one incident post.</text>
  <line x1="0" y1="66.0" x2="636" y2="66.0" stroke="var(--line)" stroke-width="1"/>
  <text x="104.0" y="92.0" font-size="17" font-weight="600" text-anchor="end" fill="var(--s1)" font-variant-numeric="tabular-nums">10,000+</text>
  <text x="118.0" y="88.0" font-size="12.5" fill="var(--text)">Tenants with the apps whose sign-in logs Huntress could review</text>
  <text x="636" y="88.0" font-size="11" text-anchor="end" fill="var(--muted)">19 Oct</text>
  <line x1="0" y1="102.0" x2="636" y2="102.0" stroke="var(--line)" stroke-width="1"/>
  <text x="104.0" y="128.0" font-size="17" font-weight="600" text-anchor="end" fill="var(--s1)" font-variant-numeric="tabular-nums">~1,000</text>
  <text x="118.0" y="124.0" font-size="12.5" fill="var(--text)">Tenants with sign-in activity from the attacker's address</text>
  <text x="636" y="124.0" font-size="11" text-anchor="end" fill="var(--muted)">17 Oct</text>
  <line x1="0" y1="138.0" x2="636" y2="138.0" stroke="var(--line)" stroke-width="1"/>
  <text x="104.0" y="164.0" font-size="17" font-weight="600" text-anchor="end" fill="var(--s1)" font-variant-numeric="tabular-nums">300+</text>
  <text x="118.0" y="160.0" font-size="12.5" fill="var(--text)">Of those, sign-ins that succeeded</text>
  <text x="636" y="160.0" font-size="11" text-anchor="end" fill="var(--muted)">17 Oct</text>
  <line x1="0" y1="174.0" x2="636" y2="174.0" stroke="var(--line)" stroke-width="1"/>
  <text x="104.0" y="200.0" font-size="17" font-weight="600" text-anchor="end" fill="var(--s1)" font-variant-numeric="tabular-nums">162</text>
  <text x="118.0" y="196.0" font-size="12.5" fill="var(--text)">Tenants with confirmed unauthorised sign-ins, at 19:00 UTC</text>
  <text x="636" y="196.0" font-size="11" text-anchor="end" fill="var(--muted)">16 Oct</text>
  <line x1="0" y1="210.0" x2="636" y2="210.0" stroke="var(--line)" stroke-width="1"/>
  <text x="104.0" y="236.0" font-size="17" font-weight="600" text-anchor="end" fill="var(--s1)" font-variant-numeric="tabular-nums">2</text>
  <text x="118.0" y="232.0" font-size="12.5" fill="var(--text)">Tenants where Huntress identified post-compromise activity</text>
  <text x="636" y="232.0" font-size="11" text-anchor="end" fill="var(--muted)">19 Oct</text>
  <line x1="0" y1="246.0" x2="636" y2="246.0" stroke="var(--line)" stroke-width="1"/>
  <text x="0" y="268.0" font-size="11.5" fill="var(--muted)">Huntress observations, reported between 16 and 19 October 2026.</text>
  </svg>
  <div class="chart-mobile">
    <p class="cm-title">What was actually observed, and when</p>
    <p class="cm-sub">ConnectWise Cloud Backup, October 2026. Five figures from one incident post.</p>
    <dl class="cm-obs">
      <dt>10,000+</dt>
      <dd>Tenants with the apps whose sign-in logs Huntress could review<span>19 Oct</span></dd>
      <dt>~1,000</dt>
      <dd>Tenants with sign-in activity from the attacker's address<span>17 Oct</span></dd>
      <dt>300+</dt>
      <dd>Of those, sign-ins that succeeded<span>17 Oct</span></dd>
      <dt>162</dt>
      <dd>Tenants with confirmed unauthorised sign-ins, at 19:00 UTC<span>16 Oct</span></dd>
      <dt>2</dt>
      <dd>Tenants where Huntress identified post-compromise activity<span>19 Oct</span></dd>
    </dl>
    <p class="cm-note">Huntress observations, reported between 16 and 19 October 2026.</p>
  </div>
  <figcaption>The stolen credential could be used across every customer environment that had authorised the application.</figcaption>
</figure>

Those figures come from [Huntress](https://www.huntress.com/blog/vendor-credential-enables-unauthorized-access),
a security firm that monitors customer environments and detects threats in them. It published
them across three updates over four days, and each answers a different question. They are also
bounded by what Huntress could see: its investigation covers the environments and logs
available to it, not every ConnectWise customer and not every Microsoft 365 environment.

A successful unauthorised sign-in confirms that someone got in. It does not establish what they
reached, or whether anything was taken.

In two of those environments, Huntress examined what happened next. A separate family of
ConnectWise applications — its Cloud Management products, distinct from the backup service the
stolen credential belonged to — obtained administrator-level permissions, then added new
authentication credentials to other applications already present in the customer's environment.
That last step matters commercially rather than technically: those added credentials would keep
working after the original stolen one was cancelled.

Microsoft reached further. Its own investigation
[attributed the activity](https://www.microsoft.com/en-us/security/blog/2026/10/21/storm-0940-uses-artex-agentic-ai-connectwise-supply-chain-compromise/)
to a group it tracks as Storm-0940, and reported attempted sign-ins across more than 2,250
customer environments. Microsoft also reported that the attacker used an AI-powered
penetration-testing framework to run the campaign faster than people could.

Microsoft sees authentication across its whole platform, so its figure covers ground Huntress's
cannot. It counts attempts, though, not confirmed compromises — and the two firms' numbers
describe different things and should not be added together.

## Why one stolen credential could affect many customers

The risk followed from how the backup service was designed to work. Long before the credential
was stolen, each customer had authorised the application to reach their Microsoft 365
environment, and that authorisation stayed in place. A stolen credential could then potentially
be used across all of them.

None of that makes the design wrong. A backup product cannot protect mailboxes and files
without permission to read them. The open question is how narrowly that permission could have
been drawn while the service still worked — and that is a question for the customer granting it
as much as for the vendor asking.

> The question this incident puts to any organisation is not how securely a vendor stores its
> credentials. It is how far one of them can act on your behalf if it is lost.

## Three other recent examples of credential exposure and misuse

These are unrelated to the ConnectWise investigation. They are here because credentials get
loose in more than one way, and the consequences differ accordingly.

**Stolen AI service keys.** Google's Mandiant responders
[reported](https://cloud.google.com/blog/topics/threat-intelligence/llmjacking-monetizing-compromised-cloud-models)
fraudulent charges above US$100,000 in a single day from stolen AI provider keys, reaching
US$1 million at some organisations before access was cut. These are several separate
investigations, not one incident.

**Secrets saved by a developer tool.** Apiiro found, [as reported by
iTnews](https://www.itnews.com.au/news/dont-ask-again-in-anthropics-claude-code-leaks-developer-secrets-630203),
that a coding assistant saved the exact command a developer approved — and with it any password
typed into that command — into a settings file that people then published to public code
repositories. 1,379 secrets across 1,122 files. This is a study of what was exposed; it did not
establish that anything was used.

**Credentials taken in a wider attack.**
[Chainalysis disclosed](https://arstechnica.com/security/2026/11/chainalysis-says-hackers-stole-credentials-and-tokens-for-all-of-its-customers/)
that an attacker obtained usernames, password hashes and active session tokens for all of its
users. Human passwords were in that set as well as machine credentials, so it is a broader case
than the others here.

## What actually decides the consequences

Four properties of a credential do more to determine the damage than the method of theft does.
They are worth knowing because they are answerable about credentials an organisation already
has.

**Scope** — how much it can reach, and in how many places. ConnectWise's reached every customer
environment that had authorised the application. A credential limited to one service in one
environment is a different proposition, and that is decided when access is granted.

**Duration** — how long it stays valid. Short-lived credentials shorten the window in which a
stolen one is useful. They do not remove it: the follow-on activity above took minutes.

**Where it works from** — whether it still functions on an attacker's machine, somewhere else
entirely. Easy to assume, harder to enforce.

**Revocation speed** — how quickly access can be withdrawn, and whether anyone can produce the
list of what needs withdrawing.

## How security controls could reduce these risks, and what remains your responsibility

Products exist for each of these problems: managing the identities that applications use,
keeping secrets out of developers' hands, routing AI traffic through one controlled path, and
finding credentials nobody knew about. They address different parts of the problem, and buying
one does not cover the others.

The table below is illustrative. These are the vendors' own descriptions of their products,
which I have not tested, and none of them was necessarily present in the environments
described above. Nothing here would certainly have prevented any of these incidents.

<div class="table-scroll">
<table class="controls">
  <thead><tr><th>Example</th><th>How security tools could help</th><th>What remains your responsibility</th></tr></thead>
  <tbody>
    <tr>
      <td data-l="Example">ConnectWise</td>
      <td data-l="How security tools could help">Workload identity platforms can issue applications short-lived credentials instead of standing ones, so a stolen credential expires on its own. Credential discovery tools can show which applications hold access in the first place. Aembit and Microsoft Entra Workload Identity Federation describe the first; Clutch, Token Security and GitGuardian the second.</td>
      <td data-l="What remains your responsibility">The vendor is responsible for protecting its own credential. The customer decides what the application was authorised to reach, reviews that periodically, watches for unexpected use, and acts when a vendor discloses. None of that is purchased.</td>
    </tr>
    <tr>
      <td data-l="Example">Stolen AI service keys</td>
      <td data-l="How security tools could help">An AI gateway can route all model traffic through one path and apply spending and rate limits per key, which caps the bill when a key leaks. Kong's AI Gateway describes this. Secret management tools can deliver keys at runtime rather than leaving them stored.</td>
      <td data-l="What remains your responsibility">A gateway only governs traffic that goes through it. Closing the direct path to the provider, noticing an unexpected bill quickly, and cancelling a key fast are organisational tasks, not product features.</td>
    </tr>
    <tr>
      <td data-l="Example">Secrets in a developer tool</td>
      <td data-l="How security tools could help">Secrets can be injected at runtime so a person never handles the value — HashiCorp Vault Agent describes this. Repositories can block known secret formats before they are published, which GitHub push protection does, and scanners such as GitGuardian can find ones already out.</td>
      <td data-l="What remains your responsibility">Whether every repository and every developer tool actually uses these, whether the practice of typing secrets into commands has changed, and rotating anything already exposed. Deleting a file does not take back what was published.</td>
    </tr>
    <tr>
      <td data-l="Example">Chainalysis</td>
      <td data-l="How security tools could help">Less than the others. Shorter session lifetimes and stronger identity controls reduce how long a stolen session remains usable. This case involved human passwords and interception as well as machine credentials, so no single control on this list addresses it.</td>
      <td data-l="What remains your responsibility">A customer of a breached provider has to invalidate sessions, reset affected credentials and work out what those credentials reached. The provider's remediation and the customer's are separate tasks.</td>
    </tr>
  </tbody>
</table>
</div>

Documentation for each: [Aembit](https://docs.aembit.io/),
[Microsoft Entra Workload Identity Federation](https://learn.microsoft.com/en-us/entra/workload-id/workload-identity-federation),
[Kong AI Gateway](https://docs.konghq.com/gateway/latest/ai-gateway/),
[HashiCorp Vault Agent](https://developer.hashicorp.com/vault/docs/agent-and-proxy/agent),
[GitHub push protection](https://docs.github.com/en/code-security/secret-scanning/introduction/about-push-protection),
[Clutch](https://clutch.security/), [Token Security](https://www.token.security/),
[GitGuardian](https://www.gitguardian.com/secrets-detection).

The pattern across the right-hand column is the useful part. Buying a control narrows the
problem; it does not establish that every application, integration and workflow is covered by
it. That second thing is what an incident tests.

## The question I would put forward

Most organisations can say who their employees are and what those people can reach.

Fewer can say the same about the software acting on their behalf — the integrations, the
backup tools, the automated workloads. What can each of them reach, how long do their
credentials last, where do those credentials work from, and how quickly could they be
withdrawn?

That list is harder to produce than it sounds. In an estate with thousands of applications,
permissions, owners and revocation paths rarely sit in one place. But it is a better question
to answer on an ordinary week than during an incident.

---

*These are my personal views, based on the public evidence cited. They are not the views of my
employer, and no part of this analysis uses non-public information.*
