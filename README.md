# University-of-Vermont-Salary-Analysis

University administration is _complex_. There are hundreds, if not thousands, of employees. There are multiple colleges - and all seperate college
have their own administrative and pay systems.

**University of Vermont** is one such university. With nearly a dozen colleges, the university employees over 1750 employees. Various colleges(namely)
**College of Arts and Science(CAS)** and **College of Medicine(COM)** have different levels of success according to various metrics - including employee count, student count, and average employee salary.

In this analysis, I explore the implication given by [this article](https://vtdigger.org/2020/12/03/uvm-to-eliminate-23-programs-in-the-college-of-arts-and-sciences/) that **CAS has been struggling over the years**. This analysis will be done in 4 parts.
Each part will have corresponding charts made on Tableau Public.



|**Parts**|**Description**|**Queries Used**|
| :------------- |:-------------| :-----| : -----|
| Part 1      |Initial Salary Analysis. I use queries to understand a brief overview of which colleges have what kind of salary and employee range. |(Queries used: Count, Distinct, Group by, Order by, Where)|
| Part 2     |   I begin comparing CAS and COM in detail to understand how they interact and relate to each other in terms of salary and employee count.   | (Queries used: Case/When statements) |
| Part 3 |    I dig deeper into the relationship solidified in Part 2 and add the element of the entire university to it. | (Queries used: Count, Distinct, As, Group By, Sum, Partition/Over, Order By)  |
| Part 4 |    I finish my query by looking into the total amount each college has spent on employees.     |Queries used: Sum, Distinct, Group By)  |

As a brief conclusion: We can definitely see a downwards trajectory with employee count growth, total salary expenditure growth and a dwindling ratio
of CAS Employees to total employees. The article is correct.

The dataset was taken from [Kaggle](https://www.kaggle.com/datasets/tysonpo/university-salaries), which, in turn was taken from the [University website](https://www.uvm.edu/oir/faculty-and-staff)
