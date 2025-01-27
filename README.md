# Customer Analytics
Atliq Hardware is a dynamic hardware solutions provider specializing in enterprise-level hardware products and comprehensive technology infrastructure. Founded in 2012, the company has established itself as a key player in the hardware supply and distribution market, serving clients including brick & mortar stores and e-commerce across India.

## Purpose
Provide actionable insights to Atliq Hardware’s Customer Relations and Marketing teams to increase sales and drive business growth. By analyzing customer contributions, purchase patterns, and segmentation, this project aims to empower the team with data-driven strategies to:

- Strengthen relationships with high-value customers.
- Identify growth opportunities within mid-tier and low-performing customer segments.
- Optimize sales and marketing efforts through targeted campaigns and tailored product offerings.

### Key Metrics
1. **Customer Contribution Analysis:** To understand which customers contribute most to revenue and identify key accounts.
2. **Purchase Pattern Analysis:** To understand customer purchase behavior, when they buy, and what they buy.
3. **Customer Segmentation:** To tailor strategies based on customer’s value and behavior.

The SQL queries used to inspect data for this analysis can be found [here](https://docs.google.com/document/d/1bQb6W8Y64YgYbzR5jDvpqnA2J4GkC8SrpW9VpW9AWGw/edit?usp=sharing).

The Power BI dashboard used to report and explore customer analysis can be found [here](https://github.com/aulifiafarisa/CustomerAnalytics/blob/a4042765a77800283734824e1e1deddcc951f0fd/Customer%20Analysis%20Dashboard.pbix).

## Dataset Structure
![Table](https://github.com/aulifiafarisa/CustomerAnalytics/blob/a82857ad0f0dd0d5a335469f261779a1da0e2e29/images/ERD%20AtliQ.png)

## Executive Summary
Atliq Hardware’s Customer Analytics revealed **significant concentration in revenue** among a small number of customers, with the **top three contributing approximately 70% of total revenue**, highlighting dependency risks. **Purchase patterns** indicate **distinct seasonal peaks** in **June**, **September**, and **November**, suggesting opportunities for targeted campaigns during these periods. Additionally, a **gap exists between high-performing customers** and **mid-tier** or **low-performing segments**, indicating potential for growth through strategic engagement. This analysis provides actionable insights to strengthen relationships with top customers, diversify revenue sources, and optimize sales strategies for sustainable business growth.

## Insight Deep Dive

**1. Customer Analytics Overview**

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Customer%20Analytics%20Overview.png)

**Insight:** The dashboard shows **262 total orders** and **9 active customers**, indicating a relatively small but potentially high-value customer base. There are **17 total customers**, with an **average revenue per customer of 106K**. This suggests a concentration of revenue among a small number of customers. The **total revenue is 1.8M**, with an **average order value of 6.9K**. The high AOV indicates that customers are making substantial purchases. 

**Actions:** Explore ways to **increase the number of active customers** while **maintaining the high average revenue per customer**, such as through targeted marketing campaigns and referral programs.


**2. Customer Contribution Analysis**

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Customer%20Revenue%20Pareto%20Chart.png)

**Insight:** The chart follows the **Pareto Principle (80/20 Rule)**, showing that a small number of customers contribute to the majority of revenue. Top three customers (**Cus006**, **Cus005**, and **Cus007**) generate **approximately 70% of the total revenue**, with **Cus006** alone contributing **30%**. Beyond the top five customers, revenue contributions drop significantly, indicating a **heavy reliance on a few key customers.** Customers from Cus016 onward contribute minimal revenue individually, with the cumulative percentage nearing 100% only after including all customers. 

This highlights a **large group of low-performing customers** whose contributions are marginal. Heavy dependence on top customers like Cus006 and Cus005 poses a **risk** if any of these customers reduce their spending or leave. There is untapped potential in the middle-tier customers (Cus007, Cus016, etc.) who could be nurtured to increase their revenue contribution. The long tail of low-performing customers could be analyzed for potential upselling or cross-selling opportunities.

**Actions:** Strengthen Relationships with Top Customers by focusing on **retaining** **Cus006**, **Cus005**, and **Cus007** by offering personalized loyalty programs, exclusive deals, or premium services. Conduct **periodic reviews** with these customers to understand their needs and ensure continued satisfaction. Mitigate Risk of Dependency by diversifying revenue sources by reducing over-reliance on the top three customers. Develop strategies to grow the revenue contribution of mid-tier customers (Cus016, Cus003, etc.).


   
![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Customer%20Spending.png)

**Insight:** **Premium Stores** and **Electricalsara Stores** contribute the **highest Customer Total Revenue**, with Premium Stores leading significantly. These customers are key revenue drivers and represent high-value accounts. **Surge Stores** has the highest Average Order Value, despite not being the top contributor to total revenue. This suggests that Surge Stores makes fewer but larger purchases compared to others. **Electricalsara Stores** and **Premium Stores** also have relatively high AOV, indicating they consistently place high-value orders. Some customers, like **Info Stores**, generate moderate total revenue but have a relatively lower AOV, indicating frequent smaller purchases. Others, such as **Surge Stores**, focus on high-value purchases but may have fewer transactions.

**Actions:** For customers with high Average Order Value (AOV) such as **Surge Stores**, the focus should be on **increasing order frequency** through incentives like volume discounts or subscription services. **Mid-tier customers** like Info Stores can be targeted with **upselling and cross-selling strategies**, such as product bundles or premium offerings, to boost their order value. **Low-performing customers,** such as Flawless Stores and Acclaimed Stores, **should be re-engaged** with targeted campaigns offering discounts or smaller product bundles to encourage purchases. Additionally, **analyzing** the **preferences of high-AOV customers** can help refine product offerings and introduce premium tiers that appeal to a broader customer base. Finally, diversifying revenue sources by growing mid-tier accounts and **targeting new customers with similar profiles to top performers** will reduce reliance on a few key contributors and create a more balanced portfolio. These strategies will ensure sustainable growth and strengthen customer relationships.

**3. Purchase Pattern Analysis**

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Monthly%20Purchase%20Trends.png)

