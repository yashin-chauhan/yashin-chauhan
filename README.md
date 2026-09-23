# Hi, I'm Yashin Chauhan 👋

### Full-Stack Software Developer & Systems Engineer

I’m a Full-Stack Software Developer with **5+ years of experience** building scalable web applications, multi-tenant SaaS platforms, enterprise logistics ERPs, and high-throughput REST APIs.

I specialize in **React.js, Next.js, Node.js, Express.js, NestJS, PHP / Laravel, PostgreSQL, MySQL, and MongoDB**, with hands-on expertise across:
* **System Architecture & Database Design:** Relational schema modeling, multi-tenancy isolation, index optimization, and double-entry ledgers.
* **Backend Engineering & APIs:** RESTful API design, background worker queues (Redis / BullMQ), document rendering engines (DomPDF), and composite query optimization.
* **Modern Frontend & Mobile:** High-performance Next.js 15 (App Router), React 19, Tailwind CSS, and cross-platform mobile apps (React Native / Expo 52).
* **Production Engineering:** Cloud deployments, Nginx reverse proxies, Cloudflare WAF/CDN, PM2 process management, and CI/CD pipelines.

I take pride in transforming ideas from **problem → architecture → clean code → production systems**.

---

## 🚀 What I Build

* 🏢 **Multi-Tenant SaaS Platforms:** Scalable business operating systems with strict tenant isolation and role-based access control (RBAC).
* 📒 **Financial & Double-Entry Accounting Engines:** Immutable, balanced ledger systems with integer-paise precision to prevent monetary discrepancies.
* 📦 **Enterprise ERP & Logistics Systems:** Multi-branch dispatch workflows, dynamic counter billing, and automated print-exact documentation (DomPDF).
* ⚡ **High-Performance REST APIs:** Structured, indexed API architectures with sub-10ms response times and bilingual Unicode (`utf8mb4`) support.
* 📱 **Cross-Platform Mobile Applications:** Fluid, offline-resilient mobile applications built with React Native and Expo.
* 🛠️ **Developer Tools & Automated Ingestion Pipelines:** High-throughput batch Excel/CSV import engines with granular row validation.

---

## 🛠️ Tech Stack & Tooling

```
├── Frontend: JavaScript (ES6+), TypeScript, React.js, Next.js (App Router), HTML5, CSS3, Tailwind CSS, Bootstrap, jQuery
├── Backend: Node.js, Express.js, NestJS, Fastify, PHP (7.4, 8.x, 8.1+), Laravel (8.x & 10.x), RESTful APIs
├── Databases & ORM: PostgreSQL (Supabase), MySQL 8.x, MongoDB, Prisma 7, Eloquent ORM
├── Async & Caching: Redis, BullMQ Queue Workers
├── Reporting & Documents: Barryvdh DomPDF (Print-exact Vector Cards & Bilties), Maatwebsite Laravel-Excel, Yajra DataTables
├── Infrastructure & Cloud: Cloudflare (WAF/DNS), Nginx Reverse Proxy, Oracle Cloud Infrastructure (OCI), AWS, Linux/PM2, Git/GitHub
```

---

## 📌 Featured Engineering Projects

👉 **[Explore Full Projects Portfolio & Architecture Directory ➔](./projects/README.md)**

---

### 🏠 [RentKhata — Enterprise PG & Co-Living Operating Platform](./projects/rentkhata.md)
*A multi-tenant, double-entry financial operating system engineered for Indian PG, co-living, and hostel operators.*

* **Problem Solved:** Landlords struggle with unrecorded cashflows, deposit refund disputes, manual sub-meter electricity calculations, and spreadsheet fragmentation.
* **Engineering Highlights:**
  * **Double-Entry Financial Ledger:** Balanced debits and credits calculated strictly in **integer paise** ($\text{₹}1.00 = 100\text{ paise}$) to eliminate floating-point rounding errors.
  * **Deep Multi-Tenant Inventory Hierarchy:** Modeled $\text{Property} \rightarrow \text{Floor} \rightarrow \text{Room} \rightarrow \text{Bed} \rightarrow \text{Stay}$ with real-time occupancy state machines.
  * **Automated Utility Sub-Meter Billing:** Automatic per-unit rate calculation and shared-room quota distribution.
  * **Multi-Client Ecosystem:** Next.js 15 Owner ERP, Mobile-First Tenant Self-Service Portal, and React Native (Expo 52) Mobile App.
