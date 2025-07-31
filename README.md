💼 Salary Prediction Project
This project focuses on predicting employee salaries using machine learning techniques based on a variety of features such as education level, years of experience, job title, industry, location, and more. It aims to assist organizations in making informed salary decisions and understanding compensation patterns within their workforce.

🔍 Project Overview
Accurately predicting salaries helps companies optimize compensation strategies and ensures competitiveness in the job market. By leveraging historical salary data and employee attributes, this project builds a model that can estimate expected salaries for new or existing employees.

🛠 Features Used
Education Level: Highest qualification attained by the employee.
Years of Experience: Total work experience in years.
Job Title: Designation or role of the employer 
Age: Employee’s age.
Gender: male/female
Salary: according to experience and educational level.

📊 Data Preprocessing
Removed rows with missing salary values from training data to ensure quality.
Handled missing values in features:
Filled numerical missing values with column means.
Filled categorical missing values with the most frequent category (mode).
Encoded categorical variables using one-hot encoding to convert them into a machine-readable format.
Scaled all feature values using StandardScaler to normalize data distribution, which improves model performance.

⚙️ Model Building
Algorithm: Random Forest Regressor
Parameters: 50 decision trees (n_estimators=50), fixed random_state for reproducibility.
Training: Data split into 80% training and 20% validation.
Evaluation Metric: Root Mean Squared Error (RMSE) calculated on validation data to quantify prediction accuracy.

📈 Model Performance
The model achieved an RMSE of approximately ₹<your_rmse_value> on the validation set.
Feature importance analysis revealed which factors most influenced salary predictions, enabling interpretability.

🧑‍💻 How to Run the Project
Clone the repository or download the source files.
Ensure you have the required Python libraries installed:# salary
