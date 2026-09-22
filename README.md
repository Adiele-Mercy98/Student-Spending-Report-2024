# Student-Spending-Report-2024
The primary objective is to analyze student aid and spending data to understand how spending varies across age groups, gender, academic major, and year in school, and to identify where financial aid is aligned with actual student spending — and where it isn’t.

Problem Being Addressed

The analysis seeks to answer:

· Which students — by age, gender, and major — carry the highest spending burden, and does financial aid distribution actually track with that burden?

· How does spending shift across year in school, particularly for costs like housing, and are aid and spending patterns consistent with the institution’s assumptions about who needs the most support?

Datasets and Methodologies

Dataset: The analysis uses a student spending and financial aid dataset containing independent variables (Age Group, Gender, Major, Year in School) and dependent variables (Total Spending, Average Spending, Books & Supplies Cost, Housing Cost, Financial Aid Amount).

Methodologies: The primary methodology involved building an interactive Excel dashboard with slicers for year in school and major, alongside pivot-style breakdowns analyzing spending by age, gender, major, and year, and aid distribution by major.

Industry Type

Higher education / student financial services, with equitable aid distribution and accurate spending forecasting as the primary success measures.

Data Story

The data tells a story around how students spend and where financial aid is directed across the institution. It highlights spending by age group and gender, books & supplies costs and average total spending by major, housing costs by year in school, and how financial aid dollars are distributed relative to each major’s actual spending.

Stakeholders of Project

The Financial Aid Office and Student Affairs leadership.

What Success Means to the Industry

Directing aid to where the real financial pressure is — not just where headline totals suggest.

Planning housing and living-cost support around when costs actually jump, not a flat yearly assumption.

Reducing the gap between what students spend and what aid covers, by major and by year.

Pre-Analysis

Project Split

Category One: Independent Variables

· Age Group

· Gender

· Major

· Year in School

Category Two: Dependent Variables

· Total Spending

· Average Spending

· Books & Supplies Cost

· Housing Cost

· Financial Aid Amount

Potential Analysis/Questions

Spending performance by age group

Spending performance by gender

Books & supplies cost by major

Average total spending by major

Housing cost by year in school

Financial aid distribution by major

Aid-to-spending ratio by major

Highest spending age bracket for the year

Major with the most financial aid awarded

Major with the highest average spending per student

Potential Insights

Finetune aid allocation for the age group with the highest total spending to ensure support scales with actual cost.

Finetune the gap between genders in spending to confirm whether “top spender” framing reflects a real or marginal difference.

Finetune books & supplies budgeting across majors if the cost spread is narrow enough to standardize.

Finetune aid targeting for majors with high average spending but comparatively lower aid.

Finetune housing aid timing around the year in school where costs jump most sharply.

Identify majors where aid growth is not proportional to spending growth and adjust aid formulas accordingly.

In Analysis

Spending by Age Group

Observations:

· Students aged 24–25 topped the chart for the year, with total spending of $1,792,318.

· The 22–23 age group is the second highest, at $1,627,263.

· The 18–19 age group generated $1,463,345 in spending.

· The 20–21 age group is the lowest, at $1,432,552.

Pre Insight:

· The jump from 20–21 to 22–23 is far larger than the jump from 18–19 to 20–21, suggesting spending accelerates later rather than rising steadily with each age bracket.

· Aid planning may need to weight the 24–25 bracket more heavily, since it carries a noticeably larger share of total spending than the other three groups combined would suggest at a glance.

Spending by Gender

Observations:

· Non-binary students recorded the highest average spending, at $2,257,365.

· Female students recorded average spending of $2,030,127.

· Male students recorded average spending of $2,027,986.

Pre Insight:

· The dashboard’s headline flags male students as the “top spender,” but the actual figures show Female and Male students within about $2,000 of each other, with Non-binary students actually highest — the badge framing doesn’t match the underlying numbers.

· Given how close all three figures are, gender may not be a meaningful driver of spending differences on its own.

Books & Supplies Spending by Major

Observations:

· Engineering had the highest books & supplies cost per student, at $177.34.

Write on Medium
· Computer Science followed at $176.34.

· Economics recorded $175.10.

· Psychology recorded $173.35.

· Biology was the lowest, at $171.13.

Pre Insight:

· The full range across all five majors is just over $6, meaning books & supplies cost is not a major point of differentiation between majors.

· Standardized budgeting for this category, rather than major-specific planning, would likely be sufficient.

Average Spending by Major

Observations:

· Biology had the highest average spending per student, at $1,429,717.

· Economics followed at $1,279,244.

· Computer Science recorded $1,221,771.

· Engineering recorded $1,196,986.

· Psychology was the lowest, at $1,187,760.

Pre Insight:

· This contradicts the dashboard’s “Top Spending Major: Computer Science” badge — Computer Science actually ranks third in average per-student spending, behind Biology and Economics.

· The “top spending major” label likely reflects total dollar volume (driven by enrollment size) rather than average spending per student — these are two different measures and should be reported separately going forward.

Average Housing Cost by Year in School

Observations:

· Seniors had the highest average housing cost, at $708.96.

· Juniors followed closely at $705.29.

· Freshmen recorded $703.21.

· Sophomores had the lowest housing cost, at $665.90.

Pre Insight:

· The jump from Sophomore to Freshman/Junior/Senior is much larger than the differences among Freshman, Junior, and Senior themselves, which are within about $6 of each other.

· This suggests housing costs rise sharply once and then plateau, rather than increasing steadily year over year — aid or budgeting tied to “each year costs more than the last” would be inaccurate here.

