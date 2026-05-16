# ClientEngine Performance Dashboard Guide

## Know Your Numbers. Grow Your Business.

---

## What This Guide Covers

This guide shows you how to build and use a performance dashboard that tracks the metrics that actually matter. No vanity numbers — just the data that helps you make better decisions and spot problems before they cost you money.

---

## Part 1: Why Dashboards Matter

### The Problem with Flying Blind

Most business owners know their revenue (sort of) and their expenses (vaguely). But they can't answer simple questions like:

- How many leads did we get this month?
- What percentage of leads became customers?
- Which marketing source brings the best leads?
- How long does it take to close a deal?
- Where are leads getting stuck in our process?

**Without these answers, you're guessing.** And guessing is expensive.

---

## Part 2: The Metrics That Matter

### The 5 Core Metrics

**Track these five numbers religiously:**

| Metric | What It Measures | Why It Matters |
|--------|------------------|----------------|
| **Lead Volume** | How many new leads per week/month | Tells you if your marketing is working |
| **Conversion Rate** | % of leads who become customers | Tells you if your sales process works |
| **Cost Per Lead** | Marketing spend ÷ leads generated | Tells you if you're spending efficiently |
| **Cost Per Acquisition** | Marketing spend ÷ customers acquired | Tells you if you can scale |
| **Lifetime Value** | Average revenue per customer | Tells you what you can afford to spend |

**The Golden Ratio:** Lifetime Value ÷ Cost Per Acquisition = 3:1 minimum (ideally 5:1 or better)

---

### Secondary Metrics (Track Weekly)

**Pipeline Health:**
- Deals in pipeline (by stage)
- Average deal size
- Average time to close
- Win/loss rate

**Activity Metrics:**
- Calls made
- Proposals sent
- Follow-ups completed
- Response time to new leads

**Source Performance:**
- Leads by source
- Conversion rate by source
- Revenue by source

---

## Part 3: Building Your Dashboard

### Step 1: Choose Your Dashboard Tool

**Option 1: Built-in CRM Dashboard**
- Pros: Already connected to your data, no extra cost
- Cons: Limited customization
- Best for: Most small businesses

**Option 2: Spreadsheet (Google Sheets/Excel)**
- Pros: Free, fully customizable
- Cons: Manual data entry
- Best for: Custom calculations, simple setups

**Option 3: Dedicated Dashboard Tool**
- Examples: Databox, Geckoboard, Klipfolio
- Pros: Beautiful, automated, multiple data sources
- Cons: Monthly cost, setup time
- Best for: Growing teams, complex needs

---

### Step 2: Set Up Your Core Dashboard

**Layout: The "At a Glance" View**

**Top Row — The Big Numbers (Monthly):**
```
[LEADS THIS MONTH]    [CONVERSION RATE]    [NEW CUSTOMERS]    [REVENUE]
     47                    12.8%                 6              $14,200
   ↑ 12%                 ↑ 2.1%               ↑ 1              ↑ $3,400
```

**Middle Row — Pipeline Health:**
```
PIPELINE STAGES
New Lead: 12    Contacted: 8    Qualified: 5    Proposal: 3    Negotiation: 2
```

**Bottom Row — Source Performance:**
```
TOP PERFORMING SOURCES
1. Referrals: 15 leads, 20% conversion, $8,500 revenue
2. Website: 22 leads, 9% conversion, $4,200 revenue
3. Events: 10 leads, 10% conversion, $1,500 revenue
```

---

### Step 3: Build Your Spreadsheet Dashboard

**If using Google Sheets, here's the structure:**

**Sheet 1: Raw Data (Lead Log)**
| Date | Name | Source | Stage | Value | Notes |
|------|------|--------|-------|-------|-------|
| 5/1 | John Smith | Referral | Customer | $2,400 | Closed 5/15 |
| 5/3 | Jane Doe | Website | Proposal | $1,200 | Sent 5/10 |

**Sheet 2: Monthly Summary**
| Month | Leads | Customers | Revenue | Conv. Rate |
|-------|-------|-----------|---------|------------|
| Jan | 38 | 5 | $11,200 | 13.2% |
| Feb | 42 | 6 | $13,800 | 14.3% |

**Sheet 3: Dashboard (Visual)**
- Use formulas to pull from Sheet 2
- Add sparklines for trends
- Use conditional formatting (green = good, red = bad)

---

### Step 4: Automate Your Data Collection

**Where your data comes from:**

| Metric | Source | How to Capture |
|--------|--------|----------------|
| Lead count | CRM | New contacts this month |
| Conversion rate | CRM | Opportunities won ÷ total |
| Revenue | CRM/Accounting | Closed deals or invoices |
| Source breakdown | CRM | Lead source field |
| Activity | CRM | Tasks completed |

**Automation tips:**
- Most CRMs can export data automatically
- Use Zapier to push data to spreadsheets
- Schedule weekly exports if manual

---

## Part 4: Reading Your Dashboard

### Step 5: The Weekly Review Ritual

