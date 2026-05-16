# E-Commerce Sales & Advertising Optimization Analytics

## 📌 Project Overview
This repository delivers a data-driven analytics suite focused on evaluating net sales trends, optimizing product pricing models via price elasticity modeling, and mitigating digital advertising budget leaks. The analysis is tailored for an eco-friendly fast-moving consumer goods (FMCG) brand.

By leveraging advanced statistical computing, programmatic advertising audits, and transformer-based Natural Language Processing (NLP), this project aims to systematically boost product profitability, optimize keyword-level ad spend, and drive localized regional growth.

---

## 🚀 Key Features & Analytics Breakdown

### 1. Financial & Profitability Proxy Modeling
* **Automated Keyword Tagging:** Engineered an NLP text-classification pipeline using **Microsoft's RoBERTa model** to achieve high-accuracy, one-shot classification of over 4,800 unstructured ad-campaign keywords into 14 distinct product subcategories.
* **Profitability Mapping:** Modeled Cost of Goods Sold (COGS) to calculate precise net profit margins, allowing for strategic ranking of subcategories from most to least profitable.
* **Margin Insights:** Uncovered that *Paper Towels* generated the highest financial return ($\approx ₹81.5\text{M}$ profit) while identifying critical operational deficits in *Bathroom Cleaners* and *Facial Tissues*.

### 2. Competitive Pricing & Price Elasticity Analysis
* **Volume Correlation:** Evaluated log-scaled historical pricing data against unit volumes to map how lower pricing points correspond directly to higher consumer volume across household SKUs.
* **Price Elasticity of Demand (PED):** Computed month-over-month price elasticity metrics at the category level across the product catalog using logarithmic regression.
* **Competitor Benchmarking:** Conducted a granular market audit against a dominant e-commerce house brand to isolate specific pricing gaps.
* **Strategic Execution:** Developed a plan to implement a targeted 10% price reduction during high-sensitivity months (where elasticity peaked between $-6$ and $-7$) to catalyze an expected **30% to 40% surge in sales volume**.

### 3. Programmatic Advertising ROI Optimization (Budget Leak Auditing)
* **Conversion Rate Auditing:** Screened historic campaign performance data using a strict 3% Conversion Rate (CVR) floor benchmark to isolate active budget drains.
* **Inefficient Spend Mitigation:** Discovered a major **$₹55.9\text{M}+$ waste metric** stemming from 697 high-spend keywords performing poorly at an unsustainable Return on Ad Spend ($\text{ROAS} < 2$).
* **Brand Equity Impact:** Uncovered a strong correlation between brand-intent keywords and positive campaign metrics. Isolated over 200 high-performing keywords ($\text{ROAS} > 4$) containing explicit brand terms, prompting a recommendation to re-allocate budget away from inefficient broad phrases.

### 4. Regional Growth & Portfolio Streamlining
* **Geographic Distribution Analysis:** Mapped regional sales data, exposing a heavily skewed revenue dependency on 3 core high-performing states.
* **Market Expansion Strategy:** Proposed a replication model targeted at highly populous, under-penetrated regional zones utilizing localized marketing frameworks and influencer networks.
* **Portfolio Rationalization:** Conducted lifecycle evaluations on underperforming SKUs (such as *Dryer Sheets*), providing a quantitative framework to halt stagnant manufacturing streams and pivot capital allocation to top-performing margins.

---

## 🛠️ Tech Stack & Methodology

* **NLP / Machine Learning:** Microsoft RoBERTa (one-shot transformer pipeline for keyword classification).
* **Data Analysis & Modeling:** Python (`pandas`, `numpy`, `scipy` for Price Elasticity calculations).
* **Data Visualization:** `matplotlib` & `seaborn` (Log-scaled scatter plots, temporal bar trends, and regional sales maps).
* **Business Frameworks:** Cost of Goods Sold (COGS) Proxy Modeling, Competitive Matrix Auditing, Conversion Funnel Optimization.

---

## 📈 Impact Summary

* **Deficit Prevention:** Isolated over **$₹55.9\text{M}$** in inefficient ad spend for immediate campaign mitigation and pausing.
* **Volume Uplift Strategy:** Outlined clear paths for a **30%–40% volume lift** in core high-volume categories without structural margin degradation.
* **Portfolio Rationalization:** Validated structural capital pivots away from zero-growth products to scale high-velocity, high-margin categories.
