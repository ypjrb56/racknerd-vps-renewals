# RackNerd specials: all five KVM VPS deals priced out, what renewal really costs, and which plan to pick

RackNerd's specials page currently runs five annual KVM VPS plans, from $21.99/year for 1 GB RAM up to $119.99/year for 8 GB with 7 cores. The detail that matters most — and the one most deal roundups skip — is that these are officially **lifetime recurring**: RackNerd's own FAQ states you can renew at the same rate for as long as you keep the service. Year-three pricing equals year-one pricing here, which is genuinely rare at this end of the VPS market.

> **Quick pick:** experimenting or running one small service? The 1 GB plan at $21.99/year is the entry point, and it's the plan RackNerd itself flags as "Most popular." Self-hosting a handful of apps? The 2 GB plan at $35.99/year with 2 cores and 5 TB transfer is the best all-rounder. Running heavier Docker or self-hosted AI stacks? Look at 6 GB or 8 GB. Every plan is KVM, full root, 1Gbps, with a dedicated IPv4. 👉 [see the current specials and pick your plan](https://bit.ly/my-rn)

## What the five current specials actually include

All five plans share the same skeleton: KVM virtualization, full root SSH access, one dedicated IPv4 address, a 1Gbps network port, and your choice of datacenter at order time. Ubuntu, Debian, and AlmaLinux are available at deploy, with CentOS, Rocky Linux, and Fedora also supported; custom ISO installs can be requested through a support ticket.

