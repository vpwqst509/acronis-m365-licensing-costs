# acronis m365 backup: how the licensing actually works, what a 200 GB plan really costs, and the refund fine print to check before you buy

Microsoft keeps Exchange Online, OneDrive, SharePoint, and Teams running. Under the shared responsibility model, protecting the data inside them is your job, not Microsoft's. A deleted mailbox, a ransomware attack that encrypts synced files, a Teams channel wiped by a departing admin — Microsoft will not restore any of that for you. That's the gap behind the search term "acronis m365 backup": people want real, purchasable Acronis protection for Microsoft 365 without an enterprise-level quote attached.

Acronis fills the gap: cloud-to-cloud backup for Exchange Online, OneDrive, SharePoint, and Teams, with no hardware and no agent to install, running up to six backup passes per day. The usual obstacle is licensing — Acronis sells direct through per-seat and per-workload licenses aimed at MSPs and IT departments. There's a simpler route: Sharktech, a hosting provider that has run its own datacenters since 2003, resells Acronis Cyber Protect in fixed-capacity plans starting at 200 GB for **$4/month**.

> **Quick recommendation:** for most people searching this — solo server owners, small businesses, one-person IT operations — Sharktech's Acronis Cyber Protection is the practical entry point. **$4/month gets 200 GB on month-to-month billing**, with no long commitment. If you want fully managed service or per-seat licensing with unlimited storage, the comparisons below cover who those fit better. 👉 [see the 200 GB plan and your configured total in the Sharktech portal](https://portal.sharktech.net/aff.php?aff=1626&pid=648)

## Why Microsoft 365 data needs a separate backup

Because Microsoft only guarantees availability of the service, not your data. Under the shared responsibility model, Microsoft keeps Exchange Online, OneDrive, SharePoint, and Teams online, while protecting data, accounts, and configurations sits with you. When data disappears through user error, malicious deletion, or an attack, Microsoft's default tooling gives you limited recovery options.

Acronis's M365 backup covers that gap at the platform level:

- Exchange Online (mailboxes, calendar, contacts), OneDrive, SharePoint, and Teams
- Group protection plans that automatically pick up new users, groups, sites, and teams, so a new hire doesn't slip through unprotected
- Up to six backup runs per day on supported M365 data
- AES-256 encryption, with an optional immutability window that prevents backups from being deleted — relevant when ransomware tries to destroy your recovery points
- Granular recovery: pull back a single email or file, or an entire site or mailbox
- One console that also manages 30+ other workload types, from physical servers and VMs to mobile devices

The Acronis Cyber Protect platform that Sharktech resells lists Microsoft 365 among its supported workloads, so the same plan can cover a server and your M365 data under one console.

## The two Acronis M365 storage options — and why the difference matters

Inside Acronis, M365 data can land in two different places, and recovery behaves very differently in each. Worth knowing before you compare plans, because "acronis m365 backup" is not one product.

|  | Microsoft 365 Backup Storage | Acronis Cloud |
| --- | --- | --- |
| Coverage | Exchange mailboxes, OneDrive, SharePoint sites | Those, plus Teams and Entra ID backup |
| Retention | Fixed one year | Flexible by age or count, including indefinite |
| Recovery | Whole mailbox/account/site only, no item-level restore | Granular: single emails, files, collaboration content |
| Recovery destination | Original workload only | Cross-user and cross-org within the same tenant |
| Where it sits | Inside Microsoft's trust boundary | Independent, across 50+ Acronis datacenters |
| Pricing | Consumption-based, per GB | Per-seat licensing, unlimited cloud storage on eligible plans |

Microsoft-hosted storage is fast and simple but restores whole objects on a fixed retention clock. For most real situations — recovering one email deleted three weeks ago, for instance — plans that back up to Acronis Cloud storage are the ones that behave the way you expect. Check which storage a plan uses before buying.

## Sharktech's Acronis plan: one plan, four billing cycles

Sharktech keeps this simple: there's a single Acronis Cyber Protection plan with a 200 GB base, sold across four billing cycles, with capacity and add-ons configured in the portal and the final price confirmed at checkout.

