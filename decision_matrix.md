# Quantitative Decision Matrix & TCO Evaluation

**Client:** Apex Cloud Services  
**Scope:** CRM Platform Migration for 150 Active Sales Representatives  
**Methodology:** Quantitative Graph of Thoughts (Q-GoT) & Multi-Criteria Decision Analysis (MCDA)  
**Lead Analyst:** Abhishek Nikam, Principal Consultant  

---

## 1. Quantitative Graph of Thoughts (Q-GoT) Total Cost of Ownership (TCO)

The Total Cost of Ownership (TCO) was evaluated using a closed-form deterministic arithmetic model:
$$\text{TCO} = (\text{User Count} \times \text{Monthly Seat Cost} \times \text{Duration in Months}) + \text{Implementation Setup Fee}$$

### Parameters Baseline
- **Enterprise Cohort:** 150 Sales Representatives
- **Salesforce Enterprise:** $150.00 / user / month; $25,000 setup fee
- **HubSpot Sales Hub Enterprise:** $90.00 / user / month; $10,000 setup fee
- **Zoho CRM Enterprise:** $40.00 / user / month; $5,000 setup fee

---

### Step-by-Step Arithmetic Calculation & Verification Log

```
[Q-GoT NODE 1: Salesforce Enterprise TCO]
1. Annual Recurring Licensing:
   150 users × $150/mo = $22,500/mo
   $22,500/mo × 12 months = $270,000.00
2. 1-Year TCO:
   $270,000.00 licensing + $25,000.00 setup = $295,000.00
3. 36-Month Cumulative Licensing:
   $22,500/mo × 36 months = $810,000.00
4. 3-Year TCO:
   $810,000.00 licensing + $25,000.00 setup = $835,000.00
[VERIFICATION: 150 × 150 × 12 + 25000 = 295000. 150 × 150 × 36 + 25000 = 835000. PASS]

[Q-GoT NODE 2: HubSpot Sales Hub Enterprise TCO]
1. Annual Recurring Licensing:
   150 users × $90/mo = $13,500/mo
   $13,500/mo × 12 months = $162,000.00
2. 1-Year TCO:
   $162,000.00 licensing + $10,000.00 setup = $172,000.00
3. 36-Month Cumulative Licensing:
   $13,500/mo × 36 months = $486,000.00
4. 3-Year TCO:
   $486,000.00 licensing + $10,000.00 setup = $496,000.00
[VERIFICATION: 150 × 90 × 12 + 10000 = 172000. 150 × 90 × 36 + 10000 = 496000. PASS]

[Q-GoT NODE 3: Zoho CRM Enterprise TCO]
1. Annual Recurring Licensing:
   150 users × $40/mo = $6,000/mo
   $6,000/mo × 12 months = $72,000.00
2. 1-Year TCO:
   $72,000.00 licensing + $5,000.00 setup = $77,000.00
3. 36-Month Cumulative Licensing:
   $6,000/mo × 36 months = $216,000.00
4. 3-Year TCO:
   $216,000.00 licensing + $5,000.00 setup = $221,000.00
[VERIFICATION: 150 × 40 × 12 + 5000 = 77000. 150 × 40 × 36 + 5000 = 221000. PASS]
```

### Master TCO Financial Summary Table

| Vendor Candidate | Monthly Licensing (150 Users) | Setup & Onboarding Fee | 1-Year Cumulative TCO | 3-Year Cumulative TCO | Variance vs. Salesforce (3-Yr Savings) |
|:---|:---:|:---:|:---:|:---:|:---:|
| **Salesforce Enterprise** | $22,500.00 | $25,000.00 | **$295,000.00** | **$835,000.00** | $0.00 (Baseline) |
| **HubSpot Sales Hub** | $13,500.00 | $10,000.00 | **$172,000.00** | **$496,000.00** | **+$339,000.00 (-40.6%)** |
| **Zoho CRM Enterprise** | $6,000.00 | $5,000.00 | **$77,000.00** | **$221,000.00** | **+$614,000.00 (-73.5%)** |

---

## 2. Multi-Criteria Weighted Decision Matrix

To ensure holistic strategic alignment, vendors were evaluated beyond pure licensing costs. Criteria weights were calibrated based on Apex Cloud Services' board priorities:

