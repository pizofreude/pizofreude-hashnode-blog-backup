---
title: "Executive Dashboard for Cycling Superstores"
seoTitle: "Cycling Store Executive Dashboard"
seoDescription: "Transform your cycling superstore data into actionable insights with an executive dashboard for informed decision-making"
datePublished: Fri May 03 2024 09:27:17 GMT+0000 (Coordinated Universal Time)
cuid: clvqh1eid000008ih0p75e9pe
slug: executive-dashboard-for-cycling-superstores
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1714644736547/305773ea-446a-4ba3-bf59-84d0fa04e586.jpeg
tags: postgresql, data-analysis, business, sql, excel, tableau, business-analytics, 2articles1week, cycling, haqqnetwork

---

<div data-node-type="callout">
<div data-node-type="callout-emoji">💡</div>
<div data-node-type="callout-text"><strong>Discover the foundation of our current topic by exploring our previous post </strong><a target="_blank" rel="noopener noreferrer nofollow" href="https://pizofreude.hashnode.dev/business-analysis-process-management-for-cycling-superstores" style="pointer-events: none"><strong>here</strong></a><strong>. It's the perfect prelude to this discussion.</strong></div>
</div>

<details data-node-type="hn-details-summary"><summary>TL;DR</summary><div data-type="detailsContent">Business Data Analytics is used to create an executive dashboard for Cycling Superstores, enabling informed data-driven decisions to optimize strategies and accelerate long-term success. The process involves data analysis methods, SQL queries, Excel data cleaning and analysis, and Tableau dashboard creation. Insights gained include identifying sales trends, revenue breakdowns, top-performing customers, and sales reps. The interactive dashboard empowers executives to make informed decisions based on real-time data analysis.</div></details>

<iframe height="250" width="100%" src="https://suno.com/embed/6088f07f-62b1-47b2-b279-571530c3ade7"></iframe>

