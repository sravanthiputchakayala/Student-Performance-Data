This project involves an exploratory and predictive analysis of a student performance dataset using Python and popular data science libraries. The goal is to understand how various factors influence student outcomes and to model student performance based on these factors.

📂 Dataset
The dataset used includes various attributes related to students, such as:

Gender

Ethnicity

Parental level of education

Lunch type

Test preparation course

Scores in math, reading, and writing

These features help us understand the impact of socio-demographic and preparatory factors on student academic performance.

🧪 What I Did
1. Imported Required Libraries
Used standard libraries such as numpy, pandas, matplotlib, and seaborn for data manipulation and visualization.

Loaded the dataset into a pandas DataFrame for analysis.

2. Initial Data Inspection
Checked for null values and basic statistics using df.info() and df.describe().

Verified that there were no missing values in the dataset.

Looked at the shape and column data types.

3. Data Cleaning and Feature Engineering
Converted categorical variables into numeric using label encoding and one-hot encoding (if applicable).

Created a new feature for average score to summarize overall performance across subjects.

4. Exploratory Data Analysis (EDA)
Plotted histograms and box plots to visualize score distributions.

Used seaborn's pairplot and heatmap to explore relationships and correlations between features.

Performed group-wise analysis:

Score differences by gender, parental education level, and test preparation status.

Insights showed that students who completed test preparation scored significantly higher.

5. Data Visualization
Visualized average scores grouped by:

Parental level of education

Test preparation course completion

Gender

Bar plots and violin plots revealed patterns such as:

Females tend to outperform males in reading and writing.

Completing a test preparation course boosts performance across all subjects.
This analysis provides a comprehensive look at factors affecting student performance.
It helps educators and policymakers understand areas where interventions (like test preparation) can yield substantial benefits.

