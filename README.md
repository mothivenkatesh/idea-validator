
<p align="center">
  <img src="assets/ai-cofounder-banner.svg" alt="AI Cofounder" width="720"/>
</p>

<h1 align="center">AI Cofounder</h1>

<p align="center">
  <strong>The world's most advanced AI skill for startup idea validation.</strong>
</p>

<p align="center">
  <a href="https://github.com/anthropics/claude-code"><img src="https://img.shields.io/badge/Claude_Code-skill-blueviolet?style=flat-square" alt="Claude Code Skill"/></a>
  <img src="https://img.shields.io/badge/frameworks-9_embedded-f76b1c?style=flat-square" alt="9 Frameworks"/>
  <img src="https://img.shields.io/badge/knowledge-100KB-3178c6?style=flat-square" alt="100KB"/>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="MIT"/></a>
</p>

<div align="center">
  <a href="#-quickstart">Quickstart</a>
  <span>&nbsp;&nbsp;✦&nbsp;&nbsp;</span>
  <a href="#-what-it-does">What it does</a>
  <span>&nbsp;&nbsp;✦&nbsp;&nbsp;</span>
  <a href="#-the-framework">Framework</a>
  <span>&nbsp;&nbsp;✦&nbsp;&nbsp;</span>
  <a href="#-see-it-live">Demo</a>
  <span>&nbsp;&nbsp;✦&nbsp;&nbsp;</span>
  <a href="#-faq">FAQ</a>
</div>

<br/>

```
    ┌─────────────────────────────────────────────────────────────────┐
    │                                                                 │
    │   90% of startups fail.                                         │
    │   Most had a product nobody needed.                             │
    │                                                                 │
    │   The questions that kill bad ideas early are known.             │
    │   YC partners ask them. McKinsey charges $500/hr for them.      │
    │   Seasoned investors pattern-match on them in 10 minutes.       │
    │                                                                 │
    │   This puts all of it in your terminal. One conversation.       │
    │                                                                 │
    └─────────────────────────────────────────────────────────────────┘
```

---

## Why This Exists

Every AI chatbot will tell you your idea is "interesting" and give you a bullet list of tips.

**AI Cofounder does the opposite.** It finds the hole in your idea before you spend 6 months building toward it. It asks the question you've been avoiding. It does the business math with you. It scores every layer of your idea 1-5 and tells you exactly where the gaps are.

**No other AI tool does this.** Not as a prompt. Not as a GPT. Not as a template. This is a 100KB structured knowledge system with 9 embedded frameworks, model-specific validation paths for 8 business types, and adaptive questioning logic that changes based on every answer you give.

It's the closest thing to having a YC partner, a McKinsey consultant, and a seasoned product operator sit with you for an hour — except it's free, instant, and brutally honest.

---

## ⚡ Quickstart

```console
$ claude skill install ai-cofounder
```

Done. Say *"I have a startup idea"* and it activates.

<details>
<summary>Other install methods</summary>

```console
# From release file
$ claude skill install ./ideavalidator.skill

# From source
$ git clone https://github.com/mothivenkatesh/idea-validator.git
$ cd idea-validator
$ claude skill install ./skill
```

</details>

---

## 🧠 What It Does

```
  ≡ × ═══════════════════ AI COFOUNDER ═══════════════════

  ┌───────────┐       ┌───────────┐       ┌───────────┐
  │  ✦ YOUR   │       │  ✦ SCOPE  │       │  ✦ DEEP   │
  │    IDEA    │──────▶│    & MAP  │──────▶│    DIVE   │
  │           │       │  3-4 turns │       │ risk-first │
  └───────────┘       └───────────┘       └─────┬─────┘
                                                │
                      ┌───────────┐       ┌─────▼─────┐
                      │  ✦ SCORE  │       │  ✦ MATH   │
                      │    CARD   │◀──────│  with you  │
                      │  1-5/layer │       │ LTV, CAC.. │
                      └───────────┘       └───────────┘
```