Welcome back, cycling enthusiasts and business aficionados alike. In our previous [blog](https://pizofreude.hashnode.dev/business-analysis-process-management-for-cycling-superstores), we witnesssed the transformative power of Business Analysis & Process Management (BA&PM) in optimizing Cycling Superstores' operations. We learned how BA&PM equips us with the tools and strategies to navigate the challenging terrain of business processes and achieve peak performance iteratively.

And the journey doesn't stop there. Just like a cyclist meticulously analyzes their performance metrics to achieve peak fitness, Cycling Superstores needs to leverage the power of data to gain a deeper understanding of our customers, operations, and market landscape.

This is where Business Data Analytics (BDA) steps in. Buckle up and prepare to shift gears, because in this blog, we'll unveil the practical of Executive Dashboards – a cyclist's GPS for navigating the ever-changing world of business. Here, we'll explore how Cycling Superstores can harness the power of data visualization to make informed data-driven decisions, optimize strategies, and ultimately, accelerate our journey towards long-term success. We’ll be using SQL, Excel, and Tableau for this project.

> *“The secret of change is to focus all your energy not on fighting the old but on building the new.” — Socrates*

## Data Analysis Methods

We’re going to create an executive dashboard for sales at our aspiring Cycling Superstores, a bicycle retail outlets company of from our childhood dream. After all, as an avid cyclist what’s not to like when generating income from personal hobbies. First, by pulling out the relevant data from the company's database using SQL and then defining the business goals and laying out a plan to find a solution towards the aims. Second, collecting and gathering data from various sources based on set priorities. Third, cleaning the data to remove unwanted redundant and missing values that may impede analysis. Fourth, exploring and analyzing the data using business intelligence tools, data visualization, data mining techniques and predictive modeling. Finally, interpreting the results to gain insights.

![Data analysis process: Ask, Prepare, Process, Analyze, Share, Act.](https://cdn.hashnode.com/res/hashnode/image/upload/v1714645111730/7042a46e-d1a2-4fc2-909f-2148dd87c781.jpeg align="center")

## **Overview of Interactive Sales Dashboard for Cycling Superstores**

### **1\. Project Overview**

**Project Title:** Building an Interactive Sales Dashboard for Improved Decision-Making at Cycling Superstores

**Problem Statement:** Cycling Superstores lacked a centralized and user-friendly platform to analyze sales data. This made it difficult for executives to gain insights into sales performance across various metrics like product category, brand, store location, and customer demographics.

**Data Sources:**

* Relational Database: The project utilized data from Cycling Superstores' internal relational database containing sales transactions, customer information, product details, and store locations.
    

### **2\. Methodology**

The project involved the following steps:

* **Data Acquisition:** SQL queries were written to extract relevant data from the relational database, including order details, customer information, product categories, brands, store locations, and sales rep IDs.
    
* **Data Cleaning:** The extracted data was reviewed and cleaned in Excel to address any missing values, inconsistencies, or redundancies.
    
* **Data Analysis:** Pivot tables and charts were used in Excel to analyze sales trends by year, month, state, store, brand, product category, customer, and sales rep.
    
* **Data Visualization:**
    
    * Excel: Charts like line charts, pie charts, and bar charts were created to present key sales insights in Excel.
        
    * Tableau: Interactive visualizations like line charts, map charts, pie charts, tree maps, and bar charts were developed in Tableau for a more dynamic and informative dashboard.
        
* **Dashboard Creation:**
    
    * Excel: A basic sales dashboard was built in Excel, combining various charts with slicers to allow for interactive filtering by year, state, and store name.
        
    * Tableau: An interactive dashboard was created in Tableau, enabling executives to explore sales data by year, state, store, brand, product category, customer, and sales rep. Action filters were implemented to ensure all charts update dynamically based on user selections.
        

### **3\. Results and Insights**

The project resulted in several key insights:

* Seasonal trends were identified in sales data, highlighting peak sales periods.
    
* Revenue breakdown by state, store, brand, and product category revealed valuable information for targeted marketing campaigns and inventory management.
    
* Top-performing customers and sales reps were identified, allowing for recognition and reward programs to boost customer loyalty and sales motivation.
    

**Overall, the interactive sales dashboards empowered executives at Cycling Superstores to make data-driven decisions regarding product offerings, marketing strategies, inventory allocation, and sales team performance.**

### **4\. Skills and Tools**

* Data Wrangling (Data Cleaning and Transformation)
    
* SQL Querying via PostgreSQL
    
* Data Visualization (Excel Charts, Tableau Dashboards)
    
* Business Intelligence Tools (Tableau)
    
* VS Code as Code Editor with SQLTools extension
    

### **5\. Sharing Information & Action**

* The dashboard link for Tableau Public can be accessed [here](https://public.tableau.com/views/CyclingSuperstoresExecutiveDashboard/CyclingSuperstoresDashboard?:language=en-GB&publish=yes&:sid=&:display_count=n&:origin=viz_share_link).
    
* You can find the GitHub repo for this project [here](https://github.com/pizofreude/cycling-superstores).
    

## **Step 1: Defining the Goal and Data Collection**

First, we need to understand what information management wants to see in the P**roblem Statement**. In this case, we'll create a sales dashboard that provides insights into:

* Total revenue by year and month
    
* Revenue breakdown by state, store, brand, product category, and sales rep
    
* Top performing customers
    

Since this problem relates to internal transactions, we'll retrieve the available data from the company's relational database using SQL.

<div data-node-type="callout">
<div data-node-type="callout-emoji">💡</div>
<div data-node-type="callout-text">For this project purpose, we’ll default to PostgreSQL server with VS Code plugin. Watch how to run PostgreSQL on a database with VS Code below:</div>
</div>

%[https://youtu.be/cc-cSSsGqbA?si=AnKy5bhImRS0H7cU] 

Once [PostgreSQL](https://www.postgresql.org/) installed, we set the following to load the data into our PostgreSQL server database:

1. Download and unzip our [raw data](https://github.com/pizofreude/cycling-superstores/blob/main/Cycling-Superstores-Database.zip) → `Cycling-Superstores-Database.zip`
    
2. Open PostgreSQL server via pgAdmin 4, create a new database and name it `CyclingSuperstoresDB`
    
3. Right-click the new `CyclingSuperstoresDB`database in the PostgreSQL server and select `Query Tool` to open a new query editor tab
    
4. Browse and open the “create objects.sql” from the unzipped file in Step 1 i.e. via Notepad++
    
5. Copy all from “create objects.sql” and paste it in the query editor
    
6. Click the ‘Execute/Refresh’ button or press `F5` to run the script. In the message tab, you should be prompted:
    
    ```sql
    CREATE TABLE
    
    Query returned successfully in 120 msec.
    ```
    
7. Browse and open the “load data.sql” from the unzipped file in Step 1 i.e. via Notepad++
    
8. Copy all from “load data.sql” and paste it in the query editor and confirm success query. Disclaimer: the next VS Code specific steps onwards are only applicable if you’re using VS Code as the database UI as intended in this project. Otherwise, feel free to proceed with the SQL queries directly within pgAdmin4 Query Tool for postgres or any SQL server to your preference.
    
9. Create PostgreSQL Server connection via [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) extension in VS Code and populate:
    
    1. Connection name: `PG Server Local`
        
    2. Server Address: `localhost`
        
    3. Database: `CyclingSuperstoresDB` which is already created in the local PostgreSQL server
        
    4. And set username and password for it accordingly. Username is the *owner* of created database which is `postgres` by default.
        
    5. Test connection and once successful, save it and connect now.
        
    6. Remember to add `.vscode/` in the `.gitignore` to avoid git tracking for confidential information.
        
10. Select the newly connected `CyclingSuperstoresDB` database in the VS Code and we can now building the SQL Query in the `PG Server Local.session.sql`.
    

## **Step 2: Building the SQL Query**

From our [raw data,](https://github.com/pizofreude/cycling-superstores/blob/main/Cycling-Superstores-Database.zip) we'll write an SQL script to generate a dataset containing the following fields:

* Order ID
    
* Customer name (first & last)
    
* Customer city & state
    
* Order date
    
* Sales volume
    
* Revenue
    
* Product name, category, and brand
    
* Store name
    
* Sales rep
    

These fields are spread across several tables in the database. We'll use JOINs to combine the relevant tables based on shared fields like customer ID and product category ID.

Let’s first start with Order ID, Customer name (first & last in one column using CONCAT), Customer city & state and Order date:

```sql
SELECT
	order_id,
	CONCAT(first_name,' ', last_name),
	city,
	state,
	order_date
FROM sales.orders ord
JOIN sales.customers cus
-- we'll combine ord & cus table on their customer_id field
ON ord.customer_id = cus.customer_id
```

Once that is done, we need to specify which information selected belongs to which table e.g. `order_id` belongs to sales order table `ord` whilst `first_name` and `last_name` belongs to `cus` table:

```sql
SELECT
	ord.order_id,
	CONCAT(cus.first_name,' ', cus.last_name) AS customers,
	cus.city,
	cus.state,
	ord.order_date
FROM sales.orders ord
JOIN sales.customers cus
-- we'll combine ord & cus table on their customer_id field
ON ord.customer_id = cus.customer_id
```

We can now query sales volume and revenue, in this case `SUM(quantity)`& `SUM(quantity*list_price)` respectively:

```sql
SELECT
	ord.order_id,
	CONCAT(cus.first_name,' ', cus.last_name) AS customers,
	cus.city,
	cus.state,
	ord.order_date,
	SUM(quantity) AS 'total_units',
	SUM(quantity * list_price) AS 'revenue',
FROM sales.orders ord
JOIN sales.customers cus
-- we'll combine ord & cus table on their customer_id field
ON ord.customer_id = cus.customer_id
```

It would be easier if we also join the sales order items to the sales order table using the order ID field now. We also need to specify that the `quantity` and `list_price` field belongs to the sales order items, `ite`.

```sql
JOIN sales.order_items ite
ON ord.order_id = ite.order_id
```

**Added a**`GROUP BY` clause at the end of the query. This is necessary because we’re using aggregate functions (`SUM`) on the `quantity` and `quantity * list_price` columns. We need to tell SQL how to group the other non-aggregated columns (`order_id`, `full_name`, `city`, `state`, `order_date`). In this case, we’re grouping by each unique order, along with the customer’s name and location, and the order date.

```sql
GROUP BY ord.order_id, customers, cus.city, cus.state, ord.order_date
```

It would be easier if we know the product name as well which can be added in `SELECT` as `product_name` and then join the production table. This enables us to join the production products table to the sales order items table using the product ID field.

```sql
SELECT
	pro.product_name
JOIN production.products pro
ON ite.product_id = pro.product_id
GROUP BY ord.order_id, customers, cus.city, cus.state, ord.order_date, pro.product_name
```

Introducing `category` filter would be another useful metric. It’s found in the production table. Which can be joined from products production table using the category id field.

```sql
SELECT
	cat.category_name
JOIN production.categories cat
ON pro.category_id = cat.category_id
```

For targeted local marketing, it makes sense to add `store_name` to ascertain which stores sell what products the most. It’s found in the store’s `sales` table. And this table can be joined with the sales order table using the store ID field as well as `GROUP BY` →`sto.store_name`:

```sql
SELECT
	sto.store_name
JOIN sales.stores sto
ON ord.store_id = sto.store_id
```

Finally, we’d love to know the sales rep who made the sales. Employee bonus goes a long way. We need to concate `first_name` and `last_name` from sales staff table and join this table with the sales orders table using the `staff ID` field as well as `GROUP BY` it:

```sql
SELECT
	CONCAT(sta.first_name, ' ', sta.last_name) AS sales_rep
JOIN sales.staffs sta
ON ord.staff_id = sta.staff_id
```

That will do for our query and here’s the sneak peek of the structured data:

![Sneak peak at structured data with the SQL Query above.](https://cdn.hashnode.com/res/hashnode/image/upload/v1714646331580/838b947d-b00b-4735-a67a-28e3325012a5.png align="center")

For ease of syncing dataset from Postgres to other platforms such as MS Excel, we can create a new table in Postgres Cycling Superstore Public database:

```sql
CREATE TABLE public.cc_dashboard AS
```

Our dataset is comprehensively structured and includes several fields: **Order IDs**, **Customer Names** (combining first and last names), **Customer Location** (city and state), **Order Dates**, **Total Units Sold** per order, **Revenue Generated** per order, **Product Names**, **Bike Brands**, **Sales Store Location**, and the **Sales Representative** associated with each transaction.

We can move on the Step 3 of the data analysis process, which is crucial for ensuring the integrity of the sale records, involves **cleansing the data** to eliminate any **unwanted, redundant, or erroneous values** that could hinder the analysis.

## **Step 3: Data Cleaning in Excel**

After importing the data from the Postgres database into Excel, we'll check for missing values, redundancies, or inconsistencies that might hinder analysis. In our case, the data appears clean and ready for further exploration.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714646417295/cbe17bd9-86b5-4278-a41f-0f552a92e2a1.png align="center")

## **Step 4: Data Analysis and Visualization in Excel**

Now, it's time to create some visuals. We'll use Excel's pivot tables and charts to present the data in a clear and concise way. Here are some examples of the charts we'll create:

* **Total Revenue:** Pivot tables and charts showing total revenue by year and month. Since both table based from the same dataset, we need to decouple them by using command `[Alt + D, P](<`[`https://sheetleveller.com/open-pivot-table-wizard/`](https://sheetleveller.com/open-pivot-table-wizard/)`>)` for Windows when creating the second table.
    
    * **By Year:**
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714724784443/cdc7f978-1892-4164-9cf8-a1eb30f5218d.png align="center")
        
    * **By Month:**
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714724935399/7c1aab32-08db-415a-8739-c9ab67a1e827.jpeg align="center")
        
        * **By Chart:**
            
            ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725215435/d7000794-694c-4cb4-90af-9a75df5e7a80.jpeg align="center")
            
        * **Revenue Breakdown:** Charts illustrating revenue by state, store, product category, and top 10 customers.
            
            * Revenue by State:
                
                ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725327043/4bd6a522-6fcc-417b-a527-e2f9e0b1b290.jpeg align="center")
                
            * Revenue by Store:
                
                ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725390322/70aab417-4151-470a-8144-5b92a2646070.jpeg align="center")
                
            * Revenue by Product Category:
                
                ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725486460/908d809e-84f7-454d-8db1-42c14a4090fb.jpeg align="center")
                
            * Top 10 Customers:
                
                ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725573756/04334c64-defa-4e69-a655-a3e37f0e869f.jpeg align="center")
                
            * Revenue per Sales Rep:
                
                ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725657372/189e6b0f-7489-42ae-83fa-6cd10299a84a.jpeg align="center")
                

## **Step 5: Creating an Interactive Dashboard in Excel**

We'll combine the charts into a single dashboard to provide a holistic view of sales performance. Additionally, we can add **slicers** to filter the data by year, state, and store name, allowing for interactive exploratory data analysis (EDA).

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714725714891/3a371f77-85f9-402c-bcde-193f4184fa5c.jpeg align="center")

1. Use the slicers to select the desired year, state, or store name.
    
2. Observe how the charts dynamically update to reflect the filtered data.
    
3. Explore different combinations of filters to uncover trends and patterns in sales performance.
    

By leveraging this interactive dashboard, stakeholders can make informed decisions based on real-time data analysis.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714726064234/006aa170-630b-4e0d-9722-4629b839e2f3.jpeg align="center")

