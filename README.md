<p align="center">
  <img src="assets/header.svg" alt="hi, I'm Oscar: AI & Full-Stack Engineer, founder of bxq" width="100%">
</p>

<p align="center">
  <b>Oscar Omar Martínez Lujano</b> · Monterrey, MX 🌵 · remote-friendly<br>
  <a href="https://bxq.app">bxq.app</a> · <a href="https://www.linkedin.com/in/oscarmartinezl">LinkedIn</a> · <a href="mailto:oscar@bxq.app">oscar@bxq.app</a>
</p>

<img src="assets/divider.svg" width="100%" alt="">

### 🌀 what I do

I take a messy manual process and turn it into software that runs on its own.

In 2016 that meant wiring Siemens PLCs to valves and sensors on a factory floor. From 2019 it meant RPA bots for some of Latin America's biggest companies. Today it means **LLM agents in production**: WhatsApp agents built on the Claude API that qualify leads, send quotes, collect payments and book meetings, and hand the conversation to a human when it matters.

<p align="center">
  <img src="assets/engineering-path.svg" alt="engineering path: PLCs 2016, UDEM 2019, RPA 2019, C#/.NET 2023, founder 2024, LLM agents 2026" width="100%">
</p>

<img src="assets/divider.svg" width="100%" alt="">

### 🍄 bxq: the thing I'm building (and will keep building)

**bxq** is a multi-tenant SaaS platform that small and mid-size businesses run on: CRM and sales pipeline, WhatsApp inbox, commerce, payments, Mexican e-invoicing and AI agents. One codebase hosts many businesses, each with its own roles, menus, dashboards and agents.

Everything below is live. It's also only the first ring. The map further down shows what's being built right now and what's still a dream.

| piece | what it is |
|---|---|
| 🧠 **AI agents** | Claude agents with about 18 tools (quotes, Stripe payment links, meeting scheduling, pipeline moves, human escalation). Agents are versioned and sandboxed, with reply review and per-tenant AI budgets |
| 💬 **WhatsApp pipeline** | Cloud API with message bundling, media in and out, templates, opt-outs, an outbox, per-message cost tracking and Whisper transcription of voice notes |
| 🤖 **in-app assistant** | operates the API *as the user*, with the same permissions; its tools are generated from the API routes, and risky actions ask for confirmation first |
| 🛤️ **Rails 8 API** | shared-database multi-tenancy, JWT with refresh rotation, per-tenant roles & permissions, Solid Queue |
| 🖥️ **Next.js 16 admin** | a config-driven dashboard, permission gates, and a proxy so tokens never touch the browser |
| 📱 **native iOS app** | Swift / SwiftUI, push notifications for agent escalations, deep links. *Currently in active development* |
| 🚚 **delivery** | GitHub Actions on self-hosted runners, Kamal deploys to DigitalOcean, 900+ test files |

<p align="center">
  <img src="assets/zen-backend.svg" alt="a quiet place: how a request travels through the bxq stack, from channels to Next.js proxy to Rails API to services to Postgres and Solid Queue to Kamal on DigitalOcean" width="100%">
</p>

<img src="assets/divider.svg" width="100%" alt="">

### 💗 software that makes you feel something

A CRM can be a cold grid of rows, or it can feel like walking into a place someone cared about. I build for the second one:

- 🌲 **A walk through the forest.** The bxq home is a scroll-driven scene. You walk into a misty forest, and the day turns to night as you go deeper.
- 🔮 **Objects you can hold.** Every 3D piece on my sites (a glamping lodge, a mountain) is grabbed only by its solid. The cursor turns into a hand only over the object, never over the empty air. On a phone, your finger turns the model and the page stays put.
- 💬 **Agents that write like people.** WhatsApp agents bundle your messages before answering and reply at a human pace, in chunks. When a conversation needs a person, they step aside.
- ✨ **A hand-animated icon set** for the CRM sidebar, so even navigation has a little heartbeat.
- 🧪 **A lab of experiments** (surfaces, an oscilloscope, LEDs, liquid glass, a showreel, a letter) where I prototype how an interface should *feel* before it becomes a feature.
- 📱 **Native feel on iOS.** SwiftUI with Liquid Glass, push notifications that open exactly the right conversation, and haptics on the way.

<img src="assets/divider.svg" width="100%" alt="">

### 🛰️ still building: the map

<p align="center">
  <img src="assets/roadmap.svg" alt="roadmap constellation: shipped, building, dreaming" width="100%">
</p>

