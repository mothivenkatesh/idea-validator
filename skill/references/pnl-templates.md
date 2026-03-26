# P&L & Contribution Margin Templates

## Standard P&L Structure

```
Revenue (MRR × 12 or transactional)
  - COGS
  = Gross Profit                [Gross Margin %]

  - Sales & Marketing (S&M)
  - Research & Development (R&D)
  - General & Administrative (G&A)
  = EBITDA                      [EBITDA Margin %]

  - Depreciation & Amortization (D&A)
  = EBIT

  - Interest Expense
  = EBT (Earnings Before Tax)

  - Taxes
  = Net Profit                  [Net Margin %]
```

---

## What Goes in COGS (by model)

Getting COGS wrong is the #1 financial mistake founders make.

**B2B SaaS COGS:**
- Cloud hosting & infrastructure (AWS/GCP/Azure)
- Third-party APIs directly tied to product delivery (e.g., SMS, verification APIs)
- Customer support team (portion tied to delivery, not sales)
- Implementation/onboarding cost (if delivery-side)
- Security & compliance tooling tied to delivery

**Does NOT go in COGS:** R&D salaries, sales team, marketing, G&A.

**Marketplace COGS:**
- Payment processing fees (1.5-3% of GMV)
- Trust & safety / fraud ops
- Supply-side onboarding costs
- Infrastructure for matching/logistics

**D2C/E-commerce COGS:**
- Product cost / manufacturing
- Inbound shipping to warehouse
- Packaging
- Outbound fulfillment (pick, pack, ship)
- Returns processing
- Merchant fees if on a platform

**Fintech/Lending COGS:**
- Cost of funds (interest paid)
- Credit loss provision
- KYC/verification costs
- Payment processing

---

## Contribution Margin

Contribution Margin = Revenue per unit - Variable Costs per unit

This is the most important metric for early-stage businesses. If contribution margin is negative, adding customers makes you lose more money.

```
Selling Price:               ₹X
  - Variable COGS:           -₹Y
  - Variable S&M (e.g., paid CAC amortized): -₹Z
  = Contribution Margin:     ₹X-Y-Z   [Contribution Margin %]
```

**Healthy contribution margins by model:**
- B2B SaaS: 60-75% (after variable COGS only)
- D2C: 20-40% after all variable costs including shipping/returns
- Marketplace: 40-60% of take rate after variable ops costs
- Fintech lending: Risk-adjusted margin after defaults = 3-8%

---

## Break-Even Analysis

Break-even point = Fixed Costs / Contribution Margin per unit

Example:
- Fixed costs per month: ₹50L (salaries, rent, infra baseline)
- Contribution margin per customer per month: ₹5,000
- Break-even: ₹50L / ₹5,000 = 1,000 customers

Questions to ask:
1. What are your monthly fixed costs today?
2. What's your contribution margin per customer/transaction?
3. How many customers/transactions to break even?
4. At what growth rate do you reach break-even? In how many months?

---

## EBITDA Deep Dive

EBITDA = Earnings Before Interest, Taxes, Depreciation, Amortization

Why it matters:
- Measures operating profitability before capital structure
- Used in valuation multiples (EV/EBITDA)
- Shows whether the core business generates cash

EBITDA Margin benchmarks:
| Stage | B2B SaaS | Marketplace | D2C |
|-------|---------|-------------|-----|
| Early | Negative | Negative | Negative |
| Growth | -20% to 0% | -10% to 5% | -10% to 0% |
| Scale | 10-20% | 15-25% | 5-15% |
| Mature | 25-40% | 25-35% | 10-20% |

---

## Cash Flow vs. P&L

A business can be P&L positive but cash-flow negative if:
- Annual contracts billed upfront (good for cash, deferred revenue on P&L)
- Long collection cycles (B2B invoices paid in 60-90 days)
- Heavy inventory (D2C, hardware)
- Lending businesses deploying capital

Key questions:
1. What are your payment terms? Do customers pay upfront, monthly, or on 30/60/90 day invoices?
2. What's your cash conversion cycle?
3. Do you need working capital to fund growth? How much?

---

## Common P&L Mistakes Founders Make

1. **Excluding their own salary from costs.** Founder's time is not free.
2. **Excluding COGS that scale with users.** Cloud costs, API costs, support costs.
3. **Assuming 100% gross margin on software.** Infrastructure costs are real.
4. **Putting CAC amortization wrong.** CAC is a cash cost, not always a P&L cost in the period.
5. **Ignoring working capital.** The cash is tied up even if the P&L looks fine.
6. **Mixing up revenue and GMV.** Marketplace revenue is the take rate, not GMV.
7. **Confusing contribution margin with gross margin.** Gross margin excludes S&M; contribution margin includes variable S&M.