While Excel offers basic dashboarding capabilities, it might not be ideal for very large datasets. We acknowledge this limitation and introduce Tableau as an alternative for complex BI visualizations especially those who works with large dataset, requires advance viz and guided analysis feature.

## **Step 6: Building an Interactive Dashboard in Tableau**

We'll import the Excel data set into [Tableau Desktop Public Edition](https://www.tableau.com/en-gb/products/public/download) and create interactive visualizations:

* **Revenue per Year & Month:** Bar and Line chart showing yearly & monthly revenue with a year filter.
    
* **Revenue by State and Store:** Map and pie charts for revenue breakdown by state and store.
    
* **Revenue by Product Category:** Treemap for revenue breakdown by product category.
    
* **Top Customers and Revenue per Sales Rep:** Bar charts with a parameter filter to control the number of displayed key figure[s.](https://www.tableau.com/en-gb/products/public/download)
    

### **Adding Interactivity in Tableau**

We'll create action filters in Tableau to allow management to explore the data dynamically. By clicking on a specific year, state, or sales rep in one chart, all other charts will update to reflect the chosen filter.

**Final Touches and Sharing**

We'll finalize the design of both the Excel and Tableau dashboards, ensuring they are visually appealing and user-friendly. Finally, we'll upload the Tableau dashboard to an online server for easy access and sharing.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714726776969/c7b9dc6a-b52e-41e9-852f-bbbf22e4c7b2.png align="center")

