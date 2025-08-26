**Data Preprocessing Report**

📌 Dataset


Dataset: Student Performance Dataset

Rows: 10000

Columns: 12

🔧 Preprocessing Steps Done


=>**Column Cleaning**

=>Stripped extra spaces in column names

=>Converted to lowercase with underscores (math_score, reading_score, writing_score)

=>**Missing Value Handling**

=>Numeric columns (math_score, reading_score, writing_score) → filled with column mean

=>Categorical columns (e.g., gender, race/ethnicity) → filled with mode

=>**Data Type Conversion**

=>Converted scores to numeric (float64) using pd.to_numeric(errors='coerce')

=>**Duplicates Removal**

=>Checked and removed duplicate rows

=>**Outlier Detection**

=>Visualized with boxplots

=>Removed values beyond ±3 Z-scores

=>**Encoding Categorical Variables**

=>Applied One-Hot Encoding for gender, race/ethnicity

📚**Used Libraries**

==>pandas → Data loading, cleaning, handling missing values, encoding

==>numpy → Numerical operations, handling arrays, Z-score outlier removal

==>matplotlib → Data visualization (plots, histograms)

==>seaborn → Advanced visualizations (boxplots, distribution plots)
