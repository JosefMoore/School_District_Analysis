# School_District_Analysis
_______________________________________

####The purpose of this analysis was to practice using pandas methods to filter and group a dataset. 

* We started by using .isnull(), .dropna(), .duplicated(), drop_duplicates(), and .isna().sum() to find and drop any rows with null values or duplicate rows.

* We then used .dtypes() to determine our columns data types and then changed them if necessary. 

* After that, we used .loc() and .iloc() to filter our data set by rows and/or columns. This allows us to apply measures of central tendency or any other operation to specific rows and columns. 

* For our last section, we used .groupBy() to group certain columns in our data set. We first used this to group our dataset by school type and then used that variable to get the mean budget per school type. Charter schools had a much higher average budget. 

* We then grouped our data set by school name, counted the number of students in those schools, all while assigning our results to a student_count column. Afterwards, we were able to sort our student_count column in descending order. We learned that Montgomery High School had the most students.

* Finally, we wanted to find our the average math score by grade per school type. We used groupBy() on our school_type and grade columns, then performed the mean() method on our math_score column. Charter schools had a higher average math score per grade compared to public schools, which makes a case for higher funding for public schools potentially.