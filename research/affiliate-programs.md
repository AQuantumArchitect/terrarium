# Terrarium affiliate programs map

Research run of Nov 11, 2026 (PT) for the storefront at https://store.terrariumproject.org (repo AQuantumArchitect/terrarium-storefront). It covers 94 merchant programs, 8 aligned brands with no program, and 12 networks or platforms.

**How to read the numbers.** Every rate, cookie and threshold below comes from a public page: the brand's own program page, the network's public listing, or a third-party directory. Nothing was checked inside a publisher dashboard, because no accounts exist and none were created. Program terms change often, and several sources disagree, so re-check each one on the official page at application time. The **Src** column says what kind of source backs each row:

- **OFF**: the brand's own program page, or the network's own public listing for that brand.
- **3P**: a third-party directory or review site. Treat it as reported, not confirmed.
- **CONFLICT**: sources disagree. The range is shown.
- **NONE**: no public program found.

Where a field was not found, it says "n/f". Commission is a percent of the sale unless stated otherwise.

**Axis codes:** SH Shelter & Hospitality · FN Food & Nutrition · WA Water Security · SN Sanitation & Hygiene · EN Energy & Power · HM Health & Medical · SE Security & Safety · CI Communication & Info · TM Transport & Mobility · TL Tools & Manufacturing · GV Governance & Coordination · CR Culture & Recreation

**Fit (1-5)** combines four things: how many Terrarium concepts the merchant can fill, brand tone (calm preparedness, not fear marketing), commission times typical basket, and cookie length.

**Ready now?** is judged for a young, low-traffic site with original buyer's guides, a privacy page and an affiliate disclosure, and no Associate status:

- **Yes**: apply as soon as Luke's payee, tax and mailing-address details exist. The program is known to accept new or small content sites, or it reviews loosely.
- **Try**: cheap to apply now, but a decline at current traffic is likely. A decline usually allows reapplying later.
- **Later**: the network or brand states or commonly applies age or traffic bars, so wait for traffic.
- **No**: no usable program.

---

## Luke's direction (Nov 11, 2026)

- **No zero-percent programs.** Terrarium is mission-driven but has to earn. Programs that pay 0% (Lowe's affiliate since July 2026, Target's 0% categories, Best Buy's 0% categories, Costco's product links) are out. The Lowe's Creator Program is a separate track and stays a "Try".
- **Costco is out** because it pays only on memberships. Sam's Club (1.6% on products) can take its place.
- **Berkey is out** after the EPA ban on Black Berkey filters was upheld on 2026-09-18 (see suppliers.md), whatever its commission.
- **Long-term map.** Programs that turn down young or low-traffic sites aren't dead, just later. Re-apply on this schedule:
  - **Around 3 months after the store has steady original content:** the AvantLink programs (REI, Backcountry, Bass Pro, Cabela's, Sawyer, Augason Farms, Mountain House, BioLite, Kodiak Canvas, Lectric, Midland).
  - **Once Instagram passes 500 followers:** the Rakuten influencer track.
  - **Once one platform passes 10,000 followers:** Levanta, for Amazon-seller goods without Associates.


## 1. Recommended apply order

### What's in place, and what blocks everything

- **Prior repo work.** The repo already covers the Amazon Associates and Etsy/Rakuten applications in issues #61, #21 and #22. `docs/brand/channels.md` covers Rakuten's rules: it rejects sites under construction, and its influencer track needs 500+ Instagram followers. The only other earlier affiliate research is one line in `research/notes/gemini-more-simple-products.md`, which says EcoFlow could be reached "via ShareASale". That is stale: ShareASale shut down in 2025 and moved into Awin, and EcoFlow US now runs its own program. This document builds on that work and doesn't redo it.
- **The address blocks more than Amazon.** Rakuten's publisher rules say signup needs tax information and a valid mailing address ([Rakuten](https://pubhelp.rakutenadvertising.com/hc/en-us/articles/360060314292-Requirements-for-New-Publishers)). Partnerize asks for an address and phone at signup. Every network needs payee and tax details before it pays out. In practice the mailing address gates every program on this list, not just Amazon. Nothing below can be fully submitted until it arrives.
- **Code.** `src/config/affiliate.js` only knows two programs: an Amazon tag and Etsy deep links. Every program below needs either a stored `affiliate_url` on each offering or a deep-link template for each network. It also needs the disclosure copy to name each program truthfully once it is approved. That is a builder task to run after the first approval, not before.

### Apply order

**Step 0 (already planned): Amazon Associates.** After signup there are 180 days to make 3 qualifying sales. It stays first because about 1,100 catalog links already point at Amazon. Other programs don't replace it.

Then, in this order. Each step names one account that unlocks several merchants.

1. **Impact (network account), then Walmart.** 4% top rate, 3-day cookie. The catalog already has 96 Walmart links.
2. **eBay Partner Network.** In-house and reviews within hours. 1-4% by category, 24-hour cookie. 37 eBay links already exist.
3. **Etsy via Rakuten.** Already prepared in #61. Rate is set case by case, 30-day cookie. About 1,000 Etsy links exist, and it fills the artisanal rung.
4. **Home Depot (Impact).** 1%, or 8% on select décor; 1-day cookie. 32 links exist, and it covers bulk water tanks, tools and solar.
5. **Target Partners (Impact).** Up to 8%, 7-day cookie, and it pays on repeat orders in that window. Several categories reportedly pay 0%, so check which ones.
6. **LifeStraw (Impact).** 5%, 30-day cookie. The best-known water brand.
7. **Survival Frog (Awin).** 12% base, 30-day cookie. A full preparedness catalog. Opening Awin costs a $1 refundable deposit.
8. **ReadyWise (CJ).** Up to 10%, 120-day cookie, the longest found. Food storage.
9. **EcoFlow US (direct).** 5%, 7-day cookie. Energy, and a high basket.
10. **Tractor Supply (FlexOffers only).** 1.6-5.6%, 7-day cookie. Rural, food, tools and animals. It is the only way into FlexOffers worth taking first.

**Next wave** (same accounts, so applying costs little once each network is open):

- **Impact:** Ace Hardware (14-day cookie), Acme Tools, Sportsman's Warehouse (up to 8%, 30-day), Lodge, North Spore, Gardener's Supply, DX Engineering, Chewy, SimpliSafe.
- **Awin:** Bluetti, Jackery US, Legacy Food Storage, True Leaf Market, Botanical Interests, High Mowing Seeds, Bootstrap Farmer, American Family Safety, Bookshop.org, Ooni, Bambu Lab, VEVOR.
- **Direct brand programs** (these often accept small content sites): Anker SOLIX, Valley Food Storage, Berkey (Refersion: 15%, 365-day window), Back to the Roots (Refersion, 20%), Epic Water Filters (15%, 60-day), My Medic, Adventure Medical Kits, Uncharted Supply, Midland, Harvest Right, Excalibur, AirGradient, ZOLEO, Tern.

**Later** (needs site age and traffic):

- **AvantLink:** REI, Backcountry, Bass Pro, Cabela's, Sawyer, Augason Farms, Mountain House, BioLite, Kodiak Canvas, Rad Power, Lectric. AvantLink says sites under three months old and low-traffic sites are common denials, and suggests building for about six months.
- **Others:** Partnerize (Goal Zero), CJ for Harbor Freight, Garmin, Wayfair and DICK'S, and Skimlinks or Sovrn as a catch-all for the long tail of about 100 other retailer hosts in the catalog.

**Skip or park:**

- Costco: it pays only on membership sign-ups, not products.
- Lowe's affiliate: it cut some affiliates to 0% in July 2026.
- Levanta: needs 10,000+ followers.
- Shopify Collabs: closed to new creators.

### Notable findings

1. **Costco has no product affiliate program.** It pays only on new memberships ($3.20-6.40 on FlexOffers). The store's bulk rung points shoppers to Costco and Walmart, and the Costco links will never earn. Sam's Club does pay on products (1.6%), so it can stand in for the bulk rung.
2. **Lowe's told at least some affiliates in July 2026 that their rate was dropping to 0%** for the rest of the quarter, as ToolGuyd reported. The separate Lowe's Creator Program advertises up to 25% with a 30-day window, but it is aimed at social creators.
3. **The outdoor retailers cluster on AvantLink**, which screens out young sites. REI, Backcountry, Bass Pro and Cabela's are excellent fits but aren't realistic in the first wave.
4. **Brand-direct programs pay 3-10 times what the big boxes do.** The big boxes pay 1-4% with 1-3 day cookies. Survival Frog pays 12%, Berkey 15% with a 365-day window, Epic Water 15% with a 60-day window, ReadyWise 10% with a 120-day cookie, and Back to the Roots 20%. The supplier and brand step may out-earn retailer links for the same click.
5. **Sub-network listings show lower rates than the brand's own program.** FlexOffers often shows about 80% of the brand rate (for example Lowe's 1.6% against about 2%). This is an inference, not confirmed. Apply direct where a brand runs its own program.
6. **Several aligned brands have no affiliate program:** WaterBrick (reseller program only), Baker Creek Heirloom Seeds, Seed Savers Exchange, Ham Radio Outlet, Eton radios and Sun Oven. These belong on the supplier list, not here.
7. **Thin coverage on two axes.** Governance & Coordination has almost no affiliate inventory; radios such as Midland are the nearest. Sanitation & Hygiene is also thin: Separett has a program with no public rate, and nothing was found for Nature's Head.
8. **Levanta can pay commission on Amazon-seller products without an Associates account**, but it needs 10,000+ followers on one platform. That isn't an option now, but it is the one known route to Amazon-sold goods that doesn't depend on Associates.

