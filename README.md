# School_District_Analysis

#PyCIty Schools District Analysis

##Project Overview

The purpose of this project is to analyze data from standardized testing scores, school populations, school funding and school types to find trends within the data.  By isolating trends in this data set, the PyCity School Board and Superintendent will have a deeper understanding of the performance of the high schools in the district.  With this deeper understanding, the Board and Superintendent will be able to effectively manage school budgets and set priorities for improving the underperforming schools.

##Results

###Thomas High School

The removal of potentially altered grades from 9th graders at Thomas High School did not have any noticeable affects on the district wide comparisons for spending, size or type.  The changes did negatively affect all five student performance metrics for the individual school. However, the changes only dropped the overall passing percentage of Thomas High School by three hundredths of a percent.  The biggest difference noticed with the Thomas High School changes was the average math score. This change was nearly inconsequential for the purposes of this report.

###Top Performing Schools

![top_performing_schools](https://user-images.githubusercontent.com/105960365/177220769-ca248b60-60fc-48f7-8387-56a9ed4784db.png)
Top performing schools adjust for THomas High School academic dishonesty.

![top_performing_schools_uncorrected](https://user-images.githubusercontent.com/105960365/177220850-9efa867b-9418-407d-bccb-7f7a0b27f74b.png)
Top performing schools uncorrected for academic dishonesty.

The top performing schools in order are as follows:
-	Cabera High School
-	Thomas High School
-	Griffin High School
-	Wilson High School
-	Pena High School

The most noticeable commonality between these schools is their charter designation. Beyond that they vary in per student budget and total students although the bottom performing schools are significantly larger. Due to the academic dishonesty among 9th graders at Thomas High School, their grades had to be removed from the data. This did change the passing rates and average scores for Thomas High School as a whole, but not significantly.  After removing the suspect grades from the calculations, Thomas High School remained the second highest performing school. This can be seen in the following images of the top five performing schools.

###Bottom Performing Schools

![bottom_performing_schools](https://user-images.githubusercontent.com/105960365/177220903-f0677581-eb50-44b8-b068-cdc1a09de558.png)

The bottom performing schools in order are as follows:
-	Rodriquez High School
-	Figueroa High School
-	Huang High School
-	Hernandez High School
-	Johnson High School

The five worst performing schools were all district with larger numbers of students.  These schools all seemed to be largely affected by underperforming in the math portion of the standardized testing.

###Average Scores by Grade

![math_scores_by_grade](https://user-images.githubusercontent.com/105960365/177220939-b7ce1076-7d9c-44ad-8a3b-e0741e319b26.png)
Math scores by grade and school.

![reading_scores_by_grade](https://user-images.githubusercontent.com/105960365/177220978-a745a551-0116-4b2a-b1f4-c7887813bbff.png)
Reading scores by grade and school.

Looking at average scores per grade for each school does not provide much insight.  For both math and reading each school had very similar averages for each grade.  Thomas High School had very similar grades for 9th graders before the values were replaced. 

###Scores by Spending Per Student

![school_spending_per_student](https://user-images.githubusercontent.com/105960365/177221010-5c510480-d355-4f21-9695-753186932496.png)

Spending per student at these levels did not have an outcome on student performance. Based on the data provided, as spending per student increased, overall student performance decreased.  The changes with Thomas High School did not affect this comparison.

###Scores Based on School Size

![scores_by_school_sizes](https://user-images.githubusercontent.com/105960365/177221026-a2427793-5625-4c88-9f6c-a5b6d6a1ffae.png)

For the size comparison, schools were divided into three size groups. Large schools had the worst performance by a large margin. Small and medium schools performed at a very similar level with medium schools slightly edging out small school as the highest performing.  The changes with Thomas High School did not affect this comparison.

### Scores by School Type

![scores_by_school_type](https://user-images.githubusercontent.com/105960365/177221042-1e05ab73-b1b9-4489-adb0-77d6be95982d.png)

The type of school was the greatest predictor of school performance. No single school deviated a significant amount from the school type average. Charter schools are greatly outperforming district schools across all metrics but especially in the percentage of students passing math.  The changes with Thomas High School did not affect this comparison.

##Summary

This data provided some unique insight into school performance.  School funding did not provide a performance boost for schools.  The greatest determining factor for school performance was the school type.  Charter schools greatly outperformed the district schools in all metrics. Charter schools were able to produce greater results in the standardized testing with a smaller per student budget. The size of the schools could be seen as influential at first glance, but sizes difference among charter schools did not make significant impact and the same could be said for district schools.
Although academic dishonesty should not be taken lightly, the changes for Thomas High School had no real impact on these comparisons.
