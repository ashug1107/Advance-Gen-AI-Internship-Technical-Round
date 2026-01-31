# Advance-Gen-AI-Internship-Technical-Round
Advance Gen AI Internship Technical Round Repositary

Key Technical Steps
1. Data Cleaning & Integration

Merging: Using pd.merge() to combine order logs with user profiles and restaurant metadata.

Type Conversion: Ensuring numerical stability by converting currency and ratings using pd.to_numeric().

Standardization: Cleaning string data (cities, cuisines, membership levels) using .str.strip() and .str.title() to ensure accurate grouping.

2. Analytical Highlights

Distinct User Tracking: Calculated unique customer counts using .nunique() to understand reach versus frequency.

High-Rating Performance: Filtered orders for restaurants with ratings ≥4.5 to analyze premium segment volume.

AOV Benchmarking: Calculated Average Order Value specifically for Gold members to evaluate the effectiveness of loyalty programs.

Constraint-Based Filtering: Identifying niche "high-value" restaurants that maintain a high AOV even with lower order volumes (<20 orders).

📈 Key Insights
Top City: Identified the city generating the highest revenue among Gold members.

Cuisine Efficiency: Discovered cuisines with a small physical footprint (low restaurant count) that contribute disproportionately high revenue.

Membership Impact: Comparative analysis of Gold vs. Italian/Indian cuisine combinations to find the highest revenue drivers.

🧰 Tools Used
Python 3.12.10

Pandas: For data manipulation and aggregation.

Jupyter Notebook: For interactive analysis.
