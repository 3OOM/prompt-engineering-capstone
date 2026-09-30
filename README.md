# Capstone: AI-Powered Business Automation & Decision Systems

## Project Information
- **Student Name:** Abhishek Nikam
- **Topic:** AI-Powered Business Automation & Decision Systems (Topic 7 Capstone)
- **Repository:** `prompt-engineering-capstone`
- **Enterprise Case Study:** Apex Cloud Services — Strategic CRM Vendor Selection & 6-Month Phased Rollout

---

## Executive Overview

This repository represents the **Course Capstone Project**, synthesizing all advanced prompt engineering frameworks mastered throughout the curriculum—**Meta-Prompting**, **CO-STAR Framework**, **Quantitative Graph of Thoughts (Q-GoT)**, **Multi-Criteria Decision Analysis (MCDA)**, and **Planning Prompting**.

Simulating the engagement of a Principal Management Consultant, this project evaluates an enterprise CRM migration for **Apex Cloud Services** (migrating 150 sales representatives from fragmented offline spreadsheets). We evaluate **Salesforce Enterprise**, **HubSpot Sales Hub Enterprise**, and **Zoho CRM Enterprise**, conducting verified mathematical TCO calculations, multi-criteria decision scoring, a 6-month phased Gantt rollout, an executive proposal, a 6-slide board presentation, and an architectural lessons learned post-mortem.

---

## Deliverables & Repository Structure

```
prompt-engineering-capstone/
├── README.md                      # Project overview, Loom video walkthrough, and case study guide
├── prompt_portfolio.md            # Meta-prompting, specialized CRM researcher prompt, and CO-STAR Q-GoT templates
├── decision_matrix.md             # Verified Q-GoT TCO calculations and 4-criteria weighted decision matrix
├── implementation_plan.md         # 6-month phased roadmap, Markdown text Gantt chart, and risk registry
├── business_proposal.md           # Formal B2B business proposal for the Board of Directors
├── executive_presentation.md      # 6-slide executive presentation formatted with '---' dividers
└── lessons_learned_report.md      # Post-mortem on hallucination prevention, context window wind-down, and framework alignment
```

### Deliverable Manifest

| Deliverable File | Core Purpose & Contents |
|---|---|
| [`prompt_portfolio.md`](prompt_portfolio.md) | The complete prompt architecture: Meta-prompting system prompt generator, specialized CRM researcher prompt, CO-STAR + Q-GoT vendor evaluation prompt, decision matrix prompt, and roadmap prompt. |
| [`decision_matrix.md`](decision_matrix.md) | Step-by-step Q-GoT mathematical proof calculating 1-year and 3-year TCO for 150 users across all 3 vendors, plus a 4-criteria weighted decision matrix (weights summing to 100%). |
| [`implementation_plan.md`](implementation_plan.md) | 6-month enterprise rollout plan for HubSpot Sales Hub across 4 phases, featuring a text Gantt chart (M1–M6) and a 4-column risk mitigation registry. |
| [`business_proposal.md`](business_proposal.md) | Executive-ready B2B proposal outlining current spreadsheet liabilities, vendor evaluation, cost-benefit justification ($339k savings vs. Salesforce), and formal board recommendation. |
| [`executive_presentation.md`](executive_presentation.md) | 6-slide board-level presentation deck formatted with exact Markdown `---` dividers for clean slide rendering. |
| [`lessons_learned_report.md`](lessons_learned_report.md) | In-depth engineering post-mortem analyzing mathematical hallucination prevention via Q-GoT, managing context window degradation in long threads, and a comprehensive framework alignment taxonomy (RGCCO vs. CARE vs. ERA vs. CO-STAR). |
| [`README.md`](README.md) | Project synthesis, client metrics, video walkthrough agenda, and reproduction instructions. |

---

## Public Loom Walkthrough Video

Watch the complete project walkthrough and live CO-STAR Q-GoT execution demonstration here:  
**[Watch the Public Loom Video](YOUR_PUBLIC_LOOM_URL)**

### Structured Video Agenda (4–6 Minutes)
- **0:00–1:00 (Introduction & Case Study Scope):** Self-introduction by Abhishek Nikam, overview of the Apex Cloud Services case study (150 reps, spreadsheet fragmentation), and capstone goals.
- **1:00–2:00 (Prompt Architecture Walkthrough):** Open [`prompt_portfolio.md`](prompt_portfolio.md) on screen; explain how Meta-Prompting generated the specialized researcher prompt and unpack the structural components of the CO-STAR + Q-GoT framework.
- **2:00–4:00 (Live ChatGPT Demo — CO-STAR Q-GoT Execution):** In a live ChatGPT tab, execute the CO-STAR Q-GoT vendor evaluation prompt. Show the model decomposing the arithmetic step-by-step to calculate 1-year and 3-year TCO ($295K/$835K for Salesforce; $172K/$496K for HubSpot; $77K/$221K for Zoho) with visible self-checking arithmetic.
- **4:00–5:30 (Presentation & Lessons Learned Review):** Display [`executive_presentation.md`](executive_presentation.md) highlighting the 6 slides with `---` dividers and review the critical takeaways from [`lessons_learned_report.md`](lessons_learned_report.md) (hallucination mitigation and framework alignment). Conclude the presentation.

---

## Master TCO & Decision Matrix Summary

### 3-Year TCO Financial Summary (150 Users)
- **Salesforce Enterprise:** $150/user/mo × 150 × 36 + $25,000 = **$835,000.00**
- **HubSpot Sales Hub Enterprise:** $90/user/mo × 150 × 36 + $10,000 = **$496,000.00** *(**$339,000 Cost Savings / -40.6%**)*
- **Zoho CRM Enterprise:** $40/user/mo × 150 × 36 + $5,000 = **$221,000.00**

### Weighted Decision Matrix (Weights Sum to 100%)
- **TCO Cost Model (30%)** + **Customization & Scale (20%)** + **Setup Speed (25%)** + **User Adoption Ease (25%)** = **1.00 (100%)**
- **1st Place (Winner):** **HubSpot Sales Hub Enterprise** $\longrightarrow$ **8.78 / 10.00**
- **2nd Place:** **Zoho CRM Enterprise** $\longrightarrow$ **7.70 / 10.00**
- **3rd Place:** **Salesforce Enterprise** $\longrightarrow$ **6.45 / 10.00**

---

## How to Reproduce the Evaluation

1. Open [`prompt_portfolio.md`](prompt_portfolio.md).
2. Execute **Template 1** in ChatGPT ([chatgpt.com](https://chatgpt.com)) to generate the specialized researcher prompt.
3. Apply the generated prompt as system instructions and run **Template 3 (CO-STAR + Q-GoT Evaluation)** to produce verified TCO calculations.
4. Run **Template 4** to generate the weighted decision matrix.
5. Execute **Templates 5, 6, and 7** to produce the 6-month Gantt roadmap, business proposal, and 6-slide presentation deck.