1. You describe the idea. One sentence.
2. Claude scopes it. Stage, context, founder background. 3-4 exchanges.
3. Names the 2-3 riskiest layers. Not all layers equally. Depth where the risk is.
4. Adaptive interrogation. One question at a time. Weak answers get probed.
5. Scored output. Each layer 1-5. Kill risks named explicitly.

---

## 🏗 The Framework

```
  ≡ × ═════════════════ VALIDATION LAYERS ═════════════════

  L1  ░░  Problem & Pain         Is it Tier 1? Can you name 3 people?
  L2  ░░  Customer & Market      TAM/SAM/SOM triangulation
  L3  ░░  Solution & Moat        10x test, Why Now, competition
  L4  ░░  Unit Economics         LTV:CAC, churn, payback period
  L5  ░░  P&L Viability          Revenue → EBITDA → break-even
  L6  ░░  Market Dynamics        Growing wave or shrinking one?
  L7  ░░  Founder Fit            Problem fit × Market fit × Team fit
  L8  ░░  Traction & PMF         Retention curves, Sean Ellis 40%

  ─────────────────────────────────────────────────────────────
  Not all 8 equally. The skill finds YOUR idea's 2-3 riskiest
  layers and goes deep there first.
```

---

## 🎬 See It Live

```
  ≡ × ═══════════════════ SESSION ═══════════════════════

  you ·····  I'm building an AI tool that helps restaurants
             manage inventory using computer vision on their
             existing security cameras.

  ai  ·····  Have you talked to restaurant owners about this?
             Where are you — still an idea, or something built?

  you ·····  Talked to 15 owners. Prototype with 2 restaurants.

  ai  ·····  Good. Real discovery and early traction.

             The areas I want to push hardest:
             ① Unit economics — CV inference cost/location
                vs. what a restaurant will pay
             ② Distribution — 2 restaurants to 200

             Let me start with the money.

             Walk me through the cost to deploy at one
             restaurant. Not just software — everything.
```

Weak answers get probed deeper. Strong answers move on. Every 3-4 exchanges, it names what's strong, what's weak, what's still unclear.

---

## 📊 Scoring

```
  ≡ × ══════════════════ SCORECARD ══════════════════════

  Problem + insight    ████████░░  4/5
  Market size          ██████░░░░  3/5
  Solution + Why Now   ████░░░░░░  2/5  ◄ gap
  Unit economics       ████████░░  4/5
  P&L viability        ██████░░░░  3/5
  Market timing        ████░░░░░░  2/5  ◄ gap
  Founder fit          ████████░░  4/5
  Traction & PMF              N/A

  ───────────────────────────────────────────────────────
  TOTAL: 22/40
  READING: Fragile. Two crisp gaps to close.

  ───────────────────────────────────────────────────────
  34-40  ██████████  Strong signal. Build this.
  25-33  ██████░░░░  Conditional. Gaps named.
  16-24  ████░░░░░░  Fragile. Core questions open.
   < 16  ██░░░░░░░░  Don't build yet.
```

A score of 1 on any single layer — especially Problem, Unit Economics, or Moat — overrides the total. One fatal flaw sinks a business regardless of strength elsewhere.

---

## 🔀 Model-Specific

```
  ≡ × ════════════════ KILL ZONES BY MODEL ════════════════

  B2B SaaS      │ Distribution     │ ICP, NRR, sales cycle
  Marketplace   │ Liquidity        │ Chicken-egg, take rate
  D2C           │ CAC, margins     │ Gross margin/unit, Amazon
  Fintech       │ Regulation       │ Licensing, cost of funds
  Consumer App  │ Retention        │ D1/D7/D30, DAU/MAU
  API / DevTool │ Activation       │ Time to hello world, NDR
  Hardware      │ BOM, NRE         │ Mfg partner, recurring
  Services      │ Leverage         │ Scalability, key-person
```

---

## 🧩 What's Under the Hood

**9 named frameworks from the people who invented them:**

