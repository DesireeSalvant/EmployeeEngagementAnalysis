# EMPLOYEE ENGAGEMENT DASHBOARD — OVERVIEW

![Employee Engagement Dashboard](dashboardsnapshotEE.png)

Built in Microsoft Power BI, this interactive dashboard presents a consolidated view of our annual Employee Engagement results. It combines Current Year (CY) and Last Year (LY) survey data with industry benchmarks to help leaders quickly understand performance, identify gaps, and prioritize actions.

### What you’ll see

- KPI cards: Overall Engagement, YoY change, and Completion Rate.
- Comparisons: CY vs LY and Benchmark by category.
- Segmentation: Engagement by Job Level and regional respondent mix.
- Open-ended context: Dedicated visuals and files (themes, sentiment, length) for qualitative insight.
- Respondent Profile: Slicers for Region, Department, and Staff Tenure.

### How to use it

- Apply the Region / Department / Staff Tenure slicers to focus the view on your audience.
- Hover or click a bar/segment to cross-filter related visuals and view exact values.
- Use the category and job-level charts to locate strengths and gaps; pair with open-ended themes for root causes.

This experience replaces static reporting with an interactive, governed view designed for decision-ready conversations and targeted action planning.

# EXECUTIVE SUMMARY

## Key KPIs

| Metric                 | Value                  |
|------------------------|------------------------|
| Overall Engagement     | 78.2%                  |
| Year-over-Year Change  | +7.1 percentage points |
| Completion Rate        | 98.0%                  |
| Respondents (CY)       | 7,898                  |

This people analytics project explores key trends in employee engagement using a Power BI dashboard, focusing on categories, job levels, regions, departments, and staff tenure, with supporting analysis of open-ended feedback.

Headline KPIs indicate:

- _Overall Engagement:_ **78.2%**  
- _YoY change:_ **+7.1 pp**  
- _Completion Rate:_ **98%**  

These provide strong confidence in the insights.

Visuals highlight:

- Engagement follows an expected seniority gradient:  
  - **Directors ≈ 83%**  
  - **Managers ≈ 78.7%**  
  - **Executives ≈ 78.1%**  
  - **Juniors ≈ 76.1%**  

This signals opportunity in early-career enablement and coaching.

Across categories:

- Results cluster in the mid-70s vs. industry benchmark.
- Areas nearer the lower bound (e.g., Enablement, Development) warrant targeted actions.

Regional participation:

- Well distributed across **AMER**, **EMEA**, **APAC** (AMER has the largest share), ensuring balanced representation.

### Conclusion

The dashboard surfaces clear action points:
- Close gaps to benchmark
- Focus on early-career support
- Translate open-ended themes into concrete initiatives and manager playbooks

# ABOUT THE COMPANY

**MosaicWorks, Inc.** is a global digital products and services company operating across **AMER, EMEA, and APAC**.  
We design, build, and run cloud platforms and data solutions for enterprise clients in retail, healthcare, and financial services.

Our people strategy emphasizes:  
- One Team  
- Customer First  
- Integrity  
- Curiosity  
- Continuous Improvement  

With consistent investment in learning, mobility, and manager effectiveness.

---

# PROBLEM STATEMENT

Leaders needed a governed, interactive view of engagement results that:

1. Consolidates survey data into a single, reliable model.  
2. Compares Current Year vs Last Year and Industry Benchmark consistently.  
3. Reveals differences by Region, Department, Job Level, and Staff Tenure, and brings open-ended feedback into the discussion.

> The prior process relied on **spreadsheets and static decks**, limiting exploration speed, consistency, and actionability.

---

# AIM OF THE PROJECT

- Deliver an interactive Power BI dashboard surfacing the core KPIs (Overall Engagement, YoY change, Completion Rate) with clear drill-downs.  
- Provide comparison views (CY vs LY vs Benchmark) that stay interpretable while audience filters are applied.  
- Include segment views (Job Level, Region participation) and reference artifacts (ERD, category visuals, open-ended analysis) for decision-ready conversations.  
- Establish a repeatable model and theme so future survey waves can be refreshed with minimal effort and consistent quality.

  # CHART & DEEP DIVE ANALYSIS

## Engagement by Job Level (CY)

![Engagement by Job Level](engagement_by_job_level.png)

**Question it answers**  
Which job levels report the highest and lowest engagement, and how large is the gap between levels?