Financial Aid Distribution by Major

Observations:

· Computer Science received the most financial aid per student, at $549.93.

· Economics followed at $505.24.

· Engineering recorded $495.60.

· Biology recorded $489.61.

· Psychology received the least, at $485.48.

Pre Insight:

· Computer Science leads in aid despite ranking only third in average spending — this major may be receiving aid disproportionate to its actual per-student cost burden.

· Biology, which has the highest average spending, ranks fourth in aid — a potential mismatch worth investigating further.

Data Visualization — Dashboard
<img width="1087" height="431" alt="Screenshot (357)" src="https://github.com/user-attachments/assets/f52029fd-8cb9-49b9-bc90-39eb26572ef2" />

Press enter or click to view image in full size

The Student Spending Report 2024 dashboard (filterable by year in school and major) brings the analysis together:

· Top Spending Major (by total volume) — Computer Science.

· Highest Spending Age — 24–25 years.

· Major With the Most Aid — Computer Science.

· Top Spender (by gender, as labeled) — Male Students.

· Average Spending by Gender (donut) — Non-binary leads at $2,257,365, followed by Female at $2,030,127 and Male at $2,027,986.

· Total Spending by Age Group (bar) — 24–25 ($1,792,318), 22–23 ($1,627,263), 18–19 ($1,463,345), 20–21 ($1,432,552).

· Books & Supplies Spending by Major (pie) — Engineering ($177.34), Computer Science ($176.34), Economics ($175.10), Psychology ($173.35), Biology ($171.13).

· Average Spending by Major (bar) — Biology ($1,429,717), Economics ($1,279,244), Computer Science ($1,221,771), Engineering ($1,196,986), Psychology ($1,187,760).

· Average Housing Cost by Year in School (bar) — Senior ($708.96), Junior ($705.29), Freshman ($703.21), Sophomore ($665.90).

· Financial Aid Distribution by Major (bar) — Computer Science ($549.93), Economics ($505.24), Engineering ($495.60), Biology ($489.61), Psychology ($485.48).

General Observations

· The dashboard’s own headline badges don’t fully match the detailed breakdowns: Computer Science is called the “top spending major,” but Biology actually has the highest average spending per student — the badge appears to reflect total volume, not per-student cost.

· Gender spending is far more balanced than the “Top Spender: Male Students” badge suggests — all three groups sit within roughly $230,000 of each other, with Non-binary students actually highest.

· Aid distribution loosely tracks spending by major but isn’t proportional — Computer Science receives the most aid despite ranking third in average spending, while Biology, the highest spender, ranks fourth in aid.

· Housing costs jump early (Sophomore to Freshman) and then plateau through Junior and Senior year, rather than rising steadily each year as might be assumed.

· Books & supplies costs are nearly flat across majors, making this one of the more predictable, low-variance cost categories in the dataset.

General Recommendations / Insights

· Report “top spending major” and “highest average spending major” as two separate metrics going forward, since conflating total volume with per-student average is misleading for aid planning.

· Revisit the gender-based “top spender” framing, since the actual spread between Male, Female, and Non-binary students is narrow enough that it may not warrant differentiated aid policy by gender.

· Audit the aid-to-spending ratio by major specifically for Computer Science and Biology, since the current allocation appears inverted relative to actual per-student spending.

· Concentrate housing-related aid planning around the Sophomore-to-Freshman/Junior transition, where the real cost jump occurs, rather than spreading assumptions evenly across all four years.

· Continue standardizing books & supplies budgeting across majors, since the cost spread here is too narrow to justify major-specific adjustments.

Data Limitations or Biases

· The dataset reflects a single reporting year, so it isn’t possible to tell whether the age-group and housing-cost patterns are stable trends or specific to 2024 without a prior-year baseline.

· “Average spending by major” and “total spending by age/gender” appear to be measuring different things (per-student average vs. total volume), and the dashboard’s own summary badges mix the two — so headline labels should be treated cautiously until the underlying calculation for each is confirmed.

· Financial aid amounts are shown as per-major averages, but the dataset doesn’t include enrollment size per major, so it isn’t possible to confirm whether aid differences are driven by higher individual awards or more students receiving aid.

Future Research

· Bring in enrollment counts by major to determine whether “total spending” differences are driven by cost per student or by how many students are in each major.

· Layer in income or need-based data to see whether aid distribution correlates with financial need rather than just spending levels.

· Track housing costs across a full four-year cohort (rather than a single snapshot year) to confirm whether the Sophomore-to-Junior jump is a consistent pattern.

· Analyze gender spending differences alongside major and age group together, to see whether the small gender gap becomes more meaningful when cross-referenced with other variables.

Analytical Tools

· Microsoft Excel — for data cleaning, PivotTables, slicers for year in school and major, and the final interactive dashboard (donut chart, bar charts, and a pie chart).

Conclusion

This analysis shows that student spending and financial aid at this institution don’t fully align — the dashboard’s own headline framing (top spending major, top spender by gender) doesn’t hold up once the detailed breakdowns are examined. Biology students carry the highest average spending burden, not Computer Science; gender differences in spending are narrow rather than concentrated in one group; and aid distribution favors Computer Science despite it ranking behind Biology and Economics in average spending. The recommendations above focus on realigning aid with actual per-student cost, correcting how “top spender” metrics are reported, and targeting housing support around when costs actually jump. Done together, these should move aid allocation from headline-driven assumptions toward a picture that reflects what students are actually spending.
