## ABOUT ME

I'm Adebayo Michael. I started in health operations, Where data is never clean. Now i write SQL, build Power BI dashboards, and unpivot messy Excel exports until they answer one question: What should we actually do differently? Currently learning Python to do more of that, faster.


## WHAT I DO

I take raw, messy data (Excel exports, SQL dumps, CSV chaos) and turn it into something a manager can actually use to make a decision, usually a dashboard or a one-page report.

##  🚀 MY PROJECTS


*A curated selection of business intelligence and data analytics case studies demonstrating end-to-end data pipelines, predictive insights, and interactive dashboards.*

---



### 1. Clinical Survival Predictor: Tumor Analysis & Patient Outcome Prediction
Using Python to predict patient outcomes from tumor data with 87.7% accuracy.

* **The Challenge:** A clinic needed a way to screen tumor cases and predict whether a tumor was malignant or benign based on physical traits. The goal was to build an interpretable model that doctors could trust.

* **What I Did:** Cleaned the clinical data using Pandas, checked for missing values, and grouped patients by outcome to compare physical traits (radius, perimeter, texture). Ran a correlation analysis to find which features mattered most. Then trained a Logistic Regression model, standardized the features, and tested it on 114 unseen cases.

* **The Results:** The model achieved 87.7% accuracy. It correctly identified 38 malignant cases and 62 benign cases. Only missed 4 serious cases out of 114 — critical in healthcare, where missing a malignant case is the most dangerous error.

* **Tech Stack:** Python | Pandas | Matplotlib | Seaborn

* **What I'd Add Next:** Experiment with other classifiers like Random Forest or XGBoost to see if accuracy can be pushed above 90%. Also add SHAP explanations to show exactly which tumor traits drive each prediction.

<p align="center">
  <img src="Heatmap chart.png" width="80%">
</p>


**[View Project Repository](https://github.com/Olumola-6/Clinical_Survival_Predictor)** | **[Heatmap Preview](Heatmap chart.png)**




### 🏥 2. HealthPulse: Patient Appointment & Operational Analytics
**Reducing no-shows at a busy clinic: how I found a 15% revenue leak in appointment data.**

* **The Challenge:** A clinic had no way to predict which patients would skip appointments. I was given 4 years of raw appointment logs with messy date formats, missing zip codes, and no clear “no-show” flag.

* **what i did:** Cleaned the data in Power Query, created a no-show flag by comparing appointment vs. check-in timestamps, then built a dashboard showing no-show rates by doctor, clinic and appointment time, and day of week..

* **The Impact:** Showed that a certain doctor, appointment date and clinic locations were linked to high no-show rates for appointments. The clinic adjusted scheduling intervals for doctors and added a text reminder for weekend apointments. Estimated 15% revenue recovery.

* **Tech Stack:** `Excel` | `Power BI` | `Data Modeling` | `DAX`



<p align="center">
  <img src="HealthPulse Patient Appointment & No-Show Analysis.png" width="80%">
</p>

👉 **[View Project Repository](https://github.com/Olumola-6/HealthPulse-Data-Analysis)** | **[Dashboard Preview](HealthPulse Patient Appointment & No-Show Analysis.png)**
---

### 🎬 3. Sakila Entertainment: Video Rental Business Intelligencew
**Joining 5 tables across 15,000+ rental records: Finding top revenue generators and which film categories lose money from late returns .**

* **What I actually did:** Wrote 3 SQL queries joining payment → rental → inventory → film → category tables. Used `DATEDIFF` and `CASE` WHEN to flag late returns (comparing actual vs allowed rental duration). Built a Power BI dashboard showing: (1) Sports & Sci-Fi drive revenue, (2) Action films have highest late rates, (3) top 10 countries by customer spend.

* **Results** Recommended shorter rental periods for high-demand categories to free up inventory. Top revenue countries include some without physical stores, targeted marketing could acquire more customers without new locations.

* **Tech Stack:** `SQL` | `Power BI` | `Business Intelligence`

* **what i'd add next time**
  Instead of excluding `NULL return_date` entirely, i'd keep them as "not yet returned" and create a third category: **Outstanding rentals**. This would show real-time inventory pressure, not just historial late patterns.



<p align="center">
  <img src="Sakila Rental Analysis.png" width="80%" alt="Sakila Project Preview">
</p>

👉 **[View Project Repository](https://github.com/Olumola-6/Sakila-DVD-Rental-Business-Analysis)** | **[Dashboard Preview](Sakila Rental Analysis.png)**

---

### 🌍 4. World Health Efficiency & ROI Analysis
**Unpivoting 9 years of WHO data to find countries that gets the most life expectancy per dollar.**

* **What i did:** Original data was wide (years as columns). Used Power Query to unpivot into panel format (Country, Year, Life Expectancy, Health Spend). Created DAX measure: Efficiency = (Life Expectancy / Spend) * 1000. Built scatter plot with year play axis.
* **The Results:** Found diminishing returns after ~$3k/capita. Somalia & Madagascar are "efficiency leaders" (high outcomes at low spend) and stayed consistent compared to Efficiency losers (USA and Liechtenstein).

* **Tech Stack:** `Power Query` | `Power BI` | `Excel` | `DAX`

* **what i'd add next time**
  Add inflation adjustments to health expenditure (2015 dollars vs 2023 dollars aren't comparable). Also pull GDP per capita as a third variable to seperate "Wealth Effect" from "Policy Effect".



<p align="center">
  <img src="World Health ROI analysis.png" width="80%">
</p>

👉 **[View Project Repository](https://github.com/Olumola-6/Global-Health-Efficiency-Analysis)** | **[Dashboard Preview](World Health ROI analysis.png)**

---



## 🤝 CONNECT WITH ME

*Open for data analytics roles, project collaborations, or just talking about messy data problems. Find me here*

<p align="left">
  <a href="https://www.linkedin.com/in/adebayo-michael-analyst" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/Olumola-6" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
  </a>
  <a href="mailto:micolad001@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge"/>
  </a>
</p>


### 🎯 Currently focused on:
* 📊 Learning Python (Pandas + matplotlib) to move beyond SQL/Excel.
* 📈 Adding one real-world dataset per week to my portfolio. Not tutorial data.
* 🎓 Practicing explaining technical decisions in plain English (harder than SQL).


## WHAT I'M LOOKING FOR?
 **Looking for:** Junior data analyst or BI aanalyst roles where i can work with real messy data, not just cleaned datasets. Open to health, operations or retail domains.
