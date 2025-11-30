# Healthcare Industry SSARS Guide

## Overview

Healthcare entities present unique challenges for SSARS engagements due to complex revenue recognition, third-party payer relationships, regulatory compliance requirements, and specialized accounting standards.

---

## Types of Healthcare Entities

| Entity Type | Key Characteristics |
|-------------|-------------------|
| **Physician practices** | Professional services, multiple payers, E&M coding |
| **Dental practices** | Mix of insurance and patient pay |
| **Medical clinics** | Outpatient services, multiple specialties |
| **Surgery centers** | Facility fees, professional fees, high-value procedures |
| **Home health agencies** | Medicare certification, episode-based billing |
| **Nursing facilities** | Skilled nursing, Medicaid/Medicare reimbursement |
| **Behavioral health** | Mental health, substance abuse services |
| **Pharmacies** | PBM contracts, 340B program, inventory management |
| **Medical labs** | Fee schedules, specimen processing |
| **DME suppliers** | Equipment sales/rentals, complex billing |

---

## Critical Accounting Considerations

### 1. Revenue Recognition

Healthcare revenue recognition is highly complex due to:

#### Third-Party Payers

```
┌─────────────────────────────────────────────────────────────┐
│               HEALTHCARE REVENUE CYCLE                       │
├─────────────────────────────────────────────────────────────┤
│  Service Provided                                            │
│       ↓                                                      │
│  Charges Recorded (Gross Charges)                            │
│       ↓                                                      │
│  Contractual Adjustments Applied                             │
│       ↓                                                      │
│  Net Patient Service Revenue                                 │
│       ↓                                                      │
│  Collections/Payments                                        │
│       ↓                                                      │
│  Bad Debt/Charity Care Adjustments                          │
└─────────────────────────────────────────────────────────────┘
```

#### Revenue Components

| Component | Description | GAAP Treatment |
|-----------|-------------|----------------|
| **Gross charges** | Standard charge master rates | Not typically reported as revenue |
| **Contractual adjustments** | Difference between charges and expected payment | Reduce gross revenue to net |
| **Net patient revenue** | Expected collectible amount | Reported as revenue |
| **Bad debt** | Amounts deemed uncollectible | Operating expense (per ASC 606) |
| **Charity care** | Services provided free | Disclosure only, not revenue |

#### ASC 606 Considerations

Under ASC 606, healthcare entities must:
- Estimate **variable consideration** (contractual adjustments)
- Assess **collectibility** at patient level
- Report **implicit price concessions** as reduction of revenue
- Consider **constraint on variable consideration**

### 2. Accounts Receivable

Healthcare A/R is uniquely complex:

| A/R Category | Characteristics |
|--------------|-----------------|
| **Insurance receivables** | Subject to contractual rates |
| **Patient receivables** | Copays, deductibles, self-pay |
| **Government payers** | Medicare, Medicaid - subject to audits |
| **Workers' comp** | Statutory rates, longer collection cycle |
| **Unbilled receivables** | Services rendered but not yet billed |

#### Allowance Considerations

```
Allowance Estimation Factors:
[ ] Payer mix analysis
[ ] Historical collection rates by payer
[ ] Aging analysis by payer category
[ ] Contractual adjustment rates
[ ] Bad debt trends
[ ] Economic conditions affecting patient pay
[ ] Changes in reimbursement rates
```

### 3. Contractual Arrangements

| Contract Type | Accounting Implications |
|---------------|------------------------|
| **Fee-for-service** | Revenue per service rendered |
| **Capitation** | Fixed payment per member per month |
| **Bundled payments** | Single payment for episode of care |
| **Value-based** | Quality metrics affect payment |
| **Risk-sharing** | Withholds, bonuses based on utilization |
| **340B Drug Program** | Discounted drug pricing for eligible entities |

### 4. Operating Expenses

| Expense Category | Special Considerations |
|-----------------|----------------------|
| **Provider compensation** | Often largest expense; partner draws vs. salary |
| **Malpractice insurance** | Claims-made vs. occurrence; tail coverage |
| **Medical supplies** | Inventory valuation, expiration, consignment |
| **Equipment** | Lease vs. purchase, depreciation methods |
| **Laboratory costs** | In-house vs. reference lab |
| **Billing/collection** | In-house vs. outsourced billing companies |

---

## Review Engagement Considerations