**How to read it**  
Each bar shows the average engagement score (0–100) for a job level in the current year. Labels at the top of bars display exact values.

**Key insights**
- **Director:** 78.2 — highest among all levels.  
- **Manager:** 75.2 and **Executive:** 74.8 — mid-tier, tightly clustered.  
- **Junior:** 73.8 — lowest engagement.  
- **Spread:** ~4.4 points from Director to Junior, indicating a consistent seniority gradient.

**Why it matters**  
Lower engagement in early-career roles is a common driver of turnover risk and productivity drag. Addressing enablement, recognition, and career clarity at these levels can lift overall scores fastest.

**Recommended actions**
- Strengthen onboarding, peer mentoring, and role clarity for Junior roles.  
- Coach managers to improve check-ins, feedback quality, and career discussions.  
- Implement lightweight recognition programs for entry and mid levels.  
- Run pulse surveys for Junior/Executive cohorts to validate pain points.

**Caveats**
- Results are averages; check sample sizes before drawing conclusions.  
- Descriptive, not causal; consider department and region effects.

---

## Engagement Scores by Category (CY)

![Engagement by Category](engagement_by_category.png)

**Question it answers**  
Which engagement categories score highest/lowest, and where should improvement efforts focus?

**How to read it**  
Horizontal bars show the average engagement score (0–100) by category for the current year.  
“Open Ended” appears for context but is not scored.

**Key insights**
- **Leadership:** 83.1 — strongest category.  
- **Alignment:** 76.0 — healthy but improvable.  
- **Development:** 74.9 and **Company Confidence:** 74.1 — mid-tier.  
- **Employee Engagement:** 73.4  
- **Enablement:** 68.9 — lowest; likely tooling/process/workload friction.

**Why it matters**  
Enablement gaps correlate with friction, burnout, and attr

## Employee Distribution by Department

![Employee Distribution by Department](department_distribution.png)

**Question it answers**  
What is the workforce mix across departments?

**How to read it**  
Pie wedges show % of headcount by department.

**Key insights**
- **Operations & Services:** 32.5% — largest  
- **Sales & Marketing:** 25.3%  
- **Engineering & Technology:** 18.4%  
- **Corporate Office:** 14.7%  
- **Research & Development:** 9.1%

**Why it matters**  
Biggest departments shape overall KPIs. Small cohorts (e.g., R&D) require caution.

**Recommended actions**
- Prioritize enablement in Ops & Sales  
- Coach managers in largest segments  
- Set min-n thresholds for small departments  
- Adjust outreach to ensure balanced participation

**Caveats**
- Headcount ≠ engagement levels.  
- Confirm proportional response rates.

---

## Open-Ended Response Volume by Question Type (CY)

![Open-Ended Response Volume](openended_response_volume.png)

**Question it answers**  
Which open-ended questions generate the most written feedback?

**How to read it**  
Bars show count of responses per open-ended question.

**Key insights**
- **Q21 ("Not so great")**: 73 — highest volume  
- **Q20 ("Things we do great")**: 44  
- **Q22 (Additional comments)**: 39

**Why it matters**  
High Q21 volume shows employees want to surface pain points.

**Recommended actions**
- Extract 5–7 key themes from Q21  
- Assign theme owners + SLAs  
- Use Q20 themes to scale best practices  
- Communicate "You said, we did"  
- Segment volumes by Department and Tenure

**Caveats**
- Volume ≠ severity  
- Ensure de-duplication, min-n threshold for quotes

---

## Open-Ended Themes (Q20 vs Q21)

![Open-Ended Themes Analysis](openended_themes_analysis.png)

**Question it answers**  
What do employees praise vs. want to improve?

**How to read it**  
Two panels: left = Q20 (strengths), right = Q21 (improvements). Bar length = theme frequency.

**Key insights**
- **Strengths:** Positive (10), Great (8), Team/Management/Support (4–6)  
- **Improvements:** Training (8), Time (6), Stress/Comm/Process/Balance (2–4)

**Why it matters**  
Shows top positive drivers and main improvement opportunities.

**Recommended actions**
- Build role-based training  
- Tighten prioritization to reduce overload  
- Codify positive team/manager practices  
- Share manager toolkits for communication/process

**Caveats**
- Frequency ≠ impact  
- Validate themes by segment

---

## Open-Ended Response Rate by Department (CY)

![Open-Ended Response Rate by Department](openended_response_rate_by_dept.png)

**Question it answers**  
Which departments write the most comments?

