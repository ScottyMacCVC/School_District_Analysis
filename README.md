# School Analysis & Thomas High School Revisions

## The School Board has asked for a set of deliverables to analyze schools in their area. We will present a high-level snapshot of the school's key metrics. 

Our team was presented a data set for the schools in the area. We used python and pandas to convert the data into a usable format. We measured the average math & reading score received by students in each grade level, at each school. The compiled data will show the Top 5 and bottom 5 performing schools based on the overall passing rate. We will look at the school performance based on the budget per student, school size, and type of school. To evaluate the students performance within each school, we determine the passing grade, gather the number of students who passed math and reading, and convert the percentage of students who passed math and reading into an overall passing percentage. Thomas High School's 9th grade created an anomoly, we removed the results, and we will explain the affected results below. 
---
### Results and Thomas High School's 9th Grade
 - First, we will discuss how the district summary was affected. The district summary needs to be updated because we have eliminated a set of grades. Thomas High School's 9th grade data was inconsistent and may be due to academic dishonestly. Because the data was asked to be altered, our summary statistics will change. 
 - Secondly, we will see an update to the school summary. The school summary will need to be updated for the eliminated set of grades. All percentiles & averages will shift. 
 - Lastly, replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools. Once we removed the 9th grade from the overall school csv data, we see THS in the top 5 schools of the district. 
---

## How replacing the 9th Grade scores affect the following:
   - **Math & Reading Scores by Grade** The majority of our information will remain the same. We isolated the 9th grade at Thomas High School and replaced them with NaN or Not a Number. Math and reading scores for the 10th to the 12th grade will be unaffected by the change. But we will see a correction for the 9th grade, the averages for the 9th grade in the district and all schools will be updated.  
### ![Math and reading scores by grade](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/Math%20and%20reading%20scores%20by%20grade.JPG)
  - **Scores by School Spending** We sorted each school into spending buckets. The section $630-$644 contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by Spending Ranges](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20Spending%20Ranges.JPG)
  - **Scores by School Size** We sorted each school into shool sizes. The section Medium contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by School Size](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Size.JPG) 
  - **Scores by School Type** We sorted each school into shool Types. The section Charter type contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by School Type](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Type.JPG) 


- **Four Changes for the School District Analysis **
-- **1** Removed 9th grade data from Thomas High School 
-- **2** Using Dataframes, we built a DF without 9th grade data from Thomas High School and combined it with the existing data 
-- **3** Using the new data, we presented the data in several ways such as by math/reading, by grade, spending ranges, school size, and type. 
-- **4** We recalculated the new data from the Dataframe and added it to the summaries


## Resources
- Data Source: schools_complete.csv
- Software: Python 3.7.6. Jupyter Notebook with Pandas