| | what | why it matters |
|---|---|---|
| 🟡 | **voice agents** | the same agent that answers WhatsApp answers the phone (a restaurant's line, a clinic). bxq stays the brain, and the telephony provider only does speech |
| 🟡 | **campaigns that know what sold** | businesses launch campaigns from the CRM and finally see which ones turned into sales, not just clicks |
| 🟡 | **one pipeline for everything** | a single config-driven pipeline that attaches to prospects, clients, projects or any future process, replacing three separate mechanisms |
| 🟡 | **iPad + haptics** | the iOS app growing into a real workstation |
| 🩷 | **no-code agent tool builder** | businesses compose their own agent tools from data, without waiting for me to write code |
| 🩷 | **dashboards from data** | every business arranges its own home screen; the layouts already live as data and the per-tenant editor comes next |
| 🩷 | **agents that feel like your team** | each business's agent carries its voice, its memory and its manners |

<img src="assets/divider.svg" width="100%" alt="">

### 🗝️ from the archive: the Recreo years

Before bxq there was **Recreo**: a first version of the platform that ran a whole roster of businesses (wine shops, a candy brand, a B2B food trader, logistics, travel) on one Rails API and one Next.js CRM. Some of its best ideas are on their way back:

- 💻 **A macOS menu-bar agent and a Chrome extension** that report how company laptops are used (active vs. idle, which app or site is in front) so a team can see where the day went. They are privacy-first by design and deliberately never read window titles, full URLs or content.
- 🎬 **Video inside the CRM** (Mux), for teams that sell with stories.
- 🗺️ **Custom travel itineraries** (Kiko Iga), where the CRM hands a traveler something beautiful instead of a PDF.
- 🍬 **Playful storefronts** with three.js and GSAP, built so buying candy feels like candy.

Recreo taught me what breaks when you run many businesses on one codebase. bxq is the rebuild that took those lessons seriously.

<img src="assets/divider.svg" width="100%" alt="">

### 🌈 things shipped for clients

- 🏭 **Purchase-order bot for a Mexican steel group.** Sales reps chat their orders on WhatsApp. Claude structures each one, including the Mexican tax fields, and reads orders straight from PDFs and photos. Orders land in Salesforce and operations gets a Slack alert.
- 🌱 **[Plan 20·40](https://plan2040.org).** An end-to-end platform for an NGO supporting families in Coahuila. It tracks communities, families, cases, visits and life-plan goals to measure real impact, and takes donations through Stripe.
- ⛺ **[Glamping Co](https://glampingco.mx).** A catalog site with a three.js 3D model viewer, generated floor-plan PDFs and a WhatsApp quote flow.
- 👗 **farouche** & ☕ **Seltari.** Headless storefronts running on the bxq API, with React Three Fiber, maps and GSAP scroll storytelling.
- 📸 **272.** An Instagram feed planner embedded in Notion: drag to reorder, and the new dates sync back to Notion.

<details>
<summary>🔧 <b>the before times</b> (click me)</summary>
<br>

- **2016–2018 · field service engineer intern, Aselec.** Siemens S7-1500 PLC automation for a steel slitter line: control cabinets, valves, sensors and DC motors.
- **2019–2023 · RPA developer, Practia Global (EY engagements).** UiPath, Blue Prism and Power Automate bots for Televisa, Soriana, Alsea, Estafeta, Sodimac, Falabella and BanBif. I mapped each process into flowcharts and PDD/SDD documents before automating it.
- **2019–2022 · Power Apps developer, Anderssen Gauguin.** Power Apps, a SharePoint intranet and Power Automate flows.
- **2023–2024 · software developer, Neoris for CEMEX.** Power Platform apps on C#/.NET, a first taste of Angular, and the leap into TypeScript and Next.js.
- **B.Eng. Electronics Technologies & Robotics, UDEM.** I came for the robots and stayed for the software.

</details>

<img src="assets/divider.svg" width="100%" alt="">

### 🎨 toolbox

`Ruby on Rails` `TypeScript` `Next.js` `React` `Swift / SwiftUI` `PostgreSQL` `Claude API` `WhatsApp Cloud API` `Stripe` `Salesforce` `Docker` `Kamal` `GitHub Actions` `DigitalOcean` `Vercel` `three.js` `UiPath` `C# / .NET`

I build with **Claude Code** every day: project instructions, custom skills, code review and CI gates. The AI moves fast, and I own the architecture and what ships.

<p align="center"><i>most of my code lives in private client repos. Ask me about any of it ✌️</i></p>

<p align="center">
  <img src="assets/divider.svg" width="100%" alt="">
</p>
