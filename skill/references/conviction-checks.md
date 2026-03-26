# Conviction Checks — YC, Shark Tank & Operator-Grade Probes

Distilled from: YC partner interviews, 200+ post-interview founder recaps, Shark Tank analysis,
Michael Seibel / Paul Graham / Dalton Caldwell writings, and seasoned investor patterns.

Use this file when the main validation layers feel covered but conviction is still shaky.
These are the sharper, second-order questions that separate real ideas from polished ones.

---

## 1. The Non-Obvious Insight Test (Peter Thiel / YC)

Every compelling startup is built on a secret — something true that most people don't believe yet.

**The question:** "What do you understand about this problem/market that most people outside it don't?"

This is one of YC's most revealing questions. A strong answer reveals proprietary insight. A weak answer reveals a derivative idea.

**Strong answer signals:**
- Specific, domain-grounded insight gained from firsthand experience
- Counter-intuitive belief backed by customer evidence (not just intuition)
- A pattern that explains why incumbents have failed or ignored the segment

**Weak answer signals:**
- "The market is big and no one is serving it well" (generic)
- "We read that X is a problem" (no lived experience)
- Insight that any consultant could derive from a market report

**Follow-up probes:**
- "Have you talked to anyone who disagrees with that insight? What did they say?"
- "If you're right, what does that imply about why every competitor has gotten it wrong?"
- "How long has this insight been true? If it's been true for 5 years, why hasn't someone acted on it?"

---

## 2. The Why Now Test (YC — most commonly failed)

This is the question founders most often blank on in YC interviews. Timing is a founding condition.

**The question:** "What has changed in the last 12-24 months that makes this the right time to build this?"

**Strong tailwinds to look for:**
- New regulation creating mandate or unlocking capability (e.g., DPDP, open banking APIs, Aadhaar eKYC)
- Infrastructure cost drop making unit economics viable now (e.g., LLM API costs, cloud pricing)
- Behavior shift reaching critical mass (e.g., SMBs now comfortable paying for SaaS)
- Incumbent exit or neglect opening a segment
- New dataset or distribution channel that didn't exist before

**Weak timing signals:**
- "The market has always had this problem" (timing-agnostic = timing-indifferent = probably not the right time)
- "AI is changing everything" (not specific enough)
- "We just had the idea" (not a tailwind)

**Follow-up probes:**
- "Why couldn't someone have built this in 2020? What's different?"
- "Is the tailwind regulatory, behavioral, or technical? How durable is it?"
- "What happens if you wait 2 more years — does the window close or open wider?"

---

## 3. Founder-Market Fit Test (YC's most weighted criterion)

YC often says: we invest in founders, not ideas. The idea will change. The founder's edge stays.

**The question:** "Why are YOU the right person to build this? What do you know, who do you know, or what have you experienced that gives you an unfair edge?"

**Strong FMF signals:**
- Domain operator: Has lived the problem professionally (ex-banker building for banks)
- Insider distribution: Has the relationships to get to the first 100 customers directly
- Technical depth: Can build the core product without outsourcing
- Obsession provenance: Built early versions or workarounds before the company existed
- Regulatory/network access: Has licenses, contacts, or credibility hard to replicate

**Weak FMF signals:**
- "We're passionate about the problem" (passion is table stakes)
- "We researched it extensively" (anyone can do this)
- "We identified a gap in the market" (not same as ability to close it)

**Follow-up probes:**
- "Have you worked inside this industry? For how long?"
- "Who are your first 10 customers, and do you already have their phone numbers?"
- "What have you built before — even a side project — that's in this domain?"
- "If a well-funded team started this same company today, would your edge survive?"

---

## 4. The Traction Honesty Test (YC + Shark Tank)

Traction means different things at different stages. The question is whether what you have is real signal or noise.

**YC traction hierarchy (strongest to weakest):**
1. Revenue with growth rate — actual money in the bank, growing week-over-week
2. Paying pilots — customers paying, even small amounts (payment = signal)
3. Committed LOIs — named companies who've signed letters of intent
4. Active free users with retention — not signups, but people returning
5. Waitlist signups — weakest, but better than nothing

**Key YC insight:** YC cares about the *rate of increase* in growth, not just growth. Flat 10% monthly growth is weaker than accelerating from 5% to 12% to 18%.

**Questions for post-launch ideas:**
- "What's your month-over-month growth rate for the last 3 months? Is it accelerating?"
- "Of users who sign up, what % are still active 30 days later?"
- "What's your most surprising user behavior — something you didn't expect?"
- "Have any users referred others without being asked to?"
- "If you turned off your product tomorrow, which users would be most upset? Have you talked to them?"

