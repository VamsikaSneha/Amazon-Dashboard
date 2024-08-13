# Amazon Sales Dashboard

# Problem Statement 

Analyze and visualize key aspects of Amazon's sales data, including sales performance by product category, customer segment, region, and sales channel. Use data analysis and visualization to identify trends, patterns, and insights that can optimize sales strategies and improve profitability.

# Data Set Explanation 

𝐎𝐫𝐝𝐞𝐫 𝐈𝐃: A unique identifier for each order made by customers.

𝐎𝐫𝐝𝐞𝐫 𝐃𝐚𝐭𝐞: The date on which the order was made.

𝐒𝐡𝐢𝐩 𝐃𝐚𝐭𝐞: The date on which the order was shipped.

𝐒𝐡𝐢𝐩 𝐌𝐨𝐝𝐞: The shipping method used for the order.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐈𝐃: A unique identifier for each customer.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐍𝐚𝐦𝐞: The name of the customer.

𝐒𝐞𝐠𝐦𝐞𝐧𝐭: The customer segment (e.g., consumer, corporate).

𝐂𝐨𝐮𝐧𝐭𝐫𝐲: The country where the order was shipped.

𝐂𝐢𝐭𝐲: The city where the order was delivered.

𝐒𝐭𝐚𝐭𝐞: The state or province of the order delivery.

𝐑𝐞𝐠𝐢𝐨𝐧: The region of the order delivery.

𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐈𝐃: A unique identifier for each product.

𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: The product category (e.g., electronics, home appliances)

𝐒𝐮𝐛-𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: The sub-category of the product.

𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐍𝐚𝐦𝐞: The name of the product.

𝐒𝐚𝐥𝐞𝐬: The total sales revenue from the order.

𝐐𝐮𝐚𝐧𝐭𝐢𝐭𝐲: The quantity of each product ordered.

𝐃𝐢𝐬𝐜𝐨𝐮𝐧𝐭 %: The discount percentage applied to the order.

𝐏𝐫𝐨𝐟𝐢𝐭: The profit from the order (sales revenue minus cost).

𝐒𝐡𝐢𝐩𝐦𝐞𝐧𝐭 𝐂𝐨𝐬𝐭: The cost of shipping the order.


# Steps Followed

1.𝐃𝐚𝐭𝐚 𝐋𝐨𝐚𝐝𝐢𝐧𝐠

Start by importing the Amazon sales data into Power BI Desktop. Go to the Home tab, click on Get Data, and select the file format of your dataset.

𝟐. 𝐃𝐚𝐭𝐚 𝐐𝐮𝐚𝐥𝐢𝐭𝐲 𝐂𝐡𝐞𝐜𝐤

 Open Power Query Editor to check the data quality. Look for any anomalies, missing values, or errors. This can be done by selecting Transform Data from the Home tab.

𝐄𝐫𝐫𝐨𝐫 𝐚𝐧𝐝 𝐄𝐦𝐩𝐭𝐲 𝐕𝐚𝐥𝐮𝐞 𝐂𝐡𝐞𝐜𝐤
 Use the column headers to filter for errors and empty values. Correct any issues found or remove irrelevant data if necessary.

𝟑.𝐃𝐚𝐭𝐚 𝐏𝐫𝐨𝐟𝐢𝐥𝐢𝐧𝐠

 Use the Data Profiling tools within Power Query to get a better understanding of the data distribution, column statistics, and more. This step helps identify any further data cleaning or transformations needed.

𝟒.𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠

 Replace or remove null values and handle any errors found in the data columns. Use functions like Remove Errors or Replace Errors available in Power Query.



5.𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧𝐬

𝐓𝐨𝐭𝐚𝐥 𝐌𝐞𝐭𝐫𝐢𝐜𝐬 𝐂𝐚𝐫𝐝𝐬: Add card visuals to display the total sales, total quantity, total profit, and total shipment cost. Drag the respective measures to the canvas and format the cards.

𝐂𝐨𝐥𝐮𝐦𝐧 𝐂𝐡𝐚𝐫𝐭: Create a column chart to show total sales by product category. Use Category on the axis and Sales on the values.

𝐋𝐢𝐧𝐞 𝐂𝐡𝐚𝐫𝐭: Add a line chart to display the sales trend over time. Use the Order Date on the axis and Sales on the values. Ensure the date is properly formatted to show trends over months and years.

𝐒𝐜𝐚𝐭𝐭𝐞𝐫 𝐂𝐡𝐚𝐫𝐭: Create a scatter chart to compare sales and profits across different customer segments by product categories. Use Category on the axis, Segment as legend, and Sales and Profit as the respective values.

𝐓𝐫𝐞𝐞𝐦𝐚𝐩: Implement a treemap to illustrate sales revenue and profit across different product categories and sub-categories. Place Category and Sub-Category on the axis and Sales and Profit as values.

𝐁𝐚𝐫 𝐂𝐡𝐚𝐫𝐭 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧: Use a bar chart to show sales and profit variations by region. Use Region on the axis and Sales and Profit as values.

𝐌𝐚𝐩 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧: Add a map visualization to show the geographic distribution of customers by state, with states ranked by profit.

# Insights

𝐒𝐚𝐥𝐞𝐬 𝐛𝐲 𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: Technology products have the highest sales, indicating a strong market demand.

𝐒𝐚𝐥𝐞𝐬 𝐓𝐫𝐞𝐧𝐝: There is a consistent increase in sales year-over-year, suggesting a growing customer base or market share.

