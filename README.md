# Travel Insurance Prediction using Machine Learning

## Project Overview
This project focuses on predicting whether a customer will purchase travel insurance using machine learning techniques. The model analyzes customer demographics, travel behavior, and financial details to make predictions.

---

## Dataset Information
The dataset contains 1987 records with 10 features.

Features include:
- Age: Age of the customer  
- Employment Type: Type of employment  
- GraduateOrNot: Graduation status  
- AnnualIncome: Annual income of the customer  
- FamilyMembers: Number of family members  
- ChronicDiseases: Whether the customer has chronic diseases  
- FrequentFlyer: Whether the customer frequently travels  
- EverTravelledAbroad: Whether the customer has traveled abroad  
- TravelInsurance: Target variable (0 = No, 1 = Yes)  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Project Workflow
1. Data Loading  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Encoding  
5. Train-Test Split  
6. Feature Scaling  
7. Model Building  
8. Model Evaluation  

---

## Data Preprocessing
- Removed unnecessary column (Unnamed: 0)  
- Converted categorical variables using encoding  
- Scaled numerical features using StandardScaler  

---

## Machine Learning Models
- Logistic Regression  
- Random Forest Classifier  

---

## Model Evaluation
The models were evaluated using:

- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## Key Insights
- Frequent travelers are more likely to purchase insurance  
- Customers who have traveled abroad tend to buy insurance  
- Higher income increases the likelihood of purchasing insurance  
- Employment type influences customer decisions  

---

## Conclusion
The project successfully predicts travel insurance purchases using machine learning. It provides useful insights into customer behavior and helps in decision-making for insurance companies.

---

## Future Improvements
- Hyperparameter tuning  
- Use advanced models such as XGBoost  
- Deploy the model using Flask or Streamlit  

---

## Project Structure
travel-insurance-prediction-ml/
│
├── travel_insurance.ipynb  
├── dataset.csv  
├── README.md  

---

## Author
Karthikadevi O  
Aspiring Data Scientist  

---

## Note
This project is created for educational purposes and demonstrates machine learning techniques.
