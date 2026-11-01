# colocation services: What a Rack Unit Really Costs, Which Space Tier Fits Your Hardware, and the Fees Most Listings Don't Mention

Colocation means you own the servers and rent the space, power, cooling, and network connectivity for them inside a professional data center. It makes sense once you have hardware worth keeping: instead of running gear out of an office closet, you get redundant power, enterprise cooling, physical security, and a multi-gigabit network connection that no single office could justify. This guide walks through what colocation plans actually include, what they cost in 2025–2026 market conditions, and how Sharktech's plans — from single server space in Denver starting around $35/month in its partner listings up to full 42U cabinets — compare against both the market and the fine print.

One thing to know upfront: Sharktech doesn't publish fixed prices on its colocation page. Pricing is configured in the customer portal, and cages or custom deployments get itemized quotes. The numbers below come from the company's partner and promotional listings plus third-party hosting directories, and we'll flag exactly where those sources disagree — including a setup-fee discrepancy most affiliate writeups skip.

> **Quick take:** For a single 1U–2U server, Sharktech's Denver location is the price leader, with partner listings showing 1U–6U space from **$35/month** including a 10Gbps-class port and bundled DDoS protection. Cabinet space runs roughly $449–$899/month depending on size. Most listings advertise free setup, but third-party SKU records show $150–$500 setup fees on some plans — confirm the one-time charge in the portal before ordering. **👉 [Check current Sharktech colocation pricing in the portal](https://bit.ly/SharKtech)**

## What you're actually renting with colocation

You're renting four things: physical space (measured in rack units, or U), power delivery, a network port with bandwidth, and hands on site. You keep ownership and control of the hardware — you can log into it, reinstall it, swap drives, and eventually take it home. That's the core difference from cloud: with colocation you own the asset, while with cloud services you rent someone else's infrastructure.

Retail colocation typically comes in three shapes: single-server or partial-rack space for a few boxes, cabinet space (quarter, half, or full racks) for growing deployments, and private cages for serious footprints. Most guides stop at that description. What actually matters when comparing offers is the fine print around each of those four rented things — power wattage included, port speed, whether bandwidth is metered or unmetered, what remote hands cost, and what one-time fees apply at signup. Those details are where cheap-looking quotes get expensive.

## Sharktech's colocation plans and pricing

Sharktech's space options run from a single server up through shared 42U–48U cabinets to custom cages, across five data centers: Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam. The company operates its own network (AS46844) rather than reselling someone else's, which affects everything from pricing to how DDoS protection is applied.

Here are the single-server tiers as listed in Sharktech's partner and promotional materials:

| Space tier | Location | Listed starting price | Network / power |
| --- | --- | --- | --- |
| 1U–6U | Denver | $35/mo | 10G–100Gbps port, 200–1200W |
| 1U–6U | Las Vegas | $65/mo | same |
| 1U–6U | Los Angeles / Chicago / Amsterdam | $99/mo | same |

For larger footprints, third-party directories that track Sharktech's plans list these specific SKUs:

| Plan | Listed monthly price | Listed setup fee | Notes |
| --- | --- | --- | --- |
| 4U servers (200–1200W) | $129/mo | $150 | 1G unmetered, upgradeable to 40Gbps |
| 1/4 cabinet (10U, 1600–5500W) | $449/mo | $500 | 1G unmetered, upgradeable to 100Gbps |
| 1/2 cabinet (20U, 1600–5500W) | $599/mo | $500 | same, plus cage/BGP/cross-connect options |
| Full cabinet (42U, 1600–5500W) | $899/mo | $500 | same network options |

Two honest caveats before you treat any of these numbers as final. First, partner listings quote different figures than the SKU directory for cabinet space — some Sharktech promotional material lists 10U–42U space starting at $280/month in Denver, $520 in Las Vegas, and $792 in Los Angeles, Chicago, and Amsterdam, which undercuts the directory SKUs above. The likeliest explanation is that the directory tracks specific configurations while the promotional figures are location-based starting points, but either way the number you'll actually pay comes from the portal configuration. Second, the same partner material that advertises those low starting prices claims free setup with no one-time fee, while the SKU directory shows $150 on the 4U plan and $500 on cabinet plans. That's a real gap worth tens or hundreds of dollars, and it's exactly why you should confirm the setup charge in the portal before committing. **👉 [Configure your space and see the actual charges before you order](https://bit.ly/SharKtech)**

