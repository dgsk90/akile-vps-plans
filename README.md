# Akile VPS Review: Is 10Gbps for ¥50 Real, Which Chinese ISP Gets a Direct Route, and Which Plan Is Enough? (Full Plan and Price Table)

AkileCloud sells port speed cheap. Hong Kong, Japan, Singapore, Taiwan, Korea, the US, the UK and Germany, KVM on Proxmox, a self-built control panel with an API, and DNS streaming unlock switched on for every node. Prices start around $1.40 a month, and one Hong Kong tier advertises 10Gbps with unmetered traffic for ¥50 a month.

What the company does not sell is a fast route into mainland China, and it says so itself: nodes "come with DNS streaming unlock but do not guarantee direct connections to mainland China." A hands-on review published in May 2026 measured the Hong Kong HKLite plan at roughly **300 ms average latency** from a China Mobile line, with all three carriers leaving the country through the United States and only China Mobile coming back direct.

Three things decide whether you should order: which broadband you're on, how much traffic and disk your workload actually burns, and where the cheap price stops being cheap. All three are covered below, along with every plan I could verify a published spec and price for.

> **Quick verdict.** If streaming and international bandwidth are the point, start with the Hong Kong HKLite entry tier at **¥50/month with unmetered traffic**. If you just want the cheapest possible test of the network, HKLite-One at **$12.21/year** is the floor. If your main line is China Telecom and you care about latency, buy nothing here.
> 👉 [Check current Hong Kong plan availability and pricing](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## AkileCloud plans and prices

The catalogue rotates constantly, and the shop lists more configurations than any single snapshot captures. The tables below use plans with published specs and prices that can be verified from AkileCloud's own offer post and a plan index that refreshes daily. CNY figures are list prices; USD in brackets is the conversion published alongside them.

### Hong Kong and Asia-Pacific

| Plan | CPU / RAM / Disk | Port | Monthly traffic | Price | Order |
| --- | --- | --- | --- | --- | --- |
| HKLite (2026 entry) | 1 core / 1GB / 20GB | 10Gbps | Unmetered | ¥50/mo | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-One | 1 core / 1GB / 5GB | 5Gbps | 1TB | $12.21/yr (¥88.48) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKLite-Starter | 1 core / 1GB / 10GB | 2Gbps | 5TB | ¥437.40/yr (~$65.44) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKS-Starter | 1 core / 1GB / 5GB | 1Gbps | 1TB | $3.45/mo (¥24.99) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Mini | 1 core / 1GB / 5GB | 1Gbps | 1TB | $2.76/mo (¥19.99) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGLite-Standard | 1 core / 1GB / 10GB | 1.5Gbps | 6TB | ¥874.90/yr (~$130.89) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPLite-One | 1 core / 1GB / 5GB | 500Mbps | 1TB | $13.80/yr (¥99.99) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-Lite | 1 core / 1GB / 10GB | 2Gbps | 3TB | ¥420.00/yr (~$62.83) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPBase-Standard | 1 core / 2GB / 10GB | 2Gbps | 6TB | ¥840.00/yr (~$125.66) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPIIJ-Starter | 1 core / 1GB / 20GB | 1Gbps | 2TB | ¥583.20/yr (~$87.25) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Mini | 2 cores / 2GB / 10GB | 2.5Gbps | 2.5TB | ¥259.90/yr (~$38.88) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Starter | 2 cores / 2GB / 10GB | 2.5Gbps | 5TB | ¥499.90/yr (~$74.79) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| JPHyper-Standard | 2 cores / 2GB / 20GB | 2.5Gbps | 10TB | ¥999.90/yr (~$149.59) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| TWLite-Mini | 1 core / 2GB / 10GB | 1Gbps | 1.5TB | ¥249.90/yr (~$37.39) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

The two HKLite rows are not the same product. HKLite-One is the older 5Gbps / 1TB / 5GB annual tier that has been circulating since 2025; the ¥50 plan is the 2026 10Gbps / unmetered / 20GB tier that the May 2026 hands-on review actually tested. Same name, different hardware generation, so don't compare them as one offer.

### US, UK and Germany

| Plan | CPU / RAM / Disk | Port | Monthly traffic | Price | Order |
| --- | --- | --- | --- | --- | --- |
| UKLite-Starter | 1 core / 1GB / 10GB | 500Mbps | 1TB | $2.20/mo (¥15.99) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXPremium-M1 | 1 core / 1GB / 10GB | 100Mbps | 500GB | $4.14/mo (¥29.99) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXLite-Standard | 2 cores / 4GB / 20GB | 5Gbps | 10TB | ¥699.90/yr (~$104.71) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXHyper-Standard | 2 cores / 4GB / 20GB | 5Gbps | 40TB | ¥874.90/yr (~$130.89) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXISP-Mini | 1 core / 2GB / 10GB | 1Gbps | 5TB | ¥499.90/yr (~$74.79) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| LAXISP-Starter | 2 cores / 2GB / 20GB | 1Gbps | 10TB | ¥899.90/yr (~$134.63) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SJCBGP-2048M | 1 core / 2GB / 15GB | 10Gbps | 5.1TB | ¥747.50/yr (~$111.83) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| DEBase-Standard | 1 core / 2GB / 10GB | 2Gbps | 6TB | ¥554.88/yr (~$83.01) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| DELite-Pro | 2 cores / 4GB / 30GB | 1Gbps | 4TB | ¥499.90/yr (~$74.79) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| DELite-MAX | 2 cores / 4GB / 50GB | 1Gbps | 8TB | ¥799.90/yr (~$119.67) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| DE9929-Standard | 1 core / 1GB / 20GB | 500Mbps | 2TB | ¥799.00/yr (~$119.53) | [ Order](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

Prices and stock move; the shop page is the final word on both.

## What your broadband actually gets you

This is the part most write-ups skip, and it decides your experience more than the CPU or the price does. The May 2026 test ran traceroutes from all three Chinese carriers into the Hong Kong HKLite box:

| Carrier | Outbound | Return | Experience |
| --- | --- | --- | --- |
| China Telecom | Detours via San Jose, US | Also via the US | Worst of the three |
| China Unicom | Detours via San Jose | Some nodes via Japan or direct | Middling |
| China Mobile | Detours via the US | **Direct Hong Kong → mainland** | Best of the three |

Same server, same price, three very different products depending on who bills your internet. On China Mobile the direct return path turned into a YouTube 4K test peaking above **210,000 Kbps** with smooth playback throughout. On Telecom the same box carries a trans-Pacific round trip in both directions, which is why the average sits near 300 ms.

Raw throughput was never the problem. Asian nodes pulled over 2.5Gbps on download, the Hong Kong local node peaked above 8Gbps, and uploads toward mainland nodes sat around 250Mbps with Europe and the US around 400Mbps. One test summarised it as "noticeable fluctuation, extremely high ceiling," which is a fair description of a big international pipe that was never tuned for one country.

Practical rules from that data:

- **China Mobile at home** → this is the configuration AkileCloud happens to suit, and video is where it shows.
- **China Unicom** → usable, expect variance by node.
- **China Telecom primary line** → latency will feel wrong no matter which plan you buy.

The same test answered the hosting question directly: detoured mainland routing plus a product positioned for international bandwidth means it suits sites and services aimed at overseas visitors, not at mainland readers.

👉 [See the Hong Kong plans that use the direct return path](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## The port speed is real. The CPU is rented, shared, and can be stolen.

Two different reputations get mixed up in reviews of this provider, so keep them apart.

On bandwidth, the claims hold. Hong Kong 1Gbps plans have been observed pulling 900Mbps to 1Gbps, and 5Gbps ports come close to advertised off-peak. Multiple independent speed tests are cited for this, and it matches the hands-on numbers above.

On compute, expectations need to be lower. The HKLite box tested in May 2026 runs an **AMD EPYC 7302** at around 3.0GHz, with about 979MB of the 1GB actually usable, 1024MB of swap allocated by default, and disk read/write around **105MB/s** — SATA SSD territory, not NVMe. A LowEndTalk user who bought a $14/year plan reported "high iowait and CPU steal," while conceding the price and his workload (a simple API plus two Discord bots) made it tolerable. A comparison writeup describes the CPU and disk I/O as "adequate but not exceptional." Another notes that resources are shared, so CPU and disk fluctuate with whatever your physical host neighbours are doing.

What that means in practice: streaming, reverse proxying, traffic forwarding, lightweight APIs, a small static site, a download box. Not databases under load, not compiling, not a game server, not anything where a noisy neighbour ruins your evening.

## Where the cheap price shows up later

Three limits do the actual cost control, and they're easy to miss on the order page.

**Traffic counts both ways.** Upload plus download. A 1TB plan is 500GB in each direction. For scale, one writeup estimates 1TB covers roughly 250 hours of HD or 100 hours of 4K video.

**Overage throttles, it doesn't disconnect.** Hit the cap and the port drops to **10Mbps** until the cycle resets. Your service keeps running, just slowly.

**Traffic resets are sold per plan.** AkileCloud's own offer post prices them individually: ¥7.00 on HKLite-One, ¥9.99 on JPLite-One, ¥14.00 on UKLite-Starter, ¥15.00 on HKS-Starter, ¥19.99 on SGLite-Mini and ¥35.00 on LAXPremium-M1. Budget accordingly if you routinely blow through caps.

**Entry storage is small.** The 5GB tiers are exactly that. 5GB is enough for an OS and not much else; the May 2026 test on the 20GB tier had about 15GB free after installing BaoTa plus an LNMP stack, and roughly 587MB of RAM left. Plan your stack before you pick the disk size, not after.

👉 [Compare the traffic caps and reset prices on the current plan list](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## Streaming unlock: DNS, not a residential IP

Every node ships with DNS-based unlock for streaming services. That is how AkileCloud gets Netflix, Disney+ and the rest to resolve into the right region without handing you a residential address.

The May 2026 test on the Hong Kong box found Netflix on the Hong Kong library, Disney+ Hong Kong, TikTok Taiwan, MyTVSuper unlocked, YouTube clean, and most AI platforms reachable, with a vague caveat about "some risk of reduced AI quality" on a few of them. IP checks told a blunter story: ipinfo.io classified the address as hosting, ping0.cc as IDC/datacenter, a broadcast range with ordinary cleanliness.

One observation from that test is worth repeating because it runs against the usual shopping logic: a genuine Hong Kong residential IP would actually trigger *more* streaming restrictions, and DNS-based unlocking is close to invisible in daily viewing. You are not buying a clean IP. You are buying a working redirect.

The other thing to understand is that unlock is not a permanent feature you configure once. Platforms keep changing detection, and a provider using DNS methods tends to survive longer than one relying on IP reputation, but nobody can promise a given service stays unlocked for the life of your plan. One writeup describes user-reported success rates as stable from early 2024 into 2025 — a track record, not a guarantee.

## Refunds, payment and the checkout

Refund policy is the least generous part of the deal, and the sources disagree enough that you should assume the strict version. AkileCloud's own notes state plainly that refunds are not available once service provisioning begins. A separate writeup mentions a 7-day window, but hedges it with conditions on traffic and bandwidth usage that are never given a number, and admits the terms are vague. Buy the smallest plan in a new region first if you're unsure.

Payment is friendlier than most: Alipay, UnionPay, PayPal and various cryptocurrencies, with the provider's own offer post also listing Stripe, USDT and FPS.

On promo codes, don't build a plan around one. A redemption code field sits on the product page before checkout, and third-party roundups publish several codes for the LAX lines and a sitewide discount, while at least one comparison writeup states that AkileCloud has no standing public code. Fill the field if you have one and watch whether the cart total actually moves. Annual billing is where the real discount lives, advertised at up to 30% off.

Interfaces are in English, documentation leans Chinese, and English-language support is described in one review as hit or miss.

## FAQ

**Does AkileCloud have direct connections to mainland China?**
No. The company says so on its own pages, and traceroutes confirm it: all three carriers head out through the US. Only China Mobile gets a direct return path from Hong Kong.

**Can I host a website for mainland visitors on it?**
You can host a website; mainland visitors will feel the detour. The May 2026 test concluded it suits services aimed at overseas users. Fine for an API, a blog with a CDN in front, or a tool used outside China.

**Will I actually get 10Gbps?**
From Hong Kong and Asia-Pacific nodes, one test exceeded 8Gbps. Toward mainland China you're limited by routing, not by the port: uploads there measured around 250Mbps. The 10Gbps figure is a port speed, not a promise about one country.

**Monthly or annual?**
Annual, if you've already confirmed the region works for you, because that's where discounts sit. Monthly first for any new location, given the no-refund-after-provisioning rule.

**Is it good for CPU-heavy work?**
No. Shared fair-share cores, reported steal and roughly 105MB/s disk on the tier tested. Use it for bandwidth, not compute.

## Which plan fits

- **Region-locked streaming only** → the cheapest Hong Kong tier, ¥50/month unmetered or HKLite-One at $12.21/year. Nothing above that buys you a better Netflix library.
- **Traffic forwarding, CDN origin, large file serving** → the 5Gbps tiers with multi-terabyte caps: LAXLite-Standard (10TB), LAXHyper-Standard (40TB), SGLite-Standard (6TB), HKLite-Starter (5TB).
- **Light websites and APIs for non-China audiences** → any 2GB plan with 20GB of disk; skip the 5GB tiers unless the OS is all you're installing.
- **Databases, builds, game servers, anything latency-sensitive from China Telecom** → not this provider, at any price.

Two things to confirm on the order page before you pay: whether the tier you clicked is billed monthly or annually (the same family name appears in both), and that the traffic figure is bidirectional, so halve it when you compare against providers who only count one direction.

👉 [Open the current AkileCloud plan list and pick the tier that matches your use case](https://akile.io/shop/server?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)