**Every Monday morning, spend 15 minutes:**

1. **Check the big numbers**
   - Are we on track for monthly goals?
   - What's up or down vs. last week?

2. **Analyze the pipeline**
   - Where are deals getting stuck?
   - Do we have enough new leads coming in?

3. **Review source performance**
   - Which sources are working?
   - Should we shift budget?

4. **Identify action items**
   - What needs attention this week?
   - What experiments should we run?

---

### Step 6: Spotting Problems Early

**Red flags to watch for:**

| Warning Sign | What It Means | Action to Take |
|--------------|---------------|----------------|
| Lead volume dropping | Marketing is slowing | Boost ad spend or content output |
| Conversion rate falling | Sales process broken | Review calls, fix objections |
| Pipeline clogged at one stage | Bottleneck identified | Fix that specific stage |
| Source performance dropping | Channel fatigue | Test new creative or channels |
| Response time increasing | Leads going cold | Add automation or staff |

---

### Step 7: Setting Targets and Goals

**How to set realistic targets:**

**Step 1: Establish baseline**
- Look at last 3 months average
- That's your starting point

**Step 2: Set improvement goals**
- Lead volume: +10% per month
- Conversion rate: +1% per month
- Response time: -10% per month

**Step 3: Work backwards from revenue goal**

Example:
- Goal: $20,000/month
- Average deal: $2,000
- Need: 10 customers/month
- Conversion rate: 10%
- Need: 100 leads/month
- Need: 25 leads/week

**Now you know exactly what to hit.**

---

## Part 5: Advanced Dashboarding

### Step 8: Building Forecasts

**Predict the future (sort of):**

**Simple forecast formula:**
```
Pipeline Value × Win Rate = Predicted Revenue
```

Example:
- $50,000 in pipeline
- 20% historical win rate
- Predicted: $10,000 in new revenue

**Weighted pipeline:**
- Assign probability to each stage
- New Lead: 10%
- Qualified: 25%
- Proposal: 50%
- Negotiation: 75%

Calculate weighted value for better accuracy.

---

### Step 9: Cohort Analysis

**Track leads by when they entered:**

| Month Acquired | Leads | 30-Day Conversion | 60-Day Conversion | 90-Day Conversion |
|----------------|-------|-------------------|-------------------|-------------------|
| January | 40 | 8% | 12% | 15% |
| February | 45 | 9% | 14% | - |
| March | 42 | 7% | - | - |

**What this tells you:**
- How long it takes to convert
- If recent changes improved conversion
- When to expect revenue from new leads

---

### Step 10: Team Dashboards (If Applicable)

**If you have a sales team:**

**Individual rep dashboard:**
- Leads assigned
- Calls made
- Meetings booked
- Deals closed
- Conversion rate
- Revenue

**Team leaderboard:**
- Rank by revenue
- Rank by conversion rate
- Rank by activity

**Manager view:**
- Team totals
- Individual performance
- Pipeline by rep
- Coaching opportunities

---

## Quick Reference: Dashboard Checklist

### Setup
- [ ] Tool selected and configured
- [ ] Core 5 metrics defined
- [ ] Data sources connected
- [ ] Visual layout created
- [ ] Formulas/calculations tested
- [ ] Access shared with team

### Weekly Ritual
- [ ] Numbers reviewed (Monday AM)
- [ ] Trends analyzed
- [ ] Red flags identified
- [ ] Action items created
- [ ] Goals checked vs. actual

### Monthly Deep Dive
- [ ] Full month analysis
- [ ] Source performance review
- [ ] Forecast accuracy check
- [ ] Goal adjustment for next month
- [ ] Dashboard improvements made

---

## Sample Dashboard Views

### The Executive Summary (Monthly)
```
═══════════════════════════════════════════
THIS MONTH'S PERFORMANCE
═══════════════════════════════════════════

Leads:              47    ↑ 12% vs last month
Conversion Rate:    12.8% ↑ 2.1% vs last month
New Customers:      6     ↑ 1 vs last month
Revenue:            $14,200 ↑ $3,400 vs last month
Cost Per Lead:      $32   ↓ $8 vs last month
Cost Per Acquisition: $250 ↓ $50 vs last month

GOAL PROGRESS: 71% of monthly revenue target

TOP SOURCE: Referrals (20% conversion, $8,500 revenue)
NEEDS ATTENTION: Website leads (9% conversion, down from 14%)

ACTION ITEMS THIS WEEK:
1. Review website lead quality
2. Follow up with 3 stalled proposals
3. Increase referral program outreach
```

---

## Common Dashboard Mistakes

1. **Too many metrics** — Focus on 5-7 that matter
2. **Vanity metrics** — Track revenue, not likes
3. **No context** — Always show vs. last period
4. **Set and forget** — Review weekly or it's useless
5. **No action** — Data without action is just trivia

---

*What gets measured gets managed. What gets managed gets improved. Your dashboard is your compass — check it often, trust what it tells you, and act on what you see.*
