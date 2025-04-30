# HR-Analysis
📘 HR Attrition Prediction and Analysis – Project Summary
🎯 Project Objective
To analyze employee attrition using machine learning and visualize key attrition patterns through a Power BI dashboard. The goal is to identify factors contributing to attrition and provide data-driven recommendations for retention.

🧪 Part 1: Python-Based Machine Learning Analysis
🧷 Dataset
Source: HREmployee_data.csv
Total Records: ~50,000 employees
Features include: Age, Department, Gender, Job Role, Overtime, Business Travel, Job Satisfaction, etc.

⚙️ Steps Performed
Data Exploration:
Checked data types, null values, and descriptive statistics.
Explored key features like Attrition, Department, Overtime, and Salary.

Preprocessing:
Label encoded the target variable Attrition (Yes = 1, No = 0).
Dropped irrelevant or constant features (e.g., EmployeeID, Over18).
One-hot encoded categorical features using get_dummies.

Feature Engineering:
Created a SalaryBand using quantile-based binning of the DailyRate.
Data Visualization:
Used Seaborn and Matplotlib to analyze attrition by:
Department
Overtime
Business Travel
Promotion History
Salary Band

Model Building:
Used Logistic Regression to predict employee attrition.
Data split into training and testing sets.
StandardScaler used for feature normalization.

Model Evaluation:
Accuracy Score, Confusion Matrix, and Classification Report used for assessment.
Achieved reasonable classification performance; further models like Random Forest can be tested for improvement.
__________________________________________________________________________________________________________________________________________________________________________________________________________________
📊 Part 2: Power BI Dashboard – Visual Analysis
Key Dashboard Highlights
Total Attrition: 25K out of 50K employees (~50.21%)
Balanced Attrition by Gender: ~50% Male / 50% Female
Attrition by Department: Sales and R&D show higher attrition
Attrition by Age: Younger employees (<35) more likely to leave
Attrition by Job Role: Sales and HR roles show elevated attrition rates
Attrition & Business Travel: All travel categories (~33% each) show similar attrition, indicating other influencing factors
Attrition vs Job Satisfaction: Clear inverse relationship – low satisfaction increases attrition
_______________________________________________________________________________________________________________________________________________________________________________________________________________
✅ Recommendations for Attrition Prevention
Reduce excessive overtime and promote work-life balance.
Offer clear career paths and timely promotions.
Benchmark and improve salary structures for lower bands.
Focus on boosting job satisfaction via engagement, feedback, and recognition programs.
Target interventions in high-risk departments and roles.
__________________________________________________________________________________________________________________________________________________________________________________________________________________
📂 Project Deliverables
✅ Python code (.ipynb): Data preparation, modeling, and EDA
✅ Power BI Dashboard: Interactive attrition analysis
✅ Readme Summary: For reporting, PDF export, or project documentation
