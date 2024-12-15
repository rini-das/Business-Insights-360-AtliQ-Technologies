
# **BUSINESS INSIGHTS 360: ATLIQ TECHNOLOGIES**

AtliQ Hardware, has witnessed remarkable growth in recent years. To stay ahead of competitors and embrace a data-driven approach, the organization embarked on its journey into data analytics.
This initiative seeks to empower stakeholders by providing actionable insights across critical areas such as finance, sales, marketing, and supply chain, enabling smarter, more strategic decisions.

I developed this project as part of the Codebasics Data Analytics Bootcamp, which provided Step by step practical guidance on building data-driven dashboards. 

I’m attaching the Bootcamp link in case you’d like to check it out:

[![Codebasics](https://img.shields.io/badge/Codebasics-ADD8E6?style=for-the-badge&logo=Codeforces&logoColor=white)](https://codebasics.io/)


[Explore the Interactive live Dashboard Here](https://project.novypro.com/IY9I6Z)
## **🔗 Connect with Me**
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rinivbdas09/)


## **🔗 Uncover more of my Professional Journey**
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://my.novypro.com/rini-das)
[![GitHub](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rini-das)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=black)](https://www.hackerrank.com/profile/rinidas)




## **AtliQ Technologies**
AtliQ Technologies is a dynamic and innovative company that specializes in providing high-quality hardware solutions to businesses and individuals. With a mission to deliver cutting-edge technology and exceptional customer service, AtliQ has established itself as a trusted name in the industry.

### **Products and Services :**
AtliQ Technologies offers a wide range of hardware products designed to meet diverse customer needs:

- **Consumer Electronics:** High-performance laptops, desktops, and accessories.
- **Networking Solutions:** Routers, switches, and advanced network infrastructure components.
- **Enterprise Hardware:** Servers, storage devices, and business-grade computing systems.
- **Smart Home Devices:** Smart security systems, home automation tools, and IoT-enabled products.

### **Target Consumers:**
AtliQ caters to a broad audience, including:

- **Individual Customers:** Tech enthusiasts and everyday consumers seeking reliable and innovative hardware solutions.
- **Small and Medium Businesses (SMBs):** Enterprises looking for cost-effective and efficient computing and networking solutions.
- **Corporate Clients:** Large organizations requiring scalable and robust hardware infrastructure for their operations.
- **Educational Institutions:** Schools, colleges, and universities in need of technology solutions for classrooms and labs.

## **Customer Base:**
AtliQ’s customers span across industries and geographies, including:

- **Retailers and Distributors:** Partnering with B2B channels to reach broader markets.
- **IT Service Providers:** Supporting managed IT services and hardware resale.
- **Government Agencies:** Supplying secure and compliant hardware for public sector projects.
- **End Users:** Individuals purchasing directly from online platforms or retail outlets.

## **📊 Dataset Overview**
This dataset is designed by, combining **dimension tables** (static reference data) and **fact tables** (transactional and forecast data) to support decision-making across business operations.

### **📌 Key Components**
**Key Tables**
1. **Dimension Tables (Static Information)**
These tables describe the core entities like customers, markets, and products:

**Customer Information (dim_customer):**

- Covers 27 markets (e.g., India, USA, Spain).
- 75 unique customers across markets.
- Two sales platforms:
  - Brick & Mortar: Physical stores.
  - E-commerce: Online platforms (e.g., Amazon, Flipkart).
- Three sales channels: Retailers, Direct Sales, and Distributors.

**Market Information (dim_market):**

- 27 distinct markets divided into:
- 7 sub-zones.
- 4 regions: APAC, EU, LATAM, and Uncategorized.

**Product Information (dim_product):**

- **Two main divisions:**
  - **P & A (Peripherals and Accessories):** Includes items like keyboards and hard drives.
  - **N & S (Networking and Storage):** Covers devices like routers and storage units.
- Products fall under 14 categories and may have multiple variants.

2. **Fact Tables (Transactional Data)**
These tables store time-sensitive data for forecasting and sales:

- **Forecast Data (fact_forecast_monthly):**

  - Predicts customer demand to improve satisfaction and reduce storage costs.
  - Data is simplified (all dates set to the first of the month).
  - Includes a "forecasted quantity" column for planning inventory and resources.

- **Sales Data (fact_sales_monthly):**

  - Similar structure to forecast data but tracks actual quantities sold instead of forecasted values.


3. **Supporting Tables**
Additional tables provide insights into costs, pricing, and adjustments:

- **Freight Costs (freight_cost):** Contains shipping and travel costs by market and year.
- **Gross Prices (gross_price):** Lists product prices at the gross level.
- **Manufacturing Costs (manufacturing_cost):** Details production costs by product and year.
- **Pre-Invoice Deductions (pre_invoice_deductions):** Shows discount percentages applied before invoicing for each customer and year.
- **Post-Invoice Deductions (post_invoice_deductions):** Includes post-invoice discounts and other financial adjustments.
## **Actions Undertaken**

- Collected data from MySQL, Excel, and text files, enabling automated updates through Power BI Services.
- Ensured data reliability and boosted performance by utilizing tools like DAX Studio.
- Developed calculated columns,DAX measures and KPIs to make dashboards more intuitive and informative.
- Created tailored dashboards for Finance, Sales, Marketing, and Supply chain teams to meet their specific requirements.
- Designed Executive dashboards that showcased essential metrics, including top customers, financial trends, and competitive insights.
## **AtliQ's Core Data Structure**

![Screenshot (9)](https://github.com/user-attachments/assets/5fbecf49-a25b-4e49-acf7-0c86cbda08e7)

## **AtliQ's Dashboard**

The dashboard is organized into the following key sections:

- **Home:** The main landing page with a summary overview.
- **Info:** General information.
- **Support:** Tools and insights for customer support tracking.
- **Finance View:** Detailed financial performance analytics.
- **Sales View:** Insights into sales trends and patterns.
- **Marketing View:** Analysis of marketing campaigns and performance.
- **Executive View:** A high-level overview highlighting key strategic metrics.
## Tech Stack Essentials

- Power BI
- MySQL
- DAX Studio
- Excel
- Freepik
- flaticon
## **Lessons Learned**

- Developed a comprehensive understanding of OLTP and OLAP concepts, data warehousing structures, star and snowflake schema designs, and the principles of query folding.
- Designed and implemented calculated columns to enrich data insights.
- Created dynamic and reusable measures using the DAX language like ALLNOBLANKROWS, ABS, DIVIDE etc for advanced analytics.
- Built efficient data models to streamline relationships between datasets.
- Utilized bookmarks to seamlessly toggle between visuals for enhanced interactivity.
- Implemented intuitive page navigation with custom-designed buttons.
- Published interactive reports to Power BI Service for real-time sharing and collaboration.
- Set up ACTION button for smooth transitions between report pages.
- Learnt to select the most appropriate visualizations to highlight different data aspects, improve comprehension and better understanding.
- Familiarized with key analytical metrics such as forecast accuracy, net error, absolute error, YTD (Year-to-Date), YTG (Year-to-Go), and landing estimates, and understood their real-world applications.


## **Deliverables**

The outcome of this analysis provided actionable insights into the AtliQ's market performance, identified key opportunities for growth, and highlighted areas requiring strategic focus. 
It enabled improved inventory management, optimized operational strategies, and a deeper understanding of customer behavior trends. Additionally, the findings serve as a foundation for answering critical "why" questions, driving data-informed decisions, and fostering a proactive approach to market challenges and opportunities.
