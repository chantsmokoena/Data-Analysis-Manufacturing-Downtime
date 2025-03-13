
# Manufacturing Downtime Analysis
Project Overview
The primary objective of this project is to analyze manufacturing line productivity by identifying key inefficiencies, understanding downtime trends, and evaluating operator performance. Unplanned downtime in a manufacturing environment can lead to significant financial losses, decreased efficiency, and disruptions in production. This analysis provides a data-driven approach to uncover patterns and optimize operations.

# Objective
The primary goal of this analysis is to monitor and analyze equipment downtime in the manufacturing process. By identifying key contributors to downtime, such as products, operators, and time trends, this analysis helps improve operational efficiency, reduce disruptions, and enhance overall productivity.

# Key Goals
✔ Identify trends in downtime over time to assess operational improvements or recurring issues.
✔ Analyze which products contribute the most to downtime.
✔ Evaluate downtime by operator to identify potential training or process gaps.
✔ Provide actionable insights to minimize equipment failures and optimize production.

# Tools Used
✔ SQL – Extracted and structured downtime data from the manufacturing database.
✔ Excel – Cleaned and formatted data for Power BI import.
✔ Power BI – Designed an interactive dashboard for downtime analysis.

# Dashboard Breakdown
1.  Downtime Trends Over Time
A bar chart compares downtime in August (853) vs. September (535), showing a reduction in downtime.
This downward trend suggests operational improvements, possible maintenance strategies, or process adjustments.
Further investigation is required to determine if this reduction is sustainable or due to temporary factors.

2. Downtime by Product
A pie chart categorizes total downtime by product:
✓ CO-600 contributes the most to downtime (494 instances, 35.59%).
✓ CO-2L, RB-600, and LE-600 also have significant downtime durations.
✓ OR-600 and DC-600 have lower downtime, potentially indicating better reliability.
These insights help prioritize maintenance schedules and process improvements for high-downtime products.

 3. Downtime by Operator
A stacked bar chart displays downtime distribution per operator (Charlie, Dee, Mac, Dennis).
Each operator has varying contributions across different product types, which could indicate:
✔ Skill gaps or training needs for certain operators.
✔ Equipment assigned to specific operators may be more prone to failures.
✔ Process inefficiencies affecting certain operators disproportionately.

4. Operator Error Downtime
 A KPI card highlights 776 downtime instances due to operator errors.
This suggests a need for operator training, SOP improvements, or automation strategies to reduce human errors.

5. Filtering Capabilities
   Users can filter downtime data by:
✔Product (e.g., CO-2L, CO-600) to assess downtime per equipment type.
✔ Date to track performance over specific periods.
✔ Operator to analyze individual performance and identify areas for improvement.

# Business Impact & Insights
✔ Reducing Downtime & Optimizing Maintenance

Prioritizing CO-600 and other high-downtime products for proactive maintenance can reduce unplanned stoppages.
Implementing predictive maintenance using downtime trends could further minimize disruptions.
✔ Enhancing Workforce Productivity

Identifying operator-related downtime (776 instances) can drive training initiatives to improve efficiency.
Reviewing best practices among operators with lower downtime can help standardize successful techniques.
✔ Monitoring Continuous Improvement

The decrease in downtime from August to September suggests positive changes, but ongoing trend monitoring is necessary to sustain improvements.
Future enhancements can include root cause analysis for each downtime type, further refining downtime reduction strategies

# Conclusion
This Manufacturing Downtime Dashboard provides a data-driven approach to minimizing production interruptions by analyzing key downtime contributors across time, products, and operators.
By leveraging SQL, Excel, and Power BI, manufacturers can gain actionable insights, implement targeted improvements, and drive operational efficiency.

