# School Analysis & Thomas High School Revisions

## The School Board has asked for a set of deliverables to analyze schools in their area. We will present a high-level snapshot of the school's key metrics. 

Our team was presented a data set for the schools in the area. We used python and pandas to convert the data into a usable format. We will measure the average math & reading score received by students in each grade level at each school. Using a table format, the chart will show the Top 5 and bottom 5 performing schools based on the overall passing rate. We will look at the school performance based on the budget per student, school size, and type of school. To evaluate the students performance within each school, we determined the passing grade, gathered the number of students who passed math and reading, and converted the percentage of students who passed math and reading into an overall passing percentage. During our review, Thomas High School's 9th grade created an anomoly and we will explain the affected results below. 
---
## Results and Thomas High School's 9th Grade
 - First we will discuss how the district summary was affected. The district summary needs to be updated because we have eliminated a set of grades. Thomas High School's 9th grade data was inconsistent and may be due to academic dishonestly. Because the data was asked to be altered, our summary statistics will change. 
 - Secondly, we will see an update to the school summary. The school summary will need to be updated for the eliminated set of grades. All percentiles & averages will shift. 
 - Last, replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools greatly. Once we removed the 9th grade from the overall school calculation, we see the THS in the top 5 schools of the district. 
 - We need to explain how replacing the ninth-grade scores affect the following:
   - **Math and reading scores by grade**
### ![School_District_Analysis](https://github.com/ScottyMacCVC/Election_Analysis/blob/main/Election%20Results.jpg)
  - Math and reading scores for the 10th to the 12th grade will be unaffected by the change. But we will see a correction for the 9th grade. The averages for the 9th grade in the district and all schools will need to be updated.  
  - **Scores by school spending**
### ![School_District_Analysis](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20Spending%20Ranges.JPG)
  - **Scores by school size**
### ![School_District_Analysis](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Size.JPG) 
  - **Scores by school type**
### ![School_District_Analysis](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Type.JPG) 


- **Four Changes for the School District Analysis **
-- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

## Resources
- Data Source: schools_complete.csv
- Software: Python 3.7.6. Jupyter Notebook with Pandas
