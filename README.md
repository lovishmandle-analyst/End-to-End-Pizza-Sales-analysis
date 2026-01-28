# End-to-End-Pizza-Sales-analysis
Developed an end-to-end Pizza Sales Analysis Dashboard by solving real client-driven problem statements and translating business requirements into actionable data insights. Used SQL to extract, clean, validate, and transform raw sales data, ensuring high data accuracy and consistency. Built an interactive Tableau dashboard to visualize key performance metrics such as total revenue, order trends, top-selling pizzas, category-wise performance, and time-based demand patterns.
Leveraged AI tools to cross-validate SQL query outputs, detect anomalies, verify calculations, and optimize analytical workflows—significantly improving efficiency, accuracy, and turnaround time. Demonstrated the ability to integrate AI into modern business processes by using it as a decision-support and validation layer rather than a replacement, ensuring reliable insights and faster delivery. The final dashboard met client expectations and enabled data-driven decisions for inventory planning, pricing strategy, and sales optimization

KPI FORMULAS (Tableau Calculated Fields) 

Total Revenue
SUM([total_price])

Total Orders
COUNTD([order_id])

Total Pizza sold
SUM([quantity])

Avg order value
SUM([total_price]) / COUNTD([order_id])

Avg Pizza per order
SUM([quantity]) / COUNTD([order_id])




