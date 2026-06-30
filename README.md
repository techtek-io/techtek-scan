
# 🛡️ TechTek-Scan
**De-risking Startup Velocity.**

`techtek-scan` is a local-first CLI utility designed for founders and CTOs to audit AI-generated MVPs. It benchmarks your codebase against 20 years of enterprise engineering standards to identify "vibe-code" technical debt, security leaks, and scaling roadblocks before your next funding round.

---

## 🔒 Privacy First
**Your code is your IP.** 
- This tool runs **100% locally** on your machine.
- Your source code is **never** uploaded, transmitted, or stored.
- Only anonymized metadata (e.g., file counts, dependency names, complexity metrics) is used to generate your Investor-Readiness Score.

---

## 🚀 Quick Start
You don’t need to install anything permanently. Run the scan directly from your terminal using `npx`:

```bash
npx techtek-scan@latest
```

---

## 🔍 What we audit
The scanner evaluates your repository across four critical pillars of **Investor-Readiness**:

### 1. Architectural Integrity (Scale Risk)
- **Complexity Audit:** Identification of "Flat File" traps (files > 600 lines) that prevent senior engineer onboarding.
- **Type-Safety Debt:** Measurement of `any` keyword usage in TypeScript.
- **Persistence Debt:** Detection of migration tooling (Prisma/Drizzle) vs. manual database state.

### 2. Security Hygiene (Compliance Risk)
- **Secret Detection:** Scanning for hardcoded API keys (OpenAI, AWS, Stripe, etc.).
- **Auth Patterns:** Auditing for secure authentication boundaries.
- **Environment Parity:** Verification of `.env` management standards.

### 3. AI Governance (Model Risk)
- **Model Lock-in:** Identification of direct model-coupling vs. architectural abstraction layers.
- **Reliability Check:** Search for AI Evaluation frameworks (Ragas/LangSmith) and "System Prompt" hygiene.
- **Token Efficiency:** Detection of primitive wrapper patterns vs. stateful orchestration.

### 4. Operational Readiness (Due Diligence)
- **CI/CD Presence:** Detection of automated deployment pipelines.
- **Observability:** Verification of production monitoring (Sentry/PostHog).
- **Documentation:** Audit of Architecture Decision Records (ADRs) and README depth.

---

## 📊 The Result
At the end of the scan, you will receive:
1.  **Terminal Summary:** An instant "Red/Yellow/Green" risk assessment.
2.  **TechTek Scorecard:** A private link to a web-based dashboard on `techtek.io` visualizing your architectural health.
3.  **Strategy Path:** Clear steps to refactor "vibe-code" into a scalable technical asset.

---

## 🏛️ Built by TechTek
This tool is the distillation of 20 years in the engine rooms of global-scale engineering (including **BBC, Booking.com, and TUI**). We've seen how technical debt kills startups—we built this to help you avoid those same traps.

**TechTek** is an AI-native engineering partner for startups. 
- **Website:** [www.techtek.io](https://www.techtek.io)
- **The Playbook:** [techtek.io/playbook](https://www.techtek.io/playbook)
- **Services:** New Product Innovation, AI & Automation, Fractional CTO Advisory.

---

## 📄 License
MIT © [TechTek](https://github.com/techtek-io)
