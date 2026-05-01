# SECTION 1: CORE ECONOMIC ENGINE

## 1.1 Why Economic Thinking Dominates Startup Outcomes

### Premise

A startup is not primarily a product-building system.
It is a **resource allocation system under uncertainty**.

### Core Constraint

* Capital is finite
* Time is finite
* Attention is finite

### Implication

Every decision must answer:

> Does this increase long-term value per unit of resource consumed?

### Formal Expression

Let:

* ( V ) = total enterprise value
* ( R ) = total resources consumed (capital, time, effort)

Objective:

[
\max \frac{V}{R}
]

### Failure Mode

Founders optimize:

* features
* growth vanity
* hiring speed

Instead of:

* return on capital
* marginal value creation

---

## 1.2 Scarcity and Opportunity Cost

### Definition

Opportunity cost is the value of the best alternative foregone.

### Founder Reality

You are never choosing between:

* doing X vs doing nothing

You are choosing:

* doing X vs doing Y vs doing Z

### Decision Rule

For any action ( A_i ):

A* = argmax(Expected Return - Opportunity Cost)

Choose:

[
A^* = \arg\max (Expected\ Return - Opportunity\ Cost)
]

### Example

You have 3 options:

* Improve onboarding
* Launch new feature
* Run paid ads

Expected outcomes:

* Onboarding → increases retention → increases LTV
* Feature → uncertain adoption
* Ads → increases CAC immediately

Correct move depends on constraint:

* If retention is weak → onboarding dominates
* If demand exists but traffic is low → ads dominate

---

## 1.3 Marginal Thinking

### Definition

Decisions must be evaluated at the margin, not in averages.

### Formalization

[
Marginal\ Value = \frac{\Delta Output}{\Delta Input}
]

### Application Domains

#### Pricing

Do not ask:

* “What is the average willingness to pay?”

Ask:

* “At what price does one more customer stop buying?”

#### Hiring

Do not ask:

* “Do we need more engineers?”

Ask:

* “Does the next engineer increase output more than their cost?”

#### Marketing

Do not ask:

* “Is marketing working?”

Ask:

* “Does the next dollar spent produce positive return?”

---

# SECTION 2: UNIT ECONOMICS ENGINE

## 2.1 Defining the Unit

### Rule

A unit must represent a **repeatable revenue-generating event**.

### Valid Units by Model

| Model       | Unit Definition       |
| ----------- | --------------------- |
| SaaS        | Customer subscription |
| Marketplace | Transaction           |
| E-commerce  | Order                 |
| Services    | Billable hour/project |

### Constraint

If unit is unclear, economics cannot be computed.

---

## 2.2 Customer Lifetime Value (LTV)

### Core Formula

For subscription:

[
LTV = \frac{ARPU \times Gross\ Margin}{Churn\ Rate}
]

Where:

* ARPU = average revenue per user
* Gross Margin = (Revenue - COGS) / Revenue
* Churn Rate = fraction of customers leaving per period

### Assumptions

* Constant churn
* Stable pricing

### Failure Modes

* Ignoring gross margin
* Using revenue instead of contribution
* Overestimating retention

---

## 2.3 Customer Acquisition Cost (CAC)

### Formula

[
CAC = \frac{Total\ Sales\ +\ Marketing\ Spend}{New\ Customers}
]

### Types

* Paid CAC
* Organic CAC
* Blended CAC

### Critical Insight

CAC is not static. It increases with scale.

---

## 2.4 LTV to CAC Ratio

### Formula

[
LTV/CAC
]

### Decision Thresholds

| Ratio | Interpretation            |
| ----- | ------------------------- |
| < 1   | Value destruction         |
| 1–3   | Weak model                |
| 3–5   | Healthy                   |
| > 5   | Under-investing in growth |

---

## 2.5 CAC Payback Period

### Formula

[
Payback = \frac{CAC}{Monthly\ Contribution\ Margin}
]

### Rule

* < 6 months → strong
* 6–12 months → acceptable
* > 12 months → capital inefficient

---

## 2.6 Contribution Margin

### Formula

[
Contribution\ Margin = Revenue - Variable\ Costs
]

Or percentage:

[
CM% = \frac{Revenue - Variable\ Costs}{Revenue}
]

### Rule

Scaling is only rational if:

[
Contribution\ Margin > 0
]

---

## 2.7 Churn and Retention

### Formula

[
Retention = 1 - Churn
]

### Dynamics

Small improvements in retention produce exponential LTV growth.

### Proof Insight

If churn decreases:

[
LTV \propto \frac{1}{Churn}
]

Thus:

* Reducing churn from 10% to 5% doubles LTV

---

# SECTION 3: DECISION FLOW SYSTEM

## 3.1 Scaling Decision Flow

### Step 1

Check contribution margin

* If negative → stop scaling
* Fix cost structure or pricing

### Step 2

Check LTV/CAC

* If < 3 → improve retention or reduce CAC

### Step 3

Check payback

* If > 12 months → capital inefficiency

### Step 4

Check operational capacity

* If constrained → scaling breaks system

### Decision

Scale only if all conditions satisfied.

---

## 3.2 Hiring Decision Flow

### Evaluate:

[
Marginal\ Output > Marginal\ Cost
]

### Steps

1. Define expected output increase
2. Estimate cost (salary + overhead)
3. Compare:

* If output gain < cost → do not hire
* If output gain > cost → hire

---

## 3.3 Pricing Decision Flow

### Step 1

Estimate willingness to pay

### Step 2

Test elasticity

If demand drops significantly with small price increase:

* High elasticity → keep price low

If demand stable:

* Increase price

### Step 3

Validate impact on:

[
Revenue = Price \times Quantity
]

---

# SECTION 4: FAILURE PATTERNS

## 4.1 Scaling Before Unit Economics

Condition:

* Negative contribution margin
* Aggressive marketing spend

Result:

* Growth increases losses

---

## 4.2 Ignoring Opportunity Cost

Symptom:

* Too many parallel initiatives

Result:

* diluted execution
* no dominant outcome

---

## 4.3 Misreading CAC

Symptom:

* early low CAC assumed permanent

Reality:

* CAC increases with saturation

---

# SECTION 5: WEEKLY OPERATING SYSTEM

## Weekly Metrics to Track

* LTV
* CAC
* LTV/CAC
* Payback
* Contribution Margin
* Churn

## Weekly Questions

1. Are we creating value per customer?
2. Are we acquiring customers efficiently?
3. Are we retaining them?
4. Is scaling increasing or destroying value?

## Action Rule

If any metric deteriorates:

* pause expansion
* diagnose root cause
* correct before scaling

---

# FINAL PRINCIPLE

A startup survives if:

[
Unit\ Value\ Created > Unit\ Cost\ of\ Creation
]

A startup scales if:

[Marginal\ Value > Marginal\ Cost]

A startup dominates if:

[
It\ improves\ both\ faster\ than\ competitors
]

---


