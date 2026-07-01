# Python Business Insights

This section presents advanced business insights generated using Python following ETL, exploratory data analysis (EDA), feature engineering, and analytical visualization. These analyses complement the interactive Power BI dashboard by providing deeper financial and operational perspectives on hospital performance.

---

# 1. Hospital Cost Component Breakdown

<p align="center">
  <img src="visuals/Cost Component Breakdown.png" width="900">
</p>

## Key Insights

The hospital's financial structure is heavily dominated by insurance coverage, which contributes the largest share of total monetary flow. This indicates that the organization is highly dependent on third-party reimbursement systems rather than direct patient payments. While this strengthens patient affordability and treatment accessibility, it also exposes the hospital to reimbursement delays and payer dependency risks.

Surgery costs form the second-largest component, highlighting that surgical and procedural services are major revenue-generating activities. This suggests the hospital operates with a strong focus on treatment-intensive and specialty-care services requiring advanced infrastructure and specialized clinical expertise.

Room costs also contribute significantly, indicating strong inpatient utilization and effective use of hospital infrastructure. Longer admissions and intensive care services are likely major contributors to this revenue stream.

Supportive services such as rehabilitation, nutrition, diagnostics, and psychological care account for comparatively smaller proportions of overall costs, suggesting that core clinical procedures remain the hospital's primary financial drivers.

## Recommendations

- Improve insurance claim-cycle efficiency to reduce reimbursement delays.
- Continue investing in high-performing surgical specialties.
- Optimize bed management and room turnover.
- Expand rehabilitation and post-treatment services to diversify revenue.

---

# 2. Revenue Contribution by Patient Segment

<p align="center">
  <img src="visuals/Revenue Contribution by Patient Segment.png" width="900">
</p>

## Key Insights

The segmentation analysis shows that premium-value patients contribute a disproportionately large share of hospital revenue. Although encounter volumes remain relatively balanced across segments, average revenue increases substantially from low-value to premium-value patients.

Higher-value patient groups are likely associated with advanced procedures, critical care, complex treatments, and extended hospital stays, all of which require greater clinical resources and infrastructure.

The increasing average length of stay across revenue segments further suggests that higher financial returns are closely linked to greater operational complexity.

## Recommendations

- Expand premium specialty-care services.
- Strengthen referral programs for high-value treatment pathways.
- Improve operational efficiency for low- and medium-value encounters.
- Allocate resources according to patient segment profitability.

---

# 3. Monthly Revenue Trend

<p align="center">
  <img src="visuals/Monthly Revenue Trend.png" width="900">
</p>

## Key Insights

Revenue remains relatively stable throughout the year, indicating consistent operational performance. However, monthly fluctuations suggest seasonal variation in patient demand, treatment scheduling, or disease prevalence.

March represents one of the strongest-performing periods, while lower-performing months may reflect reduced admissions or seasonal slowdowns. Despite these fluctuations, the hospital consistently recovers, demonstrating operational resilience.

## Recommendations

- Analyze high-performing months to identify repeatable success factors.
- Improve demand forecasting and capacity planning.
- Increase outreach initiatives during historically weaker periods.
- Develop flexible staffing strategies for seasonal demand.

---

# 4. Pareto Analysis of Hospital Revenue

<p align="center">
  <img src="visuals/Pareto Analysis.png" width="900">
</p>

## Key Insights

The Pareto analysis demonstrates that a relatively small proportion of patient encounters generates the majority of hospital revenue. This reflects the significant contribution of specialized procedures, complex treatments, and intensive-care services.

The steep cumulative revenue curve highlights the organization's reliance on premium-value clinical services for financial performance.

## Recommendations

- Continue investing in high-value specialties.
- Protect key revenue-generating service lines.
- Diversify revenue sources to reduce concentration risk.
- Monitor dependence on premium treatment categories.

---

# 5. Disease Strategic Portfolio Matrix

<p align="center">
  <img src="visuals/Disease Strategic Portfolio Matrix.png" width="900">
</p>

## Key Insights

The portfolio matrix distinguishes between disease categories that drive patient volume and those that generate higher revenue. High-volume diseases contribute significantly to operational workload, whereas lower-volume specialty conditions contribute disproportionately to profitability.

This visualization supports strategic decisions regarding service expansion, clinical prioritization, and resource allocation.

## Recommendations

- Invest in high-margin specialty-care services.
- Improve efficiency for high-volume disease categories.
- Prioritize staffing and infrastructure based on profitability.
- Develop disease-specific operational strategies.

---

# 6. Average Revenue by Stay Duration

<p align="center">
  <img src="visuals/Average Revenue by Stay Duration.png" width="900">
</p>

## Key Insights

Revenue generally increases with longer hospital stays, reflecting greater resource utilization associated with complex treatments, intensive monitoring, and multidisciplinary care.

Short- and medium-duration admissions continue to contribute substantially to overall revenue, indicating efficient patient throughput for many treatment pathways.

Extended stays, while financially valuable, also consume significant hospital resources and capacity.

## Recommendations

- Improve discharge planning.
- Identify patients at risk of prolonged hospitalization.
- Strengthen transitional care programs.
- Optimize ICU and specialty-bed utilization.

---

# 7. Revenue Concentration Heatmap

<p align="center">
  <img src="visuals/Revenue Concentration Heat Map.png" width="900">
</p>

## Key Insights

The heatmap demonstrates that premium-value patient segments consistently generate higher revenue across multiple disease categories. Certain diagnoses exhibit significantly stronger revenue concentration than others, highlighting areas of strategic financial importance.

The visualization helps identify combinations of disease type and patient segment that contribute the greatest financial value.

## Recommendations

- Expand services in high-performing disease categories.
- Strengthen advanced treatment pathways.
- Monitor dependence on limited revenue sources.
- Prioritize investments in specialist expertise and clinical infrastructure.

---

# 8. Month-on-Month Revenue Growth

<p align="center">
  <img src="visuals/Month-on-Month Revenue Growth.png" width="900">
</p>

## Key Insights

Revenue growth varies throughout the year, reflecting fluctuations in patient demand, treatment volumes, and operational activity. Periods of strong growth are followed by temporary declines, although overall performance remains resilient.

Understanding these patterns supports improved financial planning, staffing decisions, and operational forecasting.

## Recommendations

- Enhance revenue forecasting models.
- Investigate periods of negative growth.
- Improve seasonal workforce planning.
- Diversify clinical services to reduce revenue volatility.

---

# 9. Hospital Metrics Correlation Heatmap

<p align="center">
  <img src="visuals/Hospital Metrics Correlation Heatmap.png" width="900">
</p>

## Key Insights

The correlation heatmap identifies strong relationships between operational and financial variables. Cost components such as surgery, room utilization, diagnostics, and insurance coverage exhibit meaningful associations, indicating shared drivers of hospital expenditure.

Length of stay also demonstrates a positive relationship with treatment costs, reinforcing its role as a major determinant of resource utilization and financial intensity.

These relationships provide valuable inputs for predictive analytics and strategic planning.

## Recommendations

- Develop predictive models using correlated variables.
- Monitor key cost drivers proactively.
- Support budgeting and resource planning through correlation analysis.
- Leverage identified relationships for operational optimization.
