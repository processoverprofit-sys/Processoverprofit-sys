![ProcessOverProfit Animated Banner](assets/ProcessOverProfit_Main_Animated_Banner.gif)

# ProcessOverProfit | Engineering HQ

**Independent Software Engineering · Linux · Security Research**

### Verification Before Execution

A public engineering portfolio documenting security-first software development, local-first architecture, deterministic systems and independently maintained projects.

---

Projects

1. T-Bot / Investment BOT

Status: Active private development and staged security qualification

T-Bot is a privately developed, single-user automated trading system focused on Solana and newly launched tokens.

Originally designed as a personal trading bot, the project has evolved into a hardened trading and execution architecture, combining automated market discovery, token-risk screening, strict risk controls and carefully governed transaction execution.

Core engineering principles

- Deterministic decision-making — Explicit trading rules and risk thresholds rather than LLM-controlled trading decisions.
- Fail-closed security — Missing evidence, invalid authorization or unsafe conditions must result in refusal.
- Isolated signing — Separating transaction-signing authority from trading processes.
- Bounded execution authority — One-time authorization, explicit approval boundaries and replay resistance.
- Capital protection — Dedicated wallet architecture, exposure ceilings, drawdown limits, loss cooldowns and emergency controls.
- Token-risk qualification — Screening concentration, developer holdings, insider exposure, bundled supply, sniper activity, liquidity and sellability.
- Software integrity — Cryptographic hashes, artifact provenance and reproducibility verification.
- Hardened infrastructure — Linux isolation, verified filesystem components and controlled deployment environments.
- Controlled updates and recovery — Deployment qualification, rollback procedures and recovery validation.
- Evidence-driven engineering — Structured tests, independent audit gates, traceable results and formal acceptance criteria.

T-Bot deliberately excludes an LLM from the trading authority path.

Production readiness and funded trading are not yet claimed. Live execution requires separate readiness qualification and explicit authorization.

2. BrainBot / BrainBot PC

Status: Desktop development line completed and frozen

BrainBot is a separate local-first Ubuntu desktop application and user-facing control environment.

Its purpose is to provide a structured interface for interacting with approved local resources while maintaining clear boundaries around access, authentication and privileged operations.

Core design principles

- Local-first desktop operation
- User-controlled interaction
- Authenticated access to approved resources
- Separation of interface and backend responsibilities
- Restricted source-tree visibility
- Controlled access to operational resources
- No unrestricted wallet or signing authority
- No bypass of T-Bot execution or risk controls

The BrainBot PC 3.5.0–3.5.3 development line has been recorded as complete and frozen.

BrainBot is not an autonomous trading engine and does not replace T-Bot.

The previous Android development direction has been discontinued.

---

How the Projects Relate

BrainBot provides a local user-facing software environment.

T-Bot provides specialised trading discovery, analysis, risk qualification, execution control and evidence architecture.

The projects remain independent, with distinct responsibilities and security boundaries.

Any future integration must preserve those boundaries. A user interface must never become an alternative route around authorization, signing or risk controls.

---

Engineering Philosophy

- Security before convenience
- Verification before execution
- Process over profit
- Minimum necessary authority
- Deterministic behaviour where required
- Transparent and safe failure handling
- Reproducible software and evidence
- Controlled deployment and rollback
- Local ownership and operational control
- Privacy by design

---

Current Technical Interests

"Python" · "Linux" · "Solana" · "Security Engineering" · "Desktop Applications" · "Wallet Security" · "Cryptographic Verification" · "Software Integrity" · "Reproducible Builds" · "Automation" · "Systems Architecture"

---

Privacy and Source Availability

T-Bot and BrainBot are privately developed projects and are not currently distributed as public software products.

The following materials are not publicly available:

- Production source repositories
- Private keys and signing material
- Credentials and operational configuration
- Sensitive security architecture and environment details
- Private test evidence and governance records

Selected non-sensitive architectural documentation, technical research and engineering findings may be published separately in the future.

This profile uses a project identity rather than a personal identity.

No guarantees of financial returns, independent security certification or production readiness are implied.

---

ProcessOverProfit

Building systems that prioritise control, integrity and evidence over assumptions.

Independent projects. No affiliation with or endorsement by OpenAI, Solana or other third-party organisations is implied.
