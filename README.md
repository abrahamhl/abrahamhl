# Abraham Haddioui Lastras

**Creative Technologist · AI Product Engineer · Security-minded Builder**
Arnhem, Netherlands · English C1 · Spanish native · Dutch A2 · Available now — on-site Gelderland, remote EU or relocation

I build products where design, frontend engineering and AI meet — and I verify what I ship with tests, threat models and honest limits.

---

## 🔍 OSINT & Threat Intelligence

| Project | What it does | Tests | Stack |
|---|---|---|---|
| [osint-evidence-ledger](https://github.com/abrahamhl/osint-evidence-ledger) | Tamper-evident evidence ledger for OSINT investigations: SHA-256 chain, NATO Admiral reliability grading, multilingual reporting | 14 | Python · stdlib only |
| [eu-sanctions-screen](https://github.com/abrahamhl/eu-sanctions-screen) | Explainable name screening against the EU Consolidated Financial Sanctions List with Cyrillic transliteration and scoring transparency | 15 | Python · stdlib only |
| [eu-cti-brief](https://github.com/abrahamhl/eu-cti-brief) | Prioritised vulnerability bulletin from NCSC-NL, CERT-EU, BSI, CISA KEV and EPSS — three priority tiers, watchlist support | 8 | Python · stdlib only |
| [citation-audit](https://github.com/abrahamhl/citation-audit) | Checks whether sources cited in AI-generated answers actually say what the answer claims — no AI inside | 6 | Python · stdlib only |
| [chronolocate](https://github.com/abrahamhl/chronolocate) | Sun position, shadow-based time solving, EXIF consistency, perceptual hashing, Content Credentials (C2PA) detection | 10 | Python · Pillow |
| [threat-feed-correlator](https://github.com/abrahamhl/threat-feed-correlator) | Cross-correlate multiple CERT/CISA feeds into one deduplicated, ATT&CK-mapped, EPSS-enriched threat report | 7 | Python · stdlib only |
| [ioc-evidence-store](https://github.com/abrahamhl/ioc-evidence-store) | Offline-first IOC database with STIX 2.1 export, SHA-256 integrity chain, CSV/JSON import | 12 | Python · stdlib only |
| [web-exposure-scan](https://github.com/abrahamhl/web-exposure-scan) | Passive e-mail and web exposure check for SMBs — SPF, DKIM, DMARC, TLS, headers — with client-ready reports in NL/EN/ES | 18 | Node · zero deps |

## 🛡️ Security & AI Evaluation

| Project | What it does | Stack | Live |
|---|---|---|---|
| [mcp-osint-server](https://github.com/abrahamhl/mcp-osint-server) | MCP server exposing OSINT tools (sanctions screening, CTI briefs, IOC search, chronolocation) to AI agents | TypeScript · MCP SDK | - |
| [civil-sentry](https://github.com/abrahamhl/civil-sentry) | Evidence-driven cyber situational awareness: authorization gate, SHA-256 evidence chain, AI findings grounded in proof | TypeScript · zero runtime deps · Apache-2.0 | [site](https://civil-sentry.vercel.app/) |
| [Buyer Arena](https://github.com/abrahamhl/buyer-arena) | Evidence-first evaluation of web products and AI-agent changes: seeded synthetic buyers in a real browser, baseline vs candidate, release gates | TypeScript · Node 22 · Playwright | - |
| [npm-supply-chain-auditor](https://github.com/abrahamhl/npm-supply-chain-auditor) | Read-only scanner for compromised npm packages, droppers and persistence hooks | PowerShell · offline IOC dataset | - |
| [ARGUS](https://github.com/abrahamhl/argus) | Evidence and opportunity control plane: typed, hashed evidence from collectors, correlated into findings and retests. 195 tests | TypeScript · pnpm monorepo | - |

## 🎨 Creative Technology & Product

| Project | What it does | Stack | Live |
|---|---|---|---|
| [NEXUS Visual Engine](https://github.com/abrahamhl/nexus-visual-engine) | 30 real-time audio-reactive visual engines for DJ sets, museums and installations | WebGL · Three.js · GLSL · Web Audio | [demo](https://abrahamhl.github.io/nexus-visual-engine/) |
| [IAQUARIUS Gateway](https://github.com/abrahamhl/iaquarius-gateway) | Local multi-provider AI gateway: one OpenAI-compatible endpoint with automatic failover, chat UI and observability | LiteLLM · Open WebUI · Docker | - |
| [Gelderland Crane Simulator](https://github.com/abrahamhl/gelderland-crane-simulator) | Deterministic overhead-crane training simulator with 35 automated physics checks | Godot · GDScript | - |
| [loopsmith](https://github.com/abrahamhl/loopsmith) | Exact-duration assembly of AI-generated video clips with seam analysis | Bash · FFmpeg/ffprobe | - |
| [civic-relay](https://github.com/abrahamhl/civic-relay) | Offline-first crisis messaging prototype: multi-transport routing, store-and-forward, deduplication | TypeScript · React · pnpm monorepo | [demo](https://abrahamhl.github.io/civic-relay/) |

## How I work with AI

I use AI agents (Claude, Codex, Gemini) as implementation partners, not as authors of record: I set scope and architecture, agents implement, and nothing is claimed as done unless a test or command proves it. Examples of that workflow are public — the crane simulator's [`.claude/`](https://github.com/abrahamhl/gelderland-crane-simulator/tree/main/.claude) agent roles and rules, and civic-relay's [`RELEASE_TRUTH_V0_1.md`](https://github.com/abrahamhl/civic-relay/blob/master/docs/RELEASE_TRUTH_V0_1.md) verification record.

## Looking for

CTI & Threat Intelligence · SOC Engineering · AI Product Engineering · Creative Technology · Design Engineering · Security Engineering (defensive) · Applied AI / Forward Deployed

## Links

[Portfolio](https://creative-tech-portfolio.vercel.app/) · [AUX Design](https://auxdesign.nl/) · [GitHub](https://github.com/abrahamhl)