* **Tech Stack:** `Next.js 15` · `NestJS 11` · `Fastify 5` · `React Native (Expo 52)` · `PostgreSQL (Supabase)` · `Prisma 7` · `Redis (BullMQ)` · `Tailwind CSS`
* 🔗 **Live:** [rentkhata.com](https://rentkhata.com/) | 📂 **Showcase:** [GitHub Repo](https://github.com/yashin-chauhan/rentkhata) | 📖 **Deep Dive:** [Read Architectural Case Study](./projects/rentkhata.md)

---

### 🚚 [Compass Transport — Regional Logistics ERP & Freight Management](./projects/compass-transport.md)
*A multi-branch freight billing, consignment management, and automated documentation system engineered for Indian road logistics operators.*

* **Problem Solved:** High-volume transport hubs across state corridors (Delhi & Haryana) faced invoice numbering collisions, slow manual bilty drafting, and complex GST liability allocations.
* **Engineering Highlights:**
  * **Multi-Branch Session Context Partitioning:** Automatic branch isolation between Delhi (`DLI-`) and Ambala (`UMB-`) hubs preventing invoice sequence collisions.
  * **Zero-Friction Dynamic Counter Billing:** Real-time browser-side recalculation of cargo weights, tariffs, cartage, and surcharges without server lag.
  * **Smart Payment-Status GST Allocation:** Dynamic tax compliance rules assigning liability to Consignor (`PAID`) or Consignee (`TO PAY`).
  * **Print-Exact Vector PDF Generation:** Barryvdh DomPDF templates rendering crisp, printable Lorry Receipts and consolidated consignee statements in <300ms.
* **Tech Stack:** `PHP 8` · `Laravel 8` · `MySQL 8` · `Blade` · `DomPDF` · `Laravel-Excel 3.1` · `jQuery` · `Bootstrap 4`
* 🔗 **Live:** [compasstransport.in](https://compasstransport.in/) | 📂 **Showcase:** [GitHub Repo](https://github.com/yashin-chauhan/compass-transport-showcase) | 📖 **Deep Dive:** [Read Architectural Case Study](./projects/compass-transport.md)

---

### 💎 [Gems Testing India (GTI) — Gemological Laboratory Management Platform](./projects/gems-testing-india.md)
*A multi-division gemstone authentication, physical certificate generation, and instant public verification platform for professional gemological laboratories.*

* **Problem Solved:** Counterfeit physical gem certificates, manual card formatting bottlenecks, and disparate data requirements for gemstones, diamonds, jewelry, and Rudraksha beads.
* **Engineering Highlights:**
  * **Sub-8ms Universal SQL UNION Engine:** Single-index lookup helper resolving report numbers across 4 distinct database tables with zero polymorphic overhead.
  * **Millimeter-Exact PVC Card PDF Engine:** Custom DomPDF rendering ($400 \times 590\text{ pt}$ landscape) with Base64 embedded laboratory seals and macro stone photos.
  * **Asynchronous High-Throughput Catalog:** Yajra DataTables integration with server-side pagination and granular batch Excel import validation handlers.
* **Tech Stack:** `PHP 8.1+` · `Laravel 10` · `MySQL 8` · `Blade` · `DomPDF 2.0` · `Yajra DataTables` · `Laravel-Excel 3.1` · `Bootstrap 5`
* 📂 **Showcase:** [GitHub Repo](https://github.com/yashin-chauhan/gems-testing-india-showcase) | 📖 **Deep Dive:** [Read Architectural Case Study](./projects/gems-testing-india.md)

---

### 🌾 [Pragya Crop Advisory — Bilingual AgriTech Intelligence Platform & REST API](./projects/pragya-crop-advisory.md)
*A high-performance, bilingual (Hindi & English) agricultural advisory operating system and REST API engineered for Pragya NGO to empower rural smallholder farmers.*

* **Problem Solved:** Rural farmers face language barriers, fragmented agronomy information, and crop loss from lack of timely pest/disease treatment protocols.
* **Engineering Highlights:**
  * **12-Stage Agricultural Lifecycle Modeling:** Complete advisory engine covering climate baselines, soil preparation, seed treatment, NPK nutrient schedules, and post-harvest storage.
  * **Composite Relational IPM Joins:** Multi-table queries linking plant disease symptoms directly to actionable chemical and organic remedies in unified single-request payloads.
  * **Bilingual UTF-8 Devanagari Engine:** Strict locale boundaries ensuring high-fidelity Hindi and English JSON response contracts.
  * **Dynamic Navigation Taxonomy:** Database-backed navigation tabs allowing agronomy teams to reorder mobile app sections without app store releases.
* **Tech Stack:** `PHP 8.1+` · `Laravel 10` · `MySQL 8` · `REST API Architecture` · `Devanagari UTF-8 Localization`
* 📂 **Showcase:** [GitHub Repo](https://github.com/yashin-chauhan/pragya-crop-advisory) | 📖 **Deep Dive:** [Read Architectural Case Study](./projects/pragya-crop-advisory.md)

---

### 📚 Rudravidya
A learning and skill-assessment platform focused on helping users understand their knowledge, identify gaps, and improve through structured assessment across web and mobile.

* **Tech:** `React` · `Node.js` · `PostgreSQL` · `Mobile` · `AI-assisted development`

---

### 🔬 AI & Software Engineering Research
Evidence-based research into the impact of generative AI on developer productivity, code quality, software architecture, and the software engineering job market.

* 🔗 **Repository:** [github.com/yashin-chauhan/ai-software-jobs-research](https://github.com/yashin-chauhan/ai-software-jobs-research)

---

## 💼 Work Experience

**Bakuun Pvt. Ltd. — Full Stack MERN Developer**  
*2024 – 2026*
* Developed and maintained RESTful APIs, admin-panel functionality, and features across multiple Bakuun travel-tech portals.
* Engineered hotel/travel data synchronization, booking workflows, partner integrations, backend business logic, and end-to-end platform features.
* Debugged production issues, optimized high-throughput database queries, and maintained reliable application code using React.js, Node.js, Express.js, and MongoDB.

**GlobalLogic Pvt. Ltd. — Full Stack MERN Developer**  
*Aug 2023 – Jan 2024*
* Built and enhanced RESTful APIs and backend services for scalable enterprise web applications.
* Collaborated with cross-functional engineering teams to improve application performance, code quality, and user experience.

**Digitally Bird Pvt. Ltd. — Full Stack Developer**  
*Apr 2022 – Aug 2023*
* Developed responsive frontend web applications using React.js and modern JavaScript (ES6+).
* Improved application performance and ensured cross-device accessibility and responsiveness.

**Native Developers — Backend Engineer**  
*2021 – 2022*
* Assisted in backend service development using Node.js and Express.js and improved code maintainability and test coverage.

---

## 🧠 Currently Exploring & Deepening

* **System Design & Distributed Systems:** Event-driven architectures, caching strategies, and high-concurrency database indexing.
* **AI Agents & LLM Tooling:** Agentic workflows, MCP (Model Context Protocol) tools, generative UI, and AI-assisted developer tooling.
* **Scalable SaaS Engineering:** Subscription lifecycle management, webhook reliability, and automated multi-tenant provisioning.

---

## 📫 Connect With Me

* 📧 **Email:** [yashin123786@gmail.com](mailto:yashin123786@gmail.com)
* 📍 **Location:** Delhi, India
* 🐙 **GitHub:** [github.com/yashin-chauhan](https://github.com/yashin-chauhan)
* 💼 **LinkedIn:** [linkedin.com/in/yashin-chauhan](https://www.linkedin.com/in/yashin-chauhan)

---

> *"Building reliable software, learning in public, and turning architectural ideas into production products."*
