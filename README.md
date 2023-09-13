# Pandas-Challenge
PyCity Schools Analysis
This analysis starts by assessing the overall performance of the district. It is evident from this examination that students face greater challenges in mathematics compared to reading. Additionally, the data reveals that while many students pass either reading or math, fewer excel in both subjects. This suggests a tendency among students to favor one subject over the other, making it uncommon to excel in both simultaneously.
The analysis further delves into school-specific comparisons. Key observations include the significantly higher pass rates in charter schools compared to district schools. Surprisingly, schools with a higher budget per student demonstrate poorer overall exam performance. Moreover, medium and small-sized schools consistently outperform their larger counterparts.
An intriguing point to investigate is whether charter schools employ higher-caliber teachers or employ slightly different curricula, which could be adopted in other schools to improve outcomes.
Notably, there is a negative correlation between budget per student and performance. While this may imply that increasing funding isn’t the most effective solution for improving scores, it’s essential to consider whether these funds have been directed towards historically underperforming schools, potentially contributing to their recent improvements. Examining past years’ data is crucial before making any definitive decisions.
In conclusion, smaller and medium-sized schools consistently yield better test scores. Exploring the possibility of breaking up larger schools and establishing new ones nearby could be a viable strategy to enhance academic performance.


Total school budget
total_budget = school_df["budget"].sum()
total_budget

Per student budget

Average math score
average_math_score = combined_school_df["math_score"].mean()