**Questions for pre-launch ideas:**
- "Who have you shown this to? What was the most skeptical reaction you got?"
- "Have any potential customers pre-paid, signed an LOI, or agreed to be a design partner?"
- "What's the fastest you can get something in front of a real user?"

**Shark Tank version:**
- "What are your sales for the last 12 months?"
- "What's your cost per unit / cost to deliver the service?"
- "What's your profit margin? Net and gross?"
- "How did your first customer find you?"

---

## 5. The PMF Signal Test (Michael Seibel / Sean Ellis)

Product-Market Fit is not a binary. Use these tests to assess how close you are.

**Sean Ellis 40% Test:**
Ask users: "How would you feel if you could no longer use this product?"
- Very disappointed: target >40% for PMF signal
- Somewhat disappointed: weak signal
- Not disappointed: no PMF

**Seibel's "explosive usage" test:**
PMF is when usage is growing in ways that overwhelm your ability to serve it. Signs:
- You're getting support requests you can't keep up with
- Users are using the product in ways you didn't design for
- Word of mouth is driving signups without paid acquisition
- Revenue is growing despite you not focusing on sales

**Retention curve test:**
Plot cohort retention over time. A healthy retention curve flattens (churns stabilize at some %). A declining curve = no PMF, no matter how many users you have.

**Questions:**
- "What's your D30 retention rate? D90?" (Users active 30/90 days after signup)
- "What does your retention curve look like — does it flatten or go to zero?"
- "If you stopped all marketing tomorrow, what would happen to usage?"
- "Have users ever complained when you tried to remove or change a feature?"
- "Are customers renewing? At what rate?"

---

## 6. The "What Would Kill You" Test (YC's most revealing)

YC partners use this to understand how clearly founders see their own risks.

**The question:** "What's the single biggest risk to this business — the thing that, if it went wrong, would kill the company?"