| Billing cycle | Price | Included storage | Overage (per extra GB) | Order |
| --- | --- | --- | --- | --- |
| Monthly | $4.00/mo | 200 GB | $0.02 | [start the monthly plan](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Quarterly | $8.00/qtr | 200 GB | $0.04 | [start the quarterly plan](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Semi-annual | $12.00/6 mo | 200 GB | $0.06 | [start the semi-annual plan](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |
| Annual | $24.00/yr | 200 GB | $0.12 | [start the annual plan](https://portal.sharktech.net/aff.php?aff=1626&pid=648) |

A note on sourcing, since it matters: Sharktech's own product page confirms that services start at $4/month and that the final price depends on the capacity and protection options you select in the portal. The full four-cycle rate table above reflects the plan's published configuration-page pricing as compiled by independent write-ups, not a static official price sheet — treat the portal's itemized total as the authoritative number at checkout.

Two things most plan pages won't tell you:

First, the billing-cycle trade-off cuts both ways. The base price drops as the cycle lengthens — annual works out to roughly $2/month versus $4 monthly — but the overage rate moves in the opposite direction, from $0.02/GB on monthly to $0.12/GB on annual, a sixfold difference. If your storage sits near 200 GB, the $24/year base price wins outright. If your data will actually grow past that, work out the projected overage before committing, because the longer cycles carry the steepest per-GB rates.

Second, there's an optional Files Sync & Share add-on, priced at $0.03/GB on the monthly cycle and scaled to the other cycles. It turns the backup target into a shareable cloud drive. Solo server owners generally leave it off; MSPs reselling backup to clients often turn it on. It isn't bundled by default, but it is billed separately, so check the itemized selection before confirming your order — that's Sharktech's own advice on the product page. 👉 [configure the plan in the Sharktech cart and check your itemized price](https://portal.sharktech.net/aff.php?aff=1626&pid=648)

## How this compares with buying Acronis M365 backup other ways

Per-GB reseller pricing sits at the low end of the market. What you give up is managed service and, as covered below, a refund guarantee. Here's the landscape with the relevant numbers.

| Option | Pricing model | Reported price | Best for |
| --- | --- | --- | --- |
| Sharktech (resold Acronis Cyber Protect) | Per GB, 200 GB base | From $4/mo | Self-managed small workloads, 1–10 machines |
| Acronis direct | Per-seat / per-workload license | ~$85/yr per device (third-party estimate), storage extra | Teams wanting unlimited cloud storage on eligible plans |
| Liquid Web (managed Acronis) | Managed, capacity-tiered | From ~$11/mo (100 GB), ~$134/mo at 1 TB | Buyers who want the provider to run backups |
| Microsoft native M365 Backup | Consumption-based, per GB | Published by Microsoft | Fast whole-object restores, fixed 1-year retention |

Buying direct from Acronis means per-seat licensing with unlimited Acronis Cloud storage on eligible plans, or per-workload licenses for IT departments — third-party analysis puts direct pricing around $85 per device per year before storage. If you have many seats but modest data volume, that unlimited-storage model can beat per-GB pricing. For a single server, it's usually more than you need.

Liquid Web's managed Acronis Cyber Backups start around $11/month for 100 GB and climb to roughly $134/month at 1 TB, according to published comparisons. You're paying a premium to have backups operated for you. That's a legitimate choice if you don't want to touch anything, but at entry-level capacity it runs about three times Sharktech's monthly price.

Microsoft's native option is the Microsoft-hosted storage described in the table above — consumption-based per-GB billing, with the fixed one-year retention and whole-object-only restore limits that come with it.

Sharktech's positioning is honest about what it is: self-service. You configure backup schedules, retention, and recovery in the Acronis web console yourself; Sharktech's 24/7 technical team supports the service. If you want managed, pick the managed provider. If you want unlimited storage per seat, pick direct. If your budget is small and the workload is a server or two plus some M365 accounts, the per-GB table makes the case on its own.

## The refund fine print — read this before ordering

Buying through Sharktech means Sharktech's billing terms apply, and they are strict: **all payments to Sharktech are non-refundable**. Its terms of service state this in plain language — every payment, including any setup fee, is non-refundable regardless of how much of the service you used. The one exception is a billing dispute, which must be raised within 30 days of the invoice; even then, a favorable ruling returns the amount as account credit rather than cash.

Other terms worth knowing before you click order:

- Plans renew automatically for the same cycle; cancel by emailing the sales department **at least 5 days before the current period ends**, with your account details included
- Late payments trigger late fees, and interrupted service carries a reconnect charge; the terms allow 1.5% monthly interest on overdue balances
- Servers are unmanaged — Sharktech keeps them online and remotely accessible, and draws the line at application-level problems

This is where buying direct versus through a reseller genuinely differs. Acronis's own return policy for direct-channel subscriptions includes a 30-day money-back window on Cyber Protect plans, and consumers in the EU keep a 14-day statutory right of withdrawal for digital services under EU consumer law. Those protections belong to the direct purchase channel and don't automatically transfer to a reseller's terms, which is worth weighing if a refund guarantee matters to your decision.

Practically, this is why the monthly cycle is the sane way to evaluate a provider with a no-refund policy: your maximum exposure is $4, and you can walk away with 5 days' notice. Confirm the itemized price in the portal before paying, since extra capacity and the File Sync & Share add-on are billed as separate line items. 👉 [build your Acronis plan and see the configured total first](https://portal.sharktech.net/aff.php?aff=1626&pid=648)

For balance on the provider itself: third-party reviews on Trustpilot average around 3.5 for Sharktech, with praise focused on responsive technical support and low-latency connectivity, and complaints centered on exactly the no-refund policy described above — better to know it now than after the invoice.

## Who this plan fits — and who should skip it

Four situations where it's a genuinely good deal:

- You already run, or are about to rent, a Sharktech dedicated server or VPS. Traffic between your server and the backup target stays on one network, and you have one support number for both.
- Compliance or client trust requires "Acronis Cyber Protect" on the invoice — this is real Acronis, not a generic-branded backup.
- You're running 1–10 machines and have been putting off backups because quotes kept landing at $50+/month. The $4 entry point exists precisely for that situation.
- You're an MSP or IT consultant who wants to resell backup per GB to clients — the add-on marketplace model was built for that.

Skip it if you need petabyte-scale custom retention policies, fully managed backup operations, or per-seat unlimited-storage licensing. Those requirements point at enterprise backup platforms or Acronis's direct channel — at correspondingly higher prices. Long-time Acronis users on review platforms do note quirks worth knowing: SharePoint backups automatically include every user with access rights, and licenses for dormant users can keep billing until manually cleaned up, so plan your seat and workload hygiene either way.

## FAQ

**Doesn't Microsoft 365 already include backup?** No. Microsoft guarantees service availability; under the shared responsibility model, data protection is your responsibility. Microsoft does sell a native backup option, but it uses consumption-based per-GB pricing, fixed one-year retention, and restores whole mailboxes, accounts, or sites only.

**How often does Acronis back up Microsoft 365 data?** Up to six times per day on supported M365 data, with group protection plans automatically covering new users, groups, and sites as they appear.

**Can I restore a single deleted email?** Yes, when backups are on Acronis Cloud storage — recovery goes down to individual emails and files. The Microsoft-hosted storage option restores whole mailboxes or sites only.

**Is there a trial or money-back period?** Sharktech doesn't advertise a trial, and its terms state all payments are non-refundable. Month-to-month billing at $4/month with 5 days' notice to cancel is the lowest-risk way to evaluate it. Direct-channel Acronis subscriptions carry a published 30-day money-back policy if that guarantee is a priority.

**Where does my backup data physically live?** On Acronis Cloud storage, backups sit in Acronis's independent infrastructure across 50+ datacenters with selectable regions for data sovereignty — not inside Microsoft's trust boundary — operated in Sharktech's DDoS-protected environment and supported by its 24/7 team.

## The bottom line, by situation

Storage stable around 200 GB? Take the annual cycle — $24 for the year, done. Data growing or unpredictable? Stay monthly for the $0.02/GB overage rate, and revisit once your actual usage is known. Unsure at all? Monthly is the cycle that matches a no-refund provider, because your downside is capped at one month's base price. If managed operations matter more to you than price, the managed hosting provider covered above is the better fit — at roughly triple the entry cost.

Before ordering, two last checks: confirm the itemized total in the portal, since capacity and add-ons price separately, and remember payments are non-refundable, so start month-to-month. 👉 [set up Acronis Cyber Protection with 200 GB from $4/month](https://portal.sharktech.net/aff.php?aff=1626&pid=648)