Bandwidth is another spot where listings disagree with themselves: some describe plans as unmetered, others as including 300TB or more of traffic on a 10G–100Gbps port. Both descriptions appear in Sharktech's own materials, so ask which billing method applies to the configuration you're buying. Either way, a 300TB monthly allowance on a 10Gbps port is far more than a typical single server consumes.

## What's included beyond the rack space

The reason to pick an infrastructure provider over a generic host is the network, and this is where Sharktech's setup does real work. All colocation plans ride on the company's own AS46844 backbone with 40/100G network design, and third-party plan listings consistently note bundled DDoS protection rated at 60 Gbps running on a multi-100G backbone. Protection is standard rather than an add-on, and one long-running third-party review notes it can scale toward the 1 Tbps range for customers who need it. That review also relays feedback from a gaming company that stayed up through repeated 3–8Gbps attacks without interruption — worth noting, though it's a single customer's account rather than an audited benchmark.

Other inclusions that show up across the plan listings: IPv6 support, a bare-metal management panel, BGP sessions and blended IP transit as options, dedicated cross-connects, and a 99.99% uptime goal. Treat that last figure as a target, not a contractual SLA — the listings say "goal," and no source we found documents enforcement terms.

Custom work goes beyond the standard tiers. Private cages, custom power requirements, and multi-site high-availability designs are quoted item-by-item by the sales team rather than pulled from a price list.

## Five locations, and why Denver is the cheap one

Sharktech runs colocation space in Los Angeles, Las Vegas, Denver, Chicago, and Amsterdam, hosted inside partner facilities including Equinix, CoreSite, H5 Data Centers, and Flexential, with Crown Castle also in the mix.

Denver is the one to watch. Sharktech colocates in the H5 Data Center campus in the heart of the city's technology sector, and that facility is SOC-2 compliant with fully redundant power and network and 24/7 on-site engineers. It's also where the company expanded specifically to scale its colocation offering, and it's the location behind the $35/month entry price — roughly a quarter of what comparable 1U space lists for in Chicago. If your users are spread across North America rather than clustered on a coast, Denver's central location plus its pricing makes it the default answer for a first deployment.

Las Vegas is newer: that facility opened in May 2024 at Flexential's LAS0 site, and it exists because Vegas traffic previously looped through Los Angeles — founder Tim Timrawi's own framing was that a Las Vegas resident connecting to a Las Vegas server was effectively routing through LA anyway. The fix was local transit providers plus a dedicated 100GE circuit to Los Angeles, with Sharktech citing roughly a 50% latency reduction for local users. Enterprise-grade security, net-neutral connectivity, and battery-plus-generator power redundancy come standard at that site. The company itself was founded in 2003 and is headquartered in Las Vegas, so the home-town facility was a long time coming.

The other three locations — Los Angeles, Chicago, and Amsterdam — sit at the top of the single-server price ladder ($99/month listed) but make sense when proximity matters: west coast latency, Chicago's central network density, or European data residency requirements. **👉 [Compare the five locations against where your users actually are](https://bit.ly/SharKtech)**

## How the pricing stacks up against the market

Context makes Sharktech's numbers legible. Industry benchmarks gathered by QuoteColo put 2026 US 1U colocation at roughly $120–$140/month in Chicago, $120–$240 in Los Angeles and Ashburn, and as low as $50–$100 in secondary markets like Phoenix. CBRE's widely cited market average for H2 2025 was $195.94 per kW per month for space alone — closer to $250/kW all-in once power delivery and cooling are added. Against that backdrop, $35/month for 1U–6U in Denver is well below any published US market rate, and even the $99 tier lands at the bottom of the LA and Chicago ranges.

The competition, from tracked plan listings in the same category:

| Provider | Plan | Monthly price | Setup | Key limits |
| --- | --- | --- | --- | --- |
| InterServer | Secaucus single server (1U) | $100/mo | Free | 250W, 1Gbps unmetered |
| Dedicated.com | Single 1U server | $115/mo | Free | 100TB traffic |
| Dedicated.com | Single 2U server | $135/mo | Free | 300W |
| Server Pronto | Full tower | $135.95/mo | $79.95 | 2,500GB traffic, 100Mbps port |
| RackNerd | Single server (1U–4U) | $179/mo | Free | 10TB traffic, 1A@120V |
| DigitalSpace | Rack space (10U) | $400/mo | $200 | Unmetered |
| Rad Web Hosting | 1/2 rack (~20U) | $479/mo | Free | Unmetered |
| DediSpec | Half cabinet (21U) | $450/mo | Free | 200TB, Kansas City, 1664W usable |
| Hurricane Electric | Cabinet + GigE | $600/mo | Free | 42U, power and 1Gbps included |

