# Call Centre Performance Dashboard
This project features an interactive Tableau dashboard designed to analyse and visualise call centre performance. It provides a two-dashboard solution targeting Operations Managers, who need a high-level command centre to monitor overall health, and Team Supervisors, who require tools for deep-dive analyses into individual agent performance. The solution leverages advanced Tableau features like Level of Detail (LOD) expressions and parameters for dynamic interaction.

LiveDashboard: https://public.tableau.com/views/CallCentresPerformance/Main?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Data Source: https://sonsofhierarchies.com/2025/09/08/rwfd-season-4-dataset-2-call-center-performance/
<br><br>
## Dashboards
The analysis is presented across two distinct, interactive dashboards:
### 1. Operational Command Centre
This dashboard is designed to give managers a 360-degree view of the call centre's performance at a glance. It focuses on identifying macro trends, spotting potential issues with "red flag" alerts, and understanding operational load. Its key features include:

<img width="1792" height="892" alt="Main" src="https://github.com/user-attachments/assets/04d59ce4-c487-48aa-bfce-09d9b6801836" />

* Core Performance KPIs: At-a-glance metrics for Total Calls, Average Handle Time (AHT), First Call Resolution (FCR) Rate, Average CSAT Score, and Service Level Agreement (SLA) Met %, with comparisons to a previous period.

* Call Volume Heatmap: A visual matrix of call density by day of the week and hour of the day, helping to identify peak times for effective workforce planning.

* Sentiment & CSAT Trend Analysis: A dual-axis chart correlating call volume with customer satisfaction over time, tracking trends in CSAT and sentiment scores.

* "Red Flag" Escalation Table: An actionable table that automatically filters for calls requiring review (e.g., CSAT Score < 3). It uses conditional formatting to highlight low scores for immediate attention.
<br><br>
### 2. Dynamic Agent Scorecard
This dashboard is an interactive tool for performance management, allowing supervisors to select a specific agent for a detailed breakdown of their metrics and compare them against team benchmarks. Its key features include:

<img width="1792" height="892" alt="Main (1)" src="https://github.com/user-attachments/assets/f367527a-ea0b-4805-9cb5-1b5285a14e79" />

* Dynamic Agent Analysis: Utilises a parameter to select a single agent, dynamically updating all scorecard visuals to reflect their performance.

* FCR vs. CSAT Correlation Plot: A scatter plot where each point represents an agent, visualising the relationship between their FCR Rate and Average CSAT. The selected agent is highlighted for easy comparison against peers, with reference lines indicating team averages.
<br><br>
## Key Insights
### 1. Identified Peak Call Times
The call volume heatmap reveals clear peak periods, notably between 4:00 PM - 6:00 PM on Mondays and 10:00 AM - 12:00 PM on Fridays. This insight is critical for optimising staffing schedules to meet demand.

### 2. Actionable Performance Alerts
The "Red Flag" table effectively isolates calls with poor customer feedback, providing supervisors with a prioritised list for review and targeted agent coaching to address service quality issues.

### 3. Efficient Service Level Management
With a Service Level Agreement (SLA) threshold set at a 2-minute wait time, the dashboard indicates a generally high percentage of calls are answered within this target, reflecting efficient queue management and initial response times.
<br><br>
## How to Use This Dashboard
The dashboard is designed for interactive exploration.

* Navigate Between Views: Use the tabs at the top to switch between the Operational Command Centre and the Dynamic Agent Scorecard.

* Filter by Agent: On the Dynamic Agent Scorecard, use the dropdown parameter to select a specific Agent ID. All charts on this dashboard will update to show that individual's performance data.