---

## 2. Full table

### A. Networks and platforms (one account each, many merchants)

| # | Network | Signup requirements (public) | Payout min | Notable Terrarium merchants found | Ready now? | Src |
|---|---|---|---|---|---|---|
| N1 | Impact | Free. Verify a website. No stated traffic minimum; each brand reviews separately. | $10 | Walmart, Home Depot, Target, Ace, Acme Tools, Sportsman's Whse, LifeStraw, Lodge, North Spore, Gardener's Supply, DX Engineering, Chewy, Best Buy, SimpliSafe | Yes | OFF [i1], 3P [i2] |
| N2 | Awin (ShareASale merged in 2025) | $1 refundable deposit (waived with an invitation code) | $20 | Bluetti, Jackery US, Survival Frog, Legacy, True Leaf, Botanical Interests, High Mowing, Bootstrap Farmer, Am. Family Safety, Bookshop.org, Ooni, Bambu Lab, VEVOR | Yes | OFF [aw1][aw2] |
| N3 | CJ Affiliate | Free; live site; 18+. Account deactivated after 6 months with no earnings. | $50 direct deposit / $100 check | ReadyWise, Harbor Freight, Garmin, Wayfair, DICK'S | Try (watch the inactivity rule) | 3P [cj1] |
| N4 | Rakuten Advertising | Website, **tax info, valid mailing address**. No screening at signup; each advertiser screens. | $50 | Etsy US, Anker SOLIX (listed) | Yes (already planned, #61) | OFF [rk1][rk2] |
| N5 | FlexOffers | Live, owned, original content. Underdeveloped sites declined. | $25 | Tractor Supply (exclusive), Lowe's, Sam's Club, Emergency Essentials, Zoro, Costco (membership) | Yes | OFF [fo1] |
| N6 | AvantLink | Manual review. Sites under 3 months old and low traffic are common denials; suggests building about 6 months. | $25 | REI, Backcountry, Bass Pro, Cabela's, Sawyer, Augason, Mountain House, BioLite, Kodiak, Rad Power, Lectric, Midland | Later | OFF [av1][av2] |
| N7 | Partnerize | Address, phone and URL at signup; each brand approves. | US$30 | Goal Zero | Try | OFF [pz1][pz2] |
| N8 | Skimlinks | Shopping-focused site, 10+ articles, organic traffic. Manual review, 3-5 days. Network keeps a revenue share (~25%, reported). | $65 | Catch-all for long-tail hosts (Home Depot, Lectric, WebstaurantStore listed) | Try | OFF [sk1] |
| N9 | Sovrn Commerce | Install the script, generate clicks, then a quality review | n/f | Catch-all for long-tail hosts | Later | OFF [sv1] |
| N10 | Levanta | Creators need 10,000+ followers on one platform. Pays on Amazon-seller goods without Associates. | n/f | Amazon third-party brands | No (follower bar) | OFF [lv1] |
| N11 | Refersion / GoAffPro / UpPromote (brand-run portals) | Set by each brand | per brand | Berkey, Back to the Roots, Rokland | Yes | OFF |
| N12 | Shopify Collabs | Not accepting new creator signups | — | — | No | OFF [sh1] |

### B. Merchant programs

| # | Program | Network | Commission | Cookie | Approval notes / payout min | Axes | Fit | Ready now? | Src |
|---|---|---|---|---|---|---|---|---|---|
| **Big-box and general retail** |||||||||
| 1 | Amazon Associates (US) | in-house | 3% home, tools, outdoors, lawn & garden; 4.5% kitchen and books; 1% grocery and health; 4% "all other" | 24 h (+89 days if added to cart) | 3 qualifying sales in 180 days; ~10 posts; paid or boosted ad referrals excluded since Apr 14, 2026 | all | 5 | Yes, once the address arrives (#61) | 3P copy of official schedule [am1]; OFF [am2] |
| 2 | Walmart | Impact | up to 4% (1% grocery and electronics reported) | 3 days | Excludes Sam's, pharmacy, tires, gift cards. Min payout $10 (3P). | FN WA EN HM TL SH | 5 | Yes | OFF [wm1][wm2]; 3P cookie [wm3] |
| 3 | Walmart Creator | Walmart Creator (pays via Impact) | in account, not public | 14 days | 18+, US, linked public social account, no follower minimum | all | 3 | Try (social-led) | OFF [wm4] |
| 4 | The Home Depot | Impact (also via Skimlinks, Sovrn, FlexOffers) | 1% products and appliances; 8% select décor | 1 day | $50 direct deposit / $100 check | WA EN TL SH SN SE | 4 | Yes | OFF [hd1]; 3P [hd2] |
| 5 | Home Depot Installation leads | Impact | $20-200 per qualified lead | 30 days | — | SH EN | 2 | Try | 3P [hd3] |
| 6 | Lowe's (affiliate) | Impact (reported); FlexOffers lists 1.6% | ~2%; **0% for some affiliates from July 2026** | 1 day | — | TL SH WA | 1 | No (park) | 3P [lw1][lw2] |
| 7 | Lowe's Creator Program | Lowe's Creator Portal | up to 25% (page also says 20%), tiered | 30 days | US creators with a following; blogs accepted | TL SH WA EN | 3 | Try | OFF [lw3] |
| 8 | Target Partners | Impact | up to 8%, set per contract; reported 0% on electronics, grocery and sporting goods | 7 days, repeat orders count | Publishes EPC of $3-4 per 100 clicks; US traffic only | SH FN HM CR | 3 | Yes | OFF [tg1]; 3P [tg2] |
| 9 | Costco | FlexOffers / Partnerize | **memberships only**, $3.20-6.40 each | 1 day | No product commissions | — | 1 | No | OFF [co1]; 3P [co2] |
| 10 | Sam's Club | FlexOffers | 1.6% products; 12% new memberships | 3 days | — | FN WA (bulk rung) | 3 | Yes | OFF [sc1]; 3P [sc2] |
| 11 | Tractor Supply | FlexOffers (exclusive) | 1.6-5.6% | 7 days | Old official page still points to Pepperjam | FN TL SH SE | 4 | Yes | OFF [ts1][ts2] |
| 12 | Ace Hardware | Impact | not published (2% reported; rate depends on monthly sales) | 14 days | Excludes gift cards | TL SH SE | 3 | Yes | OFF [ah1]; 3P [ah2] |
| 13 | Harbor Freight | CJ (FlexOffers lists 3.2%, 7 days) | 3% | 30 days | — | TL EN | 3 | Try | 3P [hf1][hf2] (CONFLICT on cookie) |
| 14 | Northern Tool | n/f | 3% | 30 days | — | TL EN | 3 | Try | 3P [nt1] |
| 15 | Acme Tools | Impact | min 2% | 15 days | — | TL | 3 | Yes | OFF [at1] |
| 16 | Zoro | FlexOffers | 3.2% | 30 days | — | TL SN | 2 | Yes | OFF network listing [zo1] |
| 17 | Rockler Woodworking | n/f | 5% | 14 days | — | TL | 2 | Try | 3P [ro1] |
| 18 | Wayfair (US) | CJ | ~7% | 7 days | — | SH | 2 | Try | 3P [wf1] |
| 19 | Best Buy | Impact | ~0.5-1% (some 0%) | ~1 day | Rates set in the dashboard | EN CI | 1 | Try | OFF [bb1]; 3P [bb2] |
| 20 | Chewy | Impact | 1% | 15 days | Excludes pharmacy | FN (animals) | 2 | Yes | OFF [ch1]; 3P [ch2] |
| 21 | Thrive Market | n/f | $30 per annual membership / $5 monthly | 14 days | — | FN | 2 | Try | 3P [th1] |
| 22 | WebstaurantStore | sub-networks only (Skimlinks etc.) | 0.88% | 30 days | — | FN SN (bulk) | 2 | Later (via Skimlinks) | 3P [we1] |
| 23 | eBay Partner Network | in-house | 1-4% by category (Home & Garden 3%, Business & Industrial 2.5%) | 24 h (auctions: bid in 24 h, win in 10 days) | Active eBay account; reviewed in hours; $10 min | all (used and repair) | 4 | Yes | OFF [eb1][eb2] |
| 24 | Etsy (US) | Rakuten | set case by case (~4% reported) | 30 days web, 7 days app | 18+; site quality review; excludes dropshipping and price-comparison sites; related-shop disclosure | SH FN CR TL SN (artisanal rung) | 5 | Yes (#61) | OFF [et1][et2]; 3P rate [et3] |
| 25 | Bookshop.org | Awin / direct | 10% | 48 h | — | CR GV (manuals, skills books) | 4 | Yes | OFF [bk1][bk2] |
| **Outdoor and preparedness retailers** |||||||||
| 26 | REI | AvantLink | 5% | 15 days | Written permission needed for social and email links | SH WA EN HM TM CR | 4 | Later | 3P [re1][re2] |
| 27 | Backcountry | AvantLink | 4-12% tiered | 30 days | — | SH WA CR | 3 | Later | 3P [bc1] |
| 28 | Bass Pro Shops | AvantLink | 5% | 14 days | — | FN SH SE CR | 3 | Later | OFF [bp1]; 3P [bp2] |
| 29 | Cabela's | AvantLink | 1-5% | 14 days | — | FN SH SE CR | 3 | Later | OFF [cb1]; 3P [cb2] |
| 30 | Sportsman's Warehouse | Impact | up to 8% | 30 days | — | SH FN SE CR | 3 | Yes | OFF [sw1] |
| 31 | DICK'S Sporting Goods | CJ | ~2% | 3 days | — | CR TM | 2 | Try | 3P [dk1] |
| 32 | Scheels | AvantLink + others | 1.6-5.6% | 7 days | — | CR SH | 2 | Later | 3P [ag-av] |
| 33 | Survival Frog | Awin, Shopify Collective | 12% base | 30 days | — | FN WA EN HM SE CI | 4 | Yes | OFF [sf1][sf2] |
| 34 | Emergency Essentials (BePrepared) | FlexOffers | 10% | 14 days | — | FN WA HM | 4 | Yes | OFF network listing [ee1] |
| 35 | American Family Safety (72-hour kits) | Awin / FlexOffers | 12% | 30 days | — | HM FN WA | 4 | Yes | OFF [af1][af2] |
| 36 | 5.11 Tactical | n/f | ~8% | 30 days | Tactical tone; brand-fit caution | SE | 2 | Try | 3P [bi1] |
| 37 | Uncharted Supply Co. | in-house / FlexOffers | 6% | 30 days | — | HM FN WA | 3 | Yes | OFF [uc1] |
| **Energy and power** |||||||||
| 38 | EcoFlow (US) | in-house | 5% | 7 days | — | EN | 5 | Yes | OFF [ef1] |
| 39 | Jackery (US) | Awin (also Impact, CJ, FlexOffers, AvantLink) | ~6% on Awin; 2-4% on other networks | 30 days (Awin UK / Affiliatly) | — | EN | 4 | Yes | CONFLICT [jk1][jk2][jk3] |
| 40 | Bluetti (US) | Awin | n/f | 30 days | Same-browser rule | EN | 4 | Yes | OFF [bl1][bl2] |
| 41 | Anker SOLIX (US) | in-house / Rakuten | 5% | 30 days | — | EN | 4 | Yes | OFF [an1]; 3P [an2] |
| 42 | Goal Zero | Partnerize (old AvantLink links inactive) | up to 10% (dynamic) | 30 days | — | EN CI | 4 | Try | OFF [gz1] |
| 43 | Renogy | Acceleration Partners | 4-15% (avg ~6%) | 30 days | — | EN | 4 | Try | OFF [rn1]; 3P [rn2] |
| 44 | BioLite | AvantLink | ~7% | 30 days | — | EN FN CI | 4 | Later | OFF [bi2]; 3P [bi3] |
| **Water** |||||||||
| 45 | LifeStraw | Impact | 5% (5-10% reported) | 30 days | — | WA | 5 | Yes | OFF [ls1]; 3P [ls2] |
| 46 | Sawyer | AvantLink | 12% | 30 days | — | WA | 5 | Later | OFF [sa1] |
| 47 | Berkey (Berkey Filters) | Refersion | 15% | **365-day** window | US residents, PayPal, $50 min. The product line's regulatory history should be re-checked before featuring it (not researched here). | WA | 4 | Yes | OFF [bk3] |
| 48 | Epic Water Filters | in-house | 15% | 60 days | — | WA | 4 | Yes | OFF [ep1] |
| 49 | AquaTru | in-house | 2.8% (reported) | 30 days | — | WA | 2 | Try | OFF page [aq1]; 3P rate [aq2] |
| 50 | Clearly Filtered | FlexOffers | 1.6% | 45 days | — | WA | 2 | Yes | OFF network listing [cf1] |
| 51 | WaterBrick | — | no affiliate program (reseller program) | — | Move to the supplier list | WA | — | No | NONE [wb1] |
| **Food storage and kitchen** |||||||||
| 52 | ReadyWise | CJ | up to 10% | **120 days** | $25 min | FN | 5 | Try (CJ) | OFF [rw1] |
| 53 | Valley Food Storage | in-house | 10% | 30 days | — | FN | 5 | Yes | OFF [vf1] |
| 54 | Augason Farms | AvantLink / FlexOffers | 10% | 30 days | — | FN | 4 | Later (AvantLink) / Yes (FlexOffers) | 3P [au1] |
| 55 | Mountain House | AvantLink (+FlexOffers, Skimlinks) | 0.8% listed (looks low) | 30 days | — | FN | 3 | Later | CONFLICT [mh1] |
| 56 | Legacy Food Storage | Awin / direct | 10% (up to 15%) | 30 days | — | FN | 4 | Yes | OFF [lf1][lf2] |
| 57 | My Patriot Supply | direct | 5% | 30 days | Tone caution | FN | 3 | Try | 3P [bi1] |
| 58 | 4Patriots | Levanta / Digidip | 10% | 30 days | Fear-heavy marketing; brand-fit caution | FN EN | 2 | Try | 3P [fp1] |
| 59 | Nutrient Survival | FlexOffers / direct | 0.8-15% depending on source | 7-30 days | — | FN | 3 | Try | CONFLICT [ns1][ns2][bi1] |
| 60 | Harvest Right (freeze dryers) | in-house (iDevAffiliate) | 3-10% | 45 days | $100 min | FN | 5 | Yes | OFF [hr1] |
| 61 | Excalibur Dehydrator | in-house / Awin (Legacy Cos.) | from 10%, volume tiers | 3 days (direct) / 30 days (Awin) | — | FN | 4 | Yes | OFF [ex1]; CONFLICT on cookie |
| 62 | Weston Brands | n/f | 5% | 45 days | — | FN | 3 | Try | 3P [ws1] |
| 63 | Lodge Cast Iron | Impact | 8% (1% on FlexOffers) | 30 days | — | FN SH | 4 | Yes | 3P [lo1][lo2] |
| 64 | Ooni (US) | Awin | from 10% | 30 days | — | FN CR | 3 | Yes | OFF [oo1] |
| 65 | Solo Stove | in-house / FlexOffers | 0.8% listed (verify) | 30 days | — | FN SH CR | 2 | Try | CONFLICT [so1] |
| 66 | Cultures for Health | n/f | 5% | 30 days | $100 min | FN | 3 | Try | 3P [cu1] |
| 67 | Fermentaholics | Awin | listed 0% (unverified) | 30 days | — | FN | 2 | Try | CONFLICT [fe1][fe2] |
| 68 | Masontops | — | wholesale portal only seen | — | Supplier list | FN | — | No | NONE [mt1] |
| **Gardening, seeds, growing** |||||||||
| 69 | True Leaf Market | Awin | 10-20% (content); 2-5% (coupon sites) | n/f | — | FN | 5 | Yes | OFF [tl1][tl2] |
| 70 | Botanical Interests | Awin | 15% (bloggers) | n/f | — | FN | 5 | Yes | OFF [bt1][bt2] |
| 71 | High Mowing Organic Seeds | Awin | from 10% | 60 days | — | FN | 5 | Yes | OFF [hm1][hm2] |
| 72 | Johnny's Selected Seeds | n/f | 5-10% (one listing only) | n/f | Unverified on Johnny's own site | FN | 4 | Try | 3P [js1] |
| 73 | Mary's Heirloom Seeds | email application | 10% | n/f | Source dated 2018 | FN | 3 | Try | 3P stale [mh2] |
| 74 | Baker Creek Heirloom Seeds | — | no affiliate program | — | Supplier list | FN | — | No | NONE [bc2] |
| 75 | Seed Savers Exchange | — | no affiliate program | — | Mission-aligned collaborations only | FN CR | — | No | NONE [ss1] |
| 76 | Gardener's Supply Co. | Impact | 4% (older listings 8%) | 30 days | — | FN WA | 3 | Yes | 3P [gs1] |
| 77 | Bootstrap Farmer | Awin | 10% | 15 days | — | FN | 4 | Yes | OFF [bf1][bf2] |
| 78 | Back to the Roots | Refersion | 20% | 30 days | — | FN CR | 4 | Yes | OFF [br1] |
| 79 | North Spore (mushrooms) | Impact | 10% | n/f | US sales | FN | 4 | Yes | 3P [nsp1] |
| 80 | Rokland (hydroponics, Meshtastic) | GoAffPro | up to 10% (typically 5%) | n/f | — | FN CI | 3 | Yes | OFF [rk3] |
| **Health and medical** |||||||||
| 81 | My Medic | in-house | 10% | 30 days | — | HM | 5 | Yes | OFF [mm1] |
| 82 | Adventure Medical Kits | in-house / FlexOffers | 8-15% (content partners) | 30 days | — | HM | 5 | Yes | OFF [ak1] |
| **Communication** |||||||||
| 83 | Midland Radio | in-house (also AvantLink) | 8% (content partners) | 30 days | — | CI GV SE | 5 | Yes | OFF [md1]; 3P [md2] |
| 84 | DX Engineering (ham radio) | Impact | 5% | 14 days | — | CI | 4 | Yes | 3P [dx1] |
| 85 | Garmin / Garmin Outdoor (inReach) | CJ | 2% general; 4% Outdoor | 30 days | — | CI TM SE | 3 | Try | OFF [gm1]; 3P [gm2] |
| 86 | ZOLEO (satellite messenger) | n/f | 10% | 90 days | — | CI SE | 4 | Yes | 3P [zl1] |
| 87 | RAKwireless (Meshtastic / LoRa) | in-house | n/f | "extended" | — | CI GV | 3 | Yes | OFF [rw2] |
| — | Ham Radio Outlet, Eton | — | no public program found | — | Supplier list | CI | — | No | NONE [dx1][eton] |
| **Security and safety** |||||||||
| 88 | SimpliSafe | Impact (Awin listing too) | flat $25 per online sale (reported) | 30 days | — | SE | 3 | Yes | 3P [ss2] |
| **Transport** |||||||||
| 89 | Rad Power Bikes | AvantLink / FlexOffers | ~5% (4% US/CA on some listings) | 30 days | — | TM | 4 | Later / Yes (FlexOffers) | 3P [rp1] |
| 90 | Lectric eBikes | AvantLink / Skimlinks | 3% | 30 days | — | TM | 3 | Later | 3P [le1] |
| 91 | Tern (cargo and folding bikes) | in-house | 3% flat | 30 days | — | TM | 4 | Yes | OFF [tn1] |
| 92 | Specialized | in-house | 3-12% | 30 days | — | TM | 3 | Try | OFF [sp1] |
| 93 | Aventon | AvantLink + others | 2-5% | n/f | — | TM | 3 | Later | 3P [ag-av] |
| **Tools and manufacturing** |||||||||
| 94 | Bambu Lab (3D printers) | Awin | 3% printers; 5% filament and parts | 15 days | — | TL | 4 | Yes | OFF [bm1] |
| 95 | VEVOR | Awin / in-house | 2-10% by traffic type | 30 days | — | TL FN SN EN | 3 | Yes | OFF [vv1][vv2] |
| **Shelter** |||||||||
| 96 | Kodiak Canvas (tents) | AvantLink | 8% | n/f | — | SH | 4 | Later | OFF [kc1] |
| **Sanitation, air** |||||||||
| 97 | Separett (composting toilets) | in-house | not public | n/f | Contact needed (do not contact without Luke) | SN | 4 | Try | OFF [sp2] |
| 98 | AirGradient (air monitors) | in-house | 6-8% | 90 days | $100 PayPal min | HM SH | 4 | Yes | OFF [ai1] |
| — | Nature's Head, Sun Oven | — | none found | — | Supplier list | SN FN | — | No | NONE |

Count: 94 merchant programs (numbered rows 1-98, minus rows 51, 68, 74 and 75, which are marked NONE), plus 8 aligned brands with no program (WaterBrick, Masontops, Baker Creek, Seed Savers, Ham Radio Outlet, Eton, Nature's Head, Sun Oven) and 12 networks.

### Axis coverage (merchants scoring Fit 4-5)

- **Food & Nutrition:** deep. ReadyWise, Valley, Legacy, Harvest Right, True Leaf, Botanical Interests, High Mowing, Survival Frog, Tractor Supply and others.
- **Water Security:** LifeStraw, Sawyer, Berkey, Epic.
- **Energy & Power:** EcoFlow, Jackery, Bluetti, Anker SOLIX, Goal Zero, Renogy, BioLite.
- **Health & Medical:** My Medic, Adventure Medical Kits, American Family Safety.
- **Communication & Info:** Midland, DX Engineering, ZOLEO.
- **Transport & Mobility:** Tern, Rad Power.
- **Tools & Manufacturing:** Bambu Lab, plus the big boxes.
- **Shelter & Hospitality:** Kodiak Canvas, Home Depot.
- **Culture & Recreation:** Bookshop.org, Etsy.
- **Security & Safety:** thin and tactical-leaning. SimpliSafe and Midland are the calm options.
- **Sanitation & Hygiene:** thin (Separett, with no public rate).
- **Governance & Coordination:** effectively none. Books and radios are the nearest.

---

## 3. Sources

All sources were accessed Nov 11, 2026 (PT). Most rows rest on search-engine summaries of the linked page; the amawp.com Amazon table and the brandid.app survival list were read in full.

- [i1] https://help.impact.com/partner/what-would-you-like-to-learn-about/getting-started/sign-up-as-a-partner-on-impactcom
- [i2] https://affdigest.com/network/impact-com/
- [aw1] https://success.awin.com/s/article/ShareASale-to-Awin-platform-upgrade-FAQ?language=en_US
- [aw2] https://success.awin.com/s/article/What-are-the-payment-thresholds?language=en_US
- [cj1] https://smartblogger.com/cj-affiliate-commission-junction/ ; https://payoutdeals.com/networks/cj-affiliate
- [rk1] https://pubhelp.rakutenadvertising.com/hc/en-us/articles/360060314292-Requirements-for-New-Publishers
- [rk2] https://pubhelp.rakutenadvertising.com/hc/en-us/articles/4412254867981-Minimum-Payment-Threshold
- [fo1] https://supportbeta.flexoffers.com/knowledge/why-was-my-publisher-application-declined ; https://www.flexoffers.com/terms-and-conditions/
- [av1] https://support.avantlink.com/hc/en-us/articles/204952129-Affiliate-Application-FAQ
- [av2] https://support.avantlink.com/hc/en-us/articles/204796409-Commission-Payout-FAQ-for-Affiliates
- [pz1] https://help.phgsupport.com/hc/en-us/articles/20079182273565-How-to-Sign-Up-to-Partnerize-as-a-Partner
- [pz2] https://partnerize.com/wp-content/uploads/2024/05/20240503-Partnerize-Publisher-Terms-and-Conditions-1.7.-UK-Entity.pdf
- [sk1] https://support.skimlinks.com/hc/en-us/articles/223835528 ; https://support.skimlinks.com/hc/en-us/articles/223835508-How-much-does-Skimlinks-charge
- [sv1] https://knowledge.sovrn.com/kb/getting-started-with-sovrn-commerce
- [lv1] https://knowledge.levanta.io/articles/1540173350-faq-s ; https://knowledge.levanta.io/articles/4886311347-why-wasn-t-my-creator-account-accepted
- [sh1] https://help.shopify.com/en/manual/promoting-marketing/collabs
- [am1] https://amawp.com/amazon-associates-commission-rates/ (a third-party copy of Amazon's US fee schedule, checked by its author Aug 25, 2026). amazon.com was not fetched, per Amazon's agent terms.
- [am2] https://affiliate-program.amazon.com/help/node/topic/G8TW5AE9XL2VX9VM (cited in repo issue #61, checked Nov 8, 2026; not re-fetched)
- [wm1] https://affiliates.walmart.com/page/faqs
- [wm2] https://affiliates.walmart.com/terms
- [wm3] https://payouts.com/resources/walmart-affiliate-commission-rates ; https://affiliateprogramsguru.com/programs/walmart/
- [wm4] https://creator.walmart.com/terms ; https://creator.walmart.com/education/how-to-become-a-walmart-creator
- [hd1] https://www.homedepot.com/c/SF_MS_Affiliate_Program_FAQs
- [hd2] https://www.affiliategraph.ai/programs/home-depot
- [hd3] https://odiproductions.com/blog/home-depot-affiliate-program ; https://gatoraffiliator.com/guides/home-improvement-affiliate-programs
- [lw1] https://reverbico.com/blog/lowes-affiliate-program/
- [lw2] https://www.flexoffers.com/affiliate-programs/lowes-affiliate-program/ ; https://www.postaffiliatepro.com/affiliate-program-directory/lowes-affiliate-program/
- [lw3] https://www.lowes.com/l/creator/joinlowescreator
- [tg1] https://partners.target.com/faqs ; https://partners.target.com/termsandconditions
- [tg2] https://affmaven.com/target-affiliate-program/ ; https://creatorflow.so/blog/target-creator-program/
- [co1] https://www.flexoffers.com/affiliate-programs/costco-membership-affiliate-program/
- [co2] https://reverbico.com/blog/costco-affiliate-program/
- [sc1] https://www.flexoffers.com/affiliate-programs/sams-club-affiliate-program/
- [sc2] https://referralrocket.io/affiliate-program/sams-club_B5
- [ts1] https://www.flexoffers.com/affiliate-programs/tractor-supply-company-affiliate-program/
- [ts2] https://www.affilitizer.com/programs/tractorsupply.com ; https://www.tractorsupply.com/policies-information_affiliate-program
- [ah1] https://www.acehardware.com/affiliate-faq
- [ah2] https://gatoraffiliator.com/guides/home-improvement-affiliate-programs
- [hf1] https://getlasso.co/affiliate/harbor-freight-tools/
- [hf2] https://www.flexoffers.com/affiliate-programs/harbor-freight-tools-affiliate-program/
- [nt1] https://getlasso.co/affiliate/northerntool/
- [at1] https://www.acmetools.com/affiliates.html
- [zo1] https://www.flexoffers.com/affiliate-programs/zoro-affiliate-program/
- [ro1] https://gatoraffiliator.com/guides/home-improvement-affiliate-programs
- [wf1] https://affiliateprogramsguru.com/programs/wayfair-affiliate-program/
- [bb1] https://www.bestbuy.com/site/best-buy-affiliate-program/affiliate-terms-and-conditions/pcmcat748302046001.c?id=pcmcat748302046001
- [bb2] https://reverbico.com/blog/best-buy-affiliate-program/
- [ch1] https://www.chewy.com/app/content/affiliate
- [ch2] https://affiliateorchard.com/programs/chewy/
- [th1] https://marketplace.referly.so/affiliate-programs/thrive-market ; https://thrivemarket.com/affiliate-program
- [we1] https://www.affiliategraph.ai/programs/webstaurantstore
- [eb1] https://partnernetwork.ebay.com/our-program/rate-card ; https://partnernetwork.ebay.com/solutions/step-1-understanding-cookies-commissions-and-getting-paid
- [eb2] https://partnernetwork.ebay.com/solutions/joining-the-ebay-partner-network
- [et1] https://www.etsy.com/legal/affiliates/
- [et2] https://help.etsy.com/hc/en-us/articles/360000335987-The-Etsy-Affiliates-Program-and-Creator-Collective
- [et3] https://zonhack.com/etsy-affiliate-commission-rate/ ; https://makermanifest.co/blog/etsy-leaves-awin-what-creators-need-to-know
- [bk1] https://ui.awin.com/merchant-profile/92005
- [bk2] https://bookshop.org/affiliate_profile/introduction
- [re1] https://linktolooks.com/guides/affiliate-programs-for-outdoor-creators/
- [re2] https://affiliateprogramsguru.com/programs/rei-affiliate-program/
- [bc1] https://affiliateprogramsguru.com/programs/backcountry-affiliate-program/
- [bp1] https://www.basspro.com/b/affiliate-program
- [bp2] https://commissiondex.com/programs/bass-pro-shops/
- [cb1] https://www.cabelas.com/b/affiliate-program
- [cb2] https://commissiondex.com/programs/cabelas/
- [sw1] https://www.sportsmans.com/sportsmans-warehouse-affiliate-program
- [dk1] https://affiliateorchard.com/programs/dicks-sporting-goods/
- [ag-av] https://www.affiliategraph.ai/networks/avantlink
- [sf1] https://www.survivalfrog.com/pages/affiliate-program
- [sf2] https://ui.awin.com/merchant-profile/88727
- [ee1] https://www.flexoffers.com/affiliate-programs/emergency-essentialsbeprepared-affiliate-program/
- [af1] https://ui.awin.com/merchant-profile/83331
- [af2] https://www.flexoffers.com/affiliate-programs/american-family-safety-affiliate-program/
- [bi1] https://brandid.app/blog/survival-affiliate-programs/ (Sept 2026 third-party roundup)
- [uc1] https://unchartedsupplyco.com/pages/affiliate-program
- [ef1] https://us.ecoflow.com/pages/affiliate-program
- [jk1] https://www.jackery.com/pages/affiliate-program
- [jk2] https://www.affiliategraph.ai/programs/jackery
- [jk3] https://ui.awin.com/advertiser-terms/59183
- [bl1] https://www.bluettipower.com/pages/affiliate-program
- [bl2] https://ui.awin.com/merchant-profile/59271
- [an1] https://www.ankersolix.com/become-an-affiliate
- [an2] https://bestaffiliateprograms.cc/programs/anker-solix
- [gz1] https://goalzero.com/pages/affiliate-marketing-program
- [rn1] https://www.renogy.com/pages/affiliate-program
- [rn2] https://bestaffiliateprograms.cc/programs/renogy
- [bi2] https://help.bioliteenergy.com/hc/en-us/articles/4402108755355-How-can-I-become-a-BioLite-affiliate
- [bi3] https://getlasso.co/affiliate/biolite/
- [ls1] https://lifestraw.com/pages/affiliate-program
- [ls2] https://linkclicky.com/affiliate-program/lifestraw/
- [sa1] https://besawyer.com/pages/affiliate-program
- [bk3] https://berkey.refersion.com/
- [ep1] https://www.epicwaterfilters.com/pages/affiliate-program
- [aq1] https://aquatru.com/pages/affiliate-program
- [aq2] https://www.affjumbo.com/new-offer-launched-aquatru-affiliate-program/
- [cf1] https://www.flexoffers.com/affiliate-programs/clearly-filtered-affiliate-program/
- [wb1] https://www.waterbrick.org/partners/
- [rw1] https://readywise.com/pages/affiliate-program
- [vf1] https://valleyfoodstorage.com/pages/affiliates
- [au1] https://www.affiliategraph.ai/programs/augason-farms
- [mh1] https://www.affiliategraph.ai/programs/mountain-house ; https://www.flexoffers.com/affiliate-programs/mountain-house-affiliate-program/
- [lf1] https://www.legacyfoodstorage.com/pages/affiliate-home
- [lf2] https://ui.awin.com/merchant-profile/88307
- [fp1] https://www.affiliategraph.ai/programs/4patriots
- [ns1] https://www.flexoffers.com/affiliate-programs/nutrient-survival-affiliate-program/
- [ns2] https://nutrientsurvival.com/pages/affiliates ; https://www.affiliategraph.ai/programs/nutrient-survival
- [hr1] https://harvestright.com/pages/affiliate-program
- [ex1] https://excaliburdehydrator.com/pages/affiliate ; https://ui.awin.com/merchant-profile-terms/96969
- [ws1] https://www.revshare.so/programs/advertiser/weston-brands-performance-e5f2b399
- [lo1] https://app.hienergy.ai/a/927796
- [lo2] https://www.affiliategraph.ai/programs/lodge-cast-iron
- [oo1] https://ui.awin.com/merchant-profile/77074 ; https://discover.ooni.com/affiliates/
- [so1] https://www.solostove.com/us/en-us/s/affiliate-program ; https://www.flexoffers.com/affiliate-programs/solo-stove-affiliate-program/
- [cu1] https://www.postaffiliatepro.pl/katalog/cultures-for-health-affiliate-program/
- [fe1] https://fermentaholics.com/fermentaholics-affiliate-program/
- [fe2] https://ui.awin.com/merchant-profile/90863
- [mt1] https://wholesale.masontops.com/
- [tl1] https://ui.awin.com/merchant-profile/124042
- [tl2] https://trueleafmarket.com/pages/affiliate-program-trueleafmarket
- [bt1] https://ui.awin.com/merchant-profile/88147
- [bt2] https://www.botanicalinterests.com/pages/creator-community-program
- [hm1] https://www.highmowingseeds.com/high-mowing-affiliate-program
- [hm2] https://ui.awin.com/merchant-profile/95143
- [js1] https://www.shopper.com/partnerships/johnnyseeds-com-affiliate-program
- [mh2] http://back2basichealth.blogspot.com/2018/10/marys-heirloom-seeds-affiliate-program.html
- [bc2] https://mcstaging.rareseeds.com/media_relations
- [ss1] https://seedsavers.org/creators/
- [gs1] https://affiliateorchard.com/programs/gardeners-supply/
- [bf1] https://www.bootstrapfarmer.com/pages/affiliate-program
- [bf2] https://ui.awin.com/merchant-profile/59109
- [br1] https://bttr.refersion.com/
- [nsp1] https://www.affiliategraph.ai/programs/north-spore
- [rk3] https://rokland.goaffpro.com/
- [mm1] https://mymedic.com/pages/affiliates
- [ak1] https://adventuremedicalkits.com/pages/affiliate-program
- [md1] https://midlandusa.com/pages/midland-affiliate-program
- [md2] https://www.affiliategraph.ai/programs/midland-radio
- [dx1] https://www.onallbands.com/dx-engineering-invites-content-creators-website-owners-to-join-its-new-affiliate-program/ ; https://aes.knoji.com/questions/ham-radio-outlet-affiliate-programs/
- [eton] https://etoncorp.com/ (no program found)
- [gm1] https://www.garmin.com/en-US/ambassadors-and-affiliates/affiliates/
- [gm2] https://commissiondex.com/programs/garmin-outdoor/
- [zl1] https://www.affiliategraph.ai/programs/zoleo
- [rw2] https://www.rakwireless.com/en-us/company/affiliate-program
- [ss2] https://www.affiliategraph.ai/programs/simplisafe ; https://avidaffiliate.com/programs/simplisafe-com/
- [rp1] https://www.affiliategraph.ai/programs/rad-power-bikes
- [le1] https://www.affiliategraph.ai/programs/lectric-ebikes
- [tn1] https://store.ternbicycles.com/pages/affiliate-program
- [sp1] https://www.specialized.com/us/en/specialized-affiliate-program
- [bm1] https://ui.awin.com/merchant-profile/46345
- [vv1] https://ui.awin.com/merchant-profile/28831
- [vv2] https://affiliate-program.vevor.com/overview/
- [kc1] https://kodiakcanvas.com/pages/become-an-affiliate
- [sp2] https://separett.shop/pages/affiliates-program
- [ai1] https://www.airgradient.com/partner-program

### Repo sources reviewed (prior work)

- terrarium-storefront: issues #21, #22 and #61; `src/config/affiliate.js`; `src/config/sourcing-hints.js`; `docs/brand/channels.md`; `research/amazon/README.md`; `research/notes/*.md`.
- Catalog host counts were taken from `src/seed` and `research/`: amazon.com 1127, etsy.com 1000, walmart.com 96, ebay.com 37, homedepot.com 32, target.com 13, costco.com 10, tractorsupply.com 7, harborfreight.com 5. These count URL mentions in seed and research files, not live offerings.
- terrarium-ecom (archived) has no affiliate-program research.
- the-broadcast `knowledge/spine/briefs/commerce.md` covers rules only.
- GitHub code search hit a rate limit partway through. The local clones were searched instead, so other repos under AQuantumArchitect may hold research this run missed.
