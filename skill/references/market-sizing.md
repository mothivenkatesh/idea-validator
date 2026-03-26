# Market Sizing — Methods, Examples & Questions

## The Three-Layer Framework

| Layer | Definition | How to Calculate |
|-------|-----------|-----------------|
| TAM | Total Addressable Market — if you captured 100% of everyone who could ever buy this globally | Top-down (industry report) OR bottom-up |
| SAM | Serviceable Addressable Market — realistic geography/segment you can serve | TAM × (your accessible segment %) |
| SOM | Serviceable Obtainable Market — what you can realistically capture in 3-5 years | SAM × realistic market share % |

**Rule:** Investors trust bottom-up SOM more than top-down TAM. Always push founders to build from the customer unit, not from a market report.

---

## Three Sizing Methods

### Top-Down (weakest alone)
Start from an industry report. Segment down.
- "The global KYC market is $12B. India is 8%. Our segment is mid-market (30% of India). TAM = $288M."
- Problem: You're trusting someone else's number and guessing at the percentages. Never use this alone.

### Bottom-Up (stronger)
Build from the actual customer count × price.
- "There are 3,000 NBFCs in India. 40% need digital KYC (1,200). Average ACV = ₹15L. SAM = ₹180Cr."
- Honest, testable, defensible. But still depends on your ARPU and customer count assumptions being right.

### Triangulation (most credible — always use this)
Run all three methods independently, then compare. If they converge, your number is defensible. If they diverge, you have a wrong assumption somewhere — find it before an investor does.

**The three legs of triangulation:**

**Leg 1 — Top-Down (industry supply-side)**
Start from the total category spend, apply segment filters.
- Source: analyst reports, government data, public company filings
- Example: "RBI data shows Indian NBFCs spent ₹3,200Cr on compliance in FY24. Digital tools are ~15% of that = ₹480Cr TAM."

**Leg 2 — Bottom-Up (customer demand-side)**
Build from real buyer count × realistic price.
- Source: your ICP research, sales conversations, LinkedIn/registry data
- Example: "3,000 mid-size NBFCs × ₹8L ACV = ₹240Cr SAM."

