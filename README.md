
# 🚀 Applied Data Science Capstone Project  
## Predicting the Successful Landing of Falcon 9 First Stage  

SpaceX has revolutionized space travel by significantly reducing launch costs, primarily through the reusability of its Falcon 9 rocket's first stage. While SpaceX advertises launches for $62 million, competitors charge upward of $165 million. Accurately predicting Falcon 9’s first stage landing success helps in estimating launch costs and supports decision-making for companies competing against SpaceX.

---

## 🎯 Project Objectives

This capstone project is structured into several comprehensive modules, each building on the previous one. By the end of the project, we developed a robust machine learning model to predict the landing success of Falcon 9’s first stage.

---

## 📦 Modules Overview

### 1. Request to the SpaceX API and Data Wrangling
- **Data Collection**: Fetched historical launch data via GET requests from the SpaceX API.
- **Data Cleaning**: Removed anomalies and missing values, formatted the data for consistency.

### 2. Web Scraping Falcon 9 Launch Records
- **Web Scraping**: Utilized `BeautifulSoup` to scrape Falcon 9 launch data from Wikipedia.
- **Data Parsing**: Converted the extracted HTML tables into Pandas DataFrames.

### 3. Exploratory Data Analysis (EDA) and Training Labels
- **EDA**: Visualized data using `Matplotlib` and `Seaborn` to uncover patterns.
- **Training Labels**: Created target labels necessary for model training.

### 4. Database Integration
- **Db2 Integration**: Loaded data into an IBM Db2 database.
- **SQL Analysis**: Ran SQL queries to extract insights from structured data.

### 5. Feature Engineering and Visualization
- **Feature Engineering**: Created meaningful features to boost model performance.
- **Mapping with Folium**: Built interactive maps to visualize launch sites and success rates.

### 6. Interactive Visual Analytics with Plotly Dash
- **Dash App**: Built an interactive dashboard using `Plotly Dash`.
- **User Interactions**: Integrated dropdowns and sliders for dynamic charts and insights.

### 7. Machine Learning Models and Hyperparameter Tuning
- **Preprocessing**: Standardized data and split it into train/test sets.
- **Hyperparameter Tuning**: Used `GridSearchCV` to tune SVM, Decision Trees, and Logistic Regression.
- **Evaluation**: Compared model performance to select the best-performing algorithm.

---

## ✅ Results

| Model                  | Accuracy |
|------------------------|----------|
| 🎯 Decision Tree       | 0.9444   |
| SVM                    | 0.8333   |
| K-Nearest Neighbors    | 0.8333   |

> The **Decision Tree Classifier** achieved the highest accuracy, making it the best-performing model.

---

## 🧠 Conclusion

This project demonstrates how data science can be applied to solve real-world problems in space technology. With clean data, insightful visualizations, and tuned ML models, we successfully predicted Falcon 9’s first stage landing outcomes, aiding in cost estimation and strategic planning for space missions.

---

## 📁 Repository Structure

```
├── data/           # Dataset and preprocessing scripts  
├── notebooks/      # Jupyter notebooks for each project module  
├── scripts/        # Python scripts for EDA, modeling, and visualization  
├── dash_app/       # Source code for Plotly Dash interactive app  
├── README.md       # Project overview and details  
```

---

## 🙏 Acknowledgments

- **IBM** – For offering the Applied Data Science Capstone course.  
- **Coursera** – For providing the platform and resources.  

---

## 👨‍🚀 Explore More

Whether you're a:
- 🧠 Data science enthusiast  
- 🚀 Space exploration fan  
- 💼 Professional working with predictive analytics  

...this project provides valuable insights into end-to-end data science and machine learning applications.
