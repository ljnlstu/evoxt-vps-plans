# Evoxt VPS: What All 11 Plans Cost, Which One You Actually Need, and Why Hong Kong and Osaka Give You Half the Transfer (Full Price Table)

Evoxt sells VPS plans from **$2.99 to $95.99 per month**, and the one most buyers settle on is **VM-1 at $5.99/month**: 1 core, 2 GB RAM, 20 GB storage, 1 TB of monthly transfer. A personal site, a small API, a Discord bot or a Docker sandbox fits in VM-1 or the $11.99 VM-2 without much deliberation.

The harder decisions are elsewhere. Evoxt runs three regional price tiers where identical plans get different transfer allowances, publishes add-on prices that usually cost more than simply moving up a tier, and leaves out a few features some workloads can't live without. All three are worth knowing before you pay.

> **Quick pick:** VM-1 at **$5.99/month** (1 core / 2 GB / 20 GB / 1 TB) covers a personal site, a small API or a single Docker host. Take VM-2 at **$11.99** if a database runs alongside the app. 👉 [Open the Evoxt console and pick your region and plan](https://bit.ly/EvoXt)

## Every Evoxt plan, side by side

The table below is the Standard region: United States, United Kingdom, Canada, Germany, Poland, Amsterdam, Japan (Tokyo), Malaysia and Australia. Every plan on the list includes a weekly offsite backup at no extra cost.

| Plan | vCPU / RAM | Storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 500 GB | **$2.99/mo** | [Get VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 750 GB | **$4.99/mo** | [Get VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | 1000 GB | **$5.99/mo** | [Get VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | 1500 GB | **$6.95/mo** | [Get VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | 2000 GB | **$11.99/mo** | [Get VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | 3000 GB | **$14.99/mo** | [Get VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | 4000 GB | **$23.99/mo** | [Get VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | 5000 GB | **$29.99/mo** | [Get VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | 6000 GB | **$47.99/mo** | [Get VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | 8000 GB | **$60.95/mo** | [Get VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | 10 TB | **$95.99/mo** | [Get VM-16](https://bit.ly/EvoXt) |

Two things about this table are worth flagging. Prices are quoted in USD and billed monthly, and the pricing page shows one rate per plan with no separate introductory price and renewal price. What you see is what the invoice says, month after month. Also, the CPU column is where Evoxt's marketing lives: the site advertises "up to 6.0 GHz+", while Evoxt's own statement to VPSBenchmarks describes "CPUs with frequencies that are at least 3.5 GHz and above". Read those together and you get a base clock floor of 3.5 GHz with a boost ceiling around 6.0 GHz. Evoxt does not publish which CPU model sits in which plan.

## Same price, less transfer: Hong Kong, Osaka and Malaysia Premium

This is the part that changes monthly bills. Hong Kong and Osaka sit in what Evoxt calls the Premium Network. Every plan costs exactly what it costs in the Standard region, and every plan gets half the transfer.

| Plan | Price | Standard | Hong Kong / Osaka | Malaysia (Premium) |
| --- | --- | --- | --- | --- |
| VM-0.5 | $2.99 / $3.49 | 500 GB | 250 GB | 150 GB |
| VM-0.75 | $4.99 | 750 GB | 250 GB | 250 GB |
| VM-1 | $5.99 | 1000 GB | 500 GB | 300 GB |
| VM-1.5 | $6.95 | 1500 GB | 500 GB | 300 GB |
| VM-2 | $11.99 | 2000 GB | 1000 GB | 600 GB |
| VM-3 | $14.99 | 3000 GB | 1000 GB | 700 GB |
| VM-4 | $23.99 | 4000 GB | 2000 GB | 1000 GB |
| VM-6 | $29.99 | 5000 GB | 2000 GB | 1250 GB |
| VM-8 | $47.99 | 6000 GB | 3000 GB | 2000 GB |
| VM-12 | $60.95 | 8000 GB | 3000 GB | 2500 GB |
| VM-16 | $95.99 | 10 TB | 5000 GB | 4000 GB |

The VM-0.5 row is the only one where the price differs: Malaysia (Premium) charges $3.49 instead of $2.99. Everything else matches on price and diverges on bandwidth.

Concretely: **the same $5.99 buys 1 TB in the Standard region, 500 GB in Hong Kong or Osaka, and 300 GB in Malaysia (Premium).** If you're moving 800 GB a month, a Hong Kong VM-1 is over its allowance every single month while the identical Standard plan sits comfortably under it. The region you click first determines your bandwidth budget more than the plan tier does.

What happens when you exceed it isn't stated in one place. Evoxt's price list sells additional transfer at **$3/TB in Standard, $12/TB in Premium, and $24/TB in Premium Plus**, which means overage in Hong Kong or Osaka costs four times what it costs in Germany. VPSBenchmarks, meanwhile, describes Evoxt's model as an allowance followed by throttling rather than billing. Treat the allowance as a hard ceiling you plan around, and confirm which behaviour applies to your plan at checkout.

👉 [Start on a Standard-region plan if you need the full terabyte](https://bit.ly/EvoXt)

## Adding a core costs $3. Upgrading a whole tier costs less.

Evoxt publishes its add-on prices: **$3/month per extra vCore, $2/month per extra GB of RAM, $3/month per extra IPv4 address.** They're available from the upgrade tab in the VM control panel, which makes them convenient. Convenient isn't the same as cheap. Run the arithmetic:

- VM-1 ($5.99) plus one vCore ($3) is **$8.99**. VM-1.5, which ships with 2 cores and 2 GB, costs **$6.95**.
- VM-2 ($11.99) plus two vCores ($6) is **$17.99**. VM-3, with 4 cores and 4 GB, costs **$14.99**.
- Only short on memory? VM-1 plus 2 GB of RAM ($4) is **$9.99**, still above VM-1.5 at **$6.95**, and VM-1.5 also hands you a second core.

The pattern holds across the ladder. If a plan leaves you short on two resources at once, the next tier is almost always the cheaper route. Add-ons earn their place in narrower cases: you want more transfer without touching anything else, or the server is already configured and you'd rather pay a premium than move.

## What independent testing found on four of these plans

VPSBenchmarks buys and tests plans itself, and it has run four Evoxt configurations between November 2025 and August 2026. Grades run A (best) to F.

| Plan | Price | Tested | Web / Raw CPU / Stability / Disk IO / Network |
| --- | --- | --- | --- |
| VM-1 | $5.99 | Feb 25, 2026 | B / **E** / C / B / D |
| VM-2 | $11.99 | Aug 19, 2026 | C / D / **E** / B / C |
| VM-4 | $23.99 | Nov 30, 2025 | B / B / D / B / D |
| VM-8 | $47.99 | May 24, 2026 | A / **A** / D / C / **E** |

Overall scores across those four tests were 50 to 62 out of 100, and the consistency score, which tracks how stable performance stays over time, is **62**. VPSBenchmarks treats anything above 65 as consistent.

The table is a useful corrective to the "6.0 GHz" headline. The $5.99 plan graded **E on raw CPU**, the worst of the four, while the $47.99 plan graded **A on raw CPU and E on network**. Whatever the clock speed is on paper, the plan you pick matters more than the brand claim. Provisioning speed was reasonable: across six test orders, the median time from payment to SSH access was **175 seconds**, the average 261 seconds, the slowest 600.

None of this says Evoxt is slow. It says the cheap tiers and the expensive tiers don't perform alike, so don't buy VM-0.5 expecting VM-8 behaviour.

## What Evoxt includes, and what it doesn't

Included on every plan:

- **Weekly offsite backup at no cost**, restorable from the panel
- A custom control panel with firewall rules you set without logging into the VM
- VNC console access, VM cloning, sub-accounts for separate admin, technical and billing access
- A REST API at api.evoxt.com, IPv6 support, SSH key setup
- Monitoring charts for CPU, bandwidth, RAM and storage
- Plan upgrades from the admin console
- 18 data centers across 4 continents

Not included, and these are hard stops for some workloads:

- **No DDoS protection.** If you're hosting a game server or anything that attracts attacks, this is disqualifying.
- **No reverse DNS.** Mail servers and some integrations need PTR records. Evoxt doesn't offer them.
- **No hourly billing.** One month is the shortest commitment, so a two-hour experiment costs a full month.
- **No block storage, object storage or load balancer.** Storage scales with the plan, not independently.
- **No shelving.** You can't park a server and stop paying for compute while keeping the disk.

Evoxt is unmanaged. You get root, a control panel and an OS choice, and you install and maintain the rest yourself.

👉 [Check the current feature list and plan availability in the Evoxt console](https://bit.ly/EvoXt)

## Billing, payment and the discount question

Billing runs **monthly up to 3 years**. You can also top up account credit and let Evoxt apply it to future invoices. Payment methods are credit cards, debit cards, PayPal, Bitcoin and USDt Tron. There is no hourly option, and the pricing page doesn't publish an annual or multi-year discount rate, so don't assume prepaying three years saves money until the checkout total shows it.

On coupons: Evoxt's own price list contains no discount codes and no limited-time offers. Third-party affiliate pages have circulated a 40% recurring code for VM-1 and above, along with a discounted figure around $3.59/month for VM-1. Those codes don't appear anywhere on Evoxt's own pages, the pages carrying them are promotional and several months old, and they can't be confirmed as active. The only reliable test is the total at checkout: if a code validates and the number drops, it works; if not, budget the list price.

## How to order without picking the wrong thing

1. **Pick the region first.** It sets your transfer allowance and, for the smallest Malaysian plan, your price.
2. **Pick the plan.** Evoxt's own FAQ suggests starting with the smallest plan you think you need and scaling up later, and upgrades happen from the console.
3. **Choose your OS.** Linux distributions or Windows. Anything above the OS, from the web server to the database, is on you.
4. **Check out.** Provisioning in testing ranged from 2 minutes to 10.

## Which plan fits which job

- **Personal blog, static site, small API, bot:** VM-1, **$5.99**. One core and 2 GB handles all of it.
- **App with a database on the same box:** VM-2, **$11.99**. The 4 GB matters once MySQL or Postgres shares memory with your application.
- **Several sites or a Docker host running a handful of containers:** VM-4, **$23.99** for 4 cores, 8 GB and 60 GB.
- **Build machine, CI runner, anything compiling regularly:** start at VM-8 and check the benchmark grades for that tier before committing.
- **Mostly serving users in Hong Kong or East Asia:** Hong Kong or Osaka Premium makes sense geographically, but plan your transfer at half the Standard allowance and remember overage there is $12/TB.
- **Need DDoS protection, reverse DNS, object storage or hourly billing:** Evoxt doesn't offer them. Pick a provider that does.

Before you pay, confirm two things: the transfer allowance for the exact region you selected, and that nothing in your stack depends on reverse DNS or DDoS mitigation. If both check out, the price ladder is genuinely hard to argue with.

👉 [Deploy your chosen Evoxt plan here](https://bit.ly/EvoXt)
