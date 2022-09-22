# School_Distric_Analysis

A school board employee has given us the following tasks to analyise a set of data in a school district with a school that is suspected of altering testing data. The suspect data will be removed, specifically the Math and Reading test scores for the 9th graders at Thomas High School, and the impact on the overall data will be analysed. The school board asked for the data to be removed and analyzed again for a comparison. 


## Results

Due to potential academic dishonesty by the ninth grade students of Thomas High School, this analysis was conducted twice. The first trial of this analysis included the full set of student data. In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have had their scores replaced with NaN. The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN.

1. How is the district summary affected?

   - The modified summary shows that the Average Math Score decrease, the Average Reading Score increase, the percentage of students Passing Math decrease, the percentage of students Passing Reading decreased and the percentage of students passing both Math and Reading decreased. The adjusted summary is the lower graphic, and the original is the upper graphic.
   
Original

![District_Summary_df_Original.png](https://github.com/OrGriss26/School_District_Analysis/tree/main/Resources/District_Summary_df_Original.png)

Updated

![District_Summary_df_Updated.png](https://github.com/OrGriss26/School_District_Analysis/tree/main/Resources/District_Summary_df_Updated.png)

2. How is the school summary affected?

  - The modified summary shows that with-in Thomas High School, the Average Math Score decreased, the Average Reading Score increased, the percentage of students Passing Math decreased, the percentage of students Passing Reading decreased, and the percentage of students Passing both Math and Reading decreased. The adjusted summary is the lower graphic, and the original is the upper graphic.

Original

![School_Summary_df_Original.png](https://github.com/OrGriss26/School_District_Analysis/tree/main/Resources/School_Summary_df_Original.png)

Updated

![School_Summary_df_Updated.png](https://github.com/OrGriss26/School_District_Analysis/tree/main/Resources/School_Summary_df_Updated.png)

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

