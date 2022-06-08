# School_District_Analysis
# Challenge Objectives & Environments: 

- Open Jupyter Notebook files from local directories using a development environment.
- Read an external CSV file into a DataFrame.
- Format a DataFrame column.
- Retrieve data from specific columns of a DataFrame.
- Merge, filter, slice, and sort a DataFrame.
- Apply the groupby() function to a DataFrame.
- Use multiple methods to perform a function on a DataFrame.
- Perform mathematical calculations on columns of a DataFrame or Series.
### Environments:
- conda 4.8.3 
- Jupyter Notebook 6.4.8
- Python 3.7
- NumPy
- Pandas


## Overview 
 A school district's stardardized tested data was analyzed to be used for the following school year's educational allocations. 
After careful reporting of a school district analysis, it was determined some of the information within the school district's original dataset had been compromised. Specifically, the reading and math scores of the ninth grade class from Thomas High School, a Charter within the District. A 2nd analysis had to be conducted after voiding the compromised scores of the entire ninth grade class of Thomas High School. This left the school with scores from only 1,176 students from a 1,635 count student body. The following metrics were re-measured after the adjustment:
- A high-level snapshot of the district's key metrics:
    - Average math score
    - Average reading score
    - Percentage of students who passed math
    - Percentage of students who passed reading
    - Overall passing percentage
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

## Results: 

- The initial Overall Passing Score Percentage for the District was 65%. After the adjustment the passing score percentage average was fairly 64.9%. This was expected, the 461 ninth grade math and reading scores that were removed only accounted for .01% of the 39,170 district student body.


- The School's Summary of % Passing Math, % Passing Reading, and % Overall Passing Rate decreased by 29%.
    - from 93%, 97%, and 90% respectively, to 66%, 69%, and 65% respectively.
<img width="841" alt="Per school initial" src="https://user-images.githubusercontent.com/105556091/172732910-02261184-85d3-48ae-87ce-5b0699363343.png">
<img width="814" alt="Per School adjustment" src="https://user-images.githubusercontent.com/105556091/172732924-773a2bfa-2ec0-4aeb-acaa-a62feb1d7088.png">

- The voiding of the ninth grade class' score's for Thomas High School resulted in the school losing it's placement as 2nd in the district of Top 5 Schools to the 8th top performing school.

- Math and reading scores by grade, orginally for the ninth grade class were 83.% and 83.6%. After the adjustment, It left Thomas High School with out a referenceable score value for the upcoming school-year
- <img width="310" alt="Screen Shot 2022-06-08 at 7 23 29 PM" src="https://user-images.githubusercontent.com/105556091/172733606-176e4b3a-d327-42b9-bc5a-beacab6e7b04.png">


- Overall passing percentage by School Spending-per student, decreased from 63% to 56%
    - it represented a negative relationship of spending per student. In the updated analysis the reported spending per student, $631-$645, is maintained but the overall passing score percentage of the student body decreased. This adjustment indicates the appearance of a negative trend on spending in regards to performance. A trend of this nature could cause Thomas high school to lose budgeting. 

- Overall passing score percentage by school size, decreased from 91% to 85% for schools of Medium size (1000--1999).

- For Types of Schools in the district, Voiding the ninth grade scores for Thomas High School decreased the Overall Passing Scores Percentage by roughly 3%. For Chartered Schools, the Overall Passing Score Percentage went from 90.4% to 87.1%.
<img width="745" alt="Screen Shot 2022-06-08 at 7 29 44 PM" src="https://user-images.githubusercontent.com/105556091/172734178-9038106f-3d87-491d-99e9-16c5e2b2db72.png">
-<img width="758" alt="Screen Shot 2022-06-08 at 7 29 11 PM" src="https://user-images.githubusercontent.com/105556091/172734141-00f166b5-7a38-4e73-b137-de04e201bd05.png">


Summary:

After voiding the ninth grade class' math and reading scores-replacing the values with NaN-4 changes were apparent:
- Scores by grade has no data for the freshman class-its value is represented by NaN
- Thomas High School's rank as 2nd in the district was changed to 8th.
- Thomas High school's overall passing percentage decrease by 28%
- Overall passing percentage grouped by spending per student reflected a negative trend, that may result in an unfavorable allocation for the upcoming school year.
-