**How to read it**  
Bars = open-ended response rate (%) per department.

**Key insights**
- **R&D:** 2.1% — highest  
- **Corporate:** 1.4%  
- **Engineering:** 1.1%  
- **Sales & Ops:** 0.8% — lowest

**Why it matters**  
Low voice = less context. Ops & Sales may be under-heard.

**Recommended actions**
- Add simple prompts for low-rate groups  
- Manager nudges during team huddles  
- Align reminders to workload cycles  
- Publish short "You said, we did" updates

**Caveats**
- High comment rate ≠ worse experience  
- Apply minimum-n rules for small teams

---

## Open-Ended Sentiment by Job Level (CY)

![Open-Ended Sentiment by Job Level](sentiment_by_job_level.png)

**Question it answers**  
Which job levels write more positive or negative comments?

**How to read it**  
Bar = average sentiment score (higher = more positive).

**Key insights**
- **Executive:** 0.21 (n=57)  
- **Manager:** 0.20 (n=40)  
- **Director:** 0.17 (n=18)  
- **Junior:** 0.12 (n=41) — least positive

**Why it matters**  
Lower sentiment in Junior roles = possible friction.

**Recommended actions**
- Targeted fixes for Junior segment  
- Build toolkits using Executive/Manager tone  
- Highlight "You said, we did" to uplift tone  
- Monitor sentiment trends over time

**Caveats**
- Sentiment is model-dependent  
- Low n increases volatility  
- Use alongside theme & score data

---

## Open-Ended Response Length Analysis (CY)

![Open-Ended Response Length Analysis](response_length_analysis.png)

**Question it answers**  
Which questions generate the longest comments?

**How to read it**  
Bars = Average + Median word count per open-ended item.

**Key insights**
- **Q22:** Avg 11.5, Median 11.0  
- **Q21:** Avg 10.4, Median 10.0  
- **Q20:** Avg 6.2, Median 5.0  
- Short vs long gaps are small → consistent lengths

**Why it matters**  
Longer = more actionable detail. Focus NLP effort here.

**Recommended actions**
- Prioritize Q21/Q22 for theme extraction  
- Add sub-prompts to Q20 to increase value  
- Segment by Dept/Tenure to find short responders  
- Calibrate models to weigh longer comments

**Caveats**
- Length ≠ severity  
- Mobile users & non-native speakers may write shorter text

## Q20 Detailed Word Analysis — Positive Feedback (Things we do great)

![Q20 Detailed Word Analysis](q20_detailed_word_analysis.png)

**Question it answers**  
What words dominate positive comments?

**How to read it**  
Bars = word frequency after basic cleaning.

**Key insights**
- **Top words:** positive (10), work (8), environment (8), great (8), company (8)  
- **Reinforcing:** management (6), culture (6), team (4), support (4)

**Why it matters**  
Highlights strengths worth scaling.

**Recommended actions**
- Document effective team/manager practices  
- Build recognition programs  
- Feature positives in employer branding  
- Tie strengths to business outcomes

**Caveats**
- Word counts are descriptive; filter out noise ("from", etc.)  
- Combine with sentiment/themes for meaning

---

## Q21 Detailed Word Analysis — Improvement Areas (Things not so great)

![Q21 Detailed Word Analysis](q21_detailed_word_analysis.png)

**Question it answers**  
Which words dominate improvement feedback?

**How to read it**  
Bars = frequency of single words in Q21 responses.

**Key insights**
- **Top words:** more (27), staff (27), need (19), increase (16)  
- **Secondary:** benefits (10), activities (10), team (10), systems (8), family (8)

**Why it matters**  
Capacity/staffing is the most visible gap.

**Recommended actions**
- Validate resourcing needs  
- Reduce low-value work  
- Review total rewards and benefit comms  
- Add team-building and flexibility options  
- Close the loop with targeted updates

**Caveats**
- Words ≠ phrases — pair with theme clustering  
- Improve stop-word filtering and lemmatization

---

# ASSUMPTIONS & LIMITATIONS

## Data Scope
- Reflects current wave only (CY)  
- Data is anonymized via Masked ID  
- Demographics joined by Masked ID + SurveyYear

## Survey Design
- Voluntary participation  
- No psychometric weighting or factor analysis  
- Equal treatment of all questions unless benchmarked

## Modeling & Measures
- Scores on 0–100 scale  
- Tenure = time at company (not time in role)  
- Relationships are descriptive, not causal

