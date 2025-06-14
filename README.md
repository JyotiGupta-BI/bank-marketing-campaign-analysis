📊 Bank Marketing Campaign Analysis with Power BI

📌 Project Overview

In this project, I analyzed the **Bank Marketing Dataset** (sourced from Kaggle), which contains data on over 40,000 individuals targeted in a recent marketing campaign conducted by a Portuguese banking institution. The marketing campaign was executed through phone calls, often requiring multiple calls before customers agreed or declined to subscribe to a term deposit.

The main objective of the analysis was to study:
- Customer demographics and audience segmentation
- Campaign performance across different contact strategies and customer groups

**Tools Used:**
- Power BI 
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization & Reporting

---
🔍 Project Breakdown

📂 Dataset Summary

- **Total Records**: 41,188 customers
- **Key Variables**: Age, Job, Marital Status, Education, Contact Type, Number of Contacts, Previous Campaign Outcomes, Subscription Outcome (`y`)

🔎 Analysis Sections

1️⃣ Audience of Campaign

Using DAX and Power BI, I built dashboards to analyze the personal status of the campaign audience:

- Total audience: 41,188 people targeted.
- Age distribution: Majority aged 30–40; most common age: 31 years.
- Marital status: 60% married.
- Education: ~30% had university degrees.
- Job types: Admin, Blue-Collar, and Technician were the top 3.
- Older subscribers: Over 45% of people aged 60+ subscribed.

**Example DAX Measure:**

```see my PBIX file

2️⃣ Performance of Campaign
I created several DAX measures and visual dashboards to analyze the performance of the campaign:

**Overall Campaign Performance:**
- Conversion Rate: ~11% (4,640 subscriptions out of 41,188 people).
- Most subscriptions occurred in May.

**Based on Contact Type:**
- 83% of subscriptions came via cellular contact.
- Conversion rate via cellular: ~15%
- Conversion rate via telephone: ~5%

**Based on Number of Calls Made:**
- Total calls made: 105,754
- ~17% of audience received only 1 call (~18,000 people).


Conversion rate for:

- 1 call: ~13%
- More than 5 calls: ~6%

**Based on Previous Contact:**
86% were never contacted before.

Conversion rate:

- Previous contacts: ~9%
- No previous contacts: ~13%

**Based on Previous Campaign Results:**
- 86% were not part of any previous campaign.
- 65% of people who converted previously also converted again.
- 14% of non-converted customers from previous campaigns converted this time.

📈 Visual Dashboards
The following dashboards were created in Power BI to visualize the findings:

Audience segmentation (age, job, marital status, education)

1.Contact channel performance

2.Call volume and conversion analysis

3.Prior campaign impact analysis

(Dashboard screenshots will be added here once uploaded)

📝 Key Insights

1. Cellular contact was far more effective than telephone.

2. Fewer contact attempts correlated with higher conversion rates.

3. Previous campaign success influenced future conversions.

4. Certain demographic groups (age, marital status, job type) demonstrated higher conversion likelihood.

📊 Conclusion
This Power BI analysis provides useful insights into customer behavior and marketing campaign performance, allowing better audience targeting and more efficient resource allocation for future campaigns.


