# Cheap Windows VPS RDP: What $2.99/mo Actually Gets You, How Many People Can Log In at Once, and Who Pays for the Windows Licence (All 11 Evoxt Plans Compared)

A Windows RDP VPS you can actually log into starts at roughly $5 to $8 a month. Listings that undercut that number usually mean one of three things: a 180-day evaluation copy of Windows Server, a 512 MB plan that Windows cannot realistically run on, or a price with no Windows licence in it at all.

Evoxt's plan list opens at $2.99/month. The first plan that clears the 2 GB memory floor a modern Windows desktop needs is VM-1 at $5.99/month, and that is where most people searching for a cheap windows vps rdp should start. What follows covers all eleven Evoxt plans, the licence arithmetic that makes two "$4 Windows VPS" offers cost very different amounts in year two, and the point at which a second or third user forces you to buy extra RDP licences.

> **Quick pick:** Evoxt VM-1, $5.99/month for 1 vCore, 2 GB RAM, 20 GB storage and 500 GB monthly transfer, with weekly offsite backup included. Enough for one person running a browser, a trading terminal or a single automation script. 👉 [See VM-1 and its current price](https://bit.ly/EvoXt)

## All Evoxt plans, side by side

Evoxt lists eleven plans on its pricing page, all with the same backup and management features and all priced in USD per month.

| Plan | vCPU / RAM | Storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 core / 512 MB | 5 GB | 250 GB | $2.99/mo | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 core / 1 GB | 10 GB | 250 GB | $4.99/mo | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 core / 2 GB | 20 GB | 500 GB | $5.99/mo | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 cores / 2 GB | 20 GB | 500 GB | $6.95/mo | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 cores / 4 GB | 30 GB | 1,000 GB | $11.99/mo | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 cores / 4 GB | 30 GB | 1,000 GB | $14.99/mo | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 cores / 8 GB | 60 GB | 2,000 GB | $23.99/mo | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 cores / 8 GB | 60 GB | 2,000 GB | $29.99/mo | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 cores / 16 GB | 80 GB | 3,000 GB | $47.99/mo | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 cores / 16 GB | 80 GB | 3,000 GB | $60.95/mo | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 cores / 32 GB | 100 GB | 5,000 GB | $95.99/mo | [Deploy VM-16](https://bit.ly/EvoXt) |

Evoxt advertises CPU clock speeds of up to 6.0 GHz across these plans, and prices single-core performance as the selling point rather than core count. That matters for remote desktop work, where a trading terminal or a browser tab usually cares more about per-core speed than about having eight slow cores.

Every plan includes weekly offsite backups at no additional cost, a browser-based VNC console, full administrator access, floating IP addresses you can move between servers, machine cloning and sub-accounts in the control panel. You can pay by credit or debit card, PayPal, Bitcoin or USDt on Tron, and prepay from one month up to three years, with account credit applied to future invoices.

## Which Evoxt plans can actually run Windows?

Two of them, in practice, cannot. VM-0.5 has 512 MB of RAM and VM-0.75 has 1 GB. Windows 11 Pro needs at least 2 GB before anything is installed, and Windows Server will boot on 1 GB but leave nothing for the applications you bought the server for. Treat those two tiers as Linux plans.

VM-1 is the honest floor for a single-user Windows desktop, and even here you should check the disk. 20 GB holds a Windows image plus updates and a couple of applications, not a full Office install with years of patches. One host that publishes its own minimums pairs Windows 11 Pro with 32 GB of storage in its smallest configuration. If you plan on installing more than a browser and one work application, VM-2 at $11.99 doubles the RAM to 4 GB and gives you 30 GB, which removes a predictable annoyance six months in.

## Who pays for the Windows licence, and what it does to year two

Two hosts can advertise the same vCPU count with a tenfold price difference between them. Licensing and management explain most of that gap, and the licensing half is where budget buyers get caught.

The common budget setup is a 180-day evaluation image of Windows Server. It works normally for six months. When the evaluation expires, the machine does not brick itself and your files stay where they are, but the server shuts down once an hour and only accepts security updates until you apply a licence. Converting is done in place, with no reinstall and no data migration.

Hosts that itemise the licence charge quote around **$6.31 per vCPU per month**. On a 2-core box that is $12.62/month, or **$151.44 a year**, which is more than the annual cost of most plans in this article. A "$3.99 Windows VPS" and a "$12 Windows VPS" can therefore end up costing the same in month thirteen, or the cheap one can end up costing more.

Desktop editions follow different rules. Microsoft does not let hosting providers rent Windows 10 or 11 Pro licences, so those templates typically install unactivated and you supply your own product key. The desktop edition also allows only one interactive session, which rules it out for anything involving a second person.

Evoxt's public pricing page lists specs and prices but does not spell out on the page whether its Windows images come with a licence, run as evaluation copies, or expect your own key. That single answer changes your first-year and second-year cost more than any plan choice in the table. Ask support before you prepay for a year or three. 👉 [Check Evoxt's Windows RDP plans](https://bit.ly/EvoXt)

## How many people can share one Windows VPS?

Windows Server ships with **two administrator sessions** included. That is two people connected at the same time, or one person connected from two devices. A third concurrent user requires an RDP user licence, quoted by at least one provider at **$8.90 per user per month**. Three extra users cost more per month than the server itself at Evoxt's entry tiers.

RAM is the other limit. 2 GB runs one desktop comfortably and complains when Chrome has ten tabs open next to a spreadsheet. 4 GB is the realistic minimum for two people doing browser work simultaneously. At 8 GB you can put three or four sessions on one box without swapping.

If your answer to "how many users" is more than two, price the licences before you price the server. The server is the cheap part.

## Picking a plan by what you'll run

**One person, browser and one application.** VM-1 at $5.99. Remote office, a single MetaTrader window, one scheduled script, a bit of admin work over RDP from a laptop or phone.

**One person who lives in Chrome.** VM-2 at $11.99. Ten tabs plus Office plus a chat client is where 2 GB stops being enough.

**Two people at once.** VM-2 as well, since the two admin sessions are already included and 4 GB splits cleanly. Move to VM-4 at $23.99 if both sessions run heavy software.

**Three or more users.** VM-4 at minimum, plus RDP user licences. At this point a dedicated-core product from another provider is often the saner purchase, because shared cores get unpredictable once four people are typing at once.

**Trading terminal running 24/7.** VM-1 or VM-2 depending on how many charts and terminals you keep open. Location near your broker matters more than an extra core here. The session keeps running after you close the RDP window, which is the whole reason people rent these boxes.

**Browser automation, scrapers, SEO tools.** VM-3 at $14.99 gives you 4 cores and 4 GB, which suits parallel browser instances better than VM-2's 2 cores. VM-4 if each instance carries a real browser profile.

**Development with Visual Studio, Docker and a local database.** VM-8 at $47.99. Below that, the build times will annoy you more than the price difference saves.

**Anything that needs reserved cores.** None of these plans offer them. Every tier is shared vCPU, so a workload that must never compete with a neighbour belongs on a dedicated VPS product elsewhere.

👉 [Compare VM-1 and VM-2 against the rest of the lineup](https://bit.ly/EvoXt)

## What other cheap Windows RDP hosts charge

These are published starting prices, and the columns matter more than the numbers, because the numbers mean different things.

| Provider | Published starting price | What sits behind that price |
| --- | --- | --- |
| LightNode | $7.71/mo, or $0.012/hour | 1 vCPU, 2 GB, 50 GB NVMe, 40+ locations. Licence model not stated on the page. |
| MassiveGRID | $3.99/mo | 1 GB Windows Server Starter on a 180-day evaluation licence. Licence costs $6.31/vCPU/month after that. Windows 11 Pro from $4.79/mo at 2 GB, unactivated, your own key. |
| HOSTKEY | $1.42/mo | A 0.5 GB VPS tier. The page does not state whether a Windows Server licence is included, and 0.5 GB will not run a Windows desktop. |
| Infrawire | €8.30/mo | Windows 10 template with admin RDP access, 7-day money-back guarantee. Their own page notes Windows 10 support ended 14 October 2025. |
| Liquid Web | $54/mo | Fully managed RDP VPS, separate memory and CPU tiers at $54 and $71 monthly. Page dated January 2025, so treat the price as indicative. |

Read the table by intent rather than by price. LightNode suits people who want hourly billing and a wide choice of locations. MassiveGRID is the one host here that publishes its licence structure in full, which makes it easy to budget the second year and easy to see why the $3.99 headline is not the price you pay long term. HOSTKEY's cheap tiers are Linux-shaped, whatever the marketing page implies. Infrawire is worth a look only if you specifically need a Windows 10 environment for legacy software and accept the missing security updates. Liquid Web is a managed product at four to ten times the price and competes with a different budget entirely.

None of that makes Evoxt the right answer for everyone. It is the cheapest of the group once you pass the 2 GB Windows floor, at $5.99 for a 2 GB plan, and it throws in weekly offsite backups that some hosts charge extra for. If you need hourly billing, more than a couple of data-centre regions, or a managed service that patches Windows for you, one of the others fits better.

## FAQ

### Can I still use Windows 10 for RDP?

You can run it, and you should not deploy it new. Microsoft ended support on **14 October 2025**, so the image no longer receives security updates. Any Windows 10 VPS sold today is aimed at software validated on that version and nothing else. For a new remote desktop, choose Windows Server or Windows 11 Pro.

### How many people can log in at the same time?

Two with Windows Server, using the admin sessions that come included. A third concurrent user needs an RDP user licence, typically billed per user per month. Windows 10 and 11 Pro allow one interactive session only.

### RDP stopped responding after I changed a firewall rule. What now?

Use the browser VNC console in your control panel. It shows the server's screen without going through RDP, so you can undo the firewall change or re-enable Remote Desktop from inside. Evoxt includes a VNC console on every plan, and the same tool gets you back in when Network Level Authentication or an IP ban locks you out.

### Hourly billing or monthly?

Evoxt bills monthly, with prepay terms from one month to three years and account credit you can top up. Hourly billing exists at other hosts and suits short testing jobs. For a desktop you intend to keep, monthly is simpler and annual prepay usually costs less.

### Do I need to buy my own Windows key?

It depends on the provider's licence model, and the answer is rarely on the pricing page. Evaluation images are free for 180 days and then need a licence or they shut down hourly. Desktop editions usually require your own key because providers cannot rent them. Bundled licences exist on managed and dedicated products. Confirm which one you are buying before you pay for a long term.

## Before you order

Match the plan to the job, not to the price list. One person doing light work should take VM-1 at $5.99 and ignore everything above it. Two people, or one person with a heavy browser habit, take VM-2 at $11.99. Anything involving a third simultaneous user needs VM-4 plus RDP licences, and at that point compare a dedicated-core product before committing.

Two things to confirm before you pay: whether the Windows licence is included or comes as an evaluation image, and which data-centre region you are buying into, since latency to your broker or your office decides how usable the desktop feels. If a refund window matters to you, ask about it before prepaying for a year, because budget hosts rarely advertise one.

👉 [Start with Evoxt VM-1 at $5.99/month](https://bit.ly/EvoXt)
