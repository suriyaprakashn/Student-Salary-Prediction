# Student Salary Prediction Project

A comprehensive machine learning project to predict student salaries based on educational background, work experience, and academic performance.

## 📊 Project Overview

This project aims to develop a predictive model that estimates the expected salary of students based on their complete educational journey - from schooling through MBA, including work experience and specialization details.

## 📁 Dataset Information

- **Features**: 19 variables
- **Target Variable**: Salary

### Dataset Attributes

| Feature | Description | Type |
|---------|-------------|------|
| SlNo | ID of the student | Identifier |
| Gender | Gender of Student | Categorical |
| Percent_SSC | Percentage of marks scored in SSC | Numerical |
| Board_SSC | Types of Boards in SSC | Categorical |
| Percent_HSC | Percentage of marks scored in HSC | Numerical |
| Board_HSC | Types of Boards in HSC | Categorical |
| Stream_HSC | Specialization in HSC | Categorical |
| Percent_Degree | Percentage of marks scored in Degree | Numerical |
| Course_Degree | Different courses in degree | Categorical |
| Experience_Yrs | Work Experience of the Students | Numerical |
| Entrance_Test | Test which students give for MBA college Entrance | Categorical |
| Percentile_ET | Percentage of marks scored in Entrance_Test | Numerical |
| Percent_MBA | Percentage of marks scored in MBA | Numerical |
| Specialization_MBA | Specialization in MBA | Categorical |
| Marks_Communication | Percentage of marks scored in Communication | Numerical |
| Marks_Projectwork | Percentage of marks scored in Project Work | Numerical |
| Marks_BOCA | Percentage of marks scored in Extra Curricular activities | Numerical |
| Placement | Whether Student got placed or not | Categorical |
| Salary | Salary of students (Target Variable) | Numerical |

## 🎯 Project Objectives

1. Perform comprehensive exploratory data analysis (EDA)
2. Preprocess and clean the dataset
3. Engineer relevant features
4. Build and compare multiple regression models
5. Optimize the best performing model
6. Deploy the model for salary predictions

## 🛠️ Technical Stack

- **Programming Language**: Python 3.8+
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-Learn, XGBoost, LightGBM
- **Model Deployment**: Flask/FastAPI (optional)
- **Version Control**: Git, GitHub


## 🔍 Exploratory Data Analysis

Key areas of investigation:
- Distribution of target variable (Salary)
- Correlation between academic performance and salary
- Impact of work experience on salary
- Effect of different specializations on earning potential
- Gender-based salary differences
- Board and stream preferences vs salary outcomes

## ⚙️ Data Preprocessing

### Handling Missing Values
- Identify and impute missing values appropriately
- Use domain knowledge for intelligent imputation

### Feature Engineering
- Create composite academic performance scores
- Encode categorical variables (One-Hot, Label Encoding)
- Normalize/Standardize numerical features
- Handle skewed distributions

### Categorical Encoding
- Board types (SSC, HSC)
- Stream specializations
- Degree courses
- MBA specializations
- Entrance test types

## 🤖 Modeling Approach

### Algorithms to Implement
1. **Linear Regression** (Baseline)
2. **Random Forest Regressor**
3. **Gradient Boosting Regressor**
4. **XGBoost Regressor**
5. **LightGBM Regressor**
6. **Support Vector Regressor**
7. **Neural Networks** (Optional)

### Evaluation Metrics
- **R-squared** (Primary metric)
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Percentage Error (MAPE)**

### Validation Strategy
- Train-Test Split (80-20)
- 
- Cross-Validation (5-fold)
- Stratified sampling based on key features

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/student-salary-prediction.git
   cd student-salary-prediction
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebooks**
   ```bash
   jupyter notebook
   ```

## 📈 Expected Outcomes

1. A robust salary prediction model with high accuracy
2. Insights into factors most influencing salary outcomes
3. Visualization of educational patterns and their financial impacts
4. Recommendations for students to maximize earning potential

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Dataset providers and educational institutions
- Open-source community for machine learning libraries
- Contributors and reviewers

---

**Note**: This project is for educational purposes and should be used responsibly. Salary predictions are estimates based on historical data and may not accurately predict individual outcomes due to various external factors.