**Leg 3 — Value-Based (problem cost proxy)**
Size the market by what the problem costs the buyer today — then estimate what share of that cost they'd pay to solve it.
- Formula: (# of buyers × cost of the problem per buyer) × % they'd pay for a solution
- Example: "Mid-size NBFCs spend ~₹25L/year on manual KYC ops (staff, rework, penalties). A software solution at 30% of that savings = ₹7.5L/year. 3,000 buyers × ₹7.5L = ₹225Cr SAM."

**Triangulation read:**
```
Top-Down:    ₹480Cr TAM
Bottom-Up:   ₹240Cr SAM
Value-Based: ₹225Cr SAM

Convergence: Bottom-Up and Value-Based are close → ₹225-240Cr SAM is defensible.
Top-Down is higher because it includes spend that won't shift to software yet.
```

**When they don't converge:**
- Bottom-up >> value-based → your price assumption is too high, or buyers won't pay that fraction of cost
- Top-down >> bottom-up × 3 → you're probably over-counting TAM; re-check segment filter assumptions
- Value-based >> bottom-up → your buyer count is too conservative, or you're underpricing

**Triangulation questions to ask founders:**
1. Run all three methods for me. What does each give you?
2. Where do they diverge? What's driving the gap?
3. How much of the problem cost does the buyer actually allocate to buying software? (Willingness to pay test)
4. Does the top-down number include spend that will never migrate to your category?
5. Is your bottom-up count based on registry data or a rough estimate?

---

## Market Dynamic Questions to Ask

**Is the market growing?**
- What's the CAGR? (Compound Annual Growth Rate)
- What's driving the growth? (regulation, behavior change, tech unlock)
- Is the growth in the segment you're targeting, or the periphery?

**Shrinking market signals:**
- Incumbents not investing in the space
- Pricing pressure across all players
- Customers trying to eliminate the category (automate it away)
- Regulatory crackdown reducing TAM

**Growing market signals:**
- Regulatory mandates creating new demand (e.g., DPDP, Aadhaar-based eKYC)
- New customer segment entering the market (e.g., D2C brands needing fraud tools)
- Tech unlock reducing friction (e.g., UPI enabling micro-payment use cases)
- Incumbent pulling back from a segment (opportunity gap)

---

## Market Sizing Worked Examples (with Triangulation)

### Example 1: B2B SaaS for Indian Fintech Compliance

**Leg 1 — Top-Down:**
- India RegTech/compliance software market: ~₹900Cr (analyst estimate)
- KYC/identity sub-segment: ~35% = ₹315Cr
- Mid-market addressable (not enterprise, not micro): ~40% = **₹125Cr TAM**

**Leg 2 — Bottom-Up:**
- Regulated entities: ~12,000 (banks, NBFCs, PAs, insurers)
- Mid-size with software budget: ~4,000
- Currently willing to switch to software from manual: ~1,500
- ACV: ₹8L/year
- **SAM = 1,500 × ₹8L = ₹120Cr**

**Leg 3 — Value-Based:**
- Average mid-size NBFC spends ~₹20-30L/year on manual KYC (2-3 FTEs + rework + penalties)
- Willingness to pay for software = 30-40% of that cost saved = ~₹7-10L/year
- 1,500 buyers × ₹8.5L (midpoint) = **₹127Cr SAM**

**Triangulation read:** All three methods land between ₹120-127Cr SAM. Strong convergence — this number is defensible. Use ₹120Cr SAM.
- **SOM (Year 3): 150 customers × ₹8L = ₹12Cr ARR**

---

### Example 2: Consumer Fintech App

**Leg 1 — Top-Down:**
- India personal finance app market: ~$800M (growing 22% CAGR)
- Subscription sub-segment (not ads): ~20% = ~$160M = ₹1,300Cr

**Leg 2 — Bottom-Up:**
- Indian smartphone users: 700M
- Active internet banking users: 250M
- Target segment (25-40, salaried, tier 1-2 cities): 80M
- Problem-aware, willing to pay: ~30M
- At ₹199/month, 5% conversion = 1.5M paying subscribers
- **SAM = 1.5M × ₹199 × 12 = ₹357Cr**

**Leg 3 — Value-Based:**
- Target users spend ~₹3,000-5,000/year on related problem costs (fees, bad decisions, missed savings)
- Willingness to pay a tool that solves it: 5-8% of that = ₹150-400/year
- 30M problem-aware users × ₹250/year avg = ₹750Cr theoretical ceiling
- Realistic capture with 5% conversion = **₹37Cr SOM**

**Triangulation read:** Top-down gives ₹1,300Cr (too wide, includes ad-based apps), bottom-up SAM is ₹357Cr, value-based SOM is ₹37Cr. The divergence between SAM and SOM is healthy — it correctly shows that capturing 5% of willing-to-pay users is the Year 3 target, not the full SAM.
- **SOM (Year 3): 500K subs × ₹199/month × 12 = ₹120Cr ARR**

---

## Questions to Stress-Test Market Size

1. Where does your TAM number come from? Industry report or your own math?
2. Run all three methods — top-down, bottom-up, value-based. Do they converge?
3. Show me the bottom-up. Customer count × price. How many real buyers, by name or registry?
4. What does the buyer currently spend on this problem today (the value-based leg)?
5. What % of that cost are they willing to pay for a software solution? How do you know?
6. If your three estimates diverge by more than 2x, what assumption is causing the gap?
7. What % of the SAM do you realistically reach in Year 3?
8. Is the market growing faster than 15%/year, or is it mature?
9. Who controls distribution to this market? (You, channel, platform)
10. Is this a new category (you create demand) or existing (you displace)?

---

## Market Sizing Red Flags

- "The market is $50 billion" with no bottom-up or value-based backup
- Only one sizing method used — convergence is the credibility signal, a single number is a guess
- Top-down and bottom-up diverge by more than 3x with no explanation
- Value-based leg shows buyers won't pay anywhere near the assumed ARPU
- TAM includes customers who would never actually pay for this
- Market defined so broadly it's meaningless ("everyone with a smartphone")
- SOM assumes 10%+ market share in Year 1 (unrealistic)
- No account for existing solutions taking share
- Confusing market size with revenue opportunity (they're different)
- Buyer count sourced from a rough guess, not a registry, LinkedIn filter, or real list