| Plan | vCPU | SSD storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 core | 20 GB | 3 TB @ 1Gbps | $21.99/yr | [Order 1 GB plan](https://bit.ly/my-rn) |
| 2 GB KVM VPS | 2 cores | 35 GB | 5 TB @ 1Gbps | $35.99/yr | [Order 2 GB plan](https://bit.ly/my-rn) |
| 4 GB KVM VPS | 3 cores | 60 GB | 7 TB @ 1Gbps | $59.99/yr | [Order 4 GB plan](https://bit.ly/my-rn) |
| 6 GB KVM VPS | 6 cores | 100 GB | 12 TB @ 1Gbps | $89.99/yr | [Order 6 GB plan](https://bit.ly/my-rn) |
| 8 GB KVM VPS | 7 cores | 150 GB | 20 TB @ 1Gbps | $119.99/yr | [Order 8 GB plan](https://bit.ly/my-rn) |

Two things worth noticing in that table. The 6 GB plan doubles your cores from 3 to 6 — the biggest CPU jump between any two tiers — for $30 more. And the 1 GB plan carries the "Most popular" label on the official page, which tells you something about who's buying at this price point.

## Renewal pricing: the part most deal posts leave out

These specials renew at the price you paid, indefinitely. RackNerd's FAQ is explicit: the specials are lifetime recurring, and you can renew at the same rate for as long as you decide to keep the service. The 1 GB plan costs $21.99 in year one and $21.99 in year four. There's no reset to a higher "standard" rate waiting for you down the road.

The trade-off is that the config you buy is the config you keep. Upgrading to the next plan up is supported later — the transition is seamless and only takes about a minute of downtime for a reboot — but the deal price is tied to the plan you ordered. If you already suspect you'll need 4 GB within a year, start there rather than planning to grow into it. Worth noting too: all five specials are billed annually, so the yearly commitment is the whole game here.

👉 [lock in a special at the current rate](https://bit.ly/my-rn)

## ctrl: what the control panel actually does

Every special now ships with **ctrl**, RackNerd's in-house panel. It handles power actions and reboots, OS reinstalls, an out-of-band HTML5 VNC console for recovery, root password resets, and inbound firewall rules you manage yourself. The one-click app catalog includes Ollama, AnythingLLM, LibreChat, n8n, Hermes Agent, AdminBolt, and OpenClaw — a lineup clearly aimed at self-hosting and AI workloads rather than generic "website builders."

One detail older summaries get wrong: plenty of third-party listings (and RackNerd's own Black Friday promo page) still say "KVM / SolusVM," but the current official specials page lists ctrl. Either way, the panel is a convenience layer on top of full root SSH, so you can ignore it entirely and configure everything by hand. There's an interactive ctrl demo right on the specials page if you want to poke around before buying — no account needed.

## Locations, IPv6, and the small print

You choose the datacenter in the order form, and RackNerd's promo page advertises 15+ global locations. A few practical notes before you click buy:

- **IPv6** is available — up to 100 free addresses on request — but currently only at the Los Angeles and France locations. You claim it by opening a support ticket after ordering. If IPv6 matters to your project, pick one of those two datacenters up front instead of migrating later.
- **Port 25** (outbound mail) is reportedly not blocked, at least according to one detailed Trustpilot review that calls this out as unusual among legitimate providers. Relevant if you plan to send low-volume mail from the box; for anything serious you'd want proper deliverability setup regardless.
- **Custom ISO installs** and most other edge cases run through the 24/7 support ticket system.

## Holiday specials vs. the year-round five

The five plans above stay up all year. On top of them, RackNerd runs limited-time drops — Black Friday is the big one — and those go cheaper: RackNerd's own Black Friday promo page advertises KVM VPS deals from $10.76/year, well under the $21.99 floor of the year-round lineup. That page also carries bare-metal dedicated server specials and cPanel shared hosting if you're shopping beyond VPS.

The trade is timing versus certainty. Holiday deals are tied to a promo window and limited stock, so the exact plan you want may not exist in that window. The year-round specials are always available and equally lifetime-recurring. If your timeline is flexible and you don't mind watching for a sale, you can pay less. If you need a server this week, the year-round five are the practical floor — and $21.99/year is already a low bar.

## Are RackNerd specials legit?

RackNerd is an established budget provider. It's recognized on the Inc. 5000 — No. 3693 on the 2026 national list, plus No. 90 in the Inc. Regionals Pacific ranking — and holds a 4.1/5 rating on Trustpilot from 371 reviews. Provisioning is automated, so the VPS comes online right after payment rather than hours later.

Recent reviews back the support claims with specifics. One reviewer who bought the 2 GB promo at $35.99/year says support changed his rDNS record within 10 minutes, and notes the port 25 detail mentioned above. Another reports 100% uptime in UptimeRobot since signing up through a Black Friday deal. Calibrate expectations accordingly: this is budget KVM at budget prices, and the reviews describe exactly that experience — fast tickets, solid uptime, self-managed everything.

## Which special should you actually buy?

Cheap VPS is only cheap if the plan fits the job. Based on the current lineup:

- **Learning Linux, a personal proxy, or a small bot:** the 1 GB plan at $21.99/year. 20 GB SSD holds the OS plus a couple of services, and 3 TB of monthly transfer is generous at this tier.
- **Self-hosting a handful of apps — a website, n8n automations, a dashboard:** the 2 GB plan at $35.99/year. Two cores, 5 TB transfer, and enough headroom for light container use. Best value-for-money ratio in the lineup.
- **Docker-heavy projects or small local LLM experiments:** the 4 GB plan at $59.99/year. Just watch the 60 GB SSD — container images eat disk faster than you'd expect.
- **Multiple services or self-hosted AI tooling:** the 6 GB plan at $89.99/year, mainly for the jump to 6 cores and a 100 GB SSD.
- **You already know you need the resources:** the 8 GB plan at $119.99/year with 7 cores, 150 GB SSD, and 20 TB transfer. At roughly $10/month equivalent, it undercuts most monthly-billed VPS of similar size.

👉 [order the 2 GB KVM special if that's your use case](https://bit.ly/my-rn)

## RackNerd specials FAQ

### Do RackNerd specials renew at the same price?
Yes. RackNerd's FAQ states the specials are lifetime recurring — you renew at the same rate for as long as you keep the service.

### How fast is the VPS set up?
Immediately. Provisioning is automated, and the server is ready to use right after payment.

### Can I change the operating system later?
Yes. You can reinstall from the control panel at any time and switch distributions if you want. Custom ISO installs go through a support ticket.

### Can I upgrade after buying?
Yes, to the next plan up. The transition is seamless and only requires about a minute of downtime for a reboot.

### Do I get IPv6 with a special plan?
Up to 100 free IPv6 addresses are available on request, currently at the Los Angeles and France locations. Open a ticket after your order to claim them.

### Can I run Docker, WordPress, or my own stack?
Yes. These are full KVM machines with root SSH access, so you can deploy whatever stack you like — and the ctrl one-click catalog already covers common self-host tools such as n8n and Ollama if you'd rather not set things up manually.

## Before you order

Three last checks. Pick the datacenter closest to your users in the order form — especially if you want IPv6, which currently means Los Angeles or France. Match the tier to a realistic 12-month forecast, since the deal price belongs to the plan you buy today and upgrades step up from there. And if your timeline allows, it's worth knowing a Black Friday or New Year window may undercut the year-round pricing.

If you just want the short version: $21.99/year to learn and experiment, $35.99/year for a serious little self-hosting box, $119.99/year if you're running real workloads. 👉 [compare all five specials and place your order](https://bit.ly/my-rn)
