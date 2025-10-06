# 🛍️ Limelight vs Competitors Who's Winning Pakistan's Online Fashion Race
## 📘 Project Overview
In today’s digital-first world, **online presence defines market share** — especially in the competitive **retail fashion industry** of Pakistan.  
This project applies the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework to evaluate **Limelight’s digital performance** against key competitors:  
**Nishat Linen, Zellbury, Gul Ahmed,** and **Bonanza Satrangi**.  

The analysis identifies **where Limelight stands**, **how customers interact** with its site, and **which channels drive growth opportunities**.

---

## ⚙️ Framework: CRISP-DM

### 1️⃣ Business Understanding
The fashion retail industry in Pakistan is highly competitive.  
A brand’s digital footprint reflects both its **current reach** and **growth potential**.

**Key Business Questions:**
1. How does Limelight’s website traffic compare to its competitors?  
2. Is Limelight providing a better or worse customer experience?  
3. Which marketing channels drive the most valuable traffic?

**Goal:**  
To identify Limelight’s **strengths, weaknesses, and opportunities** for improvement.

---

### 2️⃣ Data Understanding
**Data Source:** [SimilarWeb](https://www.similarweb.com/) — a trusted platform for tracking online activity.  

**Data Collected:**
- Monthly website visits  
- User engagement metrics (visit duration, pages per visit, bounce rate)  
- Marketing channel distribution (organic search, direct, paid, referrals, etc.)

**Competitors:**
- Nishat Linen  
- Zellbury  
- Gul Ahmed  
- Bonanza Satrangi  

---

### 3️⃣ Data Preparation
The raw data required cleaning and formatting before analysis.

**Tools Used:** `Python`, `Pandas`, `NumPy`  

**Data Cleaning Steps:**
- Standardized metrics (e.g., removed `%` signs, converted K/M to numeric values)  
- Handled missing values  
- Structured competitor data into comparable formats  

This cleaned dataset became the foundation for the analysis.

---

### 4️⃣ Modeling (Analysis)
Comparative analysis was performed to answer the business questions.

#### 🧮 Traffic Comparison
| Brand | Monthly Visits (approx.) |
|--------|--------------------------|
| **Nishat Linen** | 3.7M |
| **Zellbury** | 2.9M |
| **Limelight** | 2.7M |
| **Gul Ahmed** | 1.5M |
| **Bonanza Satrangi** | 0.6M |

**Insights:**  
- Limelight ranks **3rd**, close to Zellbury but behind Nishat Linen.  
- **Global Rank:** 18,475 | **Industry Rank:** 482 | **Country Rank:** 93  

---

#### 🌐 Customer Experience
| Metric | Limelight | Competitor Average | Interpretation |
|---------|------------|--------------------|----------------|
| Visit Duration | 2:27 min | 2:57 min | Slightly lower engagement |
| Pages per Visit | 5.41 | 5.97 | Fewer pages explored |
| Bounce Rate | **20.9%** | **30.2%** | Strong initial attention |

**Insight:**  
Limelight excels at **reducing bounce rate** but needs to **improve engagement time**.

---

#### 📈 Marketing Channel Distribution
**Organic Search → Strength**  
- Limelight dominates with ~1.2M visits (vs competitor avg. ~840K).  
- Indicates strong SEO visibility.

**Direct Traffic → Weakness**  
- Limelight: 654K vs competitor avg. 817K.  
- Suggests weaker **brand recall** and loyalty.

**Other Channels (Paid, Referrals, Display, Email)**  
- Comparable to competitors; no major differentiator.

---

### 5️⃣ Evaluation

**Strengths**
- Strong SEO performance (high organic traffic).  
- Low bounce rate — users stay interested upon arrival.  

**Weaknesses**
- Lower average session duration.  
- Fewer pages per visit → engagement gap.  
- Lower direct traffic → weak brand loyalty.  

**Opportunities**
- Overtake Zellbury in traffic volume.  
- Enhance navigation and content for better engagement.  
- Build loyalty programs to increase returning users.  

---

### 6️⃣ Deployment (Recommendations)
**Strategic Recommendations for Limelight:**
1. **SEO & Promotions:**  
   - Strengthen seasonal campaigns and mobile-first UX to surpass Zellbury.  
2. **User Engagement:**  
   - Improve navigation speed and personalize content to retain visitors.  
3. **Brand Loyalty:**  
   - Launch loyalty programs and brand-building campaigns to convert one-time visitors into repeat customers.

---

## 🧰 Tools & Technologies
- **Python** (Pandas, NumPy)  
- **Excel / CSV** for data handling  
- **SimilarWeb** for data sourcing  
- **Matplotlib / Seaborn (optional)** for visualization  

---

## 📂 Project Structure
📁 Limelight-Digital-Analysis
├── data/
│ ├── raw_data.csv
│ ├── cleaned_data.csv
├── notebooks/
│ ├── data_preparation.ipynb
│ ├── analysis.ipynb
├── visuals/
│ ├── traffic_comparison.png
│ ├── engagement_metrics.png
├── README.md
└── requirements.txt


---

## 📊 Key Takeaways
- Limelight is **competitive but not leading**.  
- With better engagement strategies and brand-building efforts, it can realistically **overtake Zellbury** and challenge **Nishat Linen**.  

---

## 🏁 Final Thoughts
This project demonstrates how applying the **CRISP-DM framework** provides clear business insights from web analytics.  
Limelight’s case shows that **strong SEO visibility isn’t enough** — building loyalty and engagement is equally vital for long-term dominance.

> 🗒️ *Data used in this project is original and authentic, sourced and scraped from SimilarWeb.*

---

### 👩‍💻 Author
**Aqiba Farman**  
Data Analyst | Python • Power BI • SQL • Excel  
[LinkedIn](https://www.linkedin.com/in/aqibafarman) | [GitHub](https://github.com/aqibafarman)

