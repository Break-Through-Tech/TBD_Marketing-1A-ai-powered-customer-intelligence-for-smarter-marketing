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
**Challenge Advisor:** Pallavi Sharma, pallavi@witomni.com.  
**AI Studio Coach:** Bhavya Gopal, bhavya.gopal@breakthroughtech.ai.  
**Program:** Break Through Tech AI Studio - Fall 2026  

---

## 🏢 About Witomni
WitOmni is a forward-thinking organization dedicated to helping founder-led companies grow using AI for marketing initiatives from strategy to campaign execution. By leveraging machine learning, the team aims to transform raw transaction history into actionable insights that empower businesses to better understand and serve their unique customer base.

---

## 🎯 The Challenge
### Project Summary
In this project, you will use publicly available e-commerce transaction data and supervised machine learning techniques to build a model that predicts which customers are most likely to become repeat purchasers. This will help our company identify high-value customer segments, prioritize marketing efforts, and develop more effective customer retention strategies.

### Success Criteria
Success will be measured by the team’s ability to:
- Build and compare classification models.
- Evaluate performance using precision, recall, F1-score, and ROC-AUC.
- Identify the customer behaviors that are most predictive of repeat purchasing.
- Translate model results into practical marketing recommendations.
- Clearly explain the model's limitations and assumptions.
  
### Stretch Goals
If the team progresses ahead of schedule, they may:   
• Develop a simple interactive dashboard to visualize customer insights.   
• Build an LLM-powered assistant that generates personalized marketing recommendations for predicted customer segments.   
• Compare additional machine learning algorithms.   

### Project Milestones
Use these milestones to guide your work. Your team will create a GitHub Projects board to track tasks within each milestone.

| Month | Milestone | Key Activities |
|---|---|---|
| September | Business Understanding & Data Exploration | • Understand the business problem and success criteria.<br>• Explore and clean the dataset.<br>• Perform exploratory data analysis and visualization.<br>• Engineer customer-level features (e.g., purchase frequency, recency, average order value). |
| October | Model Development & Selection | • Develop and compare multiple classification models.<br>• Evaluate model performance using appropriate metrics.<br>• Identify the most important features influencing predictions.<br>• Refine the best-performing model. |
| November | Business Insights & Final Delivery | • Translate model results into actionable marketing recommendations.<br>• Develop customer segments/personas based on model outputs.<br>• Prepare a final presentation, technical documentation, and business recommendations.<br>• (Stretch Goal) Use an LLM to generate personalized marketing recommendations based on customer profiles. |

---

## 📊 Dataset
**Name and Source:** Online Retail Dataset (Publicly available)  
**Format:** CSV / Structured tabular data  
**Size:** under 1gb  
**Location:** https://archive.ics.uci.edu/dataset/352/online+retail

### Key Details
- This is a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

### Key Variables
- `InvoiceNo`: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- `StockCode`: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- `Description`: Product (item) name. Nominal.
- `Quantity`: The quantities of each product (item) per transaction. Numeric.
- `InvoiceDate`: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- `UnitPrice`: Unit price. Numeric, Product price per unit in sterling.
- `CustomerID`: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- `Country`: Country name. Nominal, the name of the country where each customer resides.
  
---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification (Primary), Clustering, Generative AI (Stretch)

**Recommended Libraries:**
- pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, shap

**Evaluation Metrics:**
- Accuracy (be wary of class imbalance), Precision/Recall, F1-Score, ROC-AUC, Confusion Matrix
  
---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- Original Dataset Paper
Chen, D., Sain, S. L., & Guo, K. (2012). [Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining.](https://www.semanticscholar.org/paper/Data-mining-for-the-online-retail-industry%3A-A-case-Chen-Sain/e43a5a90fa33d419df42e485099f8f08badf2149)
- Kumar, N. (2025). [Intelligent customer segmentation: unveiling consumer patterns with machine learning](https://link.springer.com/article/10.1007/s43995-025-00180-7)
- S. Arefin et al. (2024), [Retail Industry Analytics: Unraveling Consumer Behavior through RFM Segmentation and Machine Learning](https://ieeexplore.ieee.org/document/10609927) 

**Code Examples:**
- https://github.com/MinoshPerera/Online-Retail-RFM-Customer-Segmentation


*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* Your team's channel within Break Through Tech’s Discord space
* Email: pallavi@witomni.com; please copy your teammates and AI Studio Coach 
* Request a team check-in on Zoom: Please use calendly but ideal to reach out to me via email first. CALENDLY: https://calendly.com/pallavi-witomni/discovery-call-ai-marketing
* Note: I will aim to respond within 48 hours. Please reach out to your AI Studio Coach with urgent questions.

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I’m excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session C). 
