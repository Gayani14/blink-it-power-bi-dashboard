# Blinkit-power-bi-dashboard

Welcome to the blink it power bi dashboard repository! This project aims to provide insightful analysis and visualization of blink it sales using Power BI.

# This is my powerbi dashboard-
https://app.fabric.microsoft.com/reportEmbed?reportId=b4ffb5b1-71e4-4c68-8cd4-59947a79f2a9&autoAuth=true&ctid=73a9e30d-f408-43f6-829e-36358204db49

This project conducted a comprehensive analysis of Blinkit's sales data. It involved examining sales patterns over time, understanding customer satisfaction through ratings, and studying the characteristics of different outlet types. The analysis aimed to uncover key factors influencing sales performance, such as the outlet's size and location.

### KPIs

Total Sales: Overall revenue generated.

Average Sales: Revenue per sale.

Number of Items: Total items sold.

Average Rating: Customer rating for items.

### CHARTS

Donut Chart: Revealed that certain product categories, such as fresh produce and dairy, were the top revenue generators. This insight helped in strategic planning for inventory management and promotional activities.

Matrix Chart: This chart showed that sales were higher in urban areas than in rural areas, and certain months, like December, had peak sales due to holiday shopping. This information helped optimise inventory levels and plan marketing campaigns.

Clustered Bar Chart: Indicated that regions with higher sales also had more customer complaints, suggesting a need for improving service quality in those areas. It also highlighted underperforming regions that required targeted marketing efforts.

Stacked Bar Chart: Demonstrated that while some segments, like premium products, had higher sales, they also had a lower inventory turnover, indicating overstocking issues. This prompted a review of stocking policies.

Line Chart: Identified consistent growth in sales over the last four quarters but also revealed a significant drop during a specific period, which was traced back to a supply chain disruption. This led to measures to strengthen supply chain resilience.

Slicers: Allowed detailed analysis of customer purchasing patterns by applying filters for different demographics and regions. This interactive feature facilitated tailored marketing strategies.

Metrics: Provided a snapshot of critical performance indicators, such as a steady increase in the average order value, which indicated effective upselling strategies. It also showed a dip in the customer satisfaction score, prompting an immediate review of customer service protocols.

Cards: Highlighted that the total number of new customers had increased by 20% in the last quarter, signalling successful customer acquisition strategies. It also revealed that the inventory turnover rate was slower than industry, indicating a need for inventory optimisation.

### DAX MEASURES

Avg Rating = AVERAGE('BlinkIT Grocery Data'[Rating]) 

Avg Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

No of Items = COUNTROWS('BlinkIT Grocery Data') 

Total Sales = SUM('BlinkIT Grocery Data'[Sales])

### METRICS

<img src="https://i.imghippo.com/files/Ap9sG1727365533.png">

## Summary of Findings

Total sales reached $1.20M with an average sale of $141, encompassing 8553 items and an average customer rating of 3.9.

Low-fat products were more popular than regular products. Fruits, vegetables, and snack foods were top-selling item types.

Tier 3 locations and medium-sized outlets generated the highest sales.

The average customer rating was 3.9, indicating generally positive feedback.

The year 2018 saw the highest sales, while 2011 was comparatively lower. Other years exhibited average performance.


### DASHBOARD
<img src="https://i.imghippo.com/files/9xMGP1727365515.png">


