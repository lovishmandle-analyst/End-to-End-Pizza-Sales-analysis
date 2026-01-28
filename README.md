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

Explore the live [DASHBOARD](https://public.tableau.com/views/PizzaSalesReportAnalysis_17695963176440/PizzaSalesReportAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) on Tableau Public.

## My ANALYSIS
1) The business is doing strong volume with stable demand patterns.You have 21,350 unique orders and total revenue of 817,860.05 in the period covered by the file. That’s a healthy base to optimize because small conversion and upsell gains will compound quickly across thousands of orders.Revenue and order volume are seasonal but predictable.

## Business implication
Predictability means you should run operations and marketing like a cadence plan (staffing plans, prep plans, promos) rather than “reacting” week by week.

## Solution
  Build a simple monthly playbook

  a. Pre-plan staffing and prep for peak months (stock, labor scheduling, delivery capacity)
  b. Run targeted promos in softer months focused on AOV (bundles) instead of discounting core items

2) Category mix is well balanced, Classic leads revenue


## Business implication
Because categories are close in revenue, improvements in any one category can move topline. Classic being the biggest bucket is also your best lever for “default upsells” because it likely has the highest order frequency.

## Solution
   Menu engineering by category

  a. Keep Classic as the “upsell engine” (default prompts for size upgrades, add-ons, bundles)
  b. Use Supreme/Chicken/Veggie for variety and limited-time rotations to avoid cannibalizing Classic

3) A small set of pizzas drives most of the money (portfolio concentration)

About 21 pizzas account for ~80% of revenue (classic long-tail effect).

## Business implication
The menu is probably larger than what drives profit and operational simplicity. Long-tail items add prep complexity, waste risk, and decision fatigue without contributing much revenue.

## Solution
  Simplify and spotlight
a. Create a “Core 20” list (the items driving ~80% of revenue) and ensure they’re always perfectly executed (inventory, prep, photo quality, menu placement)
b.  For low performers, either reprice, rename/reposition, or rotate out seasonally (don’t permanently kill everything at once; test)

4) Demand is highly time-bound (clear peak hours)
 
## Business implication
Your constraint is probably throughput at peaks (kitchen capacity, delivery, front-of-house). Peak-hour speed and accuracy impacts reviews, repeat purchase, and labor cost.

## Solution
Operational “peak hour system”

a. Staff to the heatmap, not to intuition
b. Pre-prep ingredients for peak windows, and reduce on-the-fly complexity by promoting “fast lane” best sellers during rush
c. Introduce peak-only bundles that are operationally easy (e.g., 2-pizza + drink with limited customization)

5) Biggest lever is likely AOV and items-per-order (not just more traffic)

With this many orders already, you’ll usually get better ROI from increasing average revenue per order than trying to acquire lots of new customers.

## Business implication
Even a small AOV lift (e.g., 3–5%) can create a meaningful annual revenue delta without extra ad spend.

## Solution
Practical AOV uplift tactics (low risk)

a.  Default size anchoring: show L as “Most popular” and M as “Best value,” prompt upgrade at checkout
b.  Bundles: “Pizza + side + drink” (price it to be a no-brainer vs à la carte)
c. Add-on prompts: extra cheese, toppings, garlic bread, sauces (keep it to 2–3 prompts to avoid friction)
d. Price architecture: ensure price gaps between sizes make upgrading feel efficient (small gap from M→L)




