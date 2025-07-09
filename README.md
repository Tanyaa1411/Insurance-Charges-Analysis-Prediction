Insurance-Charges-Analysis-Prediction

Analyze factors influencing medical insurance charges and predict costs for individuals based on features like age, BMI, sex, smoking status, children, and region. Key Tasks Performed: Data Exploration & Visualization:

Used scatter and box plots to study how age, BMI, sex, and smoking affect medical charges.

Findings:

Smoking is the most significant cost driver — smokers incur much higher charges.

Age and BMI show positive correlation with charges.

Sex has minimal impact on average charges.

Model Building:

Built a Linear Regression model using scikit-learn.

Applied OneHotEncoding to handle categorical variables (sex, smoker, region).

Trained the model on 1338 samples from insurance.csv.

Cost Prediction Example:

Input: Age 28, Male, BMI 33.0, 3 Children, Non-Smoker, Southeast Region

Predicted Insurance Cost: ₹6,707

🛠️ Tools Used: Python (Pandas, Matplotlib, Seaborn, scikit-learn)

Dataset: insurance.csv (1338 rows, 7 features) [kaggle link:https://www.kaggle.com/datasets/mirichoi0218/insurance]
