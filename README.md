# Júlio Max

Founder-engineer and CTO with 30+ years of building software. I take products from a blank page
to production: architecture, core code, infrastructure, and then the team. Today I work mostly
in **Rust, TypeScript and Python**, with a long track record in distributed systems, fintech /
digital assets, and applied AI since before it was mainstream.

Brazil-based · remote · open to founding, staff and lead engineering roles.

---

### Tilt Technology — Co-Founder & CTO · 2024–present

Distributed computing platform that turns a company's existing, heterogeneous hardware
(laptops, phones, TVs, servers, cloud VMs — Android, Linux, Windows, macOS) into a single
compute grid. Run workloads on machines you already own before paying for more cloud.

- Designed the architecture and infrastructure; wrote the entire core in Rust, including the
  scheduler that splits, distributes and merges workloads.
- Built a fault-tolerant execution model for devices that can go offline at any moment:
  stateless agents receive only a data slice plus a recipe, and any slice can be picked up by
  another node. Jobs always complete, and no agent ever sees the full dataset.
- An early proof of concept ran across **300,000 devices** via an embedded SDK; now in production.
- Freight pricing for a large retailer (30k+ SKUs × every Brazilian ZIP code):
  **27 h → 4 h**, running on the customer's own machines.
- Moved LLM and speech workloads (transcription, diarization, summarization) from cloud GPUs to
  machines the customer already kept running: **95%+ cost reduction**, as a drop-in replacement.
- Solo-built the core platform through thesis, product and funding; then hired and led an engineering
  team of up to 10.

### Enor Securities — Founder & CTO

Founded in 2019. Licensed digital asset platform in El Salvador (CNAD), bridging traditional
finance and digital assets. Incubated inside Titanium Capital.

- Wrote the smart contracts for **$ESOY** (Polygon + Ethereum), audited by Consensys, including an
  on-chain KYC-based authorization layer; integrated Fireblocks for institutional custody.
  $ESOY was the **first digital asset issuance approved under El Salvador's Digital Assets Law**,
  a US$100M offering
  ([Forbes Centroamérica, 2024](https://forbescentroamerica.com/2024/01/24/el-salvador-autorizo-la-primera-emision-de-activos-digitales-por-100-mdd/)),
  now traded globally on Enor's book.
- Built the core trading stack by hand: real-time order book, matching engine and settlement
  engine; integrated and maintained connectivity with 20+ exchanges.
- Shipped a token launchpad, staking engine, wealth-manager platform, and an NFT marketplace
  (concept to launch in one month).
- Led the technical side of CNAD licensing, including Transfer365 integration.
- Grew and led an engineering team of up to 20.

### Titanium Capital — CTO · 2018–2026

Investment firm and venture builder managing portfolios of Brazilian court-ordered government
debts (precatórios).

- Solo-built an automated portfolio management platform (TypeScript / Node.js / Meteor) that syncs
  with Brazilian court systems to track lawsuits and precatórios, computes monetary updates, and
  builds full timelines of cases, parties, payments and settlements.
- Managed portfolios worth **billions of BRL**; platform security was independently reviewed and
  approved by two major São Paulo law firms.
- Portfolios became due-diligence-ready and fully traceable, which directly enabled their sale.
- Cut legal operations for very large portfolios to one senior and one junior lawyer working a
  few hours per month. Later led a team of 3.

### LipperHub — Founder & CTO · 2014–2018

One of Brazil's early applied AI/ML companies, focused on legal and financial documents.

- Built a court-outcome prediction system: ML models consumed full lawsuits and returned
  favorable-outcome probabilities per judge.
- Existing OCR could not handle scanned court records, so I built a custom computer-vision OCR
  pipeline in Python / OpenCV.
- That pipeline became a product sold to banks and large companies: structured data extraction
  from photographed documents (complex forms, mixed fonts, layouts and quality) captured by
  2,000+ devices.

### Independent consulting — TCP Latam · 2015

- Built a contract-reading and bank-reconciliation system for a judicial recovery case: it
  interpreted loan contracts, projected debt and reconciled it against bank statements.
- Re-checked eight months of manual work by the legal and accounting team in about two weeks,
  matched every finding and uncovered more: **R$4M+ in improper bank charges**, validated by
  the auditors.

---

**Stack:** Rust · TypeScript / Node.js · Python · Solidity · OpenCV / ML · distributed systems ·
trading systems (order book, matching, settlement)

**Contact:** julio.maxf@gmail.com · [LinkedIn](https://www.linkedin.com/in/juliomax)
