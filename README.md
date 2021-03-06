# School_District_Analysis

## Overview of the school district analysis

The purpose of this analysis was to use Jupyter Notebook to read in .CSV files to create dataframes for displaying various metrics for math and reading broken down by district type, grade, and school. And this is to provide insight on performance trends and patterns. The reading and math grades for Thomas High School 9th grade are changed to nAn as there was academic dishonesty from the 9th graders.  

## Results

# How is the district summary affected?

The district summary isn't really affected noticeably with the removal of the THS 9th grader's scores. The first image below is from the inital analysis and the second is from the updated analysis with the 9th grade THS scores disallowed. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20District%20Summary.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Updated%20District%20Summary.png)

# How is the school summary affected?
With the 9th grade scores disallowed, we see a dramatic drop in overall passing for each subject for THS, as shown in the below images. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/top%20bar.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20School%20Summary.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/top%20bar.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Updated%20School%20Summary.png)
# How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
THS is among the top schools in passing percentages for math and reading, as well as overall passing percentage. The updated analysis drops them to the middle bottom, just above the bottom 5. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20Schools.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Updated%20Schools.png)

# How does replacing the ninth-grade scores affect the following:
# Math and reading scores by grade
We see the math and reading scores as null values for THS in the updated scores by grade. The first image is for math with reading below it. 

![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/New%20Math%20Scores.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/New%20Reading%20Score.png)

# Scores by school spending
Thomas High School is in the $630 - $644 range for spending range per student. There was very little change in spending with replacing the 9th grade scores. The original school spending dataframe is below this with updated spending under that. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20spending.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/updated%20spending.png)
# Scores by school size
With 1635 total students, Thomas High School is defined as a medium sized school. We see minimal changes with replacing the 9th grade scores. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20school%20size.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Updated%20size.png)

# Scores by school type
THS is a charter school. And again we see nominal reductions relative to math, reading, and overall passing percentages. 
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Original%20District%20Summary.png)
![alt text](https://github.com/Jgray353/School_District_Analysis/blob/main/Updated%20District%20Summary.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The data will now show nAn for Thomas High School 9th grade as we replaced the test scores with null since there was academic dishonesty. 
2. Thomsa High dropped from 2nd to 8th in overall performance.
3. We saw slight shifts across all aggregations (scores by spending, size, etc.)
4. Thomas High School's overall passing rate went drastically down, from 91 to 65%. 
