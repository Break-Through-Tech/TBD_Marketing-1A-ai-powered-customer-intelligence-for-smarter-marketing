---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff and CAs only — remove before sharing with students)*

### Technical Vetting
| Check | Status | Notes |
| :--- | :--- | :--- |
| Python Compatibility | 🟢 | The project is centered on Python, utilizing it as the primary language for machine learning techniques and data manipulation. |
| Data Readiness | 🟢 | The dataset is publicly available and under 1GB, indicating it is likely to be usable without excessive cleaning. |
| Resource Check | 🟢 | The project utilizes free-tier tools like Google Colab, ensuring all resources are accessible to students. |

### Internal Scores
- **Student Fit Score:** 9/10
- **Technical Depth Score:** 7/10
- **Overall Recommendation:** APPROVE

### Advisor Feedback Draft
The project demonstrates strong applicability to real-world marketing challenges, offering a clear business insight model. Consider enhancing data preparation scope to account for outlier handling and ensuring feature engineering has quantifiable steps. Additionally, balance the model evaluation metrics with business implications to better align performance with marketing goals.

---

# AI-Powered Customer Intelligence for Smarter Marketing

**Company / Org:** Witomni  
**Challenge Advisor:** Pallavi Sharma, pallavi@witomni.com  
**Program:** Break Through Tech AI Studio - Fall 2026  

---

## 🏢 About Witomni
Witomni is a forward-thinking organization dedicated to optimizing marketing performance through advanced data analytics and predictive intelligence. By leveraging machine learning, the team aims to transform raw transaction history into actionable insights that empower businesses to better understand and serve their unique customer base.

---

## 🎯 The Challenge
### Project Summary
The team will develop a classification model using ecommerce transaction data to predict future customer purchase behavior, specifically identifying potential repeat purchasers. By integrating supervised machine learning techniques and exploratory data analysis, the project aims to help Witomni prioritize high-value segments and refine retention strategies.

### Success Criteria
The model will be evaluated using precision, recall, F1-score, and ROC-AUC. Success also includes the team's ability to explain model predictions and translate insights into practical marketing recommendations that improve customer engagement and retention.

### Project Milestones
Use these milestones to guide your work. Your team will create a GitHub Projects board to track tasks within each milestone.
| Month | Milestone | Key Activities |
| :--- | :--- | :--- |
| September | Data Processing, EDA & Feature Engineering | • Ingest and clean the Online Retail dataset (handling negative quantities, missing Customer IDs, and canceled transactions).<br>• Aggregate transactional data at the customer level to engineer Recency, Frequency, and Monetary (RFM) metrics.<br>• Perform Exploratory Data Analysis (EDA) on customer purchasing patterns, order distributions, and revenue drivers.<br>• Establish baseline metrics and create cross-validation splits for downstream modeling. |
| October | Customer Segmentation & Predictive Modeling | • Apply unsupervised clustering (K-Means, Hierarchical Clustering, or Gaussian Mixture Models) on RFM features to define distinct customer personas.<br>• Train supervised classification models (Logistic Regression, Random Forest, XGBoost) to predict repeat purchase probability and churn risk.<br>• Evaluate model performance using Precision, Recall, F1-Score, and ROC-AUC.<br>• Fine-tune hyperparameters and address class imbalance. |
| November / December | Explainability, Marketing Strategy & Interactive UI | • Integrate model interpretability using SHAP values to identify key behavioral triggers driving repeat purchases.<br>• Translate segment profiles into actionable marketing strategies and campaign recommendations.<br>• Build an interactive Streamlit application to display customer risk scoring, segment distributions, and purchase predictions.<br>• Finalize project documentation, reproducible GitHub repository, and executive pitch deck. |

### Stretch Goals
* **Customer Lifetime Value (CLV) Modeling:** Implement probabilistic models (such as BG/NBD and Gamma-Gamma) to forecast future transactional value per customer segment.
* **Market Basket Analysis & Next-Best-Action Recommender:** Apply association rule mining (Apriori / FP-Growth) or collaborative filtering to generate personalized product recommendations for targeted customer segments.
* **Interactive Campaign Simulator:** Build a scenario-testing widget within the Streamlit UI to estimate ROI and revenue lift based on targeted marketing interventions.
> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset
**Name and Source:** Online Retail Dataset (Publicly available)  
**Format:** CSV / Structured tabular data  
**Size:** under 1gb  
**Location:** Accessible via standard data repositories like UCI Machine Learning Repository or Kaggle.

### Key Details
- Publicly available ecommerce transaction data (Online Retail dataset) containing numerical and categorical information. Features include purchase frequency, recency, and average order value.
- Data requires normalization of currency values, handling of return transaction records, and feature creation for "time since last purchase" to define target labels.

---

## 🛠️ Suggested Approach
**ML Problem Type:** Classification  
**Recommended Libraries:**
- Python (Pandas, Scikit-Learn, XGBoost/LightGBM)
- Google Colab
- Large Language Models (LLMs) / Generative AI (for persona generation)
- Excel (for initial data investigation)
**Evaluation Metrics:** Precision, Recall, F1-Score, and ROC-AUC to ensure a balance between predictive accuracy and business utility.

---

## 📚 Resources to Get Started
The following resources will help your team understand the problem space and potential technical approaches for this project:
**Background Reading:**
- Introduction to Recency, Frequency, Monetary (RFM) segmentation models for ecommerce.
**Technical Tutorials:**
- Scikit-Learn documentation on binary classification workflows and feature transformation pipelines.
**Code Examples:**
- Sample Jupyter Notebooks demonstrating RFM analysis and supervised learning pipelines for customer churn/retention prediction.

---

## 🤝 How We'll Work Together
**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack/Email workspace provided by Witomni  
**Response time:** Within 48 hours during standard business days  
**Recommended Tools:**
- **Coding:** Google Colab Free Tier  
- **Collaboration:** GitHub, Notion  
- **Virtual Meetings:** Zoom, Google Meet  

---

## 🚀 Getting Started
1. **Review this overview document** and note any questions for our first meeting.
2. **Begin reviewing the dataset** using the link provided in the Dataset section.
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects).

I'm excited to work with you!

---

## ❓ Questions?
Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).
