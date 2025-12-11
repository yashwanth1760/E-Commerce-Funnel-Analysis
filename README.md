# 📊 E-Commerce Funnel Analysis Dashboard

### **SQL • Python • Power BI**

This project delivers a complete **end-to-end analysis of the e-commerce user journey**, uncovering major funnel drop-offs, conversion drivers, behavioral patterns, and revenue insights. Built using **SQL** for data extraction, **Python** for cleaning and feature engineering, and **Power BI** for dashboarding, this analysis provides **executive-level insights** to improve customer experience and maximize conversions.

> ✔ Designed as a real-world analytics portfolio project
> ✔ Includes 4 Power BI pages: **Overview | Revenue | Performance | Insights**
> ✔ Contains deep funnel diagnostics with actionable recommendations



# 🖼 Dashboard Preview

<img width="1116" height="625" alt="Screenshot (376)" src="https://github.com/user-attachments/assets/6a975e7c-c6ab-4bf5-bcd5-bb5d49a5182d" />


<img width="1118" height="637" alt="Screenshot (377)" src="https://github.com/user-attachments/assets/a53d8df9-87bd-4f22-b793-d051cf16376c" />


<img width="1112" height="619" alt="Screenshot (378)" src="https://github.com/user-attachments/assets/64177c71-d0cc-484e-a3f6-668e81545515" />


<img width="1135" height="651" alt="Screenshot (379)" src="https://github.com/user-attachments/assets/e52903cf-feca-4852-bd3b-da54074c4b0c" />




---

# 🚀 Project Overview

Understanding how users move from **Home → Product → Cart → Checkout → Purchase** is essential for improving conversion rate and revenue.

This project answers:

* Where do users drop off the most?
* Which channels, devices, and regions drive conversions?
* How do revenue and engagement vary across segments?
* What actions will improve funnel efficiency?

The dashboard provides a **complete analytical narrative** with insights, KPIs, and business recommendations.

---

# 📂 Tech Stack

| Component                         | Tools Used                         |
| --------------------------------- | ---------------------------------- |
| **Data Extraction & Analysis **   | SQL                                |
| **Data Cleaning & Analysis**      | Python (Pandas, NumPy) |
| **Data Modeling & Visualization** | Power BI                           |
| **Documentation**                 | GitHub                 |

---

# 📁 Data Pipeline

### **1. SQL – Data Extraction**

* Merged behavior, session, device, traffic, and transactional tables
* Removed bot sessions & duplicates
* Standardized categorical and timestamp fields
* Created aggregated user/session-level tables

### **2. Python – Feature Engineering**

* Null handling, outlier removal
* Conversion of timestamps into day/week/month/hour
* Created advanced behavioral metrics:

  * **session_type** (bounced / browsing / converting)
  * **exit_point**
  * **traffic_quality**
  * **product engagement score**
  * **sequence_length**
  * **page_sequence**

### **3. Power BI –  Dashboarding**

* DAX for:

  * Funnel Conversion Rates
  * Drop-Off %
  * Revenue segmentation
  * Time-based performance
* Slicers: date, region, device, browser, traffic source, user type

---

# 📊 Key KPIs

| KPI                         | Value / Insight         |
| --------------------------- | ----------------------- |
| **Total Sessions Analyzed** | 50,000                  |
| **Overall Conversion Rate** | 8.7%                    |
| **Cart Abandonment**        | 43%                     |
| **Total Revenue**           | ₹9,33,844               |
| **Highest Exit Point**      | Homepage (29,620 exits) |

---

# 🔎 In-Depth Funnel Insights

## **1️⃣ Home → Product Page Drop-off (59%)**

### Insight

A majority of users exit before product engagement, indicating **homepage inefficiency**.

### Why This Happens

* Weak CTAs or banner relevance
* Slow load times
* Poor first-screen layout
* Inconsistent messaging from traffic sources

### Business Impact

Fixing this stage yields the **biggest potential conversion lift**.

---

## **2️⃣ Product Page → Cart Drop-off (62%)**

### Insight

Users show interest but hesitate to commit.

### Possible Reasons

* Lacking or unclear pricing
* Missing reviews or trust indicators
* No urgency (limited stock, countdowns)
* High product variety → decision fatigue

### Recommendation

Enhance product storytelling, add social proof, highlight offers.

---

## **3️⃣ Cart → Checkout Drop-off (~30%)**

### Insight

Users abandon after building intent—this is a **high-value friction point**.

### Causes

* Unexpected fees (shipping, tax)
* Forced login or account creation
* Long multi-step checkout
* Limited payment options

### Recommendation

Enable guest checkout, simplify forms, show full cost early.

---

## **4️⃣ Checkout → Purchase Drop-off (~18%)**

### Insight

Payment-related issues dominate this drop.

### Causes

* OTP delays
* Gateway failures
* Address form issues

### Recommendation

Add auto-fill, retry payment options, UI fixes.

---

## **5️⃣ Traffic Source Performance**

### High-Intent Channels

* **Email, Direct** → highest conversion

### Low-Intent Channels

* **Referral, Display Ads** → lowest conversion

### Action

Shift budget toward high-converting channels.

---

## **6️⃣ Regional Behavior**

* **North America** → highest volume & revenue
* **Europe** → strongest conversion efficiency
* **Asia & South America** → lower engagement; require localization

---

## **7️⃣ Device & Browser Performance**

* **Chrome** → best engagement & conversions
* **Safari & Samsung Internet** → moderate performance
* **Firefox & Opera** → lowest conversions

### Recommendation

Conduct device/browser-level UX audits.

---

## **8️⃣ Exit Points**

* **Homepage exit count: 29,620** → bottleneck

Improving homepage experience can drastically uplift conversions.

---

## **9️⃣ Overall Funnel Efficiency**

### **8.7% Overall Conversion**

The funnel shows **healthy volume but high early-stage leakage**.

Optimizing the homepage and product pages can **double conversions**.

---

# 📈 Power BI Pages

### **1. Overview Page**

Key metrics, traffic segmentation, and user type analysis.

### **2. Revenue Page**

Breakdown of revenue by:

* Region
* Day / Hour
* Device
* User Type
* Campaign

### **3. Performance Page**

Deep funnel insights, browser/device conversion, channel performance.

### **4. Insights Page**

Narrative explanation of:

* Drop-offs
* User behavior patterns
* Traffic efficiency
* ROI opportunities

---

# 📌 Business Recommendations Summary

* Strengthen homepage personalization & CTAs
* Improve product detail clarity and trust signals
* Reduce checkout complexity
* Prioritize high-performing channels
* Fix underperforming devices/browsers
* Implement A/B testing across critical pages

These improvements can increase conversion by **20–40%**.

---

# 🛠 Skills Demonstrated

* Funnel Analytics
* Behavioral Segmentation
* Advanced DAX
* Power BI Storytelling
* SQL
* Python Data Cleaning & Feature Engineering
* Business Insight Generation

---

# 👨‍💻 Author

**Yashwanth Chalamalla**
E-Commerce | Analytics | Power BI | Python | SQL

