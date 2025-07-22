I recently built a comprehensive UK Train Ride Analysis dashboard using Power BI, leveraging DAX functions to create insightful measures and calculated columns. This analysis aimed to uncover critical patterns in travel behavior, revenue streams, and performance issues.
🔍 Key Business Questions Addressed:
✅ What are the most popular routes?
Answer : * The route from Manchester to London Euston tops the chart with 4.6K+ transactions, followed by London Euston to London Paddington and London King's Cross to Liverpool Lime Street.
* DAX was used to create ranking measures to dynamically show top routes.

✅ What are the peak travel times?
* Peak hours identified around 08:00 and 18:00, aligning with commuter patterns.
* DAX time-based grouping helped to analyze hourly distribution efficiently.

✅ How does revenue vary by ticket types and classes?
* Standard class contributed to 80% of the total revenue (£593K).
* Advance ticket types generated the most revenue (~41.7%).
* Revenue measures were calculated using SUMX and CALCULATE with filter context for detailed segmentation.
✅ What is the on-time performance? What are the main contributing factors?
* On-time %: 86.82%
* Delayed %: 7.24%, Cancelled %: 5.94%
* Top delay reasons include:
Weather (758 delays)
Technical Issues (472)
Signal Failures (451)
* DAX helped break down delays by category using COUNTROWS, FILTER, and RELATEDTABLE.
📈 Summary Metrics:
💰 Revenue: £742K
🧾 Transactions: 32K

This analysis not only visualizes the data but also provides actionable insights into improving operations and customer satisfaction.
💡 Tools Used:
Power BI
DAX Functions: CALCULATE, SUMX, COUNTROWS, FILTER, RANKX, RELATEDTABLE
Feel free to connect if you'd like to discuss Power BI, data analytics, or transport data solutions!
