# Flight Delay and Cancellation Analysis ✈️  

This project analyzes and predicts flight delays and cancellations using flight and weather datasets for the year 2022.  
The notebook demonstrates **data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling**.  

## 🔑 Steps in the Notebook  

### 1. Data Import & Overview  
- Load flight and weather datasets (`flights2022.csv`, `flights_weather2022.csv`)  
- Inspect shape, columns, and data types  
- Merge datasets for integrated analysis  

### 2. Data Cleaning & Preprocessing  
- Handle missing values (e.g., delay times, weather attributes)  
- Remove duplicates and irrelevant columns  
- Convert time/date fields into appropriate formats  
- Encode categorical variables for modeling  

### 3. Exploratory Data Analysis (EDA)  
- Identify distribution of delays and cancellations  
- Visualize delay patterns across airlines, airports, and routes  
- Explore seasonal and weather impacts on delays  
- Perform correlation analysis between flight and weather features  

### 4. Feature Engineering  
- Create new variables (e.g., total delay, delay category)  
- Extract temporal features (hour of day, day of week, month)  
- Combine weather and flight features for richer insights  

### 5. Model Building  
- Split data into training and testing sets  
- Train machine learning models (e.g., Logistic Regression, Decision Trees, Random Forests, Gradient Boosting)  
- Apply hyperparameter tuning for performance optimization  

### 6. Model Evaluation  
- Assess models using **accuracy, precision, recall, F1-score, and ROC-AUC**  
- Compare performance across different algorithms  
- Select the best-performing model for delay prediction  

### 7. Insights & Conclusions  
- Identify key factors affecting delays (e.g., weather, time, airline)  
- Provide business insights on delay management and prediction reliability  

---

## 🎯 Objective  
The primary goal is to **predict flight delays and cancellations** using both flight schedules and weather data, while also providing insights into the factors that contribute to these disruptions.  
