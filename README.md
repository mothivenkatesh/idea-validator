
<h1 align="center">

```
  ██╗██████╗ ███████╗ █████╗
  ██║██╔══██╗██╔════╝██╔══██╗
  ██║██║  ██║█████╗  ███████║
  ██║██║  ██║██╔══╝  ██╔══██║
  ██║██████╔╝███████╗██║  ██║
  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝
  ██╗   ██╗ █████╗ ██╗     ██╗██████╗  █████╗ ████████╗ ██████╗ ██████╗
  ██║   ██║██╔══██╗██║     ██║██╔══██╗██╔══██╗╚══██╔══╝██╔═══██╗██╔══██╗
  ██║   ██║███████║██║     ██║██║  ██║███████║   ██║   ██║   ██║██████╔╝
  ╚██╗ ██╔╝██╔══██║██║     ██║██║  ██║██╔══██║   ██║   ██║   ██║██╔══██╗
   ╚████╔╝ ██║  ██║███████╗██║██████╔╝██║  ██║   ██║   ╚██████╔╝██║  ██║
    ╚═══╝  ╚═╝  ╚═╝╚══════╝╚═╝╚═════╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝
```

  <p align="center">
    <a href="https://github.com/anthropics/claude-code"><img src="https://img.shields.io/badge/Built_for-Claude_Code-blueviolet?style=for-the-badge" alt="Claude Code"/></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/></a>
    <img src="https://img.shields.io/badge/Frameworks-9_embedded-orange?style=for-the-badge" alt="9 Frameworks"/>
    <img src="https://img.shields.io/badge/Knowledge-100KB-blue?style=for-the-badge" alt="100KB Knowledge Base"/>
  </p>
</h1>

<h3 align="center">
  Stop building things nobody wants.<br/>
  Stress-test your startup idea like a YC partner would.
</h3>

<p align="center">
  <a href="#-install">Install</a> ·
  <a href="#-how-it-works">How it works</a> ·
  <a href="#-the-7-layer-framework">Framework</a> ·
  <a href="#-see-it-in-action">Demo</a> ·
  <a href="#-faq">FAQ</a>
</p>

---

```
  ┌─────────────────────────────────────────────────────────────────────────┐
  │                                                                         │
  │   "Most startups don't fail because they can't build.                   │
  │    They fail because they build something nobody needs."                │
  │                                                                         │
  │   This skill puts a YC partner, a McKinsey consultant,                  │
  │   and a seasoned product operator in your terminal.                     │
  │                                                                         │
  │   One conversation. Real business math. No flattery.                    │
  │                                                                         │
  └─────────────────────────────────────────────────────────────────────────┘
```

---

## ⚡ Install

```bash
claude skill install idea-validator
```

That's it. Say *"I have a startup idea"* and it activates.

<details>
<summary>Other install methods</summary>

**From release file:**
```bash
# Download ideavalidator.skill from Releases tab
claude skill install ./ideavalidator.skill
```

**From source:**
```bash
git clone https://github.com/mothivenkatesh/idea-validator.git
cd idea-validator
claude skill install ./skill
```

</details>

---

## 🧠 How It Works

```
  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
  │              │     │              │     │              │
  │  YOU SHARE   │────▶│  CLAUDE      │────▶│  ADAPTIVE    │
  │  YOUR IDEA   │     │  SCOPES IT   │     │  DEEP DIVE   │
  │              │     │  (3-4 turns) │     │  (risk-first)│
  └──────────────┘     └──────────────┘     └──────┬───────┘
                                                   │
                       ┌──────────────┐     ┌──────▼───────┐
                       │              │     │              │
                       │  SCORED      │◀────│  BUSINESS    │
                       │  ASSESSMENT  │     │  MATH        │
                       │  (1-5/layer) │     │  (with you)  │
                       └──────────────┘     └──────────────┘
```

**Five things happen:**

1. **You describe the idea.** One sentence. What it does, for whom.
2. **Claude scopes it.** 3-4 exchanges to understand stage, context, founder background.
3. **It names the 2-3 riskiest layers.** Not all 7 layers equally. Depth where the risk is.
4. **Adaptive interrogation.** One question at a time. Weak answers get probed. Strong ones move on.
5. **Scored output.** Each layer scored 1-5. Kill risks named explicitly.

---

## 🏗 The 7-Layer Framework

