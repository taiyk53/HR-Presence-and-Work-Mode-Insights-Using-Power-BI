# HR-Presence-and-Work-Mode-Insights-Using-Power-BI

1. Project Objectives
•	Analyze key HR metrics like employee presence, work-from-home (WFH) percentage, and sick leave (SL) percentage.
•	Identify patterns and trends across departments and individual employee performance.
•	Provide data-driven insights to optimize workforce management and improve employee satisfaction.

2. Dataset Used
•	Source: https://github.com/taiyk53/HR-Presence-and-Work-Mode-Insights-Using-Power-BI/blob/main/Attendance%20Sheet%202022-2023_Masked.xlsx

3. Key Questions (KPIs)
•	What is the overall employee presence percentage, and how does it vary by day of the week and month?
•	What percentage of employees work from home, and how consistent is this trend over time?
•	How frequently do employees take sick leave, and are there any noticeable patterns?
•	Which employees or departments show the highest and lowest presence rates?

4. Process
•	Data Collection: Imported the Excel dataset into Power BI.
•	Data Cleaning: Removed duplicates, standardized column names, and handled missing data.
•	Data Transformation: Applied Power Query for shaping and structuring the dataset.
•	Measures Creation: Created key measures using DAX for:
o	Presence % = DIVIDE([Present Days],'Measure Table'[Total Working Days],0)
o	WFH % = DIVIDE([WFH Count],[Present Days],0)
o	SL % = DIVIDE([SL Count],[Total Working Days],0)
•	Visualization: Built interactive visualizations including:
o	Line charts for monthly trends of Presence %, WFH %, and SL %.
o	Tables showing employee-level and day-of-week breakdowns.
o	Key performance indicators (KPIs) highlighting overall metrics.

5. Project Insights
•	Overall Presence: Average presence rate is 91.83%, with consistent performance across weekdays.
•	Work-from-Home Trends: WFH rate is relatively low at 10%, peaking on certain weekdays.
•	Sick Leave Patterns: Sick leave rate remains low at 1.10%, with a slight increase mid-week.
•	Employee-Level Analysis: Some employees show perfect attendance, while others exhibit more frequent WFH or sick leaves.
•	Day-of-Week Trends: Presence percentage is highest on Tuesdays and Thursdays, while WFH spikes on Tuesdays.

6. Final Conclusion
The HR Insights Dashboard provides a clear and actionable view of workforce attendance and work mode trends at ATLAS Hardware Company. These insights can help the company optimize scheduling, enhance employee well-being, and address departments or individuals with lower engagement.