𝐏𝐫𝐨𝐟𝐢𝐭 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬: Profit margins vary significantly across product categories, highlighting the need for a focus on cost control and pricing strategy.

𝐆𝐞𝐨𝐠𝐫𝐚𝐩𝐡𝐢𝐜 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧: The majority of sales and profits are concentrated in the West and East regions, which could guide marketing and distribution strategies.



# Recommendations

𝐅𝐨𝐜𝐮𝐬 𝐨𝐧 𝐇𝐢𝐠𝐡-𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐢𝐧𝐠 𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐢𝐞𝐬: Allocate more resources to the technology category to capitalize on its high sales and profit potential.

𝐄𝐱𝐩𝐥𝐨𝐫𝐞 𝐆𝐫𝐨𝐰𝐭𝐡 𝐢𝐧 𝐄𝐦𝐞𝐫𝐠𝐢𝐧𝐠 𝐑𝐞𝐠𝐢𝐨𝐧𝐬: Increase marketing efforts in Central and South regions to tap into new customer bases.

𝐎𝐩𝐭𝐢𝐦𝐢𝐳𝐞 𝐒𝐡𝐢𝐩𝐩𝐢𝐧𝐠 𝐂𝐨𝐬𝐭𝐬: Investigate ways to reduce shipment costs, which can improve overall profitability.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐒𝐞𝐠𝐦𝐞𝐧𝐭𝐚𝐭𝐢𝐨𝐧 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐞𝐬: Develop targeted marketing strategies based on customer segments to enhance sales and customer satisfaction.

𝑩𝒚 𝒖𝒔𝒊𝒏𝒈 𝒕𝒉𝒆𝒔𝒆 𝒊𝒏𝒔𝒊𝒈𝒉𝒕𝒔, 𝒕𝒉𝒆 𝒐𝒓𝒈𝒂𝒏𝒊𝒛𝒂𝒕𝒊𝒐𝒏 𝒄𝒂𝒏 𝒃𝒐𝒐𝒔𝒕 𝒔𝒂𝒍𝒆𝒔 𝒃𝒚 𝒕𝒂𝒓𝒈𝒆𝒕𝒊𝒏𝒈 𝒉𝒊𝒈𝒉-𝒑𝒐𝒕𝒆𝒏𝒕𝒊𝒂𝒍 𝒎𝒂𝒓𝒌𝒆𝒕𝒔 𝒂𝒏𝒅 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒔𝒆𝒈𝒎𝒆𝒏𝒕𝒔 𝒎𝒐𝒓𝒆 𝒆𝒇𝒇𝒆𝒄𝒕𝒊𝒗𝒆𝒍𝒚. 𝑻𝒉𝒊𝒔 𝒘𝒊𝒍𝒍 𝒆𝒏𝒉𝒂𝒏𝒄𝒆 𝒑𝒓𝒐𝒇𝒊𝒕 𝒎𝒂𝒓𝒈𝒊𝒏𝒔 𝒕𝒉𝒓𝒐𝒖𝒈𝒉 𝒃𝒆𝒕𝒕𝒆𝒓 𝒄𝒐𝒔𝒕 𝒎𝒂𝒏𝒂𝒈𝒆𝒎𝒆𝒏𝒕 𝒂𝒏𝒅 𝒔𝒕𝒓𝒂𝒕𝒆𝒈𝒊𝒄 𝒑𝒓𝒊𝒄𝒊𝒏𝒈. 𝑨𝒅𝒅𝒊𝒕𝒊𝒐𝒏𝒂𝒍𝒍𝒚, 𝒐𝒑𝒕𝒊𝒎𝒊𝒛𝒊𝒏𝒈 𝒔𝒉𝒊𝒑𝒑𝒊𝒏𝒈 𝒑𝒓𝒐𝒄𝒆𝒔𝒔𝒆𝒔 𝒄𝒂𝒏 𝒓𝒆𝒅𝒖𝒄𝒆 𝒄𝒐𝒔𝒕𝒔 𝒂𝒏𝒅 𝒊𝒎𝒑𝒓𝒐𝒗𝒆 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒔𝒂𝒕𝒊𝒔𝒇𝒂𝒄𝒕𝒊𝒐𝒏. 𝑬𝒙𝒑𝒂𝒏𝒅𝒊𝒏𝒈 𝒊𝒏𝒕𝒐 𝒏𝒆𝒘 𝒎𝒂𝒓𝒌𝒆𝒕𝒔 𝒃𝒂𝒔𝒆𝒅 𝒐𝒏 𝒈𝒆𝒐𝒈𝒓𝒂𝒑𝒉𝒊𝒄 𝒂𝒏𝒅 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒅𝒂𝒕𝒂 𝒄𝒂𝒏 𝒄𝒓𝒆𝒂𝒕𝒆 𝒏𝒆𝒘 𝒈𝒓𝒐𝒘𝒕𝒉 𝒐𝒑𝒑𝒐𝒓𝒕𝒖𝒏𝒊𝒕𝒊𝒆𝒔 𝒂𝒏𝒅 𝒊𝒏𝒄𝒓𝒆𝒂𝒔𝒆 𝒑𝒓𝒐𝒇𝒊𝒕𝒂𝒃𝒊𝒍𝒊𝒕𝒚.

# Snapshort of Amazon Sales Dashboard (Power BI Desktop)

![Screenshot 2024-08-13 134002](https://github.com/user-attachments/assets/d1819039-c003-421b-b6e0-9fad999e1043)