```
  ╔══════════════════════════════════════════════════════════════════╗
  ║                                                                  ║
  ║   Layer 1 ░░ PROBLEM & PAIN CLARITY                             ║
  ║           ├── Is this a Tier 1 problem?                          ║
  ║           ├── Can you name 3 people who have it?                 ║
  ║           └── Non-obvious insight test                           ║
  ║                                                                  ║
  ║   Layer 2 ░░ CUSTOMER & MARKET                                  ║
  ║           ├── TAM / SAM / SOM triangulation                      ║
  ║           ├── Top-down + Bottom-up + Value-based                 ║
  ║           └── Beachhead customer identification                  ║
  ║                                                                  ║
  ║   Layer 3 ░░ SOLUTION & DIFFERENTIATION                         ║
  ║           ├── 10x better test (not 20% better)                   ║
  ║           ├── Why Now test (YC's most failed question)           ║
  ║           └── Competition honesty test                           ║
  ║                                                                  ║
  ║   Layer 4 ░░ BUSINESS MODEL & UNIT ECONOMICS                   ║
  ║           ├── LTV:CAC ratio, churn, payback period               ║
  ║           └── Model-specific benchmarks                          ║
  ║                                                                  ║
  ║   Layer 5 ░░ P&L & PATH TO PROFITABILITY                       ║
  ║           ├── Revenue → Gross Profit → EBITDA → Net              ║
  ║           └── Break-even analysis                                ║
  ║                                                                  ║
  ║   Layer 6 ░░ MARKET DYNAMICS & TIMING                           ║
  ║           ├── Growing wave or shrinking one?                     ║
  ║           └── Network effects, regulatory tailwinds              ║
  ║                                                                  ║
  ║   Layer 7 ░░ FOUNDER FIT                                        ║
  ║           ├── Founder-Problem Fit (insight depth)                ║
  ║           ├── Founder-Market Fit (access, network)               ║
  ║           └── Founder-Team Fit (model-specific)                  ║
  ║                                                                  ║
  ║   Layer 8 ░░ TRACTION & PMF SIGNAL (if product exists)          ║
  ║           ├── Retention curves, Sean Ellis 40% test              ║
  ║           └── Burn multiple, revenue quality                     ║
  ║                                                                  ║
  ╚══════════════════════════════════════════════════════════════════╝
```

Not run in rigid order. The skill identifies which 2-3 layers carry the most risk for YOUR idea and goes deep there first.

---

## 🎬 See It In Action

```
  ┌─ YOU ──────────────────────────────────────────────────────────────┐
  │                                                                    │
  │  I'm building an AI tool that helps restaurants manage their       │
  │  inventory using computer vision on their existing security        │
  │  cameras.                                                          │
  │                                                                    │
  └────────────────────────────────────────────────────────────────────┘

  ┌─ CLAUDE ───────────────────────────────────────────────────────────┐
  │                                                                    │
  │  Interesting space. Before I dig in:                               │
  │                                                                    │
  │  Have you talked to restaurant owners about this? And where are    │
  │  you with it — still an idea, or do you have something built?      │
  │                                                                    │
  └────────────────────────────────────────────────────────────────────┘

  ┌─ YOU ──────────────────────────────────────────────────────────────┐
  │                                                                    │
  │  I've talked to about 15 restaurant owners. We have a working      │
  │  prototype with 2 restaurants using it.                            │
  │                                                                    │
  └────────────────────────────────────────────────────────────────────┘

  ┌─ CLAUDE ───────────────────────────────────────────────────────────┐
  │                                                                    │
  │  Good. Real discovery and early traction.                          │
  │                                                                    │
  │  Based on what you've shared, the areas I want to push hardest    │
  │  on are:                                                           │
  │                                                                    │
  │  1. Unit economics — the hardware + CV inference cost per          │
  │     location vs. what a restaurant will pay                        │
  │  2. Distribution — how you get from 2 restaurants to 200           │
  │                                                                    │
  │  The problem seems real. The tech angle is interesting.            │
  │  Let me start with the money.                                      │
  │                                                                    │
  │  Walk me through the cost to deploy at one restaurant. Not just    │
  │  the software — everything. Camera check, onboarding, inference    │
  │  compute, support.                                                 │
  │                                                                    │
  └────────────────────────────────────────────────────────────────────┘
```

The conversation continues adaptively. Weak answers get probed deeper. Strong answers move to the next vulnerability. Every 3-4 exchanges, Claude names what's strong, what's weak, what's still unclear.

---

## 📊 Scoring

After a full session, you get a scored assessment:

```
  ┌─────────────────────────────────────────────────────────────┐
  │                                                             │
  │   IDEA VALIDATION SCORECARD                                 │
  │                                                             │
  │   Problem clarity + insight     ████████░░  4/5             │
  │   Market size & dynamics        ██████░░░░  3/5             │
  │   Solution + Why Now            ████░░░░░░  2/5  ← gap     │
  │   Unit economics                ████████░░  4/5             │
  │   P&L viability                 ██████░░░░  3/5             │
  │   Market timing + moat          ████░░░░░░  2/5  ← gap     │
  │   Founder fit                   ████████░░  4/5             │
  │   Traction & PMF                   N/A                      │
  │                                                             │
  │   TOTAL: 22/40                                              │
  │   READING: Fragile. Two gaps to close before committing.    │
  │                                                             │
  └─────────────────────────────────────────────────────────────┘
```

