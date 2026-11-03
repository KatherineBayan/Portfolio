# Katherine Nicole R. Bayan | Portfolio

Welcome to my portfolio repository! I'm a **Magna Cum Laude Computer Science graduate** (with Specialization in Intelligent Systems) from De La Salle University - Dasmariñas. I enjoy turning raw data into clear, actionable insights through analysis, dashboards, and visualizations, and I'm eager to apply my technical and analytical skills in a data-driven team.

This repository is the central hub for my **Data Analytics** and **Software Development** work.

---

## Table of Contents

- [About Me](#about-me)
- [Portfolio Repositories](#portfolio-repositories)
- [Featured Data Analytics Projects](#featured-data-analytics-projects)
  - [Coffee Sales Excel Dashboard](#coffee-sales-excel-dashboard)
  - [Hardware and Tech Sales Performance Dashboard](#hardware-and-tech-sales-performance-dashboard)
  - [ASOS Product Analysis](#asos-product-analysis)
- [Software Development Projects](#software-development-projects)
  - [JOTTER~O: A MULTIMODAL AI DIARY COMPANION FOR SUPPORTING DLSU-D STUDENT’S WELL-BEING USING DEEP NEURAL NETWORKS](#jottero-a-multimodal-ai-diary-companion-for-supporting-dlsu-d-students-well-being-using-deep-neural-networks).
- [Skills and Tools](#skills-and-tools)
- [Education](#education)
- [Experience Highlights](#experience-highlights)
- [Certifications](#certifications)
- [Languages](#languages)
- [Contact](#contact)

---

## About Me

I'm a Computer Science graduate with a strong foundation in data analysis, statistics, databases, and machine learning concepts. My experience spans building dashboard reports, maintaining structured datasets, automating spreadsheet workflows, and helping researchers with statistical analysis. I take pride in my attention to detail, critical thinking, and ability to communicate insights clearly to both technical and non-technical audiences.

Currently, I work as a **freelance data and spreadsheet specialist**, building incentive trackers, inventory systems, and spending dashboards for clients, while also assisting undergraduate and graduate researchers with thesis data analysis.

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Portfolio Repositories

| Repository | Description |
|---|---|
| [Portfolio](https://github.com/KatherineBayan/Portfolio) | Main hub (you are here) |
| [Data Analyst Portfolio](https://github.com/KatherineBayan/Data-Analyst-Portfolio) | Data analysis, visualization, and dashboard projects |
| [Software Development Portfolio](https://github.com/KatherineBayan/Software-Development-Portfolio) | Software and programming projects |

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Featured Data Analytics Projects

A selection of my dashboard and analysis work. More projects are available in the [Data Analyst Portfolio](https://github.com/KatherineBayan/Data-Analyst-Portfolio).

### 📁 Coffee Sales Excel Dashboard
Read full at **Repository:** [Coffee-Sales-Excel-Dashboard](https://github.com/KatherineBayan/Coffee-Sales-Excel-Dashboard)

<img width="1498" height="783" alt="image" src="https://github.com/user-attachments/assets/2bba5527-de6b-4822-af4e-8fda4d33a2e7" />

#### Description

An interactive sales dashboard built from a three-table coffee retail dataset: 1,000 order lines, 1,000 customers and 48 products, covering January 2019 to August 2022. The dashboard tracks revenue over time by coffee type (Arabica, Excelsa, Liberica, Robusta), compares sales across countries, and ranks the top customers. A date timeline and slicers for roast type, bag size and loyalty card status let users filter every chart at once.

### Goal

Give a coffee retailer a single view of how the business is performing, so stakeholders can quickly answer:

- Which coffee types drive revenue, and how stable is that revenue over time?
- Which markets generate the most sales?
- Who are the most valuable customers?
- Do roast, size and loyalty membership change the picture?

#### Skills Used

- **Data cleaning and preparation:** The `orders` sheet held only IDs and quantities. I enriched it with customer and product attributes (name, country, coffee type, roast, size, unit price) from the `customers` and `products` tables. I also checked ID integrity (no orphaned or duplicate keys) and flagged missing emails and phone numbers.
- **Data modeling:** Linked three related tables through Customer ID and Product ID.
- **Calculated fields:** Sales = Quantity × Unit Price.
- **Pivot tables and pivot charts:** Built the line chart (sales by coffee type by month), the bar chart (sales by country) and the Top 5 Customers ranking.
- **Interactive filtering:** Added a timeline and slicers (roast, size, loyalty card) connected to all visuals.
- **Dashboard design:** Used a consistent coffee-themed palette, a clear layout and readable labels, with filters on top and charts below.
- **Data storytelling:** Turned the numbers into findings and recommendations.

#### Results

- **Total sales were about $45.1K** across the period (US $35,639 + Ireland $6,697 + UK $2,799).
- **The US is the dominant market**, at about 79% of revenue. Ireland contributes about 15% and the UK about 6%.
- **Revenue is spread across all four coffee types.** No single type consistently leads, and each one swings sharply from month to month (roughly $50 to $850 per month).
- **Notable peaks:** Arabica spiked to about $840 in September 2021 and about $745 in early 2020. Liberica peaked at about $845 in January 2022.
- **There is no clear long-term growth trend.** Sales are volatile and flat across 2019–2022, and revenue appears to dip in the final months shown (2022 may be incomplete, since the data ends in August).
- **Customer revenue is not concentrated.** The top 5 customers (Allis Wilmore at $317, Brenn Dundredge at $307, Terri Farra at $289, Nealson Cutler at $282 and Don Flintif at $278) together account for only about 3% of total sales. That means low dependency risk, but also no standout “whale” accounts.



### 📁 Hardware and Tech Sales Performance Dashboard
Read full at **Repository:** [Hardware-and-Tech-Sales-Performance-Dashboard](https://github.com/KatherineBayan/Hardware-and-Tech-Sales-Performance-Dashboard)

<img width="1368" height="782" alt="image" src="https://github.com/user-attachments/assets/5c72a48d-bfda-4b26-a6d3-ff644db03995" />

#### Description

An interactive Excel dashboard that analyzes 2,000 orders of computer and IT products across 5 regions, 4 sales channels and 6 product categories in 2026. It opens with four KPI cards (Total Revenue, Total Orders, Total Quantity Sold, Average Order Value), followed by visuals for monthly revenue trend, top products, product category, sales channel and region. Year, quarter and month timelines plus slicers for customer type, region, sales channel and product category let users filter the whole dashboard with a click.

#### Goal

Give sales leadership one place to monitor performance and answer key questions:

- How much revenue is the business generating, and how does it move month to month?
- Which products and categories drive the most revenue?
- Which regions and channels perform best?
- How much do new vs. returning customers contribute?

#### Skills Used

- **Data preparation:** Verified headers, date formats and missing values. The 2,000 records across 12 columns had no missing values.
- **PivotTables and PivotCharts:** Built a supporting pivot for each KPI and chart, so every visual traces back to the data.
- **KPI design:** Defined Total Revenue, Total Orders, Quantity Sold and Average Order Value (Revenue ÷ Orders).
- **Interactivity:** Connected timelines (year, quarter, month) and slicers to all pivots at once.
- **Visualization choices:** Matched chart type to the question: line for trend, bars for rankings, donut for channel share, columns for regional comparison.
- **Dashboard design:** Used a consistent color theme, a filter panel on the left and a KPI-first layout with a “Date updated through” stamp.
- **Business analysis:** Turned the metrics into insights and recommendations.

#### Results

- **Total revenue was $2.45M** from 2,000 orders and 5,552 units, with an **average order value of $1,226**.
- **Computers drive the business.** Computers generate $1.35M (about 55% of revenue) from only 17% of orders. Together with Monitors ($527K), they make up about 76% of revenue.
- **Revenue is concentrated in a few products.** The Gaming Laptop alone brings in $433K (about 18%), and the top 5 products account for about 58% of total revenue.
- **Online is the largest channel** at $792K (32%), followed by Corporate Sales ($719K, 29%), Retail Store ($631K, 26%) and Marketplace ($310K, 13%).
- **Corporate Sales has the highest order value.** Its average order is $2,158, about 2.1 times the Online average ($1,003), even though it has the fewest orders after Marketplace.
- **Marketplace is the weakest channel.** It has the lowest share and the lowest average order value ($839).
- **Regional revenue is fairly balanced.** North ($562K) and Central ($557K) lead with about 46% combined, and West is lowest at $421K. West has the fewest orders (330) but a high average order value ($1,277), so its gap is about order volume rather than deal size.
- **Returning customers drive revenue.** They account for about 69% of revenue ($1.68M) and place orders about 15% larger than new customers ($1,284 vs. $1,116).
- **Monthly revenue is volatile.** It ranges from $151K (July) to $274K (November), with other dips in May ($154K). Quarterly revenue is steadier ($569K to $653K), with Q2 and Q4 strongest.
- **Discounts are heavily used.** About 86% of orders carry a discount, averaging 7.4%, which reduced revenue by about $199K (7.5% of list value).



### 📁 ASOS Product Analysis
Read full at **Repository:** [ASOS-Product-Analysis](https://github.com/KatherineBayan/ASOS-Product-Analysis)

<img width="1182" height="784" alt="image" src="https://github.com/user-attachments/assets/cb34461a-b9aa-4fa7-91b2-ed77d6328d7d" />

### Description

Conducted a product availability and inventory analysis using ASOS product listing data to identify size-level stockouts, evaluate brand performance, and determine which products require inventory attention. The project involved data cleaning, product-level consolidation, stockout analysis, brand comparisons, and product prioritization. The findings were used to develop data-driven recommendations for inventory monitoring and stock management.

### Goals

- Measure the extent of size-level stockouts across ASOS product listings.
- Identify sizes and products experiencing the greatest availability pressure.
- Compare brands based on average product prices and stockout rates.
- Prioritize products for inventory investigation using stockout rates and estimated exposure.
- Develop recommendations to improve inventory monitoring and product availability.

### Skills Used

- **Python:** Data manipulation and analysis using Pandas.
- **Data Cleaning:** Handling missing values, filtering records, and consolidating product listings.
- **Exploratory Data Analysis (EDA):** Identifying patterns and trends in product availability.
- **Data Visualization:** Creating charts and comparisons to communicate stockout patterns and brand performance.
- **Business Analytics:** Interpreting inventory-related metrics and translating findings into business recommendations.
- **Analytical Reporting:** Presenting results and actionable insights based on the data.

### Results

- Analyzed **9,708 initial records**, retaining **8,438 records** after data cleaning.
- Found that **23.98% of recorded size options were sold out**, while **50.41% of products had at least one sold-out size**.
- Identified **2XL - UK 16** as the size with the highest observed stockout rate at **43.86%**.
- Consolidated the data into **525 unique products** and classified them into inventory priority groups:
    - 109 high-priority products (20.76%)
    - 50 medium-priority products (9.52%)
    - 366 routine-monitoring products (69.71%)
- Identified brands with relatively high average prices and elevated stockout rates, highlighting potential areas for inventory review.
- Estimated a total stockout exposure proxy of **727,029.22**, calculated using listed product prices and the number of sold-out sizes. This represents potential exposure, not confirmed lost revenue.


[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Featured Software Development Projects

A selection of my software development projects, covering applications and programming projects built throughout my Computer Science studies, is collected in a dedicated repository:

More projects are available at [Software-Development-Portfolio](https://github.com/KatherineBayan/Software-Development-Portfolio)

### 📁 JOTTER~O: A MULTIMODAL AI DIARY COMPANION FOR SUPPORTING DLSU-D STUDENTS’ WELL-BEING USING DEEP NEURAL NETWORKS
Read full at **Repository:** [Jotter~O](https://github.com/KatherineBayan/JOTTER-O-A-MULTIMODAL-AI-DIARY-COMPANION-FOR-SUPPORTING-DLSU-D-STUDENTS-WELL-BEING-USING-DNN)

Jotter~O is a multimodal AI diary companion designed to enhance the emotional well-being of De La Salle University-Dasmariñas (DLSU-D) students by integrating facial emotion recognition, speech recognition, and Natural Language Processing (NLP) sentiment analysis. By leveraging deep neural networks and combining facial emotion recognition with an accuracy of 86.24%, speech recognition powered by the VOSK API, and BART Transformer Model for sentiment analysis of the conversational AI with an accuracy of 94%, the AI diary companion understands how students feel through their facial expressions, voice, and written words, offering thoughtful and supportive responses in real-time. Based on the evaluation results, the system achieved a mean satisfaction rating of 86.24% final accuracy for Facial Recognition and 94% final accuracy for NLP (BART) sentiment analysis across usability, reliability, and emotional response accuracy metrics, demonstrating its effectiveness as a supportive and empathetic AI companion for students.


[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Skills and Tools

| Category | Tools and Skills |
|---|---|
| **Data Analysis** | Excel (Advanced: PivotTables, VLOOKUP/XLOOKUP, Power Query), Google Sheets, SQL, Microsoft Access |
| **Programming** | Python (Pandas, NumPy, Jupyter, Anaconda), Visual Studio Code, Git/GitHub |
| **Visualization / BI** | Microsoft Power BI, Tableau, Google Data Studio |
| **Data Mining and ML Concepts** | RapidMiner, Apriori Algorithm, Ensemble Methods, Classification and Clustering Techniques |
| **Core Strengths** | Statistical Analysis, Dashboard Reporting, Attention to Detail, Critical Thinking, Problem-Solving, Clear Communication of Insights |

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Education

**Bachelor of Science in Computer Science, Specialization in Intelligent Systems**
De La Salle University - Dasmariñas | 2021 - 2025

- Magna Cum Laude
- Dean's Lister (A.Y. 2021 - 2025)
- Excellence in Leadership Awardee (2024)
- **Relevant Coursework:** Data Structures and Algorithms, Database Management Systems, Machine Learning, Statistics and Probability, Data Mining, Software Engineering

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Experience

**Freelance Data and Spreadsheet Specialist** | Self-Employed (Oct 2025 - Present)
- Built incentive tracking sheets that automate commission calculations
- Designed inventory management systems in Excel and Google Sheets
- Developed personal spending trackers with automated categorization and visualizations
- Supported researchers with data cleaning, statistical tests (t-tests, regression, correlation), and visualizations

**Intern, Team Lead Assistant** | The Umonics Method, Singapore (Jun 2024 - Aug 2024)
- Built and presented weekly dashboard reports on team progress and output
- Used Google Search Console to monitor website performance and inform SEO decisions
- Maintained structured datasets and managed multiple WordPress websites

**Director of Creatives** | CSCS Student Government (Jul 2024 - Feb 2025)
- Implemented Excel, Google Sheets, and Notion systems for workload tracking and reporting
- Led and mentored the Creatives Committee across multiple college events

**Legislative Councilor** | CSCS Student Government (Jan 2024 - Apr 2024)
- Researched facts and statistics and built dashboard reports to support legislative proposals

**Committee Member** | CSCS Student Government (Aug 2021 - Dec 2023)
- Managed event data and designed scoresheets, using visualizations to analyze competition results

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Certifications

### Data Science, Analytics and Machine Learning
- **Machine Learning with Python** | Cognitive Class (Oct 2026)
- **Data Visualization with Python** | Cognitive Class (Sep 2026)
- **SQL and Relational Databases 101** | Cognitive Class (Sep 2026)
- **Python 101 for Data Science** | Cognitive Class (Aug 2026)
- **Data Analytics Essentials** | Cisco Networking Academy (Apr 2024)
- **Introduction to Data Science** | Cisco Networking Academy (Apr 2024)

### Cybersecurity
- **Endpoint Security** | Cisco Networking Academy (Dec 2023)
- **Introduction to Cybersecurity** | Cisco Networking Academy (Sep 2023)

### Leadership, Ethics and Professional Development
- **Ethical Compass: Navigating Integrity in the Digital Age** | DLSU-D College of Science and Computer Studies Student Government (Apr 2024)
- **Microsoft Elective Course** | De La Salle University - Dasmariñas (Aug 2023)
- **USG Leadership Training Summit** | DLSU-D USG (Apr 2022)

### Conferences, Competitions and Events
- **INCRIS: International Conference on Research Inclusivity and Sustainability** | De La Salle University - Dasmariñas (Jun 2025)
- **CONTRENDS: Conference on Technology and Research for National Development and Sustainability** | AARO DLSU-D (May 2023)
- **CSlash IT: Leveling Up in the World of Cyber Realm** | CSIT Program Council (May 2023)
- **INCRIS: International Conference on Research Inclusivity and Sustainability** | De La Salle University - Dasmariñas (Jun 2022)
- **Codelympics 2022** | CSIT Program Council (Jun 2022)
  
[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Languages

- English: Fluent
- Filipino: Fluent

[Back to top](#katherine-nicole-r-bayan--portfolio)

---

## Contact

I'm open to opportunities in data analytics and related fields. Feel free to reach out!

- Email: [k.nicolebayan@gmail.com](mailto:k.nicolebayan@gmail.com)
- LinkedIn: [katherine-nicole-bayan](https://www.linkedin.com/in/katherine-nicole-bayan)
- GitHub: [KatherineBayan](https://github.com/KatherineBayan)
- Location: Cavite, Philippines

[Back to top](#katherine-nicole-r-bayan--portfolio)
