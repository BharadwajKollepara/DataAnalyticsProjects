## Dataset Description:
1. Columns description:
* S.NO: Serial number of students
* SECTION: Section names (ALPHA, BETA, GAMMA, DELTA, SIGMA, OMEGA, ZETA, EPSILON)
* DV, M-II, PP, BEEE, FL, FIMS: Subject names with corresponding scores
2. Initial Observations:
* Scores seem to be numerical values representing marks obtained.
* There are six subjects listed.
* No student names or IDs are present, only serial numbers

# Dataset Observations:
## Visualisation Insights
The dataset contains student midterm marks for multiple subjects. After cleaning, it includes numeric values only, removing any non-numeric data. The dataset has rows representing students and columns representing subjects and student details.

1. Key Observations:
* Number of Rows & Columns: The dataset consists of X students and Y subjects.
* Missing Values: Some subjects have missing marks, which were handled during analysis.
* Summary Statistics: The dataset provides mean, median, minimum, and maximum scores for each subject. Some subjects have high variability in marks.
* Correlation Analysis: A heatmap revealed that certain subjects have strong positive correlations, indicating that students who performed well in one subject also did well in another.
* Marks Distribution: Histograms and violin plots showed normal or skewed distributions for different subjects.
* Trends Across Students: Line plots helped visualize how marks varied across students.
* Overall, the dataset provides valuable insights into student performance, subject correlations, and trends in midterm scores.

## Statistical Insights: T-tests and Chi-Square Tests
1. T-tests:
    * T-tests were performed to compare the mean marks between two subjects to check if the difference in their averages is   statistically significant.

Purpose: To determine if the difference in performance between subjects is due to chance or a meaningful difference.
Null Hypothesis (H₀): The mean marks of the two subjects are equal.
Alternative Hypothesis (H₁): The mean marks of the two subjects are significantly different.
Key Findings:

Some subjects showed statistically significant differences in mean scores, indicating real performance variation.
Subjects with p-values < 0.05 showed significant differences, meaning the performance disparity was unlikely due to chance.
No significant difference was observed in subjects with p-values > 0.05, suggesting similar average performance.

2. Chi-Square Tests:
        *Chi-square tests were conducted to assess the independence between categorical variables, such as marks ranges (e.g., low, medium, high) across different subjects.

Purpose: To check if performance in one subject is independent of another.
Null Hypothesis (H₀): The subjects are independent (no association).
Alternative Hypothesis (H₁): The subjects are dependent (associated).

3. Key Findings:

Subjects with p-values < 0.05 indicated a statistically significant association, suggesting that performance in one subject was linked to another.
Subjects with p-values > 0.05 showed no association, meaning performance in one subject had no bearing on the other.