```
  ┌─────────────────────────────────────────────────────┐
  │  34-40  ██████████  Strong signal. Build this.      │
  │  25-33  ██████░░░░  Conditional. Gaps to close.     │
  │  16-24  ████░░░░░░  Fragile. Questions unanswered.  │
  │   < 16  ██░░░░░░░░  Don't build yet.                │
  └─────────────────────────────────────────────────────┘
```

**Override rule:** A score of 1 on any layer (Problem, Unit Economics, or Moat especially) makes the total misleading. One fatal flaw sinks a business regardless of strength elsewhere.

---

## 🔀 Model-Specific Validation

The skill adapts based on your business model:

```
  ┌─────────────────┬────────────────────┬─────────────────────────────────┐
  │ MODEL           │ DEFAULT KILL ZONE  │ WHAT IT PUSHES HARDEST          │
  ├─────────────────┼────────────────────┼─────────────────────────────────┤
  │ B2B SaaS        │ Distribution       │ ICP, NRR, sales cycle, CAC      │
  │ Marketplace     │ Liquidity          │ Chicken-egg, take rate, leakage │
  │ D2C / E-comm    │ CAC, margins       │ Gross margin/unit, Amazon risk  │
  │ Fintech         │ Regulation         │ Licensing, cost of funds, risk  │
  │ Consumer App    │ Retention          │ D1/D7/D30, DAU/MAU, virality   │
  │ API / Dev Tool  │ Activation         │ Time to hello world, NDR, lock  │
  │ Hardware        │ BOM, NRE           │ Mfg partner, recurring layer    │
  │ Services        │ Leverage           │ Scalability, key-person risk    │
  └─────────────────┴────────────────────┴─────────────────────────────────┘
```

---

## 🧩 Embedded Frameworks

Not generic advice. Named frameworks from the people who invented them:

```
  ┌──────────────────────────────────────────────────────────────────────┐
  │                                                                      │
  │  ┌──────────────────────┐   ┌──────────────────────────────────┐    │
  │  │  NON-OBVIOUS INSIGHT │   │  WHY NOW TEST                    │    │
  │  │  Peter Thiel / YC    │   │  YC's most failed question       │    │
  │  └──────────────────────┘   └──────────────────────────────────┘    │
  │                                                                      │
  │  ┌──────────────────────┐   ┌──────────────────────────────────┐    │
  │  │  DELTA 4 THEORY      │   │  AMAZON PR-FAQ                   │    │
  │  │  Kunal Shah (CRED)   │   │  Jeff Bezos                      │    │
  │  └──────────────────────┘   └──────────────────────────────────┘    │
  │                                                                      │
  │  ┌──────────────────────┐   ┌──────────────────────────────────┐    │
  │  │  JOBS TO BE DONE     │   │  SEAN ELLIS 40% TEST             │    │
  │  │  Clayton Christensen │   │  PMF validation                  │    │
  │  └──────────────────────┘   └──────────────────────────────────┘    │
  │                                                                      │
  │  ┌──────────────────────┐   ┌──────────────────────────────────┐    │
  │  │  BHAG                │   │  NORTH STAR METRIC               │    │
  │  │  Jim Collins         │   │  Chamath (Facebook)              │    │
  │  └──────────────────────┘   └──────────────────────────────────┘    │
  │                                                                      │
  │  ┌──────────────────────┐                                           │
  │  │  CIRCLES + BPM       │   The skill picks 1-3 most relevant      │
  │  │  Lewis Lin / McKinsey│   frameworks for YOUR idea. Never all 9. │
  │  └──────────────────────┘                                           │
  │                                                                      │
  └──────────────────────────────────────────────────────────────────────┘
```

---

## 🎯 What Makes This Different

```
  ┌─────────────────────────────────────────────────────────────────┐
  │                                                                 │
  │   GENERIC AI ADVICE          │    IDEA VALIDATOR               │
  │  ─────────────────────────   │   ──────────────────────────    │
  │                              │                                  │
  │   "That sounds like a        │    "Walk me through the cost    │
  │    great idea! Here are      │     to acquire one customer.    │
  │    some tips..."             │     What channel, what cost,    │
  │                              │     what conversion rate?"      │
  │   Static checklist           │    Adaptive interrogation       │
  │   Encouragement-first        │    Truth-first                  │
  │   Generic frameworks         │    Model-specific kill zones    │
  │   No business math           │    LTV:CAC, P&L, break-even    │
  │   Avoids hard questions      │    Surfaces the kill risk       │
  │                              │                                  │
  └─────────────────────────────────────────────────────────────────┘
```

---

## 🗂 What's Inside