### Analytical Procedures for Healthcare

#### Revenue Analytics

| Procedure | What to Look For |
|-----------|-----------------|
| Revenue per provider | Unusual fluctuations, new/departed providers |
| Revenue per patient visit | Changes in service mix |
| Payer mix analysis | Shifts between payer types |
| Charge/collection ratio | Collection efficiency trends |
| Days in A/R by payer | Increasing collection cycle |
| Revenue per CPT code | Coding pattern changes |

#### Key Ratios

| Ratio | Formula | Benchmark Range |
|-------|---------|-----------------|
| **Days in A/R** | (Net A/R ÷ Net Revenue) × 365 | 30-50 days typical |
| **Collection rate** | Collections ÷ Gross Charges | 35-65% depending on payer mix |
| **Net collection rate** | Collections ÷ (Charges - Adjustments) | 95-100% |
| **Overhead ratio** | Operating expenses ÷ Revenue | Varies by specialty |
| **Staff cost ratio** | Staff costs ÷ Revenue | 25-35% typical |
| **Adjustment percentage** | Adjustments ÷ Gross Charges | Varies by payer mix |

#### Expense Analytics

| Procedure | What to Look For |
|-----------|-----------------|
| Provider compensation trends | Changes in productivity |
| Malpractice insurance | Premium changes, claims activity |
| Supply cost per visit | Utilization changes |
| Occupancy costs | Expansion or contraction |
| Outside services | Changes in outsourcing |

### Inquiry Areas for Healthcare

```
Required Healthcare-Specific Inquiries:

[ ] Changes in payer contracts or rates
[ ] New service lines or discontinued services
[ ] Provider additions or departures
[ ] Regulatory audits or investigations
[ ] Malpractice claims or settlements
[ ] Changes in coding practices
[ ] RAC or MAC audit activity
[ ] Meaningful use/MIPS compliance
[ ] HIPAA compliance issues
[ ] Stark/Anti-kickback compliance
[ ] Changes in referral patterns
[ ] Equipment purchases or leases
[ ] Involvement in ACOs or risk arrangements
[ ] 340B program participation
[ ] Telehealth/telemedicine activities
```

---

## Compilation Considerations

### Financial Statement Presentation

Healthcare entities may present financial statements differently:

| Presentation Issue | Considerations |
|-------------------|----------------|
| **Revenue presentation** | Gross vs. net; contractual adjustments |
| **Charity care disclosure** | Policy and amounts |
| **Bad debt classification** | Operating expense per ASC 606 |
| **Provider compensation** | May be shown separately |
| **Concentration disclosure** | Medicare/Medicaid as % of revenue |
| **Malpractice disclosure** | Claims-made policy, tail liability |

### Common Departures from GAAP

| Departure | Issue |
|-----------|-------|
| **Cash basis revenue** | Not recognizing A/R or allowances |
| **No contractual adjustments** | Recording gross charges as revenue |
| **Inadequate allowance** | Understating bad debt allowance |
| **Missing charity care disclosure** | Required disclosure omitted |
| **Improper expense classification** | Provider compensation as draw |
| **Missing malpractice disclosure** | Claims-made implications |

---

## Regulatory Considerations

### Healthcare Regulations Affecting Financial Statements

| Regulation | Impact |
|-----------|--------|
| **Stark Law** | Physician self-referral prohibitions |
| **Anti-Kickback Statute** | Prohibited remuneration arrangements |
| **HIPAA** | Privacy and security compliance costs |
| **Medicare Conditions of Participation** | Required for Medicare participation |
| **State licensing** | Operating license requirements |
| **Certificate of Need** | Capital expenditure restrictions |
| **340B Program** | Drug pricing compliance |
| **Corporate Practice of Medicine** | State-specific restrictions |

### Potential Liabilities

| Liability Area | Financial Statement Impact |
|----------------|--------------------------|
| Overpayment refunds | Liability, revenue adjustment |
| RAC/MAC audit recoveries | Contingent liability |
| Malpractice claims | Liability, insurance receivable |
| False Claims Act exposure | Contingent liability |
| HIPAA breach penalties | Contingent liability |

---

## Common Peer Review Deficiencies - Healthcare

