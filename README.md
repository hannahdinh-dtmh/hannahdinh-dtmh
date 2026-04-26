# Hi, I'm Hannah 👋

**Data Analyst | Business Analyst | Python · SQL · Streamlit · ML Segmentation**

> Turning messy data into clear decisions — through dashboards, analytics, and applied machine learning.

---

## 🚀 About Me

I'm an data & business analyst with a passion for building tools that make data accessible and decisions smarter. My work sits at the intersection of **business analytics, customer insights, and ethical AI** — I care not just about what the model says, but what it *means* for the business.

- 🔭 **Currently building:** CPG sales analytics dashboards, cross-platform price intelligence tools, and customer segmentation models
- 🧠 **Research interests:** AI/ML for segmentation, multi-sided platform (marketplace), dynamic pricing, design science methodology, and responsible AI practices
- 💬 **Ask me about:** Python, Streamlit, e-commerce analytics, CPG sales effectiveness, clustering algorithms, Amazon & eBay market intelligence
- 🌱 **Always learning:** Advanced SQL, ML model evaluation, and French 🇫🇷

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

**Data & Scraping**

![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=flat&logo=python&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=flat&logo=python&logoColor=white)
![ScraperAPI](https://img.shields.io/badge/ScraperAPI-00C853?style=flat&logo=python&logoColor=white)

---

## 📌 Featured Projects

### 🛒 eBay Product Analytics Dashboard
**[Live App →](https://ebay-appuct-analytics-dashboard-hannahd-dtmh.streamlit.app/)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/ebay-product-analytics-dashboard--README/tree/main)** &nbsp;|&nbsp; `Python` `Streamlit` `Web Scraping` `Plotly`

An end-to-end data pipeline that scrapes live eBay product listings and transforms them into an interactive business intelligence dashboard — giving sellers and analysts instant visibility into pricing trends, category performance, and market dynamics.

**What it does:**
- Real-time product data scraping from eBay with structured parsing
- Interactive filters by category, price range, and seller rating
- Visual analytics for pricing trends and product distribution across segments

**Answer Business Questions:**
- What does this marketplace look like at a glance?
- How do products compare within and across families?
- Which products sellers specialize in?

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

> ⚙️ **Technical approach:** Data was collected via web scraping using `requests` and `BeautifulSoup`, structured into a clean Pandas DataFrame, and visualized with Plotly charts embedded in a Streamlit app.
>
> 🔍 **Key challenges:** Handling inconsistent HTML structure across eBay product pages required robust parsing logic and defensive error handling to avoid data gaps.
>
> 💡 **Key insight:** Price distribution varied significantly by category and seller rating tier, suggesting that seller reputation is a stronger price signal than category alone in some segments.

</details>

---

### 🚚 Olist Customer Analytics
**[Live App →](https://olist-customer-analytics-hannahd-dtmh.streamlit.app/)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/olist-customer-analytics-README/tree/main)** &nbsp;|&nbsp; `Python` `Pandas` `Plotly` `Streamlit`

A customer and logistics analytics project built on the Olist Brazilian e-commerce dataset, surfacing insights into delivery performance, customer satisfaction, and seller reliability across categories.

**What it does:**
- Delivery time breakdown by product category and seller tier
- Performance trend analysis with interactive visual summaries
- On-time vs. delayed shipment pattern detection
- Clean, shareable visualizations built with Pandas and Plotly

**Answer Business Questions:**
- Given this e-commerce customer journey from product discovery → purchase → delivery → retention, what's the insight into delivery-churn on top of RFM (Recency-Frequency-Monetary)?
- Which seller segments and product categories drive the most delivery failures — giving operations and supply chain teams a clear prioritization framework.

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

> ⚙️ **Technical approach:** Exploratory analysis on a multi-table relational dataset with joins across orders, sellers, products, and reviews. Aggregations were used to surface trends at the category and seller level.
>
> 🔍 **Key challenges:** The dataset had non-trivial missing values and inconsistent datetime formats that needed careful preprocessing before any delivery-time calculations could be trusted.
>
> 💡 **Key insight:** Delivery delay rates were disproportionately concentrated in a small subset of seller-category combinations — a classic long-tail distribution that suggests targeted interventions could yield outsized improvements.

</details>

---

### 🔍 Amazon Personal Care — Share of Voice Dashboard
**[Live App →](App is private for now, check README file instead)(https://amazon-beauty-sov-fxq4ak7l4urq4dwpftga5y.streamlit.app)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/amazon-beauty-sov-README/tree/main)** &nbsp;|&nbsp; `Python` `Streamlit` `ScraperAPI` `BeautifulSoup` `Plotly`

A live Amazon.com scraper and 4-tab Streamlit dashboard tracking brand visibility across 12 personal care search keywords — measuring organic vs. sponsored share of voice, price positioning, and category-level competitive dynamics.

**What it does:**
- Scrapes top 40 results per keyword (480 listings) from Amazon.com using ScraperAPI
- Calculates **Share of Voice** per brand across the top 20 organic positions
- Separates sponsored from organic placement to surface paid-dependency patterns
- Compares average prices by brand, keyword, and sponsored vs. organic status

**Answer Business Questions:**
- Which brands dominate Amazon search organically — without relying on paid ads?
- Which brands are buying visibility they can't sustain organically?
- Where is the price vs. search position sweet spot for new product launches?

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

> ⚙️ **Technical approach:** ScraperAPI handles Amazon's bot detection; BeautifulSoup parses product title, position, sponsored flag, price, and rating. Brand extraction uses shared regex patterns across a curated `BRAND_PATTERNS` dictionary. SOV is calculated over the top 20 positions per keyword.
>
> 🔍 **Key challenges:** Amazon's HTML structure varies by product type, and sponsored vs. organic labeling required careful selector logic to avoid misclassification.
>
> 💡 **Key insight:** L'Oréal holds the highest organic SOV (7.1%) across all 12 keywords — driven by product breadth and review volume, not ad spend. Premium brands like Clinique appear almost exclusively in sponsored slots, signalling heavy paid dependency and weak organic equity.

</details>

---

### 📊 CPG Sales Effectiveness Dashboard (Canada)
**[Live App →](App is private for now, check README file instead)(https://cpg-sales-effectiveness-eq8kknzrie9i7rkmkstbcx.streamlit.app)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/cpg-sales-effectiveness-README/tree/main)** &nbsp;|&nbsp; `Python` `Streamlit` `Pandas` `Plotly`

An interactive 5-tab Streamlit dashboard simulating a Canadian CPG sales team's performance — tracking rep revenue, field execution, trade spend ROI, SKU distribution, and retail vendor scorecards across 8 major accounts and 12 SKUs over 26 weeks.

**What it does:**
- Tracks rep-level revenue, fill rate, and trade spend % by territory
- Monitors planogram compliance, display compliance, OOS incidents, and perfect store scores
- Calculates **promo ROI at the SKU × account level** to identify trade spend efficiency vs. baseline
- Surfaces SKU distribution gaps and velocity opportunities across accounts
- Tracks OTIF and vendor scorecard trends by retail account over time

**Answer Business Questions:**
- Where is trade spend generating real incremental revenue — and where is it just subsidising baseline purchases?
- Which reps have field execution gaps that are silently dragging down sales velocity?
- Which high-velocity SKUs are under-distributed, and what is the revenue opportunity from gaining new listings?

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

> ⚙️ **Technical approach:** Fully synthetic dataset generated with realistic CPG scenario logic — trade spend curves, promo lift multipliers, planogram compliance decay, and OTIF trend modeling. Promo ROI calculated at SKU × account level (not aggregate) to prevent high-velocity SKUs from masking weak performers.
>
> 🔍 **Key challenges:** Getting promo ROI right required calculating each promoted SKU's incremental revenue against its own non-promo baseline at the same account — a subtle but critical methodological distinction.
>
> 💡 **Key insight:** Loblaws receives 22% trade spend but generates only 1.17x promo ROI. Metro receives 12% trade spend and generates 4.73x ROI. Reallocating budget from bottom-quartile to top-quartile accounts is the single highest-impact lever available without increasing total spend.

</details>

---
### 📦 CPG Demand Forecasting & Safety Stock Dashboard
**[Live App →](App is private for now, check README file instead)(https://cpg-demand-forecasting-bbsiohqdbbpaq4u6q6ol8c.streamlit.app)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/cpg-demand-forecasting-README/tree/main)** &nbsp;|&nbsp; `Python` `Prophet` `Streamlit` `Plotly`

An end-to-end supply chain analytics tool for Canadian CPG sales teams — forecasting weekly SKU demand 16 weeks forward, calculating statistically optimal safety stock, and surfacing stockout risk before it becomes a retailer chargeback. Built on 2 years of synthetic weekly sales data across 5 SKUs, 3 accounts, and $6M in revenue with embedded OOS events and a Canadian promotional calendar.

**What it does:**
- Generates 2 years of synthetic weekly CPG sales data (1,560 rows) with realistic Canadian market seasonality, trend, and embedded business scenarios
- Applies **Prophet multiplicative forecasting** (trend × seasonality × holidays) to produce 16-week forward forecasts with 90% confidence intervals
- Calculates **safety stock per SKU** using the industry-standard formula: `Z × σ_demand × √(lead_time)` at 90–99% service levels
- Builds a **stockout risk register** (🔴 High / 🟡 Medium / 🟢 Low) with calculated order-by dates
- Visualises the **S&OP demand vs. supply gap** across all accounts with a demand-gap waterfall

**Answer Business Questions:**
- Which SKUs will stockout before the next replenishment cycle, and when exactly must the purchase order be placed?
- How much safety stock is needed to hit 98% OTIF at Walmart Canada — and how does that change at 95% or 99%?
- What does the demand gap between our forecast and supply plan look like over the next 16 weeks?
- How much revenue was lost to the three OOS events last year, and what was the root cause of each?

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

  > ⚙️ **Technical approach:** Prophet multiplicative decomposition (`demand = trend × seasonality × holiday_effects × noise`) with Canadian statutory holidays and `changepoint_prior_scale=0.05`. OOS weeks are replaced with interpolated values before model fitting so Prophet learns true demand, not supply failures. Safety stock uses the Z-score formula at four configurable service levels; Walmart Canada's 98% OTIF threshold is the default.
>
> 🔍 **Key challenges:** Embedding realistic OOS events that the model must detect and forecast *through* — rather than treating zero-sales weeks as genuine demand drops — required careful preprocessing logic. Getting the seasonal decomposition right also meant validating the synthetic data's seasonal multipliers (e.g. Q4 peak factor = 1.53x, post-holiday dip = 0.70x) against Canadian CPG market norms before trusting the forecasts.
>
> 💡 **Key insight:** The three embedded OOS events cost $54,559 in lost revenue — with the Q4 HydraBoost stockout at Shoppers Drug Mart alone accounting for $36,062 (66% of total OOS losses). All three events shared the same root cause: safety stock was calculated against average demand but not adjusted for known seasonal spikes. A service-level-aware ROP that accounts for promotional lift would have prevented all three.
</details>

---

### 💰 Amazon vs eBay — Price Comparison Dashboard
**[Live App →](App is private for now, check README file instead)(https://amazon-ebay-price-comparison-9bdappz6qjzfyktcxvet4uc.streamlit.app)** &nbsp;|&nbsp; **[GitHub README →](https://github.com/hannahdinh-dtmh/amazon-ebay-price-comparison-README/tree/main)** &nbsp;|&nbsp; `Python` `Streamlit` `ScraperAPI` `BeautifulSoup` `Plotly`

A dual-platform scraper and 4-tab Streamlit dashboard that compares real-time pricing for 12 beauty & personal care keywords across Amazon and eBay — surfacing brand-level price disparities and flagging gray market risk for CPG brands concerned about MAP enforcement.

**What it does:**
- Scrapes top 20 results per keyword from both Amazon.com and eBay simultaneously
- Normalizes brand names across platforms using shared regex patterns
- Compares average prices by brand and keyword across platforms
- Flags brands where eBay is significantly cheaper as **gray market risk** (unauthorized resellers, MAP violations, or diversion)

**Answer Business Questions:**
- Are your products being sold cheaper on eBay than Amazon — and does that signal unauthorized reseller activity?
- Which brands maintain consistent pricing across platforms, and which ones don't?
- Where should a brand focus MAP enforcement efforts first?

<details>
<summary>📊 <strong>Deep Dive Analysis</strong> — What I Built & What I Learned</summary>

> ⚙️ **Technical approach:** Two independent scrapers (one per platform) share a common `BRAND_PATTERNS` dictionary for consistent brand attribution. eBay brand extraction re-runs on cleaned titles at load time to remove UI artifacts and phantom brand labels — allowing fixes without re-scraping. Gray market risk threshold: eBay ≥15% cheaper than Amazon.
>
> 🔍 **Key challenges:** eBay redesigned its search results HTML in 2025 (switching from `li.s-item` to `li.s-card`), requiring selector updates. Title noise ("Opens in a new window or tab") and phantom brand matches required a two-stage cleaning pipeline.
>
> 💡 **Key insight:** Amazon is cheaper than eBay across all 12 keywords — the opposite of the common assumption. eBay skews toward bundles, niche imports, and specialty products. However, Estée Lauder (-62%), Clinique (-48%), and Tarte (-36%) show eBay prices well below Amazon, signalling active gray market risk for these brands.

</details>

---

### 🔜 Coming Soon

| Project | Description | Status |
|---|---|---|
| 📦 Customer Segmentation Engine | RFM-based ML segmentation with clustering evaluation (Silhouette Index, Davies-Bouldin) | 🔨 In progress |

---

## 📝 Writing & Research

I publish literature reviews and methodology pieces on Medium, exploring the intersection of AI/ML and real-world business applications. These pieces inform the research foundation behind my projects.

---

### [From Data Quality to Model Validity — AI/ML Segmentation Effectiveness](https://medium.com/@hannah.dinh/machine-learning-applications-for-segmentation-with-transaction-data-literature-review-e3233f93c743?sk=5da7c9a0a991f54ebea2c4b81796f1ae)

A literature review examining what actually makes ML-based customer segmentation work in practice — from preprocessing and feature engineering (RFM and extensions) to rigorous clustering evaluation and stakeholder-ready interpretation.

**Key takeaways:** Effective segmentation demands both statistical rigor (iterative k testing, Silhouette Index) *and* business interpretability. AI/ML unlocks real-time behavioral insights, but only when preprocessing and model validation are treated as first-class concerns.

---

### [How Design Science Research Guides Successful AI/ML Projects](https://medium.com/@hannah.dinh/design-science-research-dsr-methodology-for-ai-ml-projects-literature-review-4fcfba10db84?sk=7228134618345bfbeb994f0cc62b4416)

An exploration of how Design Science Research (DSR) methodology provides a rigorous, iterative framework for AI/ML project development — bridging technical performance metrics with real-world business relevance and stakeholder feedback.

**Key takeaways:** DSR's artifact-driven cycles (design → evaluate → refine) make it particularly well-suited to ML projects where both accuracy and organizational fit matter. Scalability and generalizability are built in from the start.

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hannah-dinh-66094019)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white)](https://medium.com/@hannah.dinh)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:huandnh@gmail.com)

---

*Thanks for stopping by — feel free to explore my repos and reach out if you'd like to collaborate or chat about data! 🙌*