## Benchmarks
- Assumed comparable in wording, timing, scale  
- Lines shown as point estimates (no confidence intervals)

## Text Analytics
- Light NLP; sarcasm/multilingual can reduce accuracy  
- Some residual stop-word noise present  
- Anonymized; minimum-n rule applies to quotes

## Dashboard Behavior
- Power BI post-aggregation filters  
- Rounded % may not sum to 100  
- Single left-axis scale unless noted

## Operational Considerations
- Dataset is point-in-time  
- Demo version is manually refreshed

## Interpretation Guidelines
- <1.0 pp gaps = noise  
- Triangulate scores + themes + benchmarks + segments  
- Validate with HR and line leaders before rollout

---

# FUTURE OPPORTUNITIES

- **Deeper drivers:** add Key Influencers and Decomposition Trees  
- **Trendlines:** build multi-year tracking, cohort analysis  
- **Text analytics:** move to topic modeling (LDA, BERTopic)  
- **Action register:** embed progress tracking on key themes  
- **Exportable briefings:** auto-generate PPT/PDF  
- **Row-level security:** for department/leader views  
- **Mobile views & accessibility:** high contrast, alt text, keyboard nav  
- **Heatmaps:** add Category × Department, Level × Region  
- **Impact measurement:** pre/post tracking on interventions

---

# RECOMMENDATIONS

- **Enablement:** Remove blockers, set SLA, target +3–4pp  
- **Mid-tenure (3–10 yrs):** Career pathways, check-ins, mentorship  
- **Training:** Launch role-based programs  
- **Workload:** Validate capacity concerns, reduce manual work  
- **Manager effectiveness:** Ship toolkit, coach lower-scoring teams  
- **Scale wins:** Replicate APAC + Leadership practices  
- **Department focus:** Start with Ops & Sales (largest headcount)  
- **Employee voice:** Boost open-ended participation  
- **Pulse surveys:** Run 6–8 weeks post-action  
- **Governance:** Maintain single data model, standard mappings

---

# FILES INCLUDED

- `02_KS_EngagementSurvey_Dataset_Final.xlsx`  
- `dashboardsnapshotEE.png`  
- Visuals:
  - `department_distribution.png`
  - `engagement_by_category.png`
  - `engagement_by_job_level.png`
  - `engagement_by_region.png`
  - `engagement_vs_tenure.png`
  - `openended_response_rate_by_dept.png`
  - `openended_response_volume.png`
  - `openended_themes_analysis.png`
  - `q20_detailed_word_analysis.png`
  - `q21_detailed_word_analysis.png`
  - `response_length_analysis.png`
  - `sentiment_by_job_level.png`
- Model diagram: `ERD_EE.png`

---

# ABOUT THE DATA (ERD)

![Engagement Survey ERD](ERD_EE.png)

**Model summary (Star schema)**  
- Fact: `_response` – one row per respondent × question × year  
- Dimensions:
  - `_employee` – demographics  
  - `_survey` – question metadata

**Relationships**
- `_response (Many)` → `_employee (One)` on Masked ID + Year  
- `_response (Many)` → `_survey (One)` on Qn ID

**Table Dictionary**

- `_response`  
  - Masked ID  
  - Qn ID  
  - Score (0–100)  
  - Open-Ended Answers  
  - SurveyYear  
  - Tag (CY/LY)

- `_employee`  
  - Region, Department, Job Level, Tenure Band  
  - SurveyYear, Tag

- `_survey`  
  - Qn ID  
  - Category  
  - Question text  
  - Industry Benchmark

**Calculated Columns & Measures**
- `Avg Score % = AVERAGE('_response'[Score])/100`  
- YoY delta = CY – LY  
- `Completion Rate = Respondents / Employees (CY)`  
- `Employees CY = DISTINCTCOUNT('_employee'[Masked ID])`  
- `Benchmark = AVERAGE('_survey'[Industry Benchmark])/100`

**Assumptions**
- Score scale = 0–100  
- Text analytics is descriptive  
- Validate low-n segments

---

# DISCLAIMER

This project is for **portfolio and educational display** only.  
No content may be reused without permission.

---

# CONNECT WITH ME

- [LinkedIn](https://linkedin.com/in/desireesalvant)  
- [GitHub](https://github.com/DesireeSalvant)  
- [Portfolio](https://desireesalvant.com)  
- [Tableau Public](https://public.tableau.com/app/profile/desiree.salvant/vizzes)