A few honest observations. InterServer's $100 Secaucus plan is the closest single-server rival to Sharktech's low tiers, though it doesn't include comparable DDoS protection. For half cabinets, Rad Web Hosting and DediSpec undercut or match Sharktech's $599 on paper, and one full-cabinet competitor lists a 42U at $500/month — cheaper than Sharktech's $899 SKU, though that listing includes 120V/20A power (1920W usable) versus Sharktech's 1600–5500W envelope, so the two aren't equivalent on power. If absolute lowest cabinet price in a secondary market is your only criterion, those options exist. What none of the cheaper listings match is Sharktech's bundled 60Gbps DDoS protection and self-owned 10G–100Gbps backbone, which is precisely what you're paying a premium for if your servers face the public internet under hostile traffic.

## Ordering, and the three gotchas that cost people money

The process itself is three steps: pick a location based on where your users and network requirements sit, submit your hardware specs (rack units, power draw, port needs, growth expectations) through the portal, and coordinate shipment and installation requirements with Sharktech before the equipment leaves your hands.

The gotchas live in the terms, not the process. First, remote hands: 24/7 on-site technicians handle emergencies, but hands-on work beyond that gets scoped and priced individually with the team. For reference, advanced remote hands run $2–$4 per minute across the industry, so knowing what your agreement covers before a 3 a.m. drive swap matters. Second, confirm the current facility and specifications with the team before planning a shipment — Sharktech's own Denver page says exactly this, because facility details can change and shipping a server to the wrong address is an avoidable disaster. Third, review power, connectivity, installation, and remote-hands charges in the portal before ordering; the company's colocation page commits to showing all of these upfront, and the setup-fee discrepancy documented above is why that commitment is worth using.

Payment flexibility is unusually broad here: credit and debit cards, PayPal, AliPay, wire transfer, Western Union, and Bitcoin, with support available around the clock across email, help desk, phone, live chat, and messaging apps.

## When colocation is the wrong call

If you don't already own hardware, colocation mostly adds steps. The economics only work when you have servers worth housing — otherwise you're buying hardware, shipping it, and accepting hardware-refresh responsibility to rent space for it. In that case, renting a dedicated or bare-metal server is the simpler path, and Sharktech sells those too (promotional listings show single Xeon configurations with unmetered gigabit connectivity from $59–$99/month, including the same DDoS-protected network and free setup). Colocation also isn't for workloads that fit comfortably in a VPS: if your site runs fine on a small cloud instance, spending $35/month plus hardware on rack space solves a problem you don't have.

## FAQ

**Is Sharktech's 1U–6U colocation really unmetered?**
Listings differ: some say unmetered, others say 300TB+ of traffic included on the 10G–100Gbps port. Both figures come from Sharktech's own materials, so confirm the billing method for your specific configuration in the portal.

**Why are the setup fees reported differently?**
Partner materials advertise free setup with no one-time fee, while third-party SKU records list $150 on the 4U plan and $500 on cabinet plans. Treat the portal checkout as the source of truth and check the line item before paying.

**What does DDoS protection cost extra?**
Nothing on the standard tiers — listings include 60 Gbps of protection running on Sharktech's multi-100G backbone as part of the plan, with higher-scale protection available as an upgrade.

**Can Sharktech handle BGP and custom networking?**
Yes. BGP sessions, blended IP transit, dedicated cross-connects, and private cages are all listed options, with custom and multi-site HA deployments quoted item-by-item.

## Picking a tier, and one last check before you pay

If you're housing one or two servers and have no strong location constraint, Denver at $35–$65/month listed is the strongest value in the current lineup — SOC-2 facility, 10Gbps-class port, DDoS protection included. Choose Las Vegas or Los Angeles for west coast latency, Amsterdam if your users or compliance requirements sit in Europe. Once your footprint passes about 10U, skip the per-server math and get a quote on quarter or half cabinets, since the per-unit economics shift fast at that size. And if a full 42U at $899/month listed feels steep, remember power included is 1600–5500W — compare providers on watts delivered, not just rack units.

Before you click buy on any of these, confirm two things in the portal: the actual setup fee on your configuration, and whether your bandwidth bills as unmetered or metered against 300TB. Both numbers vary by listing, and both change your first invoice. **👉 [Set up your Sharktech colocation configuration and verify the final charges](https://bit.ly/SharKtech)**