**Insight:** The monthly purchase trends reveal **distinct seasonal peaks,** with **June**, **September**, and **November** consistently showing higher revenue across years, suggesting **cyclical purchasing patterns.** **Conversely**, **January** **to April** and **August** exhibit **low sales** activity, indicating **off-season periods.** The sharp increase in November 2020 highlights potential year-end demand, while overall data for 2020 is incomplete, which limits a fully comprehensive year-over-year analysis. These patterns emphasize the importance of timing in sales and marketing strategies.

**Actions:** To maximize revenue, the business should focus on **targeted campaigns** and **adequate inventory planning** during peak months like **June**, **September**, and **November**. For **off-season periods**, **promotional offers**, **bundled deals**, and **loyalty incentives** can be introduced to stimulate demand. Additionally, end-of-year campaigns, such as holiday or Black Friday sales, should be prioritized to capitalize on year-end spikes. Lastly, improving data consistency and completeness will enable more accurate analysis and better forecasting for future trends.

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Order%20Frequency.png)

**Insight:** The data shows a significant concentration of orders among a few key customer types, such as Info Stores, Excel Stores, and Logic Stores. Some customer segments exhibit shifts in order frequency over the years, indicating potential changes in their purchasing behaviors. Certain customer types like Flawless Stores and Unity Stores have a relatively low order frequency, suggesting potential to increase their engagement and order volumes.

**Actions:** Identify the key drivers behind the high order frequency of top-performing customers like Info Stores and Excel Stores. Develop targeted account management strategies to nurture these valuable customer relationships and maintain their loyalty. Investigate the reasons for the fluctuations in order frequency for customers like Logic Stores and Electricalsara Stores. Understand the factors influencing their changing purchasing patterns, such as market conditions, product availability, or changes in customer needs.

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Product%20Sold.png)