| Evaluation Criterion | Weight (%) | Weight (Decimal) | Evaluation Definition & Strategic Rationale |
|---|---|---|---|
| **TCO Cost Model** | 30.0% | 0.30 | Multi-year licensing efficiency, implementation overhead, and TCO ROI. |
| **Customization & Scale** | 20.0% | 0.20 | Enterprise data schemas, API extensibility, complex CPQ rules, and scale. |
| **Setup & Time-to-Value Speed** | 25.0% | 0.25 | Migration velocity, out-of-the-box integration, and time to operational go-live. |
| **User Adoption Ease & UI Usability**| 25.0% | 0.25 | Rep onboarding friction, modern UI/UX, email client sync, and mobile app rating. |
| **Total Weight Check** | **100.0%** | **1.00** | **Integrity Check: 0.30 + 0.20 + 0.25 + 0.25 = 1.00 (100.0%)** |

### Scored Decision Matrix Table

*Scoring Scale: 1 (Severely Deficient) to 10 (World-Class / Industry Leader)*  
*Formula: $\text{Weighted Score} = \text{Raw Score} \times \text{Weight}$*

| Solution | Criterion | Weight | Score (1-10) | Weighted Score |
|:---|:---|:---:|:---:|:---:|
| **Salesforce Enterprise** | TCO Cost Model | 0.30 | 6.0 | 1.800 |
| | Customization & Scale | 0.20 | 9.5 | 1.900 |
| | Setup & Time-to-Value Speed | 0.25 | 5.0 | 1.250 |
| | User Adoption Ease & UI Usability | 0.25 | 6.0 | 1.500 |
| | **Salesforce Composite Score** | **1.00** | — | **6.450 / 10.00** |
|---|---|---|---|---|
| **HubSpot Sales Hub** | TCO Cost Model | 0.30 | 8.5 | 2.550 |
| | Customization & Scale | 0.20 | 8.0 | 1.600 |
| | Setup & Time-to-Value Speed | 0.25 | 9.0 | 2.250 |
| | User Adoption Ease & UI Usability | 0.25 | 9.5 | 2.375 |
| | **HubSpot Composite Score** | **1.00** | — | **8.775 / 10.00** |
|---|---|---|---|---|
| **Zoho CRM Enterprise** | TCO Cost Model | 0.30 | 10.0 | 3.000 |
| | Customization & Scale | 0.20 | 6.0 | 1.200 |
| | Setup & Time-to-Value Speed | 0.25 | 7.5 | 1.875 |
| | User Adoption Ease & UI Usability | 0.25 | 6.5 | 1.625 |
| | **Zoho Composite Score** | **1.00** | — | **7.700 / 10.00** |

---

## 3. Final Strategic Ranking & Selection Justification

```
                      FINAL VENDOR RANKINGS
┌─────────────────────────────────────────────────────────────┐
│ 1st Place: HubSpot Sales Hub Enterprise    │ Score: 8.78/10 │
├─────────────────────────────────────────────┼───────────────┤
│ 2nd Place: Zoho CRM Enterprise             │ Score: 7.70/10 │
├─────────────────────────────────────────────┼───────────────┤
│ 3rd Place: Salesforce Enterprise           │ Score: 6.45/10 │
└─────────────────────────────────────────────────────────────┘
```

### Strategic Analysis of Results
1. **HubSpot Sales Hub (Selected Winner — 8.78/10):**  
   HubSpot commands the optimal equilibrium between enterprise power and sales velocity. At **$496,000 across 3 years**, it is **$339,000 cheaper than Salesforce (-40.6%)**, while scoring the highest across User Adoption Ease (9.5) and Setup Speed (9.0). Its native Gmail/Outlook integration and intuitive UI eliminate rep resistance, which is the #1 cause of failed CRM migrations.
2. **Zoho CRM (Runner-Up — 7.70/10):**  
   While Zoho offers the lowest financial cost ($221,000 3-yr TCO), its disjointed application suite, inconsistent UI polish, and complex Deluge scripting language introduce substantial technical debt and high training friction for 150 enterprise reps.
3. **Salesforce Enterprise (Eliminated — 6.45/10):**  
   Salesforce provides unmatched customization (9.5), but penalizes Apex Cloud Services with exorbitant TCO ($835,000 over 3 years), slow implementation cycles (5.0), and a mandatory requirement for full-time certified Salesforce administrators.
