# Full Bias Audit Report Documentation
🧠 MediMind Group – Bias Audit Report

**👥 Group Members**

- Siyabonga Mahlangu

- Koketso Bambo

- Lindiwe Mkuzangwe

- Georgia Legodi

- Konke Maphisa

- Banele Magubane

**📚 Project Overview**

This project analyzes and mitigates bias in an income prediction AI model. Our goal was to identify disparities across gender and racial groups, implement mitigation strategies, and ensure fair and ethical AI outcomes.

**🔍 Key Deliverables**

**1.📝 Analysis Notebook**

- Complete Python notebook with code, visualizations, and findings

- Includes data cleaning, EDA, baseline and mitigated model evaluations

- Fairness metrics computed: Demographic Parity Difference, Equal Opportunity Difference, Disparate Impact

**2.📊 Presentation Slides**

- 5–7 slides summarizing:

- Key bias patterns discovered

- Mitigation strategies implemented

- Real-world implications

- Recommendations for stakeholders

**3.⚖️ Ethics Statement**

- 500-word analysis connecting findings to broader AI ethics principles

- Covers justice, fairness, accountability, transparency, and non-discrimination

**4.📖 Reference List**

- Relevant fairness research and frameworks, including:

- Barocas et al., 2019 – Fairness and Machine Learning

- Kamiran & Calders, 2012 – Data Preprocessing Techniques

- Hardt et al., 2016 – Equality of Opportunity in Supervised Learning

- Fairlearn & AI Fairness 360 toolkits

**⚡ Key Findings**

**Gender Bias:** Females systematically underpredicted for high-income outcomes (>50K)

**Racial Bias:** Minority racial groups underpredicted compared to White and Asian-Pac-Islander individuals

**Metrics Before Mitigation:**

- Gender Demographic Parity Difference: 0.134

- Racial Parity Difference: 0.300

- Metrics After Mitigation (Reweighing + Threshold Optimization):

- Gender Demographic Parity Difference: 0.044

- Racial Parity Difference: 0.043

- Equalized Odds Differences near zero

- Overall model accuracy remained ~81%

**🛠 Mitigation Strategies Implemented**

- Reweighing – Adjusted training data weights to ensure underrepresented groups were considered fairly

- Threshold Optimization – Customized decision thresholds for sensitive groups to balance true/false positive rates

**🌐 Real-World Implications**

- Without bias mitigation, AI models can perpetuate societal inequalities

- High-stakes decisions like hiring or lending could unfairly disadvantage marginalized groups

- Fair AI ensures equitable opportunities for all demographics

**📌 Recommendations**

- Regular bias audits and fairness monitoring

- Continuous model retraining with updated, balanced data

- Transparency with stakeholders about AI limitations and fairness metrics

- Adoption of fairness toolkits like Fairlearn or AI Fairness 360
