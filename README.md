# task2
1. Generating Summary Statistics
We used the .describe() function to get basic metrics for all numeric features: count, mean, standard deviation, min, max, and quartiles.
From this, we discovered:

Some features (like Age) had missing values.

Features like Fare had very high maximum values, showing skewness.

Pclass and Survived are numeric but represent categories.

Why it matters: Summary statistics give a quick overview of the scale, spread, and missing data.

2. Creating Histograms and Boxplots
We visualized the distribution of each numeric feature:

Histograms showed us how data is distributed (e.g., right-skewed, normal).

Boxplots revealed outliers and the spread of data.

Insights included:

Age was mostly concentrated around young adults.

Fare was heavily skewed with a few very high values.

Most people had 0 siblings/spouses and 0 parents/children on board.

Why it matters: These plots help identify skewed data, need for transformation, and detect outliers.

3. Using Correlation Matrix and Pairplot
We used a correlation matrix heatmap and pairplot to study relationships between features:

Fare had a strong negative correlation with Pclass.

Survived was positively correlated with Fare, negatively with Pclass.

SibSp and Parch had a moderate positive correlation.

Why it matters: Correlations help you identify which variables may influence each other or the outcome. Pairplots visually show clusters and relationships.

4. Identifying Patterns, Trends, and Anomalies
We interpreted all visualizations and stats to make deeper observations:

Young adults formed the majority of passengers.

Higher fare and better class increased chances of survival.

Most people traveled alone.

Some features had extreme values (e.g., high Fare), marking them as anomalies.

Why it matters: Helps us form hypotheses, spot errors, and prepare for model building (like outlier handling or feature transformation).

5. Making Feature-Level Inferences
We analyzed each numeric feature individually and made basic inferences:

What the typical values were

What patterns or distributions looked like

Any irregularities or skewness

How features might influence outcomes

Why it matters: Feature-level understanding is crucial before building predictive models.