```
  ≡ × ═══════════════ EMBEDDED FRAMEWORKS ═══════════════

  ┌─────────────────────┐  ┌─────────────────────┐
  │ Non-obvious Insight │  │ Why Now Test         │
  │ Peter Thiel / YC    │  │ YC (most failed Q)   │
  ├─────────────────────┤  ├─────────────────────┤
  │ Delta 4 Theory      │  │ Amazon PR-FAQ        │
  │ Kunal Shah (CRED)   │  │ Jeff Bezos           │
  ├─────────────────────┤  ├─────────────────────┤
  │ Jobs to Be Done     │  │ Sean Ellis 40%       │
  │ Clayton Christensen │  │ PMF validation       │
  ├─────────────────────┤  ├─────────────────────┤
  │ BHAG                │  │ North Star Metric    │
  │ Jim Collins         │  │ Chamath (Facebook)   │
  ├─────────────────────┤  └─────────────────────┘
  │ CIRCLES + BPM       │
  │ Lewis Lin / McKinsey│  Picks 1-3 most relevant
  └─────────────────────┘  for YOUR idea. Never all 9.
```

**Plus:**
- 12 YC/Shark Tank-grade conviction checks
- 3-layer founder fit matrix (problem × market × team)
- TAM/SAM/SOM triangulation with worked examples
- P&L templates with COGS breakdowns by model
- Intake routing that maps your idea type to the right validation path

---

## 🗂 Repo Structure

```
  ai-cofounder/
  │
  ├── ideavalidator.skill            ← install this
  │
  ├── skill/
  │   ├── SKILL.md                   ← core skill (481 lines)
  │   └── references/
  │       ├── intake-scoping.md      ← intake & routing tables
  │       ├── model-archetypes.md    ← 8 models + benchmarks
  │       ├── market-sizing.md       ← TAM/SAM/SOM + examples
  │       ├── pnl-templates.md       ← P&L, COGS, margins
  │       ├── company-frameworks.md  ← 9 named frameworks
  │       ├── founder-fit.md         ← founder fit matrix
  │       └── conviction-checks.md   ← 12 conviction tests
  │
  ├── LICENSE
  └── README.md
```

---

## ❓ FAQ

<details>
<summary><strong>Who is this for?</strong></summary>

Anyone with a business idea who wants honest feedback before spending months building. First-time founders, repeat founders, PMs validating product direction, investors doing diligence.
</details>

<details>
<summary><strong>Non-tech ideas?</strong></summary>

Yes. Covers restaurants, services, physical products, hardware. 8 business model archetypes with model-specific benchmarks and kill zones.
</details>

<details>
<summary><strong>Is it just a checklist?</strong></summary>

No. Adapts questions based on your answers. Finds the 2-3 riskiest layers for your specific idea and goes deep. Weak answers get probed. Strong answers move on. A real conversation, not a form.
</details>

<details>
<summary><strong>Too harsh?</strong></summary>

Direct, not brutal. Honest, not cruel. Treats you as a capable adult who wants the truth. If your idea has a fatal flaw, it names it. Once.
</details>

<details>
<summary><strong>What's a Claude Code skill?</strong></summary>

Knowledge files installed into <a href="https://github.com/anthropics/claude-code">Claude Code</a> (Anthropic's CLI). They give Claude specialized capabilities that activate automatically based on what you're asking.
</details>

<details>
<summary><strong>How is this different from ChatGPT advice?</strong></summary>

(1) Adaptive — identifies YOUR idea's biggest risks. (2) Real math — TAM/SAM/SOM, LTV:CAC, P&L modeling. (3) Surfaces the kill risk — the question you're avoiding. Generic AI gives encouragement. This gives truth.
</details>

---

## 🤝 Contributing

1. Fork → 2. Edit `skill/` → 3. Test with `claude skill install ./skill` → 4. PR

**The bar:** would a YC partner or seasoned operator ask this question? If yes, it belongs.

---

<p align="center">
  <strong>MIT License</strong>
</p>

<br/>

```
    ┌─────────────────────────────────────────────────────────────────┐
    │                                                                 │
    │   The best time to kill a bad idea is before you build it.      │
    │                                                                 │
    │   If this saved you from building something nobody wanted,      │
    │   consider giving it a ⭐                                       │
    │                                                                 │
    └─────────────────────────────────────────────────────────────────┘
```
