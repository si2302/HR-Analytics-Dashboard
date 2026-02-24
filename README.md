# HR-Analytics-Dashboard
Below are the KPIs:
1️⃣ Workforce Structure KPIs
🔹 Total Headcount
Definition: Total number of active employees
Excel Formula:
=COUNTA(A2:A100)
Insight: Overall workforce size
________________________________________
🔹 Department-wise Headcount
Definition: Employees per department
Formula Logic: COUNTIFS
=COUNTIFS(E:E,"IT")
Insight: Resource allocation across functions
________________________________________
🔹 Location-wise Headcount
Insight: Regional workforce distribution
________________________________________
🔹 Age Band Distribution
Insight: Workforce age composition (young vs experienced)
________________________________________
2️⃣ Diversity & Inclusion KPIs
🔹 Gender Ratio (%)
Definition: Gender representation
=COUNTIF(D:D,"Female") / Total Headcount
Insight: Gender diversity balance
________________________________________
🔹 Gender Mix by Department
Insight: Department-level diversity gaps
________________________________________
3️⃣ Hiring & Recruitment KPIs
🔹 Hiring Source Effectiveness
Definition: Employees hired per source
=COUNTIFS(F:F,"Job Portal")
Insight: Most effective recruitment channel 🎯
________________________________________
🔹 Average Experience at Joining
=AVERAGE(I:I)
Insight: Quality of hiring (freshers vs lateral)
________________________________________
🔹 Average Age at Joining
=AVERAGE(C:C)
Insight: Hiring strategy orientation
________________________________________
🔹 Hiring Trend (Year-wise)
Derived from Date of Joining
Insight: Growth / slowdown pattern 📈
________________________________________
4️⃣ Experience & Talent KPIs
🔹 Average Experience (Years)
=AVERAGE(I:I)
Insight: Overall workforce maturity
________________________________________
🔹 Experience Band Distribution
(0–2, 2–5, 5–10, 10+)
Insight: Succession & leadership readiness
________________________________________
🔹 Senior Workforce Ratio (>10 yrs)
=COUNTIF(I:I,">10") / Total Headcount
Insight: Dependency on senior talent
________________________________________
5️⃣ Tenure-Based KPIs (Derived)
🔹 Average Tenure (Years)
=AVERAGE(TODAY()-Date_of_Joining)/365
Insight: Retention strength
________________________________________
🔹 Long-Tenure Employees (>5 years)
Insight: Organizational stability
________________________________________
🔹 Recent Joiners (<1 year)
Insight: Growth / replacement hiring
________________________________________
6️⃣ Demographic Analytics KPIs
🔹 Average Age by Department
Insight: Aging vs young teams
________________________________________
🔹 Age vs Experience Correlation
Insight: Career progression consistency
________________________________________
7️⃣ Strategic HR KPIs (MBA-Oriented)
🔹 Talent Concentration Index
Definition: % of experienced employees in critical departments
Insight: Risk exposure if attrition happens
________________________________________
🔹 Hiring Source Diversity Index
Definition: Dependency on limited sources
Insight: Recruitment risk ⚠️
________________________________________
🔹 Workforce Mobility Indicator
(Location × Department)
Insight: Location-specific hiring dependence
________________________________________
Recommended KPI Tiles (Top Dashboard)
✔ Total Headcount
✔ Avg Age
✔ Avg Experience
✔ % Female Employees
✔ Top Hiring Source
✔ Avg Tenure

