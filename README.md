# School_District_Analysis

Overview of the school district analysis: Explain the purpose of this analysis.
The school board has notified Maria and her boss that the students_complete.csv file contains evidence of academic dishonesty. In particular, it seems that the reading comprehension and math grades of 9th graders at Thomas High School  have changed. Despite not knowing the full extent of academic fraud, the school board wanted to support state exam standards and  turned to Maria for help.

Results:
District Summary Affect
- Average Math Scores: moved from 79 to 78.9 as a result of taking out Thomas High School Ninth Grade scores.
- Average Reading Scores did not change.
- Percent Passing Math moved from 75% to 74%.
- Percent Passing Reading moved from 86% to 85%.
- Percent Overall Passing moved from 65% to 64%.

School Summary Affect:
- Average Math at Thomas decreased from 83.42 to 83.35.
- Average Reading at Thomas slightly increased from 83.84 to 83.89.
- Average Percent Passing Math at Thomas greatly decreased from 93.3% to 66.9%.
- Percent Passing Reading at Thomas decreases from 97.3% to 69.7%.
- Average Percent Overall passing both Math and Reading decreased from 90.9% to 65.1%.

Replacing:
- Math and reading scores by grade
    - Thomas High School's math scores were removed from the 9th grade and all other scores remained the same.
- Scores by school spending
    - With the removal of the 9th grade scores, the overall passing percentage decreased from 62.9% to 56.4%.
- Scores by school size
    - Thomas High School is a medium sized school and no real findings after adding the NaNs.
- Scores by school type
    - For the Charter, therefore, the changes were as follows:
        - Average Math scores declined from 83.47 to 83.46.
        - Average Reading scores were slightly higher: 83.89 compared to 83.9.
        - Percent Passing Math declined from 93.6 to 90.3.
        - Percent  Passing Reading declined from 96.6% to 93.1%.
        - Percent  Overall Passing decreased from 90.4% to 87.2%.
