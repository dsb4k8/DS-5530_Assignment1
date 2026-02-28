V1 — Gender boxplots (math vs reading)
Question: Are there gender differences in math vs reading?
 - Answer
   - It would appear so:
   - **In Math:**
     - The median score for men was higher than the median for woman.
     - This is true as well for the top 25% of men and women math students.
   - **Reading:**
     - Conversely the median scores and 75th percentile for women is higher than the median for men.
   - It appears that in both cases, there is a greater spread for score outliers among females on the lower end.

# V1 — Gender boxplots (math vs reading) (2 pts)
Question: Are there gender differences in math vs reading?
 - Answer
   - It would appear so:
   - **In Math:**
     - The median score for men was higher than the median for woman.
     - This is true as well for the top 25% of men and women math students.
   - **Reading:**
     - Conversely the median scores and 75th percentile for women is higher than the median for men.
   - It appears that in both cases, there is a greater spread for score outliers among females on the lower end.

# V2 — Test prep impact on math
Question: Do students who completed test prep score higher in math?
 - Answer: grouping `average_scores = df.groupby('test preparation course', observed=False)['math score'].mean()` reveals 
   that the average score for students who took test prep scored 69.695531, while those who did not only scored 64.077882 on average
- Chart: Any chart of your choice for math score by test preparation course (completed vs none).

# V3 — Lunch type and average performance
Question: Does lunch type (standard vs free/reduced) relate to outcomes?
- Answer: Yes, Standard Lunch students got an average score of 70.837209 across the 3 subjects as opposed to 62.199061 for Free/ Reduced lunch students.
- the ~8% score discrepency is higher th

# V4 — Subject correlations (2 pts)
Question: How strongly do the three subjects move together?
- Answer: These are strongly correlated:
  - Math and reading scores have a correlation of 0.82, 
    - .82^2  = ~67% of the variation in one variable is explained by the other
  - Math vs writing has a correlation of 0.80
  - - .80^2  = ~64% of the variation in one variable is explained by the other
  - Reading and Reading have a correlation of 0.95
  - - .95^2  = ~90% of the variation in one variable is explained by the other
- These are all positive numbers close to 1.0, and this suggests that if a student did well in at-least one of these subjects, there is a high likelihood they also did well in the other 2

# V5 — Math vs reading with trend lines by test prep (2 pts)

Question: How strongly are math and reading scores associated, and do students who completed the test‑preparation course have a different slope in the math–reading relationship than those who did not?
- Answer: Math and reading scores are strongly and positively associated. 
  - The data points on this here are tightly clustered around both trend line for both subjects.
  - As reading scores increase, math scores generally increase too
  - Slopes: These slopes are nearly the same, deviate by very little. This Suggests that the rate of change in the relationship between math and reading scores are nearly identical.
