# 🏗️ Project Management Dashboard (2019–2020)

This dashboard analyzes project management performance in Nigeria between 2019 and 2020 using project-level data. The years are derived directly from the start, end, and planned dates in the dataset (e.g., start dates range from January 19, 2019, to October 1, 2020; end dates from March 12, 2019, to December 12, 2020; planned dates from February 21, 2019, to December 31, 2020). The goal is to evaluate budget utilization, project health, completion rates, and operational dynamics while identifying strategic improvement opportunities for project stakeholders.

## 🎯 Project Objective

Provide business intelligence insights to support decisions regarding resource allocation, priority management, location strategies, and team performance. The dashboard answers key performance questions across time, project types, locations, and managers.

## 📁 Dataset Used

Dataset consisted of 97 entries representing 57 unique projects (some projects have multiple entries, likely for subtasks or phases), structured as a single table with project details including budgets, dates, managers, types, statuses, and more.  

Dataset Link: <a href="(PROJECT2) Project Management Data.csv">Dataset</a>

## ❓ Questions (KPIs)

Core KPI questions explored:  
How did budgets and expenses evolve over time?  
Which project types and locations consumed the most budget and expenses?  
Which managers and priorities showed the best completion rates?  
How do project statuses, health, and delays affect overall performance?

Calculated KPI metrics included:

• Total Budget  
• Total Expenses & Utilization %  
• Delayed Projects  
• Over Budget Projects  
• Average % Complete  
• Project Counts by Status/Health

## ⚙️ Process

1. Data Preparation (Power Query/Excel): data cleaning, date parsing, type standardization, handling duplicates for unique project analysis  
2. Data Modeling: tabular schema with calculated fields, grouping by unique project names where applicable  
3. KPI Logic (DAX/Formulas): metrics & calculations developed  
4. Exploratory + Comparative Analytics: trends, types, geography, and manager segments  
5. Visualization (Power BI): interactive dashboard for executives & analysts

## 🖥️ Dashboard

![Screenshot (495)](PHS.png)

## 📊 Project Insights

Budget & Expense Behavior: Total budget allocated was approximately $1.05M (rounded to $1M in the visual) with expenses at $637K (60.4% utilization); the average project schedule was 172 days, with an average completion rate of 53%. There were 12 delayed projects (where end date exceeded planned date) and 11 over-budget instances. Majority of activity occurred in 2019, with extensions into 2020.

Type Performance: Building Construction dominated with 38 unique projects, $429,660 budget, and $183,195 expenses (average schedule 168 days); Transformer Installation had 11 unique projects, $192,700 budget, $110,590 expenses; Borehole & Reticulation: 8 unique, $122,900 budget, $87,740 expenses; Road Construction: 7 unique, $134,265 budget, $102,720 expenses; Supplies: 5 unique, $91,835 budget, $88,435 expenses; Rehabilitation: 3 unique, $83,400 budget, $64,300 expenses. As shown in the visual's bar chart, project counts by type and priority highlight Building Construction as the most frequent (stacked count ~11 in the filtered view).

Location Performance: Lagos had the highest row count (30 entries, 21 unique projects) but lower budget ($192,250) compared to Abuja ($307,230 budget, $101,925 expenses, 10 unique); Kano led expenses ($239,825) with $287,870 budget (11 unique); Borno: $130,750 budget, $104,710 expenses (11 unique); Uyo: $98,085 budget, $75,790 expenses (5 unique); Rivers: $21,000 budget, $22,250 expenses (2 unique); Sokoto: $17,575 budget, $10,000 expenses (2 unique). The map visual emphasizes Lagos and Kano as key hubs with larger bubbles.

Manager & Status Behavior: Ema Ekpo managed the most (35 entries, 28 unique projects, $307,205 budget, $199,885 expenses, avg. 54.6% complete); Dave Chieke: 21 entries, 10 unique, $342,275 budget, $156,095 expenses, 56.5% complete; Abdul Rex: 11 entries, 9 unique, $71,200 budget, $42,790 expenses, 49.4% complete; Sarah Boulos: 9 entries, 8 unique, $116,530 budget, $85,550 expenses, 27.2% complete; James Seun: 8 entries, 7 unique, $57,300 budget, $42,050 expenses, 85.8% complete (highest avg. completion); Cinci Momoh: 8 entries, 8 unique, $28,210 budget, $19,390 expenses, 53.9% complete; Vivian Ade: 5 entries, 4 unique, $132,040 budget, $91,220 expenses, 27.8% complete. Statuses: In Progress (47 entries), Completed (19), Planned (18), On Hold (8), Cancelled (5)—aligning with the pie chart's distribution (e.g., In Progress as the largest segment ~30-34%). Health: On Track (58), Needs Attention (27), Not Set (12). The bar chart in the visual confirms budget/expense breakdowns by manager.

Additional Insights: Projects like "Classroom Arrangement" appear 11 times (likely phased), "Research Offices" 7 times, indicating multi-entry tracking for larger initiatives. High-priority projects (visual's priority colors: 1-5) are distributed across types, with Building Construction showing diverse priorities. Opportunities for improvement include addressing delays in 12% of entries and over-budget in 11%, particularly in high-expense locations like Kano. The table in the visual highlights specific examples, such as low-completion projects (e.g., Training Room at 0.14%) starting in mid-2019, suggesting potential bottlenecks in execution phases.

## ✅ Final Conclusion

Projects demonstrated moderate completion (53% average) with strong on-track health (58 entries) but challenges in delays (12), over-budget (11), and needs attention (27). The 2019-2020 focus showed peak activity in 2019, with Building Construction as a core driver but higher utilization in Transformer Installation. Opportunities lie in enhancing budget controls in expense-heavy areas like Kano, boosting completion rates for lower-performing managers (e.g., Sarah Boulos and Vivian Ade), and streamlining multi-phase projects to reduce delays and improve overall efficiency.

## 🛠️ Tools Used

Power BI · Power Query · DAX · Excel/CSV · Python (EDA)

## 🚀 Live Dashboard Link

https://app.powerbi.com/view?r=EXAMPLE_DUMMY_LINK

## 📦 Repository Structure

project-management-dashboard/ → README.md, project_dashboard.pbix, project_data.csv, data_cleaning.ipynb, assets/screenshots/

## 👤 Author

Wiseman Siriro

