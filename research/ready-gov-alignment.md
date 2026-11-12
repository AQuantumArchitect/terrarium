# Ready.gov alignment map

Terrarium storefront: https://store.terrariumproject.org (repo AQuantumArchitect/terrarium-storefront)
Researched: 11 November 2026, America/Los_Angeles
Direction (Luke, 11 Nov 2026): don't work in Ready.gov's negative space. Mirror its topics, reuse its guidance, and add Terrarium's neighbor-level layer on top. Aligning with Ready.gov should also align Terrarium with grant language.

Companion to `search-terms.md`. That file finds the queries official sites answer incompletely. This file takes the opposite approach: Ready.gov's own topic tree is the backbone, and every Terrarium page should line up with a Ready.gov topic and then add what a street of neighbors does.

## Method and limits

- Ready.gov topic tree comes from its live sitemap (https://www.ready.gov/sitemap.xml, 372 URLs, read 11 Nov 2026) and from the nav menus on `/plan`, `/kit`, `/be-informed`, `/get-involved`, `/toolkits`, `/calendar` and the 2026 NPM partner toolkit.
- Listos California topics come from its WordPress sitemaps (`/wp-sitemap-posts-page-1.xml` and the topic and population taxonomies) plus `/disaster-readiness/`, `/blockparty/` and `/be-a-ready-family/`. Some Listos pages return a Cloudflare block to scripted fetches. Those are listed by URL only.
- Ready Ventura County topics come from the nav on https://ready.venturacounty.gov/ (the old readyventuracounty.org redirects there), `/neighborhood-ready/`, `/get-involved/` and `/neighborhood-ready-after-the-disaster/`.
- FEMA vocabulary comes from fema.gov pages fetched today (lifelines, core capabilities, CERT, website reuse policy) and the 2011 Whole Community PDF.
- Terrarium status is judged from each live page's title and meta description (all 198 sitemap URLs fetched today) and a spot read of `/product/household-ready-plan`. No full copy review was done, so "covered" means the topic has a dedicated, on-topic page, not that the copy has been checked against Ready.gov line by line.
- Nobody was contacted.

---

## 1. Topic inventory

### 1a. Ready.gov (FEMA's Ready Campaign)

Top-level structure: Ready.gov's own four-part framing is **Be Informed → Make a Plan → Build a Kit → Get Involved**. Ready Ventura County names the same four as its "STEPS" ("Stay informed, make a plan, build a kit, get involved").

**Disasters and Emergencies (Be Informed)**: hub https://www.ready.gov/be-informed
- Natural hazards:
  - Wildfires: https://www.ready.gov/wildfires
  - Extreme Heat: https://www.ready.gov/heat
  - Floods: https://www.ready.gov/floods
  - Earthquakes: https://www.ready.gov/earthquakes
  - Landslides & Debris Flow: https://www.ready.gov/landslides-debris-flow
  - Tsunamis: https://www.ready.gov/tsunamis
  - Drought: https://www.ready.gov/drought
  - Winter Weather: https://www.ready.gov/winter-weather
  - Severe Weather: https://www.ready.gov/severe-weather
  - Thunderstorms & Lightning: https://www.ready.gov/thunderstorms-lightning
  - Tornadoes: https://www.ready.gov/tornadoes
  - Hurricanes: https://www.ready.gov/hurricanes
  - Volcanoes: https://www.ready.gov/volcanoes
  - Avalanche: https://www.ready.gov/avalanche
  - Space Weather: https://www.ready.gov/space-weather
- Everyday and technological hazards:
  - Power Outages: https://www.ready.gov/power-outages
  - Home Fires: https://www.ready.gov/home-fires
  - Home Safety: https://www.ready.gov/home-safety, with subpages on falls (https://www.ready.gov/preventing-falls-home), poisonings (https://www.ready.gov/preventing-poisonings-home) and burns (https://www.ready.gov/preventing-and-treating-burns)
  - Household Chemical Emergencies: https://www.ready.gov/household-chemical-emergencies
  - Chemicals and Hazardous Materials Incidents: https://www.ready.gov/hazmat
  - Pandemic: https://www.ready.gov/pandemic
  - Cybersecurity: https://www.ready.gov/cybersecurity
- Human-caused and CBRN hazards:
  - Biohazard Exposure: https://www.ready.gov/biohazard
  - Radiation Emergencies: https://www.ready.gov/radiation
  - Explosions: https://www.ready.gov/explosions
  - Mass Gathering Incidents: https://www.ready.gov/mass-gatherings-incidents
  - Active-shooter guidance exists as a hazard information sheet linked from `/be-informed`.
- Alerts and after a disaster:
  - Emergency Alerts: https://www.ready.gov/alerts
  - FEMA App: https://www.ready.gov/fema-app
  - Recovering from Disaster: https://www.ready.gov/recovering-disaster
  - Coping with Disaster: https://www.ready.gov/coping-disaster
- Publications on `/be-informed`:
  - Hazard Information Sheets (17 hazards)
  - the "Are You Ready?" guide
  - Document and Insure Your Property
  - Know Your Alerts and Warnings
  - A Guide for Alerts and Warnings
  - Safeguard Critical Documents and Valuables
  - the "12 Ways to Prepare" postcard

**Make a Plan**: https://www.ready.gov/plan
- The four steps:
  1. Meet with your family. Ask how you'll get alerts, what your shelter plan and evacuation route are, what your household communication plan is, and whether your kit needs updating.
  2. Assess household needs: ages, responsibilities for assisting others, diet, medical needs and devices, access and functional needs, languages, cultural and religious considerations, pets and service animals, and school-aged kids.
  3. Document the plan with the fillable Family Emergency Plan.
  4. Practice the plan.
- Subpages:
  - Plan Ahead: https://www.ready.gov/plan-ahead-disasters
  - Low and No Cost Preparedness: https://www.ready.gov/low-and-no-cost
  - Financial Preparedness: https://www.ready.gov/financial-preparedness
  - Emergency Financial First Aid Kit: https://www.ready.gov/emergency-financial-first-aid-kit
  - Get Tech Ready: https://www.ready.gov/get-tech-ready
  - Evacuation: https://www.ready.gov/evacuation
  - Shelter: https://www.ready.gov/shelter
  - Safety Skills: https://www.ready.gov/safety-skills (first aid and CPR, fire extinguisher, shutting off gas and water)
  - Plan for Locations: https://www.ready.gov/plan-for-locations
  - Home Fire Escape Plan: https://www.ready.gov/home-fire-escape-plan
  - #SummerReady: https://www.ready.gov/summer-ready
  - #WinterReady (nav item; toolkit at https://www.ready.gov/winterready-social-media-toolkit)
  - Ready Campus: https://www.ready.gov/campus
- Specific populations:
  - People with Disabilities: https://www.ready.gov/people-disabilities
  - Older Adults: https://www.ready.gov/older-adults
  - Caregivers: https://www.ready.gov/caregivers
  - Pets and Animals: https://www.ready.gov/pets

**Build a Kit**: https://www.ready.gov/kit
- Subpages:
  - Food: https://www.ready.gov/food
  - Water: https://www.ready.gov/water
  - Car Safety: https://www.ready.gov/car
  - DIY water containers: https://www.ready.gov/preparing-your-own-containers-water and https://www.ready.gov/storing-water-plastic-soda-bottles
- The basic kit list on `/kit`, verbatim items:
  - water ("one gallon per person per day for several days, for drinking and sanitation")
  - several days of non-perishable food
  - battery-powered or hand-crank radio and a NOAA Weather Radio with tone alert
  - flashlight, first aid kit and extra batteries
  - whistle and dust mask
  - plastic sheeting, scissors and duct tape
  - moist towelettes, garbage bags and plastic ties
  - wrench or pliers to turn off utilities
  - manual can opener
  - local maps
  - phone with chargers and a backup battery
- The page also gives:
  - an "Additional Emergency Supplies" list (medications, glasses, infant supplies, pet food, cash, documents, bedding, clothes, fire extinguisher, matches, hygiene items, paper and pencil, and games for kids)
  - kit maintenance advice
  - storage locations (home, work and car)

**Ready Kids**: https://www.ready.gov/kids
- Main pages:
  - Be Ready Kids: https://www.ready.gov/kids/be-ready-kids
  - Teens: https://www.ready.gov/kids/teens
  - Teen CERT: https://www.ready.gov/kids/teen-cert
  - Prepare Your Family: https://www.ready.gov/kids/prepare-your-family
  - Family Emergency Planning: https://www.ready.gov/kids/family-emergency-planning
  - Build a Kit (family): https://www.ready.gov/kids/family-emergency-planning/build-a-kit
  - Helping Children Cope: https://www.ready.gov/kids/helping-children-cope
  - Educators and Organizations: https://www.ready.gov/kids/educators-organizations
  - Curriculum: https://www.ready.gov/kids/curriculum
  - Games: https://www.ready.gov/kids/games
  - Disaster facts for kids: https://www.ready.gov/kids/disaster-facts
- Also: https://www.ready.gov/make-a-plan-kids and https://www.ready.gov/know-facts-kids

**Ready Business**: https://www.ready.gov/business
- Planning (risk assessment, risk mitigation, impact analysis)
- Emergency plans (crisis communications, emergency response, continuity, recovery)
- Training (testing, exercises, employee training)
- Resources (incident management, resource management, hazard prevention)
- Toolkits

**Get Involved**: https://www.ready.gov/get-involved
- "Volunteer & Donate": "cash is best"; volunteer with a recognized organization; join a CERT program.
- "Train & Educate": teach the K-12 curriculum, share Ready's social toolkits and PSAs, take FEMA Emergency Management Institute independent-study courses or a Red Cross CPR course.
- Related:
  - Localized Ready programs: https://www.ready.gov/localized-ready-programs
  - Community and state info: https://www.ready.gov/community-state-info
  - Pledge: https://www.ready.gov/pledge
- CERT lives on fema.gov: https://www.fema.gov/emergency-managers/individuals-communities/preparedness-activities-webinars/community-emergency-response-team
  - Basic training covers fire safety, light search and rescue, team organization and disaster medical operations.
  - Free online courses: IS-317 (Introduction to CERT) and IS-315 (CERT and the ICS).
  - Variants: Teen, Campus and Workplace CERT.
  - Background: started by the LA City Fire Department in 1985 and went national in 1993. FEMA says there are "more than 3,200 local CERT programs" and "more than 600,000 people" trained.

**Campaigns, toolkits and calendar**
- Social media toolkits index: https://www.ready.gov/toolkits
  - Disaster toolkits: Flood, Wildfire, Extreme Heat, Earthquakes, Severe Weather, Hurricane, #WinterReady.
  - Campaign toolkits: Holiday Safety, Financial Preparedness, National Preparedness Month, Resolve to be Ready (https://www.ready.gov/resolution), Life Saving Skills (https://www.ready.gov/life-saving-skills-toolkit), It's Not Luck (https://www.ready.gov/its-not-luck).
  - Community toolkits: Pets, People with Disabilities, Youth.
- 2026 Preparedness Calendar: https://www.ready.gov/calendar (used in section 6)
- National Preparedness Month (NPM) 2026 Partner Toolkit: https://www.ready.gov/2026-national-preparedness-month-partner-toolkit
  - Theme: **"Americans Stand Ready."** It has three ideas: "uphold our patriotic duty," "protect our family and friends," "help our communities."
  - Sample-message pillars: **Make a Plan; Be in the Know** (alerts, evacuation, home injuries, schools and childcare); **Build a Kit; Be there for Your Community.**
- Ready in Your Language: https://www.ready.gov/ready-your-language

> **The key line for Terrarium** is in FEMA's own 2026 NPM toolkit: "From house fires that displace a single family, to tornadoes that destroy entire communities, we have seen time and time again that it's our neighbors who are first to respond … That's why it's so important to get to know your neighbors and invite them to be a part of your emergency plan." It also says: "In most emergencies, our families, neighbors and coworkers are the first people who come to our aid." The neighbor layer is not in Ready.gov's negative space. Ready.gov is asking for it, and Terrarium is the long-form version.

### 1b. Listos California (Cal OES)

- Hazard hub: https://www.listoscalifornia.org/disaster-readiness/. Topics: El Niño, Wildfires, Wildfire Smoke, Power Outage, Fast & Cold Water, Floods, Earthquakes, Severe Storms, Extreme Heat.
  - Subpages: `/disaster-readiness/wildfires/`, `/wildfire-smoke/`, `/power-outage/`, `/floods/`, `/fast-and-cold-water/`, `/severe-storms/`, `/earthquakes/`, `/extreme-heat/`
  - Related: `/stormseason/`, `/el-nino-in-california/`, `/winter-weather-toolkit/`
- **Neighborhood Block Party Initiative**: https://www.listoscalifornia.org/blockparty/
  - The page says "Connected neighbors survive disasters at higher rates and recover quicker." It also says it has "Distributed 4,000 kits across 51 counties."
  - It offers a free print-at-home kit with games: a scavenger hunt, "price of preparedness," and "two truths and a lie."
  - **This is the closest official match to Terrarium's Culture axis and weekly dinners.**
- Be a Ready Family: https://www.listoscalifornia.org/be-a-ready-family/
  - Listos's "5 steps to preparedness"
  - Disaster Ready Guide and Disaster Ready Card in 8 languages
  - an online course and a week of daily texts
- Other pages:
  - Prepare your community: `/prepare-your-community/`, `/prepare-your-community/host-a-training/`, `/prepare-your-community/toolkit/`
  - Hazard maps in 6 languages; disaster directories; wellness and resource guides
  - Recovery: `/recovery-help/`
  - Alerts: `/alerts/`
  - Mental health: `/impact-initiatives/mental-health/`
  - Outreach programs: peer-to-peer outreach (`/peer-to-peer-outreach/`), heroes (`/heroes/`), training (`/training/`), preparedness games (`/general-preparedness-games/`), Listas (women-led household preparedness; `/impact-initiatives/listas/`), Indigenous-language outreach, and the social bridging project (`/community-projects/social-bridging-project/`)
- Groups Listos targets: all Californians, community organizations, farmworkers, food and agricultural workers, people experiencing homelessness, families, the Deaf community, children and women.

### 1c. Ready Ventura County (County Sheriff's Office of Emergency Services)

Internal reference only. Per the standing rule, don't name Luke's location in public copy. Ready Ventura County can be cited as one example of a county Ready program, alongside others, but never as "our county."

- STEPS framing: Stay Informed (https://ready.venturacounty.gov/stay-informed/), Make a Plan (`/plan/`), Build a Kit (`/prepare/`, with a kit "plan builder"), Get Involved (`/get-involved/`)
- Hazards:
  - Dam Failure: `/dam-failure/`
  - Earthquake: `/earthquake/`
  - Extreme Heat: `/extreme-heat/`
  - Flood: `/flood/`
  - Human-Caused: `/human-caused/`
  - Landslide/Debris Flow: `/landslide-debris-flow/`
  - **Public Safety Power Shutoff: `/public-safety-power-shutoff/`**
  - Tsunami: `/tsunami/`
  - Weather: `/weather/`
  - Wildfire: `/wildfire/`
- **Neighborhood Ready**: `/neighborhood-ready/`
  - Covers access and functional needs, business and educators, "Kids Can!", pets (including a pet "exit buddy" and window sign) and older adults.
  - After the Disaster: `/neighborhood-ready-after-the-disaster/` (declarations, damage assessment, FEMA Individual Assistance, SBA loans)
- Get Involved uses a superhero metaphor:
  - "Adopt a Sidekick" means checking on neighbors and having an evacuation buddy.
  - "Become an Influencer" means sharing preparedness tips.
  - Links: Red Cross, Auxiliary Communication Services (ham radio), CERT and the Citizen Academy.
- Other: VC Alert signup (`/vc-alert/`), County Plans (EOP and Hazard Mitigation Plan updates, 2026), events calendar, Agriculture Pass Program.

---

## 2. How we may reuse it

**Short version:**
- Copy and adapt FEMA and Ready.gov text and checklists freely, and cite them with a link.
- Never use the Ready, FEMA, DHS or CERT logos, seals or program marks.
- Never imply that FEMA, Ready.gov, Cal OES or the county endorses Terrarium or what it sells.
- Treat photos and other third-party material as copyrighted unless they're marked otherwise.

What the sources say:

1. **The text is public domain.**
   - FEMA's reuse policy (https://www.fema.gov/about/website-information#copyright) says: "Most material on FEMA.gov is free of copyright and may be copied and distributed without permission … Citation of FEMA.gov and a link back is much appreciated." FEMA lists Ready.gov as one of its own domains on the same page.
   - US government works are not copyrighted (17 U.S.C. §105, linked from https://www.usa.gov/government-copyright).
2. **Photos and graphics are the exception.** FEMA: "We sometimes use photos or graphics that we licensed or that are restricted. Check to see if there is a copyright or photo credit. You need to request permission from the original source." The Get Involved and kit pages also embed co-branded partner material, such as Red Cross links and Ready Kids games. **Write our own text and make our own diagrams rather than lifting Ready.gov images.**
3. **Logos and marks are off-limits.**
   - Ready.gov Terms (https://www.ready.gov/terms-and-conditions): "The Ready workmark logo and related marks are trademarked and are owned by the U.S. Government."
   - The DHS IP policy (https://www.dhs.gov/department-homeland-security-intellectual-property-policy) lists marks that need *written permission* to use. Among them:
     - READY KIDS (word mark)
     - READY 2 HELP
     - READY CHECK (several versions)
     - LISTO (DHS's own Spanish-language campaign mark, not Listos California)
     - CITIZEN CORPS
     - YOUTH PREPAREDNESS COUNCIL
     - the DHS seal
   - The same policy says: **"Use of a DHS mark as part of a URL is forbidden."**
   - In practice:
     - Don't create `/ready-kids` or similar slugs.
     - Don't title a Terrarium page "Ready Kids" or "Ready 2 Help."
     - Describe them instead, for example: "FEMA's Ready Kids program has free games — link."
4. **No implied endorsement.** USAGov: "You cannot use government materials in a way that implies endorsement by a government agency … you cannot use an agency logo or trademark on your social media page to suggest endorsement or sponsorship." FEMA's linking policy also says it "does not endorse … the products/services they offer."
5. **The CERT logo is especially restricted.** FEMA's CERT Logo Usage Guide (https://fema-community-files.s3.amazonaws.com/CERT_Logo_Usage_Guide.pdf) says the logo "must be used in connection with registered CERT programs," "may not be used in any way … that implies the endorsement of any person, product, or service," and the customized sub-logo "may not be used for any commercial or for-profit purposes." **It must never appear on the store or on product images.** Check `/product/cert-trauma` (described as a "CERT-style loadout"). I did not inspect its images this turn.
6. **State and local works are different.**
   - USAGov: "The U.S. government work designation does not apply to works of state and local governments."
   - Listos California's terms (https://www.listoscalifornia.org/terms-conditions/, the State of California use policy) say information "unless otherwise indicated, is considered in the public domain," but copyrighted data such as photos may need permission. Quote and adapt Listos text with attribution; don't use its logo or photos.
   - Ready Ventura County: I found no reuse terms this turn. Paraphrase and link only.
7. **Keep it current.**
   - Ready.gov's terms warn its content may not be current, and FEMA's NPM toolkit asks sharers to "Update Regularly" and "clarify outdated guidance." Re-check any number we quote, at least once a year.
   - Example: the earlier `search-terms.md` quotes "3 days minimum, 2 weeks preferred." Ready.gov's `/kit` and `/water` pages, read today, say "one gallon per person per day for several days." Quote Ready.gov's current wording, or verify CDC's page before quoting the 3-day/2-week figures.
8. **The NPM toolkit explicitly invites reuse:** "We encourage you to share materials via your social media, email announcements, newsletters, and more" and "Feel free to customize these messages for your specific community or audience."

**Attribution format (use as-is):**
- On a page: `Adapted from FEMA's Ready campaign, "Build a Kit," https://www.ready.gov/kit (checked Nov 2026). Terrarium is independent and is not affiliated with or endorsed by FEMA, DHS, or Ready.gov.`
- In a social caption: `Checklist adapted from Ready.gov (FEMA). Not affiliated.`
- For Listos California: `Adapted from Listos California (Cal OES), <URL>.`

**Existing site check:**
- `/product/household-ready-plan` already says "Terrarium is not a CERT program, not a county OEM, and not FEMA-endorsed." Keep that sentence and reuse it on every civic page.
- **The problem:** free Ready.gov resources are rendered through the store product template. That page reads "Check current price at Ready.gov," "Buy on Ready.gov ↗," "✓ In stock," "Price at retailer from Ready.gov," and "We last saw a price here 78 days ago." That frames a public agency as a retailer and puts stock language next to a government resource.
- **Recommended builder fix (small PR):** for listings whose seller is a `.gov` domain or a known public program, swap the price, stock and "Buy on" block for "Free public resource · Open on Ready.gov ↗," and hide the price-freshness line.
- The same template appears on other civic product pages that link Ready.gov, the National Flood Insurance Program and similar resources: `official-alert-signup`, `access-functional-needs`, `home-fire-and-ignition`, `shelter-in-place-or-go`, `paper-degrade-path`, `disaster-assistance-door` and `household-pets-plan`.

---

## 3. Topic-by-topic alignment map

Status key:
- **Covered**: an on-topic Terrarium page exists.
- **Partial**: an adjacent page exists but doesn't target the Ready.gov topic.
- **New**: no page yet.
- **Skip**: off-mission for a neighborhood store, so link out only.

"Neighbor layer" is what Terrarium adds on top of Ready.gov's household guidance.

Axis abbreviations:
- Shelter = Shelter & Hospitality
- Food = Food & Nutrition
- Water = Water Security
- Sanit = Sanitation & Hygiene
- Energy = Energy & Power
- Health = Health & Medical
- Safety = Security & Safety
- Comms = Communication & Info
- Transport = Transport & Mobility
- Tools = Tools & Manufacturing
- Gov = Governance & Coordination
- Culture = Culture & Recreation

### 3a. The four pillars and the cross-cutting topics

| Ready.gov topic | Terrarium page(s) today | Axis | Neighbor layer Terrarium adds | Status |
|---|---|---|---|---|
| Be Informed / hazard hub (`/be-informed`) | `/scenarios` (index), `/resilience-framework` | Gov | A "what hits this street" walk: which hazards, which neighbors are most exposed, where the gathering spot is | Partial (no hazard-by-hazard hub) |
| Emergency Alerts (`/alerts`), FEMA App | `/product/official-alert-signup`, `/blog/alerts-that-actually-reach-you`, `/product/noaa-weather-radio-path`, `/product/paper-degrade-path` | Comms | Who on the block doesn't get alerts (no smartphone, language, hearing) and who knocks on their door | Covered |
| Make a Plan, 4 steps (`/plan`) | `/product/household-ready-plan`, `/neighbors`, `/blog/who-are-your-three`, `/blog/the-phone-tree-that-isnt-a-phone-tree` | Gov | Step 2 already says "responsibilities for assisting others." Terrarium turns that into "your three," an out-of-area contact and a street contact sheet | Covered (upgrade: a printable that adds the street to FEMA's form) |
| Plan Ahead (`/plan-ahead-disasters`) | `/scenarios/baseline-assessment` | Gov | A household baseline plus a street baseline (shared tools, skills, vulnerable neighbors) | Partial |
| Low and No Cost Preparedness (`/low-and-no-cost`) | `/blog/30-day-pantry-rotation-strategy`, `/blog/four-shelves-of-capability` | Gov / Food | "Borrow before you buy": tool library, shared generator, the one neighbor with a ladder. Fits the store's honest "you may already have this" stance | New (dedicated page) |
| Build a Kit (`/kit`) | Buyer's guides (water, food, first aid, comms, power), `/blog/four-shelves-of-capability` | All | The block kit: items no one household needs alone (big first-aid kit, radios, a shared power station, a canopy) | Partial (no "start from Ready.gov's list" page) |
| Food (`/food`) | `/blog/30-day-pantry-rotation-strategy`, `/blog/buyers-guide-food-storage-and-cooking`, `/scenarios/food-shortage`, `/product/emergency-food`, `/product/thirty-day-emergency-food-bucket`, `/domain/food_nutrition` | Food | Pooled cooking after an outage (the full freezers on the street get eaten first, together). Weekly dinners as practice | Covered |
| Water (`/water`, container pages) | `/blog/72-hour-water-plan-suburban-households`, `/blog/buyers-guide-water-storage-and-filtration`, `/scenarios/water-disruption`, `/product/water-storage`, `/product/water-purification` | Water | Who has a pool, rain barrels or a gravity filter. Who can't carry water up stairs | Covered (re-check the gallon wording against current Ready.gov) |
| Car Safety (`/car`) | `/scenarios/mobility-vignettes`, `/blog/15-minute-evacuation-suburban-families` | Transport | Car-less neighbors, and pairing rides before an evacuation | Partial |
| Financial Preparedness, Emergency Financial First Aid Kit | `/blog/cash-cards-chaos-financial-resilience` | Gov | A small cash envelope, informal lending norms on the block, helping a neighbor find documents | Partial (cite EFFAK) |
| Get Tech Ready (`/get-tech-ready`); Safeguard Documents | `/product/community-digital-archive`, `/product/paper-degrade-path` | Comms | Printed contact sheets; "go-drive" copies for an elder neighbor | Partial |
| Evacuation (`/evacuation`) | `/scenarios/evacuation`, `/blog/15-minute-evacuation-suburban-families`, `/product/shelter-in-place-or-go` | Transport | Two routes out of the subdivision, an evacuation buddy (Ready VC's "sidekick"), and who goes with whom | Covered |
| Shelter (`/shelter`) | `/scenarios/shelter-in-place`, `/scenarios/family-in-distress`, `/blog/hosting-household-neighborhood-anchor`, `/scenarios/bunkhouse-origin` | Shelter | Hosting evacuated friends and family: the "hospitality" half of the axis Ready.gov doesn't cover | Covered |
| Safety Skills (`/safety-skills`) | `/product/red-cross-first-aid-cpr`, `/product/stop-the-bleed-course`, `/product/cert-basic-training` | Health / Safety | Skills inventory on the block. Group sign-ups for a class. A street walk to find every gas and water shutoff | Partial (no utility-shutoff page) |
| Plan for Locations (`/plan-for-locations`) | none | Gov | School, work and care-home plans; who picks up whose kids | New |
| Home Fire Escape Plan (`/home-fire-escape-plan`) | `/product/home-fire-and-ignition` | Safety | Smoke-alarm battery day as a street event | Partial |
| #SummerReady / #WinterReady | `/scenarios/climate-failure`, `/blog/keeping-comfortable-without-grid` | Shelter / Energy | Cooling and warming rooms in someone's house; checking on heat-vulnerable neighbors | Partial |
| People with Disabilities (`/people-disabilities`) | `/product/access-functional-needs`, `/blog/access-on-a-block-of-stairs` | Health | Personal support network (Ready.gov language); device charging agreements; registry prompts | Covered |
| Older Adults (`/older-adults`) | `/product/access-functional-needs` (partly) | Health / Culture | A daily check-in rota; "one call by 10am" | Partial → New page |
| Caregivers (`/caregivers`) | none | Health | Backup caregiver on the block | New (fold into the older-adults page) |
| Pets and Animals (`/pets`) | `/product/household-pets-plan` | Shelter | Pet "exit buddy" (Ready VC), a window sign, and which neighbors can take animals | Covered |
| Ready Kids (`/kids`, teens, Teen CERT, coping) | none (the store isn't kid-facing) | Culture | Family drills as play; the block-party scavenger hunt; teens as runners. Don't use "Ready Kids" as a title (DHS word mark) | New |
| Ready Business (`/business`) | `/scenarios/workshop-house-origin`, `/product/station-as-civic-node` | Tools / Gov | Corner businesses and home workshops as block assets | Skip as a full topic; link out |
| Ready Campus (`/campus`) | none | n/a | n/a | Skip |
| Get Involved, Volunteer & Donate (`/get-involved`) | `/product/voad-and-spontaneous-volunteers`, `/civic` | Gov | Donate cash, not stuff (Ready.gov). How unaffiliated helpers plug in | Covered |
| Get Involved, CERT (fema.gov) | `/product/cert-basic-training`, `/blog/cert-is-not-a-bunker-club`, `/product/ics-shared-language`, `/blog/is-100-without-becoming-a-cop` | Gov / Safety | A CERT-trained neighbor as the street's link to the county; IS-317 as a free first step | Covered |
| Train & Educate (EMI, Red Cross CPR, share toolkits) | `/product/ics-shared-language`, `/product/red-cross-first-aid-cpr` | Gov | Hosting a class night | Covered |
| Local emergency management (`/community-state-info`, FEMA locations) | `/product/local-oem-interface`, `/blog/find-your-oem-in-twenty-minutes`, `/blog/write-your-oem-on-a-quiet-tuesday`, `/blog/the-street-and-the-county`, `/blog/county-liaison-at-the-long-table`, `/blog/day-three-protocol` | Gov | The handshake: the street holds the first 72 hours and the county arrives on day three | Covered (Terrarium's strongest cluster) |
| Recovering from Disaster (`/recovering-disaster`) | `/product/disaster-assistance-door` | Gov / Shelter | Neighbors helping each other file, document damage and clean up | Partial |
| Coping with Disaster (`/coping-disaster`) | Culture pages (`/scenarios/weekly-community-dinner`, `/blog/games-night-is-infrastructure`) | Culture / Health | Shared meals and rituals after the event; noticing who has withdrawn | Partial → New |

### 3b. Hazards

| Ready.gov hazard | Terrarium page(s) today | Axis | Neighbor layer | Status |
|---|---|---|---|---|
| Power Outages (`/power-outages`), plus Ready VC and Listos PSPS pages | `/scenarios/power-outage-v2`, `/blog/flashlights-to-quiet-power-energy-buffer`, `/blog/buyers-guide-backup-power-without-a-generator`, `/product/solar-generators` | Energy | Planned shutoffs (PSPS): device-dependent neighbors, a shared charging porch, fridge hours, the manual garage-door release | Covered for general outages; **New** for a PSPS-specific page |
| Wildfires (`/wildfires`) | `/scenarios/evacuation`, `/product/home-fire-and-ignition`, `/blog/15-minute-evacuation-suburban-families` | Safety / Transport | Zone 0 work parties; checking that every house heard the evacuation warning; pets and car-less neighbors | Partial (no wildfire hub; Zone 0 explainer missing) |
| Wildfire smoke (Listos `/disaster-readiness/wildfire-smoke/`; EPA) | `/scenarios/shelter-in-place`, `/scenarios/climate-failure` | Health / Shelter | Whose house has a cleaner-air room; HEPA lending; sensitive neighbors | New |
| Earthquakes (`/earthquakes`), Great ShakeOut | `/product/window-status-cards`, `/product/map-your-neighborhood-block` | Safety / Gov | HELP/OK window cards, the gathering site, a shutoff walk, a block ShakeOut drill | **New scenario** |
| Floods (`/floods`), Listos storm season and El Niño | `/scenarios/water-disruption` (adjacent) | Water / Shelter | Atmospheric-river week: low-lying neighbors, sandbag help, never driving through floodwater | New |
| Landslides & Debris Flow (`/landslides-debris-flow`) | none | Safety | Burn-scar neighbors after fire season; evacuation buddies | New (fold into the flood page) |
| Extreme Heat (`/heat`) | `/scenarios/climate-failure`, `/blog/keeping-comfortable-without-grid` | Shelter / Health | A cool-room host; a check-in rota for elders | Partial → New |
| Winter Weather (`/winter-weather`) | `/scenarios/climate-failure` | Shelter / Energy | A warming room; shoveling help for neighbors who can't. Matters for the national audience | Partial |
| Severe Weather, Thunderstorms, Tornadoes, Hurricanes | `/scenarios/shelter-in-place` | Shelter | Safe-room sharing; post-storm street check | Partial. Ready.gov owns these; add one "storms" page later for a national audience |
| Tsunamis (`/tsunamis`) | none | Transport | Coastal walk-out route buddies | New (low priority, coastal only) |
| Drought (`/drought`) | `/product/diverters`, `/product/solarpunk-rain-chain`, `/domain/water_security` | Water | Greywater and rainwater as street norms | Partial |
| Home Fires (`/home-fires`) | `/product/home-fire-and-ignition` | Safety | Smoke-alarm day; spare extinguishers | Covered |
| Home Safety (falls, poisonings, burns) | `/blog/home-clinic-medical-capability`, `/product/compact-first-aid-trauma-kit` | Health | Grab-bar and fall checks for elder neighbors | Partial |
| Household Chemical Emergencies, Hazmat | none | Safety | Shelter-in-place and seal-a-room supplies (plastic sheeting and tape are on Ready.gov's kit list) | Partial (cover inside the shelter-in-place page) |
| Pandemic (`/pandemic`) | `/scenarios/shelter-in-place` | Health / Sanit | Grocery runs for isolating neighbors; contactless porch drops | Partial |
| Cybersecurity (`/cybersecurity`) | none | Comms | Scam warnings after a disaster; helping an elder spot a fake "FEMA" caller | New (short) |
| Space Weather, Radiation, Biohazard, Explosions, Mass Gatherings, Avalanche, Volcanoes | none | n/a | n/a | Skip; link to Ready.gov from the hazard hub |

### 3c. State and county topics worth mirroring

| Source topic | Terrarium page(s) today | Axis | Neighbor layer | Status |
|---|---|---|---|---|
| Listos Neighborhood Block Party | `/scenarios/weekly-community-dinner`, `/blog/the-first-shared-meal`, `/blog/games-night-is-infrastructure`, `/product/block-party-kits` | Culture / Gov | Same idea; Terrarium adds the standing weekly version and the coordination that follows | Covered in spirit; **New** "host a preparedness block party" how-to that links Listos's free print-at-home kit |
| Listos "Fast & Cold Water" | none | Safety | Spring snowmelt and river safety; supervising kids | Skip/link |
| Ready VC "Adopt a Sidekick" / evacuation buddy | `/blog/who-are-your-three` | Gov | Same concept, with a different name | Covered |
| Ready VC Neighborhood Ready: Kids Can!, pets, older adults, AFN | see rows above | | | |
| Ready VC After the Disaster (Individual Assistance, SBA) | `/product/disaster-assistance-door` | Gov | Help neighbors file | Partial |
| Ready VC Agriculture Pass | none | n/a | n/a | Skip |

---

## 4. Grant and FEMA vocabulary crosswalk

### 4a. Terms to use (and how Terrarium fits them)

- **Whole Community** (FEMA, *A Whole Community Approach to Emergency Management*, 2011: https://www.fema.gov/sites/default/files/2020-07/whole_community_dec2011__2.pdf).
  - The three principles: "Understand and meet the actual needs of the whole community"; "Engage and empower all parts of the community"; "Strengthen what works well in communities on a daily basis."
  - The six strategic themes: understand community complexity; recognize community capabilities and needs; foster relationships with community leaders; build and maintain partnerships; empower local action; **"Leverage and strengthen social infrastructure, networks, and assets."**
  - Terrarium's weekly dinners, games nights and "your three" are a literal case of "strengthen what works well … on a daily basis" and "leverage and strengthen social infrastructure." Use those exact phrases in grant narratives.
- **Community Lifelines** (https://www.fema.gov/emergency-managers/practitioners/lifelines). Note that **FEMA now lists 8 lifelines, not 7.** Water Systems is the eighth, shown on FEMA's current page:
  1. Safety and Security: law enforcement and security, fire service, search and rescue, government service, community safety
  2. Food, Hydration, Shelter: food, hydration, shelter, agriculture
  3. Health and Medical: medical care, public health, patient movement, medical supply chain, fatality management
  4. Energy: power grid, fuel
  5. Communications: infrastructure, responder communications, alerts, warnings and messages, finance, 911 and dispatch
  6. Transportation: roadway, transit, rail, aviation, maritime
  7. Hazardous Materials: facilities, hazmat, pollutants, contaminants
  8. Water Systems: potable water infrastructure, wastewater management

  FEMA's page also says the lifeline concept "can be applied across the entire preparedness cycle," not just in response. That gives Terrarium standing to use it for household and street preparedness.
- **National Preparedness Goal: 5 mission areas and 32 core capabilities** (https://www.fema.gov/emergency-managers/national-preparedness/mission-core-capabilities).
  - The mission areas are Prevention, Protection, Mitigation, Response and Recovery.
  - Terrarium sits in **Mitigation, Response and Recovery**. Stay out of Prevention and Protection: those are terrorism, interdiction and law enforcement.
  - The capabilities closest to Terrarium's work:
    - **Community Resilience**: "empower individuals and communities to make informed risk management decisions." This is Terrarium's core.
    - **Planning**: "engaging the whole community."
    - **Public Information and Warning**: "culturally and linguistically appropriate methods."
    - **Operational Coordination**
    - **Risk and Disaster Resilience Assessment**: assessing risk so that "community members can take informed action"
    - **Threats and Hazards Identification**
    - **Long-term Vulnerability Reduction**
    - **Mass Care Services**: hydration, feeding, sheltering, evacuee support, reunification
    - **Critical Transportation**: "accessible transportation services … evacuation of people and animals"
    - **Logistics and Supply Chain Management**: "emergency power and fuel support … community staples"
    - **Public Health, Healthcare, and EMS**
    - **Health and Social Services**: including behavioral health
    - **Housing**
    - **Economic Recovery**
    - **Natural and Cultural Resources**: "social, cultural … fabric of communities" in the Recovery mission
    - **Infrastructure Systems**
    - **Environmental Response/Health and Safety**
    - **Fire Management and Suppression**: defensible space and home hardening only
    - **Mass Search and Rescue Operations**: only as CERT-trained light search and rescue, under official direction
- **CERT**, Teen CERT, and FEMA EMI independent-study courses (IS-317, IS-315; and IS-100 and IS-700 for ICS and NIMS, already on `/product/ics-shared-language`).
- **Access and functional needs (AFN)** and "personal support network": the phrasing Ready.gov uses on its disability pages, and the one county programs use.
- **"Culture of Preparedness"**: FEMA's CERT page uses it.
- **NPM 2026 language**: "Americans Stand Ready"; "help our communities"; "Preparedness is a shared responsibility, and we all have a role to play."

### 4b. Axes → lifelines → core capabilities

| Terrarium axis | Community Lifeline(s) | Core capabilities | Mission areas |
|---|---|---|---|
| Shelter & Hospitality | Food, Hydration, Shelter (shelter) | Mass Care Services (sheltering, evacuee support, reunification); Housing | Response, Recovery |
| Food & Nutrition | Food, Hydration, Shelter (food, agriculture) | Mass Care Services (feeding); Logistics and Supply Chain Management (community staples); Economic Recovery (food and agriculture) | Response, Recovery |
| Water Security | Water Systems (potable); Food, Hydration, Shelter (hydration) | Mass Care Services (hydration); Infrastructure Systems; Long-term Vulnerability Reduction (storage, catchment) | Mitigation, Response |
| Sanitation & Hygiene | Water Systems (wastewater); Health and Medical (public health); Hazardous Materials (pollutants and contaminants) | Environmental Response/Health and Safety; Public Health, Healthcare, and EMS | Response, Recovery |
| Energy & Power | Energy (power grid, fuel) | Infrastructure Systems; Logistics and Supply Chain Management (emergency power and fuel support); Long-term Vulnerability Reduction | Mitigation, Response |
| Health & Medical | Health and Medical (medical care, public health, medical supply chain) | Public Health, Healthcare, and EMS; Health and Social Services (incl. behavioral health) | Response, Recovery |
| Security & Safety | Safety and Security (fire service, search and rescue, community safety); Hazardous Materials (household chemicals, gas shutoff) | Fire Management and Suppression (defensible space); Long-term Vulnerability Reduction (home hardening); Mass Search and Rescue (CERT light SAR only); Environmental Response/Health and Safety; Cybersecurity (scam awareness). **Do not claim** On-Scene Security, Protection, and Law Enforcement | Mitigation, Response |
| Communication & Info | Communications (alerts, warnings and messages; finance) | Public Information and Warning; Operational Communications; Situational Assessment | All (Public Information is all-mission) |
| Transport & Mobility | Transportation (roadway) | Critical Transportation (evacuation of people and animals, accessible transport) | Response |
| Tools & Manufacturing | Safety and Security (utility shutoff as community safety); Energy and Water Systems (repair) | Infrastructure Systems; Logistics and Supply Chain Management; Long-term Vulnerability Reduction; Economic Recovery | Mitigation, Recovery |
| Governance & Coordination | Safety and Security (government service interface) | Planning; Operational Coordination; Community Resilience; Risk and Disaster Resilience Assessment; Threats and Hazards Identification | All |
| Culture & Recreation | No lifeline. Lifelines are services, and social cohesion is not one | Community Resilience; Health and Social Services (behavioral health); Natural and Cultural Resources ("social, cultural … fabric of communities"). Whole Community theme 6: "Leverage and strengthen social infrastructure, networks, and assets" | Mitigation, Recovery |

**Gap the crosswalk shows:** nothing on the 12 axes maps cleanly to the Hazardous Materials lifeline beyond household chemicals and gas. That's fine. Say so plainly in grants and don't stretch.

**Grant-narrative template sentence.** It uses FEMA's own words and makes no claim about status:
> "Terrarium supports the Community Resilience core capability by strengthening what already works in neighborhoods on a daily basis — shared meals, skills lists, and check-in networks — so that households can sustain the Food, Hydration, Shelter; Water Systems; Energy; and Communications lifelines on their own street during the first 72 hours, and hand off cleanly to local emergency management and CERT."

Don't state that Terrarium "is" a Whole Community partner, a CERT program, or a FEMA-recognized anything.

---

## 5. Top 20 content build list (prioritized)

Each page follows the same rules:
- Start from the Ready.gov page, adapted and cited with the attribution line in section 2.
- Add the neighbor layer and link existing Terrarium pages.
- Carry the "not FEMA-endorsed" line.
- No prices, stock or invented figures. No CERT, Ready or FEMA logos. No Luke location.

Ordered by Ready.gov alignment × gap × fit with the store.

1. **Fix first (builder PR):** the free-public-resource template (section 2). Swap "Buy on Ready.gov / In stock / price" for "Free public resource · Open on Ready.gov." Also:
   - remove the 301 redirect URLs from the sitemap (`/scenarios/power-outage`, `-extended` and `/scenarios/communication-loss` point to `-v2` and `communication-grid`);
   - add a `<title>` to `/product/window-status-cards`, which has none today.
2. **Preparedness basics hub, "The four steps, plus your street"** (new; suggested slug `/prepare`, not a slug with "ready" in it).
   - Covers Ready.gov's Be Informed, Make a Plan, Build a Kit and Get Involved, each with a neighbor layer.
   - Links Ready.gov and every Terrarium cluster below. This is the canonical alignment page and the one to quote in grant applications.
3. **Make a plan that includes the street** (upgrade `/product/household-ready-plan`, plus a printable). Ready.gov's 4 steps and fillable form, plus "your three," a street contact sheet, the gathering spot and who checks on whom.
4. **Build a kit over time, and borrow before you buy** (new). Ready.gov's basic list and Low and No Cost page, with what the block can share. Link the buyer's guides without prices.
5. **Planned power shutoffs (PSPS) on a street** (new). Ready.gov Power Outages plus county and Listos PSPS pages:
   - medical devices
   - fridge and freezer hours (cite USDA)
   - garage-door release
   - shared charging
6. **Earthquake: the block after the shaking** (new scenario). Ready.gov Earthquakes, the ShakeOut drill, HELP/OK window cards, the gas and water shutoff walk, the gathering site. Publish before the October ShakeOut.
7. **Wildfire hub** (new hub linking existing pages):
   - Zone 0 and home ignition (upgrade `/product/home-fire-and-ignition`)
   - the 15-minute evacuation
   - pets
   - car-less neighbors
   - evacuation warning vs. order
8. **Wildfire smoke: a cleaner-air room, and who on the block needs one** (new). Cite EPA and Listos.
9. **Extreme heat on a block** (new; extends `/scenarios/climate-failure`). Ready.gov `/heat`, a cool-room host and an elder check-in rota.
10. **Floods and atmospheric-river week** (new). Ready.gov Floods, Landslides & Debris Flow (burn scars) and Listos storm season.
11. **Older adults and caregivers: one call by 10am** (new). Ready.gov Older Adults and Caregivers, a check-in rota and a backup caregiver.
12. **People with disabilities: the personal support network** (upgrade `/product/access-functional-needs` and `/blog/access-on-a-block-of-stairs`). Ready.gov's wording and the local registry prompt from the NPM toolkit.
13. **Water when the tap is off: storage, treatment, toilets, boil-water notices** (upgrade the 72-hour plan, plus a new FAQ). Ready.gov Water and its container pages, cited exactly ("several days"). Covers the sanitation axis too.
14. **Five safety skills for every household on the street** (new). Ready.gov Safety Skills: first aid and CPR, fire extinguisher, gas and water shutoff (never turn gas back on yourself), plus Stop the Bleed. Group class sign-ups.
15. **Pets: the exit buddy** (upgrade `/product/household-pets-plan`). Ready.gov Pets, plus the pet exit buddy and window sign from county guidance.
16. **Kids and teens in the family plan** (new). Draws on Ready.gov's kids pages and Teen CERT, Listos family videos and the block-party scavenger hunt. Don't title it "Ready Kids."
17. **Host a preparedness block party** (new). Listos's Block Party Initiative and free print-at-home kit, Ready.gov's "get to know your neighbors," and Terrarium's weekly dinner as the standing version. The friendliest front door to the whole store.
18. **Money, documents and phones** (upgrade `/blog/cash-cards-chaos-financial-resilience`). Ready.gov Financial Preparedness and EFFAK, Get Tech Ready and Safeguard Critical Documents.
19. **After the disaster: recovery and coping on a street** (upgrade `/product/disaster-assistance-door`, plus new). Ready.gov Recovering and Coping, Individual Assistance and SBA basics (link, don't summarize amounts), scam warnings (Cybersecurity) and shared meals.
20. **Get involved: CERT, Red Cross, VOAD and the county** (upgrade `/civic` as the hub). Ready.gov Get Involved, IS-317 as the free first step, and "cash is best" donations. Point to official programs; no CERT logo.

Later, for a national audience: one "storms" page (tornado, hurricane, severe weather, winter storm), a tsunami walk-out note, and a short Plan for Locations page (school, work, care home).

---

## 6. Quarterly social calendar, keyed to Ready.gov's preparedness calendar

Source: Ready.gov 2026 Preparedness Calendar (https://www.ready.gov/calendar, updated 08/06/2026) and its social toolkits (https://www.ready.gov/toolkits). Re-check the calendar when FEMA posts the 2027 version. Other dates:
- Atlantic hurricane season runs June 1–November 30, and the Eastern Pacific season May 15–November 30 (https://www.ready.gov/hurricanes).
- Great ShakeOut is October 15 in 2026 (https://www.shakeout.org/). It's usually the third Thursday of October, so confirm the 2027 date there.

Rules for every post:
- Link a live Terrarium page, or a new page once it ships.
- Cite Ready.gov or Listos when adapting.
- No prices or stock claims.
- No Luke location: say "your county" or "your city," never ours.
- No agency logos. Make our own graphics.
- @terrariumresilience, posted manually through Grok Bot for now.

**Q1: January–March**
- January, #WinterReady and Resolve to be Ready (`/resolution`):
  - "One preparedness resolution: name your three." Links `/neighbors`.
  - Ready.gov's 4-step plan as a carousel. Links `/product/household-ready-plan`.
- February, National Canned Food Month and #WinterReady:
  - "The pantry that actually gets used." Links `/blog/30-day-pantry-rotation-strategy`.
  - Warming-room host checklist. Links `/scenarios/climate-failure`.
- March, Spring and Flood Safety; National Tsunami Awareness Week:
  - "Documents on a high shelf" (Ready.gov Low and No Cost). Links `/blog/cash-cards-chaos-financial-resilience`.
  - Storm-week neighbor check. Links the flood page (#10) when live, or `/scenarios/water-disruption`.

**Q2: April–June**
- April, Severe Weather Safety:
  - "Alerts that actually reach you." Links `/blog/alerts-that-actually-reach-you` and `/product/noaa-weather-radio-path`.
  - Safe-room sharing. Links `/scenarios/shelter-in-place`.
- May, National Wildfire Awareness Month; National Hurricane Preparedness Week; Eastern Pacific hurricane season opens May 15:
  - Zone 0 weekend. Links `/product/home-fire-and-ignition`.
  - The 15-minute drill. Links `/blog/15-minute-evacuation-suburban-families`.
  - "Stay or go?" Links `/product/shelter-in-place-or-go`.
  - Pet exit buddy. Links `/product/household-pets-plan`.
- June, Lightning Safety Awareness Week and #SummerReady; Atlantic season opens June 1:
  - "Who on your block needs a cool room?" Links `/scenarios/climate-failure`.
  - Power outage basics from Ready.gov. Links `/scenarios/power-outage-v2`.

**Q3: July–September**
- July, Fireworks Safety and #SummerReady:
  - The five safety skills (extinguisher, first aid). Links `/product/red-cross-first-aid-cpr` and `/product/stop-the-bleed-course`.
  - Thursday dinners. Links `/scenarios/weekly-community-dinner`.
- August, Back to School: Children and Youth Preparedness:
  - Know your school's reunification plan (NPM "Be in the Know"). Links `/product/household-ready-plan`.
  - Kids and teens page (#16). Links Ready.gov's kids pages; don't title it "Ready Kids."
- **September, National Preparedness Month.** Run one week per NPM 2026 pillar; check the 2027 theme when FEMA posts it:
  - Week 1, Make a Plan: plan carousel and "your three." Links `/neighbors` and `/product/household-ready-plan`.
  - Week 2, Be in the Know: Battery Check Day (NPM's own sample: smoke-alarm batteries, flashlights, chargers), alerts and evacuation. Links `/blog/alerts-that-actually-reach-you` and `/scenarios/evacuation`.
  - Week 3, Build a Kit: "build it over time" plus the block kit. Links the buyer's guides and the kit page (#4).
  - Week 4, Be there for Your Community: quote FEMA's "it's our neighbors who are first to respond." Links `/civic`, `/blog/cert-is-not-a-bunker-club`, `/blog/map-your-street-in-an-afternoon` and the block-party page (#17).
  - PSPS and fire weather also start in fall. Links the PSPS page (#5) once it's live.

**Q4: October–December**
- October, Cybersecurity Awareness Month; National Fire Prevention Week; Great ShakeOut:
  - "Drop, cover, hold on, then check your three." Links the earthquake page (#6) and `/product/window-status-cards`.
  - Home fire escape plan. Links `/product/home-fire-and-ignition`.
  - "A fake FEMA caller after a disaster": scam awareness for elder neighbors. Links the recovery page (#19).
- November, #WinterReady and Winter Weather Safety:
  - Shared meal as a coping practice. Links `/blog/the-first-shared-meal`.
  - Water when the tap is off. Links `/blog/72-hour-water-plan-suburban-households`.
- December, #WinterReady, Holiday Fire Safety and Winter Weather Safety:
  - Holiday candle and cooking fire safety. Links `/product/home-fire-and-ignition`.
  - "Games night is infrastructure." Links `/blog/games-night-is-infrastructure`.
  - A preparedness gift idea (Ready VC suggests giving basic kits as gifts), with no product prices or links to listings that show prices.

Cadence suggestion: 2–3 posts a week, with one Ready.gov-adapted checklist and one neighbor-layer post each week. In September, add a daily NPM carousel day.

---

## 7. Findings to act on

1. **The neighbor layer is official policy, not a gap.** FEMA's 2026 NPM toolkit, Ready.gov's "responsibilities for assisting others," Ready Ventura County's "Adopt a Sidekick" and Listos's Block Party Initiative all ask people to involve neighbors. Terrarium should present itself as the long-form "how" of what these agencies already recommend.
2. **Reuse is wide open for text and closed for marks.** Cite Ready.gov and link back. No Ready, FEMA, DHS or CERT logos. No DHS marks in URLs or titles ("Ready Kids," "Ready 2 Help," "Citizen Corps"). No implied endorsement. Make our own images.
3. **Fix the store template now.** Ready.gov resources currently show "Buy on Ready.gov / In stock / price last seen." That's the one live item that reads as implied commerce with a federal agency.
4. **FEMA uses 8 lifelines, not 7.** Water Systems was added. The crosswalk in section 4 uses the 8 on FEMA's current page.
5. **Terrarium's existing civic cluster is already well aligned:** CERT, ICS, OEM, alerts, AFN, pets, MYN, day three. The biggest Ready.gov gaps are hazards: earthquake, wildfire hub, smoke, heat, flood, and PSPS specifically. Also missing are the populations pages for older adults, caregivers and kids, and the after-disaster recovery and coping page.
6. **Quote the current Ready.gov water wording** ("one gallon per person per day for several days") or re-verify CDC's numbers before reusing the 3-day/2-week figure from `search-terms.md`.
7. **Ready Ventura County is internal reference only** in public copy, under the no-Luke-location rule. Present it as one example of a county Ready program if it's named at all.
