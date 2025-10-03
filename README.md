# superstore-sales-analysis

## 1. Project Objective

[cite_start]The primary goal of this task was to create a basic, interactive sales dashboard to visualize and summarize sales performance across key business dimensions: product (category), geographic region, and time (month)[cite: 7].

[cite_start]The outcome is to demonstrate an understanding of how to build a clean, effective dashboard and translate data into visual summaries for business users[cite: 26].

## 2. Tools and Data

* [cite_start]**Primary Tool:** Power BI (Used for Data Modeling, DAX calculations, and Visualization) [cite: 9]
* [cite_start]**Dataset:** `Superstore_Sales.csv` [cite: 12]
* [cite_start]**Key Columns Used:** `Order Date`, `Region`, `Category`, `Sales`, and `Profit`[cite: 12].

## 3. Methodology and Steps

[cite_start]The project followed the prescribed mini-guide [cite: 16] to transform the raw data and develop the visualizations.

### Data Preparation and Modeling
1.  [cite_start]**Data Import:** Imported the `Superstore_Sales.csv` file into Power BI[cite: 17].
2.  **Date Transformation (DAX):** Created two calculated columns to ensure correct chronological sorting on the time-series chart:
    * [cite_start]`Month-Year Text`: Used the `FORMAT` function (`"MMM YYYY"`) for display on the X-axis[cite: 17].
    * `Month-Year Sort`: Used the `FORMAT` function (`"YYYYMM"`) to enable proper sorting.
3.  **Data Sorting:** Applied a sort by column to set `Month-Year Text` to sort by `Month-Year Sort`.

### Dashboard Design and Visualizations

The dashboard was built using three core visuals and an interactive filter:

| Visual | Data Used | Purpose |
| :--- | :--- | :--- |
| **Line Chart** | Sales over **Month-Year Text** | [cite_start]To analyze sales trends and seasonality[cite: 18]. |
| **Bar Chart** | Sales by **Region** | [cite_start]To compare performance across different geographic markets[cite: 19]. |
| **Donut Chart** | Sales by **Category** | [cite_start]To show the proportional contribution of each product category to total sales[cite: 20]. |
| **Interactive Filter** | **Region** or **Category** Slicer | [cite_start]Allows users to filter the entire dashboard instantly[cite: 22]. |

## 4. Key Findings (Insights)

Based on the completed dashboard, here are the main insights derived from the data analysis:

*(Note: Replace the examples below with the 3-4 specific insights generated from your final dashboard.)*

1.  [cite_start]**[Insert Insight 1 Here]** (e.g., Sales exhibit strong seasonality, peaking significantly in November and December.) [cite: 24]
2.  [cite_start]**[Insert Insight 2 Here]** (e.g., The West region consistently generated the highest total sales, accounting for X% of the overall revenue.) [cite: 24]
3.  [cite_start]**[Insert Insight 3 Here]** (e.g., Office Supplies is the highest-volume category but shows the lowest profit margin compared to Furniture and Technology.) [cite: 24]

## 5. Deliverables

* [cite_start]`sales_dashboard_screenshot.png` (or `.pdf` export of the final report view) [cite: 14]
* [cite_start]`insights.txt` (or incorporated directly into this README) [cite: 15]
* [cite_start]`superstore_sales.csv` (the dataset used) 
* (Optional: Power BI `.pbix` file)
