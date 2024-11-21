# **Excel Manager Salary Survey Project Overview**


This is an overview page for my salary survery data project in Excel. This project tries to
find the effect that location and characteristics such as gender have on earnings. In this
document I will briefly outline some of the steps I have taken to complete the project,
with a small discussion on results and potential next steps at the end. To view the project 
file itself (which also contains the raw data) simply download it from my GitHub page.

Steps Taken:

1. Since I only wanted to analyse entries from the USA, I used the filter tool to find
and delete non-USA entries.

2. Used the remove duplicates tool to find and delete duplicate rows that would distort 
results.

3. Deleted the now redundant currency and country columns, after deleting the few 
entries that had workers in the US earning foreign currency.

4. Created a total compensation row which was calculated using the SUM() function on
salary and bonus rows.

5. Used Find and Replace tool to change null and unanswered race and gender values to
'unspecified'.

6. Used nested IF() statements to simplify race values for analysis.

7. Used XLOOKUP to create a region column, mapping each US state to its respective 
region.

8. Created pivot tables from the now cleaned data.

9. Created charts from the pivot tables that would make up my final dashboard.

10. Added slicers to allow for filtering on dashboard, and linked to all charts.

Using the dashboard provides some interesting results. Men are found to earn more than
women, though non-binary individuals earn even less. California, Washington (containing 
Seattle) and New York are the top 3 states for average compensation. Compensation 
increases with experience mostly, but towards the higher year values there is a notable decrease.

Using the slicers you can find other results, such as although the top 3 states are the
same for white people, the states vary on race (and other categories). For men, a PhD
does not increase their average compensation that much over a master's degree, but it
will for women and non-binary people. When filtering it is important to remember that
the more narrow the search, the lower the sample size, which diminishes the significance
of results.

Potential next steps on this project could include: Conducting hypothesis tests to
determine if a result is significant, comparing and testing results with past
surveys if the same questions were asked, using Tableau to create more powerful 
visualisations.


