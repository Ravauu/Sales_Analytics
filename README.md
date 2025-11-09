# Sales_Analytics
 # 📊 Sales Analytics & Optimization Project

The project presents a complete sales data analysis process — from data cleaning in Power Query, through analytical exploration in Excel (pivot tables, KPI calculations), to building an optimization model using Solver and visualizing the results in Power BI

## 1️⃣ Data Import & Preparation (Power Query)

<img width="1720" height="835" alt="image" src="https://github.com/user-attachments/assets/1d96a565-d113-42e8-a499-680bd2eb99e3" />  

**Actions Performed:**  

- Loaded the dataset into Power Query  
- Removed empty rows, errors, and duplicate records  
- Changed data types (dates, numbers, currencies)  
- Corrected formatting for key columns: `ORDERDATE`, `SALES`, `QUANTITYORDERED`  
- Added helper columns such as `Year`, `Month`, `Country`  

## 2️⃣ Sales Analysis and Order Status

### 📦 Order Status

<img width="1068" height="355" alt="image" src="https://github.com/user-attachments/assets/f86a0d45-b2be-419d-8a42-dc1ce6b96c48" />

**Description:**  

All order statuses (Shipped, Disputed, Cancelled, On Hold, etc.) were summarized along with their respective counts  

**Results:**  

The vast majority of orders (over 2600) have the Shipped status, indicating a high fulfillment rate and an efficient sales process.  
A small share of Cancelled and Disputed orders (<5%) confirms good customer service quality.  

### 💰 Sales per Product  

<img width="1008" height="439" alt="image" src="https://github.com/user-attachments/assets/c0f188ae-ed1d-4501-a2de-57deacae30d9" />

**Description:**  

Comparison of the 10 best-selling products based on total sales value  

**Results:**  

Product S18_3232 clearly dominates in terms of total sales (~288K $),
while the remaining products stay within a similar range of 130–190K $, indicating a consistent sales distribution across the rest of the product portfolio.  

### 📅 Sales per Year  

<img width="974" height="354" alt="image" src="https://github.com/user-attachments/assets/3114aa6c-f9c8-4d68-9784-513c9271421c" />

**Description:**  

Total sales aggregated by year (2003–2005)  

**Results:**  

Year 2004 recorded the highest sales level (~4.7M $),
while 2005 shows a decline (~1.79M $), which is explained by a limited data range — only five months of transactions available for that year  

### 🌍 Average Margin per Country  

<img width="1011" height="459" alt="image" src="https://github.com/user-attachments/assets/2f8da51c-161a-4376-8953-441a68913f72" />

**Description:**  

The average profit margin (%) was calculated for each country and visualized on a world map  

**Results:**  

The highest margins are observed in Scandinavian countries (Denmark, Sweden, Norway) and Switzerland,
while the lowest occur in the Asian region (Philippines).
The global average margin equals approximately **~34%**.  

### 🧮 Sales & Profit per Customer  

<img width="849" height="461" alt="image" src="https://github.com/user-attachments/assets/d94e6d70-8036-40a2-b62e-c8b9b3da3950" />

**Description:**  

Customer ranking based on total sales and profit  

**Results:**  

The largest customer is Euro Shopping Channel (~912K $ in sales),
followed by Mini Gifts Distributors Ltd. (~655K $).
Together, these two clients generate over 15% of total company sales  

### 📊 Pareto Analysis – Customer Sales  

<img width="831" height="505" alt="image" src="https://github.com/user-attachments/assets/790490a8-2f32-4d14-926d-84602089a865" />

**Description:**  

Pareto (80/20) analysis based on the share of each customer in total sales  

**Results:**  

The largest clients, such as Euro Shopping Channel and Mini Gifts Distributors Ltd., generate the highest individual sales shares (around 9% and 6%).
However, the remaining sales are distributed evenly across many smaller customers.
The Pareto principle (80/20) is not fully confirmed here — 80% of total revenue is reached only after including the majority of customers,
which indicates a broad and well-balanced customer base.  

### 📈 Sales Trend Over Time (2003–2005)  

<img width="687" height="382" alt="image" src="https://github.com/user-attachments/assets/10a51e32-6106-4ea5-8b5d-b70cceafcad5" />  

**Description:**  

Monthly sales trends were analyzed for the years 2003–2005 to identify seasonal patterns and performance dynamics  

**Results:**  

Sales show consistent quarterly fluctuations with a significant peak in Q4 each year, indicating strong year-end performance.
The upward trendline reflects overall business growth, while recurring Q4 spikes suggest increased demand during the holiday season.  

### 🌎 Top 5 Product Sales by Country  

<img width="737" height="474" alt="image" src="https://github.com/user-attachments/assets/8f9eb923-4c09-44a7-961d-97b0a15eeb9a" />  

**Description:**  

Visualization compares the sales of the five best-selling products across all countries  

**Results:**  

The USA leads by a wide margin in total product sales, followed by France and Spain.
Most countries demonstrate balanced distribution among the top products, with no single item monopolizing the market.  

### 🗺️ Total Sales by Country (Top 5 Products Combined)  

<img width="743" height="485" alt="image" src="https://github.com/user-attachments/assets/a10b69f2-91df-4642-b7fb-ba0748c5da6d" />  

**Description:**  

Geographical visualization of total sales for the top 5 products combined  

**Results:**  

The United States dominates overall sales, generating over $370K, followed by Spain, France, and Australia.
European markets perform strongly, while Asian and smaller regions contribute less significantly to global totals.  



