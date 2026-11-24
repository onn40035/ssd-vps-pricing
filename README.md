# Cheap SSD VPS: Is $2.99 a Month Enough for a Real Site, Which Plan Do You Actually Need, and What Do the Term and Backups Add? (Full Plan Table)

Evoxt's cheapest plan, VM-0.5, is **$2.99/month** for 1 vCPU, 512 MB RAM, 5 GB of storage and 500 GB of monthly transfer. That runs a proxy, a bot, a DNS node or a staging box. It does not run WordPress with a handful of plugins and a database.

Most readers should start one step up: **VM-1 at $5.99/month** with 2 GB RAM, 20 GB storage and 1 TB of transfer. If you expect a second core to matter, VM-1.5 costs $6.95 and doubles the core count for 96 cents.

What follows is the full plan list with prices, then the three things that decide whether a cheap VPS stays cheap: the billing term you commit to, the add-ons that sit outside the plan price, and the traffic cap. There's also a straight answer on SATA SSD versus NVMe, because "cheap SSD VPS" listings mix both and rarely say which one you're getting.

> **Quick pick:** VM-1 — 1 vCPU, 2 GB RAM, 20 GB storage, 1 TB/month, **$5.99/month**. A small WordPress site, an API, a cron-heavy script or a Docker sandbox all fit. 👉 [Start with VM-1](https://bit.ly/EvoXt)

## All Evoxt plans and prices

Every plan below is USD, billed monthly, and includes a weekly offsite backup at no extra cost. Evoxt lists the CPU as up to 6.0 GHz on the full range, all the way down to the $2.99 plan.

| Plan | vCPU · RAM | Storage | Transfer / month | Price (USD/month) | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core · 512 MB | 5 GB | 500 GB | $2.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core · 1 GB | 10 GB | 750 GB | $4.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-1 | 1 core · 2 GB | 20 GB | 1 TB | $5.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores · 2 GB | 20 GB | 1.5 TB | $6.95 | [Deploy](https://bit.ly/EvoXt) |
| VM-2 | 2 cores · 4 GB | 30 GB | 2 TB | $11.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-3 | 4 cores · 4 GB | 30 GB | 3 TB | $14.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-4 | 4 cores · 8 GB | 60 GB | 4 TB | $23.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-6 | 8 cores · 8 GB | 60 GB | 5 TB | $29.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-8 | 8 cores · 16 GB | 80 GB | 6 TB | $47.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-12 | 16 cores · 16 GB | 80 GB | 8 TB | $60.95 | [Deploy](https://bit.ly/EvoXt) |
| VM-16 | 16 cores · 32 GB | 100 GB | 10 TB | $95.99 | [Deploy](https://bit.ly/EvoXt) |

Two notes on that table. Storage is listed by capacity only, so if NVMe specifically is a requirement, ask support to confirm the media type for the plan you pick before paying. And these are the monthly rates; Evoxt's FAQ says billing terms run from monthly up to three years, and the console quotes the total for whichever term you select.

## The headline price and the number that leaves your account

A monthly rate and an advertised rate are different numbers, and the gap is where most "cheap VPS" lists quietly mislead.

SSD Nodes is the clearest example. Its homepage advertises a plan at "That's $5.50/month!" and the same page states that prices are for **three-year billing cycles**. The $5.50 is $66 divided by twelve; the actual purchase is a three-year commitment, not a monthly bill you can walk away from.

OVHcloud goes the other way. Every VPS tier is listed as "From $4.54 /month", "From $8.50 /month" and so on, with no minimum term stated on the page. A "from" price is a real entry price, but it's an entry price, and the term attached to it is something to confirm in the cart rather than assume.

Evoxt publishes one rate per plan with no separate renewal price beside it. At the monthly rate, VM-0.5 runs **$35.88** for a year, VM-1 **$71.88**, VM-1.5 **$83.40** and VM-2 **$143.88**. Prepaying a longer term changes the amount due on day one; whether it lowers the effective monthly cost depends on the quote you get at checkout, because the plan page doesn't publish a term-discount table. Compare invoice totals, not the per-month figure in the marketing line.

One more thing worth checking before you commit to any provider: the renewal price. A rate that only applies to the first invoice is a different product from a rate that applies for the life of the server. Evoxt's plan list shows a single price per configuration, which makes budgeting simpler, but the invoice for your chosen term is still the document that counts.

👉 [Check the current VM-1 rate and the billing terms on offer](https://bit.ly/EvoXt)

## Three add-ons that turn a cheap VPS into an expensive one

The plan price is rarely the whole bill. These are the line items that show up later, with verified numbers from providers that publish them.

**Backups.** Contabo charges **€5.95/month** for Auto Backup, which takes daily snapshots and keeps the last 10 versions. OVHcloud bundles daily backup of the previous 24 hours into every VPS tier. HOSTKEY includes free weekly backups. Evoxt includes weekly offsite backup at zero cost on all plans and sells an optional backup plan in the control panel's upgrade tab, priced by the VM's storage size.

**Control panels and licences.** Contabo's configurator lists cPanel at **€27.97/month**, Plesk with Linux at **€16.07/month**, and Windows Server at **€33.32/month**. Any one of those can exceed the cost of the VPS itself, which means "I need cPanel" is a budget decision, not a footnote.

**Traffic.** OVHcloud's plan table says "Unlimited traffic" on all four tiers. The footnote says Asia-Pacific locations (Mumbai, Singapore, Sydney) come with a monthly quota of **500 GB on VPS-1, 1 TB on VPS-2 and VPS-3, and 3 TB on VPS-4**, after which bandwidth is capped at **10 Mbps**. HOSTKEY's incoming traffic is free under fair use, but outgoing traffic is billed according to the traffic plan you select. Evoxt avoids the ambiguity by printing a transfer allowance on every plan, from 500 GB up to 10 TB.

Four questions to settle before you pay:

1. What is the total on the first invoice, including the term?
2. Is backup included, and how many restore points do I get?
3. Is there a panel or licence fee, and is it monthly?
4. What is the traffic cap, and what happens when I hit it — overage charge or throttle?

## SATA SSD or NVMe: what the cheap tier actually gives you

Search "cheap SSD VPS" and you'll get plans backed by two different technologies, often described with the same three letters.

HOSTKEY's published figures put the gap in concrete terms: NVMe delivers roughly **2x faster page loads** than a standard SATA SSD, **3 to 5 times the random read IOPS**, more than **2x the random write performance**, about **6x the bandwidth**, and can push past **3 GB/s** of throughput. SATA SSDs are a solid default for CMS sites and small e-commerce; the interface becomes the bottleneck under heavy load. NVMe is where databases, high-concurrency web apps and API-heavy workloads belong.

Now look at how the cheap tiers actually split:

- **SSD Nodes** ships SATA SSD on its first three plans (160 GB, 320 GB, 480 GB) and NVMe only from the 48 GB RAM plan upward (720 GB and above).
- **Contabo** makes it a same-price choice on Cloud VPS Core 8: 300 GB SSD or 150 GB NVMe. Doubling the SSD to 600 GB costs **€5.36/month**; moving to the 150 GB NVMe tier costs **€1.79/month**. The faster media is the cheaper upgrade there.
- **OVHcloud** puts NVMe in all four tiers, from VPS-1's 40 GB up to VPS-4's 200 GB.
- **Evoxt** lists capacity per plan without naming the media type, so confirm it if the storage technology is part of why you're buying.

For a static site or a small blog, the difference won't show up in a meaningful way. For a MySQL-backed store, a log pipeline or anything doing lots of small random reads, it will.

## How Evoxt's entry plans sit next to three common alternatives

| Plan | vCPU / RAM | Storage | Traffic | Price and term |
| --- | --- | --- | --- | --- |
| Evoxt VM-1 | 1 core / 2 GB | 20 GB | 1 TB/month | $5.99/month, monthly billing |
| OVHcloud VPS-1 | 2 vCores / 4 GB | 40 GB NVMe | Unmetered (APAC: 500 GB, then 10 Mbps) | From $4.54/month |
| Contabo Cloud VPS Core 8 | 8 vCPU / 24 GB | 300 GB SSD or 150 GB NVMe | 600 Mbit/s port | Monthly rate not shown in the configurator view |
| SSD Nodes SMALL | 2 vCPU / 8 GB | 160 GB SSD | 4 TB/month outbound | $66/year on a three-year cycle |

**OVHcloud VPS-1** is the strongest spec-per-dollar at the entry level: 4 GB RAM, NVMe and daily backup for a "from" price of $4.54/month, backed by a 99.9% SLA. Its catch is the Asia-Pacific traffic quota buried in the footnote.

**Contabo Cloud VPS Core 8** gives you 24 GB RAM and 8 vCPU, which is far more machine than a starter site needs. The add-on pricing is the part to model carefully, and the base monthly figure isn't visible on the configuration page, so you'll need to price it in the cart before comparing.

**SSD Nodes SMALL** offers 8 GB RAM and 160 GB of SSD for $66 a year, which looks unbeatable until you register that the rate belongs to a three-year billing cycle. If you're prepared to commit for years and want raw RAM per dollar, it's a legitimate option.

**Evoxt VM-1** sits at the low end on price and the middle on specs, with two things the others don't combine at this price: a published transfer allowance and a free weekly offsite backup on every plan.

## Pick by workload

- **A static site, a small WordPress blog, a personal API.** VM-1 at $5.99. 2 GB is the practical floor for PHP plus MySQL plus a cache; 512 MB will page.
- **The same thing with traffic spikes or a page builder.** VM-1.5 at $6.95. The second core costs 96 cents and keeps the box responsive while one process is busy.
- **Docker, a CI runner, a dev environment with a database and a couple of services.** VM-2 at $11.99 gives 4 GB, which is where containers stop fighting each other for memory.
- **Several sites on one box.** VM-3 at $14.99 (4 cores, 4 GB) or VM-4 at $23.99 if those sites carry real traffic and a shared database.
- **A production database, a scraping fleet or anything CPU-bound.** VM-6 or VM-8 at $29.99 and $47.99. Evoxt's pitch here is single-core clock speed, which matters more for PHP and Python workloads than core count does.
- **Anything below VM-1.** A VPN endpoint, a monitoring agent, a DNS secondary, a jump host. Don't put a website on it.

👉 [Compare the VM-1, VM-1.5 and VM-2 configurations](https://bit.ly/EvoXt)

## FAQ

**Can a $2.99/month VPS run WordPress?**
It can boot it. It won't be pleasant. 512 MB RAM with 5 GB of disk leaves no room for a plugin set, a database and a cache, and you'll be fighting the disk long before you hit a traffic limit. VM-1 at $5.99 with 2 GB RAM and 20 GB is the realistic entry point.

**Is the monthly transfer a hard cap?**
It depends on the provider. Evoxt prints a monthly allowance per plan (500 GB on VM-0.5 up to 10 TB on VM-16). OVHcloud advertises unlimited traffic but applies quotas in Asia-Pacific and throttles to 10 Mbps past them. HOSTKEY bills outgoing traffic by plan. Read the footnote, not the feature bullet.

**Will the price go up at renewal?**
Check what the invoice says for the term you selected. Some providers advertise a first-term rate and bill differently afterwards; others publish a single rate per plan. Evoxt's plan page shows one price per configuration with no separate renewal column, and prepayment terms run from monthly to three years.

**Is NVMe worth paying more for on a cheap plan?**
For a database, an API under concurrent load, or anything doing heavy random reads, yes. For a static site or a low-traffic blog, the difference is unlikely to be visible. If a provider offers both at the same price, take NVMe.

**Is there a promo code?**
Coupon aggregator sites list several codes for Evoxt, but none of them can be verified from outside the checkout, and code fields sometimes don't appear when discounts are applied automatically. Treat any code as a maybe, apply it before paying, and confirm the total changed.

## The rule to take away

One box for a site or an app, lowest monthly number that still works: **VM-1, $5.99/month**. You know you'll want a second core: **VM-1.5, $6.95/month**. More than one site, or a database with actual traffic: start at **VM-2 ($11.99)** rather than upgrading a too-small plan three months in.

Before you pay, confirm two things: the invoice total for the billing term you picked, and whether the backup tier you need is the free weekly one or the paid plan priced by storage size in the control panel.

👉 [See Evoxt's current plans and start with VM-1](https://bit.ly/EvoXt)