**Insight:** The Product Sold table provides granular visibility into the individual products purchased by each customer, offering insights beyond just order frequency and revenue. **Analyzing the product codes associated with each customer** can reveal their **unique product preferences**, **purchasing patterns**, and **affinities**.

**Actions:** This level of detail allows for a more nuanced understanding of each customer's business needs and **opportunities to cross-sell or upsell complementary products.** Empower the sales team with the detailed product code information to have more meaningful, value-added conversations with customers. Utilize the product code data to provide **personalized product recommendations** and create custom bundled offerings for each customer. Analyze the product code data to forecast demand at the individual product level, ensuring appropriate inventory levels and reducing stockouts.

**4. Customer Segment**

![image alt](https://github.com/aulifiafarisa/CustomerAnalytics/blob/0239df9a8511a6bcfb76307b419c689adc9360f2/images/Customer%20Rank.png)

**Insight:** The data provides a ranking of Atliq Hardware's customers based on their total revenue contribution. It reveals a **significant gap** between the **top few customers (Electricalsara Stores, Premium Stores, Info Stores)** and **the rest** of the customer base in terms of revenue generation. Some customers, like Surge Stores and Logic Stores, also stand out as mid-tier contributors, suggesting potential opportunities for growth.

**Actions:** Develop **tailored strategies** to increase their lifetime value, loyalty, and share of wallet through personalized offerings, value-added services, and strategic partnerships. Analyze the unique characteristics, purchasing behaviors, and growth opportunities of mid-tier customers like Surge Stores and Logic Stores. 

## Recommendations

Based on the insights and findings above, we would recommend the Customer Relation and Marketing Team to consider the following:

1. **Strengthen Relationships with Top Customers:** Introduce loyalty programs, exclusive deals, and personalized communication for high-value customers (e.g., Cus006 and Cus005) to retain their business and mitigate dependency risks.
2. **Upsell and Cross-Sell to Mid-Tier Customers:** Develop tailored campaigns for mid-tier contributors, such as Surge Stores and Logic Stores, to increase their share of wallet through product bundles and premium offerings.
3. **Capitalize on Seasonal Trends:** Allocate resources for targeted campaigns during high-revenue months (June, September, and November), while deploying promotional offers and bundled deals to boost sales during off-peak periods.
4. **Re-Engage Low-Performing Customers:** Implement targeted outreach programs to encourage purchases from underperforming accounts, leveraging discounts or smaller product bundles as incentives.

## Assumption and Caveats

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

1. **Order ID Creation:** Since the dataset lacked a unique Order ID column, a unique identifier was created by combining customer_code, order_date, and market_code. This approach assumes that customers may place multiple orders on the same day but in different markets.
2. **Incomplete Data for 2017 and 2020:** The data spans from October 2017 to June 2020; however, it does not include a full year of data for 2017 and 2020. Consequently, purchase patterns may appear less consistent or incomplete for those years, potentially impacting the accuracy of seasonal or year-over-year trends.
3. **Discrepancy in Customer Records:** Although the customer table lists 38 customers, only 17 of them appear in the transaction table. This suggests potential data gaps or missing transaction records, which may lead to an incomplete representation of the customer base.

Raw data originally from [codebasics](https://github.com/codebasics/DataAnalysisProjects) and can be accessed [here](https://drive.google.com/drive/folders/1b7VmboyOVzHdeJ6VYr8bXQBsOfwwP9iM?usp=drive_link).

Dax for measures and calculated columns can be accessed [here](https://docs.google.com/document/d/1iVpmY5LA0f1LGxXpPmaJ-Bvuisstq1HhhAWde4p5lzs/edit?usp=sharing).

**Tools:** Power BI, MySQL, Power Query Editor.



