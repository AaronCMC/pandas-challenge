# pandas-challenge

## Summary of Analysis

Given access to district-wide standardized test results of every student's math and reading scores, as well as various information on the schools they attend, the purpose of this analysis was to aggregate the data to showcase obvious trends in school performance.

The analysis yielded the following:
* A 'District Summary' that provides a high-levl snaptshot of the district's key metrics, 
* A 'School Summary' that summarizes key metrics about each school (and additionally sorted for overall passing percentages),
* 'Math & Reading Scores by Grade' at each school,
* 'Scores by School Spending, School Size, and School Type'.


## Conclusion

* There appears to be a negative correlation between 'per student spending' and '% Passing Math' & '% Passing Reading'. 90% of students pass both math and reading within the lowest spending range per student of below $585, whereas only 54% of students pass both math and reading within the highest spending range per student of $645-680.
* Large sized schools with student counts of 2000-5000 are performing worse off in terms of percentage of students passing math and reading (58%), as compared to small and medium sized schools with student counts of up to 2000 (90% and 91% respectively). The top five performing schools in '% Overall Passing' are smaller schools with student counts ranging between 962-2283, whereas the bottom five performing schools are larger schools with student counts ranging between 2917-4761.
* Compared to District Schools, Charter Schools students obtain better math and reading scores on average, and a significantly greater proportion of their students pass math (94% vs 67%) and reading (97% vs 81%) . Furthermore, the top five performing schools in '% Overall Passing' are Charter Schools, whereas the bottom five performing schools are District Schools.
