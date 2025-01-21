
# Revenue-Insights

### Dashboard Link : 

## Problem Statement
The primary goal of this analysis is to provide actionable insights for the company by identifying trends in sales performance, discount patterns, and their impact on revenue. Specifically, we aim to address the following key questions:

### Trends Across Time:

- Analyse sales trends over time (e.g., monthly, quarterly, yearly) to identify patterns or anomalies.
- Determine whether revenue, profit, and discount rates fluctuate during specific periods and highlight the factors contributing to these changes.

### Products Receiving the Most Discounts:

- Identify which products or categories are consistently receiving higher discounts.
- Investigate whether these discounts correlate with higher or lower sales volumes, profitability, or specific regions/customers.
- Assess whether these discounts are being used strategically or whether they might be eroding profitability.

### Recommendations to Increase Revenue:

- Based on the identified trends and discount patterns, provide tailored recommendations to optimise revenue.
- Explore opportunities to reduce unnecessary discounts, target high-performing products, or focus on underperforming regions.
- Suggest strategies for improving profit margins, such as bundling, targeted marketing, or introducing new pricing policies.

## Steps to Load and Preprocess Data in Power Query:

### Load Dataset:

- Open Power BI or Excel → Get Data → From Excel Workbook → Select Financial Sample.xlsx → Click Transform Data.

### Data Cleaning:

- Remove duplicates.
- Handle missing values (replace with 0 or "Unknown").
- Change data types (e.g., Date, Decimal Number).

### Data Transformation:

- Split columns (e.g., Region-Country).
- Extract Date parts (Year, Month, Quarter).
- Add calculated columns (e.g., Discount %, Profit Margin).

### Filtering and Grouping:

- Filter irrelevant rows or columns.
- Group data by Product, Region, or Date for aggregations (e.g., Total Revenue, Profit).

### Finalise:

Sort, rename columns, and load the cleaned dataset back.

## Insights

### Trend across time

- **Peak Sales in October**: £25,142K, followed by December (£18,343K) and September (£11,575K). This suggests significant seasonal sales likely due to Christmas holiday promotions.
- **Lowest Sales in March**: £6,124K, indicating a potential off-peak period may be because of closing year end activity.
- **Consistent Increases in June and September**: Sales in these months are relatively high, suggesting effective mid-year promotions or marketing campaigns. Potential to increase sale due to summer holidays and can focus more on Paseo and Velo which is hybrid bike, casual rides in urban areas, parks, or bike paths used for commuting or city riding will attract the eye of children and teens.

### Segment Category
1. **Government Segment**: Current Sales: £53M
- ***Strategy***: Enhance relationships with government agencies, focus on long-term contracts, and promote high-quality, reliable products suitable for government use. As this is the highest revenue generating segment
2. **Small Business Segment**: Current Sales: £42M
- ***Strategy***: Can offer tailored solutions and flexible pricing plans to attract more small businesses. Highlight success stories and case studies to build trust.
3. **Enterprise Segment**: Current Sales: £20M
- ***Strategy***: Provide comprehensive enterprise solutions, enhance customer support, and offer bespoke services to meet specific enterprise needs.
4. **Midmarket and Channel Partners Segments**: Current Sales: £2M each
- ***Strategy***: Conduct market research to understand their needs and develop targeted marketing strategies. Consider exclusive offers or bundled packages.

### Product Category

- **Paseo**: Current Sales: £33.0M
Strategy: Continue to innovate and maintain high quality. Invest in marketing campaigns that highlight product benefits and customer testimonials.
- **VTT and Velo**: Current Sales: £20.5M and £18.3M, respectively
Strategy: Consider bundling these products with complementary offerings to increase sales. Promote them during peak sales months with special discounts.
- **Amarilla, Montana, and Carretera**: Current Sales: Amarilla (£17.7M), Montana (£15.4M), Carretera (£13.8M)
Strategy: Focus on improving product features and marketing them more aggressively. Offer promotions or discounts to boost sales.

### Key findings

**Optimize Discount Strategies**:
- ***High Discounts***: Reduce high discounts on VTT and Paseo, as they do not significantly boost sales volumes and lead to low profit margins.
- ***Medium Discounts***: Focus on maintaining medium discounts for Velo and Amarilla, as this strategy effectively balances sales and profitability.
- ***Low Discounts***: Continue offering low discounts on Montana and Carretera to sustain high sales volumes and reasonable profit margins.
- ***No Discounts***: Identify the key factors that make no discount products perform well and apply these strategies to other products where possible.

**Marketing and Promotions**:
- Highlight the unique features and benefits of products with no discounts to maintain their high perceived value.
- We can use targeted marketing campaigns during peak sales months to boost sales further without relying heavily on discounts.
- Cross-sell strategy can be applicable in terms of promotional activity. And can deep dive more on customer behavior.

### Recommendations given to stakeholder

**Increase Revenue**:

- ***Focus on High-Performing Products***: Increase marketing for Paseo and VTT which is top selling product can catch eye of children and teens.

- ***Optimize Discounts***: Reevaluate discount strategies to maximize profit margins may be cross-sell improve the revenue in lowest selling products.

- ***Expand High Revenue Segments***: Invest more in Government and Small Business segments.

- ***Seasonal Promotions***: Capitalize on peak sales months (October, November, December) with targeted promotions. Product like VTT and Montana used by people during tracking in holidays.

**Different Approach**:
- Data-Driven Marketing: Use insights from sales distribution by country to tailor marketing campaigns.
- Customer Feedback: Implement feedback loops to understand customer preferences and improve product offerings.
- Diversify Product Line: Introduce new products or variants to capture more market share.

## Dashboard Overviewhttps: 
//www.markdownguide.org/basic-syntax/