For interactive Tableau Dashboard, feel free to visit [Tableau Public](https://public.tableau.com/views/CyclingSuperstoresExecutiveDashboard/CyclingSuperstoresDashboard?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link).

Based on the findings from the dashboard and discussion with stakeholders, we can suggests some potential areas for further investigation:

* **Sales Rep Performance:** The revenue per sales rep chart allows management to identify top performers and potentially low performers. They could use this information to implement sales incentives, provide additional training, or optimize team structures.
    
* **Sales Trends:** By viewing revenue per year and month charts, management can identify seasonal trends or track the effectiveness of marketing campaigns. They could use this information to adjust sales strategies or resource allocation throughout the year.
    
* **Geographic Performance:** The map chart reveals sales distribution across different states. Management could use this information to focus marketing efforts on underperforming regions or tailor product offerings based on regional preferences.
    
* **Customer Analysis:** Although not yet carried out, insights via customer survey from top customer analysis can be conducted to understand their buying patterns and preferences. This could inform targeted marketing campaigns or loyalty programs.
    

Other than that, we can point out additional analysis to consider:

* **Drill down analysis:** The current visualizations provide a high-level overview. Management might want to explore the data further by drilling down into specific regions, product categories, or sales rep performance for a particular month.
    
* **Goal setting and monitoring:** The dashboard can be used to set performance goals and monitor progress over time. For example, management could set annual sales targets by region or track the effectiveness of a new marketing campaign by comparing sales figures before and after the launch.
    
* **Guided analysis**: Once we gain more insights from the above analyses, we can formulate clearer questions and move on guided analysis to answer these specific questions as data-driven business decisions.
    

By using the dashboard interactively and asking further questions, management can gain deeper insights and take concrete actions to improve the company's performance.

Based on our current dashboard, we could oversee some additional columns of data that could be useful:

**Customer Data:**

* **Customer Lifetime Value (CLTV):** This metric indicates the total revenue a customer is expected to generate over their relationship with the company. It can help identify valuable customers and guide targeted marketing campaigns.
    
* **Customer Acquisition Cost (CAC):** This metric represents the cost of acquiring a new customer. By comparing CLTV to CAC, management can assess the profitability of customer acquisition strategies.
    
* **Purchase Frequency:** This metric tracks how often a customer makes a purchase. It can help identify loyal customers and inform strategies to encourage repeat business.
    
* **Average Order Value (AOV):** This metric represents the average amount a customer spends per order. This can be used to identify opportunities to upsell or cross-sell products.
    

**Product Data:**

* **Profit Margin:** This metric shows the profit earned on each product after accounting for its production and selling costs. It can help guide product pricing strategies and identify areas for cost optimization.
    
* **Product Category:** Granular product category data beyond the current brand categorization can allow for more focused analysis of sales trends and customer preferences within specific product types (e.g., road bikes vs. mountain bikes).
    
* **Product Cost:** Knowing the cost of each product would be essential for calculating profit margins.
    

**Sales Data:**

* **Discount Used:** Tracking the type and amount of discounts offered can help analyze their effectiveness in driving sales and identify potential areas for optimizing pricing strategies.
    
* **Marketing Channel:** Identifying the marketing channel through which a sale was generated (e.g., online advertising, social media, in-store promotion, [HAQQ](https://haqq.network/) Web3 challenges) allows for a more targeted evaluation of marketing campaign performance.
    
* **Customer Acquisition Channel:** Understanding how customers were initially acquired (e.g., referral program, online search, ) can inform strategies for attracting new customers.
    

**Time-Based Data:**

* **Day of Week:** Sales data segmented by day of the week can reveal patterns in customer buying behavior and optimize staffing or marketing efforts accordingly.
    
* **Hour of Day:** Similar to day of the week, understanding sales patterns by hour of the day can inform decisions about online store operating hours or targeted marketing campaigns during peak buying times.
    

Including some of this data could enable a richer analysis of sales performance, customer behavior, and marketing effectiveness. The specific additional data points that would be most beneficial will depend on the company's specific goals and areas of interest.

## **Conclusion**

This comprehensive portfolio showcases business data analytics using SQL, create insightful visualizations with Excel and Tableau, and build interactive dashboards to communicate complex information effectively.

Overall, the dashboard empowers management to make data-driven decisions about sales strategies, resource allocation, marketing campaigns, and potentially customer relationship management.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1714727808106/0c0d0661-6bc9-4700-b882-adf1e4658117.gif align="center")

---

**Warning: May cause increased data enthusiasm. Read the next post in our**[**Data Series**](https://pizofreude.hashnode.dev/series/data-series)**at your own risk.**

<div data-node-type="callout">
<div data-node-type="callout-emoji">💡</div>
<div data-node-type="callout-text"><strong>Hungry for more data?</strong> Share the data cookies with your network and <strong>subscribe to our newsletter</strong> for the latest insights delivered hot to your inbox.</div>
</div>

**Want to see more content like this?** Consider **supporting us** by hitting the **Sponsor button** if you found value in our articles. 💚