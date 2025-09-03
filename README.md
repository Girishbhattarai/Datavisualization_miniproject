📊 Effect of Alloy Composition on Tensile Strength

This project explores the relationship between alloying elements and the tensile strength of low-alloy steel using Python’s data analysis and visualization libraries.

🔧 Tech Stack:
Python
NumPy
Pandas
Matplotlib
Seaborn

Project Workflow:
1. Data Preparation
Collected datasets on low-alloy steel composition.
Cleaned and preprocessed data for consistency.
2. Correlation Analysis
Plotted a heatmap to visualize correlations.
Identified elements with the strongest effect on tensile strength:
Vanadium, Molybdenum, Nickel, Chromium, Carbon, Manganese.
3. Scatterplots & Regression
Visualized element-wise relationships.
Handled outliers (limited tensile strength to 0–200 MPa for clarity).
Added regression lines with R² values.
4.Plot Saving
Used plt.savefig to store plots locally.
Applied bbox_inches="tight" for improved captions.

📈 Key Insight

Certain alloying elements have a significant impact on tensile strength.
Visualization highlights positive/negative correlations clearly.

🚀 Next Steps:
Apply advanced ML models to predict tensile strength.
Extend dataset for more alloys.
