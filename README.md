# Streaming Service Customer Retention Analysis  

This project analyzes customer churn and retention behavior for a streaming platform using survival analysis techniques. The objective is to identify key behavioral and promotional factors that influence subscription renewal and determine when customers are most likely to discontinue their service.

---

## Project Objective  

Customer retention is a critical challenge for subscription-based streaming platforms. This project aims to:

- Understand how customer engagement patterns impact renewal decisions  
- Evaluate whether promotional acquisition strategies such as coupons and trial offers improve long-term retention  
- Identify high-risk churn segments and provide actionable business recommendations  

The analysis focuses on modeling the time until customer non-renewal using streaming hours as the lifecycle measure.

---

## Methodology  

This study applies advanced survival analysis techniques commonly used in customer analytics and retention modeling.

The following statistical approaches were used:

- Kaplan–Meier Survival Analysis  
- Cox Proportional Hazards Model  
- Log-rank hypothesis testing  
- Behavioral segmentation based on engagement thresholds  

Streaming hours were treated as the time variable, while non-renewal was modeled as the event of interest.

---

## Key Insights  

The analysis produced several important findings:

- Consistent weekly viewing significantly reduces the probability of customer churn.  
- Customers who registered during the pandemic period exhibited higher non-renewal risk.  
- Heavy users (customers streaming more than 1000 hours) demonstrated substantially stronger retention.  
- Promotional incentives such as coupon codes and trial offers did not significantly improve long-term retention outcomes.  
- Viewing behavior patterns, particularly engagement frequency, were stronger predictors of renewal than acquisition channel.  

These findings suggest that sustained engagement plays a more critical role in retention than initial promotional discounts.

---

## Business Implications  

The results indicate that streaming platforms should prioritize engagement-driven retention strategies rather than relying primarily on promotional acquisition incentives.

Recommended strategic actions include:

- Encouraging habitual weekly viewing through personalized recommendations  
- Designing onboarding experiences that help users quickly discover relevant content  
- Monitoring customers acquired through trial programs for early churn signals  
- Promoting content completion rather than casual browsing behavior  
- Implementing milestone-based retention interventions for high-engagement users  

---

## Tools & Technologies  

- R Programming  
- survival package  
- survminer  
- dplyr  
- Statistical survival modeling  
- Customer retention analytics  

---

## 📁 Project Structure  

Streaming-Service-Retention-Analysis  
│  
├── StreamingServiceSurvivalDataset.xlsx  
├── Streaming Service Customer Retention Analysis.pdf  
├── survival_analysis.R  
└── README.md  

---

## 📈 Model Performance  

The Cox proportional hazards model demonstrated statistically significant explanatory power with a concordance index of approximately 0.637, indicating moderate predictive performance in identifying churn risk patterns.

---

## ⚠️ Limitations  

This analysis is based on observational academic data and does not establish causal relationships. Promotional targeting strategies and additional behavioral variables may further influence retention dynamics. Future analyses may incorporate subscription tenure, content genre preferences, or real-time engagement signals.

---

## 👩‍💻 Author  

**Kanan Sharma**  
MS Business Analytics  

---

## 📌 Note  

This dataset is a synthetic academic dataset used for educational purposes in survival analysis and customer retention modeling.
