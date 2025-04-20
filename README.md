# 📊 DATACO. Supply Chain Analytics

## **Project Overview**
Interactive Power BI dashboards analyzing order fulfillment, customer segmentation, and market performance for DATACO.'s global supply chain.
# 🌐 Supply Chain E-Commerce Process Flow Dashboard
**Interactive Power BI dashboard** visualizing the end-to-end supply chain workflow from order receipt to delivery, with dynamic bookmarks for seamless navigation.


---
### **1. Process Flow Visualization**
- **4 Key Stages** with KPI summaries:
  1. **Order**  
     - Total Orders: 66K  
  2. **Customer (B2B)**  
     - Segments: Consumer (55%), Corporate (30%), Home Office (15%)
  3. **Market**  
     - Top Market: Europe (33.3 % of orders)
  4. **Shipping**  
     - On-Time Delivery: 45%  

### **2. Interactive Bookmarks**
- One-click navigation between stages:  

  [Order Stage] ➔ [Customer Stage] ➔ [Market Stage] ➔ [Shipping Stage]

![image](https://github.com/user-attachments/assets/1f51c34e-e1e1-45c2-b3fe-9abf20eb8a50)


---

## **Dashboard Features**
### **1. Process Flow Visualization**
- **4 Key Stages** with KPI summaries:
  1. **Order**  
     - Total Orders: 66K  
     - Avg. Processing Time: 2.3 days
  2. **Customer (B2B)**  
     - Segments: Consumer (55%), Corporate (30%), Home Office (15%)
  3. **Market**  
     - Top Market: USCA (38% of orders)
  4. **Shipping**  
     - On-Time Delivery: 89%  

### **2. Interactive Bookmarks**
- One-click navigation between stages:  
  ```markdown
  [Order Stage] ➔ [Customer Stage] ➔ [Market Stage] ➔ [Shipping Stage]

**Key Features**:
- Dynamic parameter controls (e.g., market filters, discount rate adjustments)
- Profitability analysis with cost/discount simulations
- Geo-mapping of order distribution and shipping efficiency

## **Dashboards**
| Dashboard | Purpose | Key Metrics |
|-----------|---------|-------------|
| [Overview](Dashboards/1_Overview.pbix) | Case study overview | Total CST (21K), Market Places (5), Sales (35.214M) |
| [Orders](Dashboards/2_Orders.pbix) | Order performance and sales | Total Orders (66K), Profit Margin (10.81%) |
| [Customer Analytics](Dashboards/3_Customer_Analytics.pbix) | B2B - B2C intermediary tracking | Retention Rate, CLV, CST Segment |
| [Market Performance](Dashboards/4_Market_Performance.pbix) | Regional analysis | Orders & Sales by Market, Sales % by Region |
| [Shipping Efficiency](Dashboards/5_Shipping_Efficiency.pbix) | Logistics optimization | On-Time Delivery %, Late Dlivery%, Orders Fulfilment, Shipping Mode|
| [Discount Problem Solving](Dashboards/6_Discount.pbix) | Discount Overcome | Parameter Adjustment, Negative Profit / Adjusted, Profitability Segment |

## **How to Use**
1. **Clone this repo**
 
  https://github.com/Israa-Essam/DataCo-SMART-SUPPLY-CHAIN-FOR-BIG-DATA-ANALYSIS

📈 Trends & Patterns
Annual Order Volume
2015: 21K orders
2016: 21K orders
2017: 22K orders (Peak year)
2018: Data incomplete (January Only)

# 📊 DATACO Supply Chain Overview Dashboard

![image](https://github.com/user-attachments/assets/2ab3e6c1-9dd5-4218-903f-28eef0ae8ce0)


## 📌 Key Metrics

| Metric                | Value       | Detail                     |
|-----------------------|-------------|----------------------------|
| **Total Orders**      | 66K         |                            |
| **Total Sales**       | $35.214M    |                            |
| **Cancelled Sales**   | $1.57M      | 4.27% of total sales       |
| **Total Profit**      | $3.806M     | 10.81% margin              |
| **Negative Profit**   | -$3.71M     | 9.53% of Sales             |

## 🌐 Global Coverage

    Market Sales
    "Africa" : 2.2 M
    "Europe" : 10.4 M
    "LATAM" : 9.8 M
    "Pacific Asia" : 7.9 M
    "USCA" : 4.8 M

🚨 Critical Alert

- 9.53% of Sales have negative profit, Its cost is higher than the profit!
+ Use discount parameter to optimize profitability.
+ Discount dashboard to optimize the negative profitability by product using the parameter.

# Orders Dashboard  
**Power BI Dashboard** for analyzing order data across markets, departments, and years.  
![image](https://github.com/user-attachments/assets/6c4654ce-2ab4-4fad-8059-a605a0e82339)


## Features  
- **Dynamic Filters**: Toggle between Total Orders, Sales, Profit, and Profit Margin.  
- **Market Segmentation**: Drill down by region (Africa, Europe, LATAM, etc.).  
- **Department Rankings**: Fan Shop and Apparel dominate sales.  
- **Yearly Trends**: Profit margins peaked in 2015 (11.17%).
- **Top Products**: For each market top selling products.

## How to Use  
1. Select a **Market** to filter data.  
2. Use the **parameter slicer** to switch between metrics. (Sales-Profit-Profit Margin-Orders) 
3. Hover over visuals for detailed insights.  

 # Customer Dashboard  
**Power BI Dashboard** for analyzing B2B/B2C customer segments and transactional behavior.  

## Features  
- **Segment Metrics**: Compare Consumers (18.3M), Corporate (10.7M), and Home Office (6.2M).
- **Customer Churn**: Retention Rate (59.16%), 2015 (92.16), 2016 (92%), and 2017 (53.07%). 
- **Regional Focus**: Puerto Rico (38.41%) vs. EE.UU. (61.59%).  
- **Customer Cards**: Drill into individual metrics like AOV, CLV, and lifespan.  
- **Payment Trends**: Debit/Transfer dominate order volume.  

## How to Use  
1. Filter by **Market** or/and **Customer Segment**.  
2. Toggle the **parameter slicer** to switch between sales, profit, and orders.  
3. Click on customer names for detailed profiles usinf the ID slicer.


# 🌍 DATACO Market Performance Dashboard

![image](https://github.com/user-attachments/assets/1e14c094-a53f-4525-81bb-84d3b7c639c1)




## 📊 Key Metrics
    Africa [Total Shipped] --> [4K Orders] to 49 Countries
    Africa --> [165 Canceled Orders]
    Africa --> [45.76% Products Sold]
    Africa --> [21.74% Order's Region %]
 🌐 Market Distribution
    total Orders by Market
    "Europe" : 18.56K
    "LATAM" : 17.18K
    "Pacific Asia" : 17.58K
    "USCA" : 8.58K
    "Africa" : 3.58K
🚚 Delivery Performance

 On-Time vs Late Deliveries
    x-axis Markets
    y-axis Orders
    "Late"
        Europe: 10.2K
    "On Time"
        Europe: 8.4K
🔍 Regional Breakdown
Africa Performance

    [North Africa] --> [Primary Hub]
    [Other Africa] --> [Emerging Markets]

# 🚚 DATACO Shipping Mode Performance Dashboard


![image](https://github.com/user-attachments/assets/b7a3a55d-762f-4282-beb0-caef6fdfcb53)




## 📊 Shipping Mode Overview
   Shipping Mode Distribution
    "Standard Class" : 59.81%
    "Second Class" : 19.43%
    "First Class" : 15.33%
    "Same Day" : 5.43%
Optimization Recommendations:
First Class :
95% of the Deliveries are late, Scheduled shipping time = 1 day, While the real days are 2.
Recommendations - Adjust the scheduled to 2 Days.

Second Class: 
80% late deliveries. Regions almost have the same late percentage.
Recommendations - Adjust the scheduled todays to be 3-4 days.
To achieve more than 90% of the orders on time

Same Day Delivery :
About 46% - 51% of the orders are late, only for average of half a day.
Recommendations - Needs to be adjusted for 24 hours delivery. and not the same for every region.
LATAM is the top in late deliveries.  (In the Caribbean & South America regions)  scored the top late %. 
Southern Africa region in Africa has the top % 
West of USA region in the USCA
The rest of the regions scored about maximum 48% of late deliveries.

Standard Class:
The largest number of orders are shipped in this mode 59.8%.
Therefore it needs more effort to fulfill on time as 38% are late.
(Under each Market --- > choose the regions and countries that resulted highest late percentage, and try to improve the service in this area for better performance)

# 💰 DATACO Customer Profitability / Discount Adjustment Dashboard


![image](https://github.com/user-attachments/assets/575d2476-45b2-4a99-b6b0-aa5d869dd3c6)





## 🔄 Dynamic Discount Optimization

Flowchart LR
    A[Product] --> B{Profit < 0?}
    B -->|Yes| C[Adjust Discount]
    B -->|No| D[Maintain Rate]
    C --> E[Recalculate Profit]
📊 Customer Segmentation

Customer Profit Segments
    "High-Value (1500-2442)" 
    "Profitable (500-1500)" 
    "Neutral    (0-500)" 
    "Moderate Loss (-2000-0)"
    "High Loss (<-2000)"
    For each customer loosing we could select the ID & use the parameter to reduce the discount and overcome the negative profit.
    First Sale ranked customer results a moderate -ve loss, after optimizing the total discount for this CST by 0.81 %, the -ve profit was turned to +ve.

📈 Optimization Results
![image](https://github.com/user-attachments/assets/17cf2c9f-ff12-4448-b30c-db7f7d4acd4e)



This example shows:
1. Interactive discount adjustment for specific product (Sole E35 Eliptical).
2. Visual feedback on profit impact to overcome the -ve profit the discount needs to decrease by 0.27%
3. Use Slicer per year for further adjustment, and sort by lowest profit for higher products loss.

The last 2 slides contains the detailed problem solving of the 2 main issues according to the dataset and an how to improve the performance and solve it.
