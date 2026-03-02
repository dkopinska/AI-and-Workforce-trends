# AI-and-Workforce-trends
# 🌍 Global AI, Workforce & Automation Analysis (2025)
# 📌 Project Overview

This project explores how AI investment, automation, and workforce dynamics interact across countries between 2015–2025, with a focus on 2025 outcomes.

# The goal was to determine whether AI:

Destroys jobs

Creates jobs

Increases productivity

Shifts labour markets toward higher-skilled roles

The dataset used is a synthetic global dataset covering 20 countries over 11 years.

# 🧰 Tools Used

Excel – Data cleaning, validation, correlation matrix, regression analysis

SQL – Aggregations, filtering, transformation

Tableau – Calculated fields, dashboards, visualisations & story

Statistical Methods – Correlation analysis & linear regression

# 🚀 Project Value

This project demonstrates:

End-to-end analytical workflow

Business question framing

Data cleaning & validation

Statistical reasoning

Dashboard storytelling

Economic interpretation of technological change

# 📊 Business Questions
1️⃣ Which countries are most AI-ready in 2025?

Measured using:

AI Readiness Score

AI Policy Index

Productivity Index

2️⃣ Which countries invest the most in:

AI?

Reskilling?

Do they invest more in AI or reskilling?

Reskilling investment was converted from millions to billions USD to allow direct comparison with AI investment.

3️⃣ Are more jobs being created or displaced in 2025?

I created:

Jobs Created / Jobs Displaced Ratio

Log transformation of the ratio (to handle skewed distribution)

After log transformation, values ranged between 1 and 2.6, indicating overall job creation exceeds displacement in most cases.

4️⃣ Does AI destroy jobs?

This was tested using:

Correlation analysis

Regression modelling

Country trend comparisons

# 📈 Key Findings
🔹 1. AI Investment & Economic Outcomes

AI Investment ↔ Job Creation → r = 0.65

AI Investment ↔ Productivity → r = 0.53

# Regression results:

AI Investment explains:

43% of variation in Job Creation

28% of variation in Productivity

14% of variation in Salary differences

Interpretation:

Countries investing more in AI tend to:

Create more jobs

Increase productivity

Strengthen economic output

AI investment had a stronger impact than reskilling investment in regression models.

# 🔹 2. AI Readiness & Governance Matter

AI Readiness ↔ Productivity → r = 0.56

AI Readiness ↔ AI Policy Strength → r = 0.51

# Regression results:

AI Readiness explains:

32% of differences in Productivity

26% of differences in AI Policy Strength

Interpretation:

Technical preparedness, infrastructure, and governance significantly improve economic outcomes from AI.

# 🔹 3. Automation & Labour Market Shifts

Automation ↔ Job Displacement → r = 0.42

Automation ↔ Average Salary → r = 0.49

# Regression results:

Automation explains:

17% of variation in Job Displacement

24% of variation in Salary differences

Interpretation:

Automation:

Replaces some lower-skilled jobs

Increases specialisation

Raises average wages

This pattern aligns with Skill-Biased Technological Change (SBTC) theory.

# 🧠 Conclusion

The results suggest that:

AI is moderately linked to job creation and productivity growth

AI does not simply destroy jobs

Outcomes depend heavily on:

AI readiness

Policy frameworks

Infrastructure

Skill levels

Countries that are technically and structurally prepared experience stronger economic gains.

AI appears to reshape labour markets rather than eliminate them.

# 📌 Recommendations

Countries should:

Continue investing in AI infrastructure

Strengthen technical readiness

Improve governance frameworks

Invest strategically in high-impact skill development

AI adoption should be paired with structural preparation to maximise growth and minimise displacement risk.

# 📊 Tableau Work

In Tableau, I:

Created calculated fields

Converted reskilling investment from millions → billions USD

Created a Jobs Created / Displaced ratio

Applied log transformation for skewed data

Built dashboards and storyboards to answer business questions

Compared country-level trends over time

# 📂 Dataset

Dataset Name: Global AI Workforce Automation 2025
Type: Synthetic dataset
Source: GitHub (synthetic economic simulation dataset)




