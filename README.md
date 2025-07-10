# Project---PWC-Call-Centre-Solution 
README

Data Analysis Project: Call Center Performance Dashboard
Project Overview
This project focuses on leveraging data analytics to enhance operational efficiency and empower employees through digital skill acceleration. As part of the PwC Virtual Experience's "The Call Centre Solution" program, I developed an interactive Power BI dashboard to visualize key call center performance metrics. The primary goal is to provide actionable insights into customer satisfaction, agent efficiency, and service trends, ultimately enabling data-driven decision-making.

Technologies Used
Microsoft Power BI Desktop: For robust data modeling, advanced DAX calculations, and compelling data visualization.

Power Query: Utilized for efficient data extraction, transformation, and loading (ETL) from the raw dataset.

Microsoft Excel: The original dataset was provided in Excel, where initial data profiling and preparation might have occurred.

[Optional: Microsoft Fabric - If you built any part of this in Fabric or plan to, mention it here e.g., "Microsoft Fabric (for potential future data warehousing and advanced analytics)"]

Objective
To develop an interactive Power BI dashboard that displays key performance indicators (KPIs) and trends in call center operations. The dashboard aims to enable strategic decision-making by highlighting areas for improvement, enhancing efficiency, and providing a clear understanding of the operational health that impacts overall business performance.

Key Performance Indicators (KPIs)
The dashboard comprehensively analyzes and visualizes the following critical KPIs:

Customer Satisfaction: Trends in overall satisfaction ratings, crucial for understanding customer sentiment and loyalty.

Call Handling Metrics:

Total Calls Answered

Total Calls Abandoned

Call Volume categorized by time and topic

Average Speed of Answer (ASA): Trends in response time, indicating operational responsiveness and areas for potential improvement.

Agent Performance Analysis:

Performance Quadrant: Correlating average handle time with the number of calls answered to identify efficiency and productivity.

Identifying top-performing and underperforming agents based on key metrics.

Data Insights & Analysis
Through the Power BI dashboard, the following critical insights were uncovered:

Speed of Answer Trends: The cumulative speed of answers (in seconds) showed a concerning decline between March 27, 2021, and March 31, 2021.

Key Contributors to Decline: Agents Dan, Becky, and Greg exhibited a notable decline in their individual performance.

Positive Shifts: Agents Diane and Martha successfully improved their response times, showcasing areas of effective agent training or best practices.

Satisfaction Ratings Decline: Customer satisfaction ratings experienced a significant drop of 82 points from March 26, 2021, to March 31, 2021.

Primary Impact Areas: Topics related to Technical Support and Admin Support were the largest drivers of negative customer feedback.

Category Volatility: Payment-related, Technical Support, and Contract-related categories showed the most significant fluctuations in satisfaction.

Agent Performance – Speed of Answer Analysis:

The overall sum of speed of answers across the call center stood at 273,729 seconds.

Agent Stewart recorded the lowest total response time at 31,570 seconds. While this might indicate efficiency, it also suggests a need for further evaluation to ensure quality is maintained, or potential targeted training if efficiency comes at the cost of resolution or satisfaction.

Conclusion & Recommendations
This project vividly demonstrates the power of data-driven decision-making in optimizing customer service operations and, by extension, overall business health. Based on the insights, the following recommendations are proposed:

Targeted Agent Training & Coaching: Implement specific training programs for agents like Stewart to improve call-handling speed without compromising quality. Develop performance improvement strategies tailored for agents (Dan, Becky, Greg) experiencing declining response rates.

Customer Support Optimization: Conduct a deep dive into Technical Support and Admin Support processes. Identify bottlenecks or areas where clearer documentation or better tools could reduce call times and improve customer satisfaction.

KPI Monitoring & Continuous Improvement: The Power BI dashboard should be regularly updated and reviewed to continuously track improvements in call center performance. Implement proactive strategies derived from these KPIs to enhance customer experience and response efficiency.

Broader Business & Financial Implications
While focused on call center operations, the insights from this dashboard have direct relevance to core business and financial health. Understanding operational efficiency, customer satisfaction, and agent productivity directly impacts:

Cost Management: Optimizing call handling reduces operational expenses (staffing, telecom costs).

Revenue & Profitability: Higher customer satisfaction leads to improved customer retention, repeat business, and a stronger brand reputation, all of which positively impact revenue streams.

Resource Allocation: Data-driven insights can guide budgeting for training, technology, and staffing to ensure optimal ROI.

Future Enhancements & Microsoft Dynamics 365 Finance Connection
This project serves as a strong foundation. Future enhancements could bridge the gap between operational insights and enterprise-level financial data, leveraging the full Microsoft ecosystem:

Integration with Dynamics 365 Finance:

Connect the Power BI dashboard to actual financial data sources within Dynamics 365 Finance, such as General Ledger for call center operating expenses (e.g., salaries, telecommunications, infrastructure costs).

Pull data from Accounts Payable for vendor payments related to call center tools or outsourced services.

Correlate call center performance with customer revenue data (from D365 Sales or other CRM integrated with D365 Finance) to calculate 'Revenue per Call' or 'Cost to Serve per Customer Segment.'

Advanced Financial Modeling with Fabric: Utilize Microsoft Fabric to create a unified data estate for both operational (call center) and financial (D365) data. This would enable more sophisticated cross-domain analysis, predictive modeling for resource needs, and advanced cost allocation.

Automated Financial Reporting: Explore using Power Automate to trigger daily/weekly financial summaries of call center performance, automatically pulling relevant data from Dynamics 365 and sending it via email or updating a central dashboard.