**Why this reveals so much:**
- Founders who can't name a clear kill risk are either not thinking clearly or hiding it
- Founders who name the right kill risk and have a plan are far more fundable
- The kill risk should match what you can see from the outside (if they name a minor risk and ignore an obvious one, that's a red flag)

**Common kill risks by model:**
- B2B SaaS: Customer adoption too slow to reach critical mass before runway ends
- Marketplace: Chicken-and-egg problem never resolves; supply or demand side never reaches liquidity
- D2C: CAC increases faster than LTV; Meta/Google dependency makes growth unsustainable
- Fintech: Regulatory action or banking partner withdrawal kills the model
- API/Dev tools: AWS/GCP releases a native competing feature
- Consumer: The engagement loop breaks (retention collapse after early virality)

**Follow-up probes:**
- "How long would it take you to know if that risk was materializing?"
- "What's your plan if it does happen?"
- "If you had to bet on what kills this company, what would you bet on?"

---

## 7. The Defensibility / Moat Test (YC + Shark Tank)

**The question:** "If your idea works and you reach $5M ARR, what stops a competitor with $10M in funding from taking the market from you?"

**Real moats (durable):**
- Network effects: Product becomes more valuable as more people use it (Slack, LinkedIn, WhatsApp)
- Data moat: You have proprietary data that competitors can't buy or replicate (fraud models trained on transaction data, medical diagnosis trained on rare cases)
- Regulatory capture: You have a license or compliance certification that's hard to get
- Distribution lock-in: You're embedded in the customer's workflow, switching costs are real
- Brand moat: Consumer trust built over time in categories where trust is the product

**Weak moats (not defensible):**
- "First mover advantage" — rarely durable without network effects
- "Patents" — slow to enforce, easy to design around in software
- "Better product" — features get copied, especially by funded competitors
- "Our team is amazing" — team is portable, people leave

**Shark Tank version:**
- "Do you have a patent? Is it granted or pending?"
- "What stops Amazon from building this?"
- "What's your barrier to entry?"

**Probes:**
- "Name the scenario where your moat is strongest. Name the scenario where it's most fragile."
- "How long would it take a competitor to replicate your core product if they started today?"
- "Are there any natural switching costs once a customer adopts your product?"

---

## 8. The Revenue Quality Test (Shark Tank focus)

Shark Tank and investors scrutinize revenue more than founders expect. Revenue quality matters as much as revenue quantity.

**Revenue quality signals:**
- Recurring vs. one-time: Annual or monthly subscription >> one-time project fee
- Gross vs. net revenue: Marketplace founders often confuse GMV with revenue
- Organic vs. promotional: Revenue driven by discounts isn't real demand signal
- Concentrated vs. diversified: If top 1 customer = 50%+ of revenue, that's a risk
- Contracted vs. at-will: Committed ARR >> month-to-month subscriptions

**Key questions:**
- "What % of revenue is recurring? What % is one-time or project-based?"
- "What's your largest customer as a % of total revenue?"
- "What's your revenue look like if you remove any discounts or one-off deals?"
- "Is any of your revenue contracted? For how long?"
- "Have any customers churned? Who was the most recent one and why?"

---

## 9. The Burn Rate & Runway Test (Shark Tank + real investors)

**Key questions:**
- "What's your current monthly burn rate?"
- "How many months of runway do you have?"
- "At what monthly revenue do you reach break-even?"
- "How much have you spent to get to your current traction? Is that efficient?"
- "If you don't raise another round, how long can you operate?"

**Benchmarks:**
- Seed stage: 18 months+ runway after raise is standard; <12 months is distressed
- Break-even targeting: Most B2B SaaS startups aim for break-even within 24-36 months of Series A
- Burn multiple: (Net burn / Net new ARR). <1 is excellent, 1-2 is acceptable, >2 is concerning

**Shark Tank context:** Sharks always ask how founders spent their own money. Amount personally invested signals conviction. Founders who haven't put skin in the game are a signal to Sharks.

---

## 10. The First Customer Test (YC's "do things that don't scale")

Paul Graham's essay is core YC doctrine. The test: have you done anything unscalable to get your first customers?

**Strong signals:**
- Named their first 10-20 target customers before building anything
- Manually delivered the service before automating it (Concierge MVP)
- Cold-called / cold-emailed their way to design partners
- Used personal network to get first paying customer
- Went door-to-door, attended conferences, built relationships before building product

**Weak signals:**
- "We'll run Facebook ads" (nobody has tried the unscalable version first)
- "Customers will find us through SEO" (if pre-launch, this is wishful thinking)
- "We'll do a Product Hunt launch" (a tactic, not a GTM strategy)

**Questions:**
- "How did you get your first customer? Walk me through exactly what happened."
- "What's the most manual, unscalable thing you've done to test this idea?"
- "Have you sold this product yet — even informally? What did you charge?"
- "Where does customer 11-100 come from? Can you replicate what got you 1-10?"

---

## 11. The Valuation Sanity Test (Shark Tank / investor lens)

Founders often anchor on a valuation without connecting it to business fundamentals.

**Revenue multiples (rough benchmarks):**
- Pre-revenue: 5-15x last 12 months of revenue (or projected Year 1 revenue) — very speculative
- Early SaaS (<$1M ARR): 10-30x ARR (depending on growth rate)
- Growth SaaS ($1M-$10M ARR, 100%+ YoY): 15-40x ARR
- Mature SaaS (slow growth): 5-10x ARR
- D2C/E-commerce: 1-3x revenue, 10-20x EBITDA

**Key investor question:** "Walk me through how you arrived at this valuation."

**Red flags:**
- Valuation not connected to revenue or growth
- "Comparable companies" that are public, mature, or at a much later stage
- Valuation higher than any logical exit outcome in the next 5 years

**Probes:**
- "If a strategic acquirer bought you in 3 years at a market multiple, what's the implied exit value? Does your current valuation work backwards from that?"
- "At what ARR / EBITDA do you justify today's valuation?"

---

## 12. The Competition Honesty Test (YC + Shark Tank)

"We have no real competitors" is almost always a red flag.

**The real question:** "Why hasn't a well-funded competitor already won this market?"

**Possible valid answers:**
- The market just emerged (regulation, tech unlock, behavior change in last 2 years)
- Incumbents are structurally prevented from competing (conflict of interest, legacy tech debt, sales channel conflict)
- The wedge is too small for big companies to care — yet
- Existing solutions address a different customer segment, not this one

**Invalid answers:**
- "We have no competitors" (there's always a workaround or substitute)
- "Competitors exist but they're bad" (why haven't better ones emerged?)
- "We're faster/cheaper/better" (feature differences get copied; this is not a moat)

**Probes:**
- "Who is the best-funded company attacking this problem? What's their approach?"
- "Why hasn't [incumbent] built this as a feature?"
- "What would happen to your customers if you shut down tomorrow — where would they go?"
- "How long have the top competitors been around? Are they growing or stalling?"
