First, I wanted to see the relationship between EMPLOYER and BASE SALARY. After computing the With Best, Hsu MCB Test, I found that Netflix could have the maximum mean base salary because its mean fails to differ significantly from the maximum mean. By the same reasoning, the minimum mean base salary could correspond to Amazon. 

Additionally, the Analysis of Means Methods shows that mean base salaries for Apple, Facebook, Google, and Netflix are above the overall mean. While the mean base salaries for Amazon and Microsoft are below the overall mean. 

I also created an interactive visual in Tableau that shows the relationship between average base salary, employer, and the number of visas submitted. Unsurprisingly, the average base salary increase with time for all employers. The number of visas submitted is less consistent but seems to show a positive trend as well.  

[Employer Salary vs Time by Employer Visual](https://public.tableau.com/profile/albert.b.joseph#!/vizhome/EmployerSalaryvsTimebyEmployer/EmployerSalaryvsTimebyEmployer){:target="_blank"}

Next, I wanted to see the impact of location on base salary. To do this, I created a separate column for City and State in my excel file and only analyzed states with at least 30 Visas submitted. 

The Analysis of Means Methods below shows that California and New York's mean base salaries are above the overall mean. This may be because of the high cost of living. 

I also ran a two-sample t-test on the mean base salaries for NY-CA and concluded at 95% confidence that the true average mean base salary for NY is less than that of CA. 

The interactive visual below shows the mean BASE SALARY plotted on a map of the U.S. with EMPLOYER as a filter.  

[Salary by Location Visual - External Link](https://public.tableau.com/profile/albert.b.joseph#!/vizhome/SalarybyLocation_16105056002930/SalarybyLocation)

Next, I analyzed the job titles using the text explorer function in JMP and a word cloud in Tableau. Unsurprisingly, "Software Engineering" was the most popular job title, followed by program manager, product manager, and data roles. For the word cloud, I only used job titles with at least 30 occurrences. 

[Text Explorer Visual](https://public.jmp.com/packages/Text-Explorer-for-JOB-TITLE/js-p/cM_Y5WHnkwFyYYBjdGzcF)

[Word Cloud Visual - External Link](https://public.tableau.com/profile/albert.b.joseph#!/vizhome/JobTitleWordCloud/JobTitleWordCloud)

I also wanted to determine the effect of job titles and job categories on base salary. To do this, I created an IF statement in Excel to classify job titles as software, product, data, supply chain, or operations program. 

After computing the With Best, Hsu MCB Test, I found that Product roles could have the maximum mean base salary because its mean fails to differ significantly from the maximum mean. The minimum mean base salary could correspond to Supply Chain or Operations Program roles by the same reasoning. Additionally, the Analysis of Means Methods shows that mean base salaries for Product roles are above the overall mean.  

An analysis of the salary for each job category by employer is summarised below:
Product Job Titles
(With Best, Hsu MCB Test)
Employers with Maximum average base salary: Netflix
Employers with Minimum average base salary: Amazon or Microsoft

(ANOM Test)
Employers with mean base salary above the overall mean: Netflix, Facebook, and Google
Employers with mean base salary below the overall mean: Amazon and Microsoft 
Software Job Titles
Employers with Maximum average base salary: Netflix
Employers with Minimum average base salary: Amazon

Employers with mean base salary above the overall mean: Apple, Facebook, and Netflix
Employers with mean base salary below the overall mean: Amazon, Google, and Microsoft
Data Job Titles
Employers with Maximum average base salary: Netflix
Employers with Minimum average base salary:  Amazon

Employers with mean base salary above the overall mean: Netflix and Facebook
Employers with mean base salary below the overall mean: Amazon, Google, and Microsoft

The interactive visual below shows the base salary associated with job titles (with at least 30 Visas submitted). 

[Job Salary Visual - External Link](https://public.tableau.com/profile/albert.b.joseph#!/vizhome/JobSalary/JobSalary)