```
  idea-validator/
  │
  ├── ideavalidator.skill               ← Install this
  │
  ├── skill/
  │   ├── SKILL.md                      ← Core skill (481 lines)
  │   │
  │   └── references/
  │       ├── intake-scoping.md         ← Intake framework & routing
  │       ├── model-archetypes.md       ← 8 models, benchmarks, kill zones
  │       ├── market-sizing.md          ← TAM/SAM/SOM + worked examples
  │       ├── pnl-templates.md          ← P&L, COGS, contribution margin
  │       ├── company-frameworks.md     ← 9 named frameworks
  │       ├── founder-fit.md            ← 3-layer founder fit matrix
  │       └── conviction-checks.md      ← 12 conviction tests
  │
  ├── LICENSE                           ← MIT
  └── README.md
```

**~100KB of distilled validation intelligence.** Built from YC partner interviews, Shark Tank patterns, McKinsey frameworks, and operator experience.

---

## ❓ FAQ

<details>
<summary><strong>Who is this for?</strong></summary>

Anyone with a business idea who wants honest, structured feedback before spending months building. First-time founders, repeat founders, PMs validating product direction, investors doing due diligence. If you've ever said "I think there's a market for this" — this is for you.

</details>

<details>
<summary><strong>Does it work for non-tech ideas?</strong></summary>

Yes. The validation layers cover problem-market fit, unit economics, distribution, and founder fit. These apply to restaurants, services businesses, physical products, and everything else. 8 business model archetypes are covered.

</details>

<details>
<summary><strong>Is it just a checklist?</strong></summary>

No. It adapts questions based on your answers. Identifies which 2-3 layers carry the most risk for your specific idea and spends depth there. Weak answers get probed deeper. Strong answers move on. A real conversation, not a form.

</details>

<details>
<summary><strong>Will it be too harsh?</strong></summary>

Direct, not brutal. Honest, not cruel. No empty encouragement. If something is strong, it says why. If it's weak, it says why. Treats you as a capable adult who wants the truth.

</details>

<details>
<summary><strong>What's a Claude Code skill?</strong></summary>

Skills are knowledge files you install into [Claude Code](https://github.com/anthropics/claude-code) (Anthropic's CLI tool). They give Claude specialized capabilities that activate automatically based on what you're asking.

</details>

<details>
<summary><strong>Can I customize it?</strong></summary>

Yes. Edit files in `skill/` or `skill/references/`, then reinstall with `claude skill install ./skill`. Add frameworks, change scoring weights, adjust the tone.

</details>

<details>
<summary><strong>How is this different from ChatGPT business advice?</strong></summary>

Three things. (1) Adaptive — identifies YOUR idea's biggest risks and focuses there. (2) Real business math — TAM/SAM/SOM triangulation, LTV:CAC, contribution margin, P&L modeling. (3) Surfaces the kill risk — the one question you're avoiding. Generic AI gives encouragement. This gives truth.

</details>

---

## 📚 Built On

```
  ┌──────────────────────────────────────────────────────────────┐
  │                                                              │
  │   YC ─── Michael Seibel, Paul Graham, Dalton Caldwell       │
  │          Founder evaluation, PMF signals, kill questions     │
  │                                                              │
  │   Peter Thiel ─── Non-obvious insight, secrets               │
  │                                                              │
  │   Clayton Christensen ─── Jobs to Be Done                    │
  │                                                              │
  │   Kunal Shah ─── Delta 4 theory, irreversible behavior       │
  │                                                              │
  │   Jeff Bezos ─── Working Backwards / PR-FAQ                  │
  │                                                              │
  │   Jim Collins ─── BHAG                                       │
  │                                                              │
  │   Chamath Palihapitiya ─── North Star metrics                │
  │                                                              │
  │   Sean Ellis ─── 40% PMF test                                │
  │                                                              │
  │   Lewis Lin ─── CIRCLES framework                            │
  │                                                              │
  │   McKinsey ─── Business process mapping                      │
  │                                                              │
  │   Shark Tank ─── Revenue quality, burn rate, real questions   │
  │                                                              │
  └──────────────────────────────────────────────────────────────┘
```

---

## 🤝 Contributing

Found a blind spot? Have a framework that should be included? Know a better question for a specific business model?

1. Fork the repo
2. Edit files in `skill/` or `skill/references/`
3. Test with `claude skill install ./skill`
4. Open a PR

**The bar:** would a YC partner or seasoned operator ask this question? If yes, it belongs here.

---

## 📄 License

MIT. Use it, modify it, build on it.

---

```
  ┌──────────────────────────────────────────────────────────────────────┐
  │                                                                      │
  │   The best time to kill a bad idea is before you build it.           │
  │                                                                      │
  │   If this saved you from building something nobody wanted,           │
  │   consider giving it a ⭐                                            │
  │                                                                      │
  └──────────────────────────────────────────────────────────────────────┘
```