| Deficiency | Prevention |
|------------|------------|
| Inadequate understanding of revenue cycle | Document revenue cycle understanding |
| No payer mix analysis | Perform payer-specific analytics |
| Insufficient A/R allowance review | Analyze by payer, age, historical collection |
| Missing required healthcare disclosures | Include charity care, concentrations, malpractice |
| Not addressing contractual adjustments | Understand and document adjustment methodology |
| Ignoring regulatory risks | Inquire about audits, investigations |

---

## Documentation Checklist - Healthcare Engagements

### Compilation Documentation

```
[ ] Engagement letter referencing healthcare considerations
[ ] Understanding of revenue cycle documented
[ ] Payer mix understood
[ ] Contractual adjustment methodology documented
[ ] A/R aging obtained and reviewed
[ ] Provider compensation arrangements understood
[ ] Malpractice insurance arrangements documented
[ ] Significant healthcare-specific matters noted
```

### Review Documentation

```
[ ] All compilation documentation items
[ ] Analytical procedures tailored to healthcare
[ ] Revenue analytics by payer documented
[ ] Days in A/R analysis
[ ] Collection rate analysis
[ ] Provider productivity analysis
[ ] Inquiries about regulatory matters
[ ] Management responses documented
[ ] Follow-up on unusual items
[ ] Representation letter addresses healthcare items
```

---

## Sample Representation Letter Items - Healthcare

Include these healthcare-specific representations:

```
Healthcare-Specific Representations:

• Revenue has been recognized in accordance with GAAP, net of estimated
  contractual adjustments, implicit price concessions, and other discounts.

• The allowance for doubtful accounts is adequate based on historical
  collection experience and current collection trends.

• All significant third-party payer contracts have been disclosed, and
  reimbursement rates used in estimating contractual adjustments reflect
  current contract terms.

• There are no known overpayments subject to refund to third-party payers,
  or such amounts have been properly recorded.

• There are no pending or threatened Medicare/Medicaid audits, RAC audits,
  or other governmental investigations, except as disclosed.

• The practice is in compliance with Stark Law, Anti-Kickback Statute,
  and other applicable healthcare regulations.

• All known malpractice claims have been disclosed and appropriately
  accrued or disclosed in the financial statements.

• Charity care amounts disclosed represent services provided to patients
  who meet the organization's charity care criteria.
```

---

## Healthcare Financial Statement Examples

### Income Statement Presentation (Net Revenue Method)

```
XYZ Medical Practice, PC
Statement of Operations
For the Year Ended December 31, 20XX

Net patient service revenue                    $2,450,000
  (Net of contractual adjustments of $1,200,000)
Other operating revenue                            50,000
                                               ----------
Total operating revenue                         2,500,000

Operating expenses:
  Provider compensation                           900,000
  Staff salaries and benefits                     625,000
  Medical supplies                                125,000
  Rent and occupancy                              200,000
  Professional liability insurance                 75,000
  Outside services (billing, lab)                 150,000
  Other operating expenses                        225,000
                                               ----------
Total operating expenses                        2,300,000
                                               ----------
Operating income                                  200,000

Other income (expense):
  Interest income                                   5,000
  Interest expense                                (10,000)
                                               ----------
Net income                                      $ 195,000
                                               ==========
```

### Balance Sheet Considerations

```
Patient accounts receivable                    $  450,000
Less: Allowance for contractual adjustments      (125,000)
Less: Allowance for doubtful accounts            (50,000)
                                               ----------
Patient accounts receivable, net               $  275,000
```

---

## Key Takeaways

1. **Revenue is complex** - Understand third-party payer relationships and contractual adjustments
2. **A/R requires special attention** - Payer-specific analysis and allowances
3. **Regulatory environment matters** - Consider compliance and contingent liabilities
4. **Industry-specific disclosures required** - Charity care, concentrations, malpractice
5. **Analytical procedures must be tailored** - Use healthcare-specific metrics
6. **ASC 606 changed bad debt treatment** - Now an operating expense
7. **Documentation must reflect healthcare complexity** - More extensive than typical entities

---

## Resources

- AICPA Audit and Accounting Guide: Health Care Entities
- Healthcare Financial Management Association (HFMA)
- Medical Group Management Association (MGMA)
- CMS Medicare Provider Reimbursement Manual
- State healthcare regulatory agencies

---

**Related Guides:**
- [Nonprofit SSARS Guide](nonprofit-ssars-guide.md) (for nonprofit healthcare)
- [Professional Services Guide](professional-services-ssars-guide.md) (for physician partnerships)
