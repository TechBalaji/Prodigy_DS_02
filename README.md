# Prodigy_DS_02
# 🛳️ Titanic Survival Data Analysis 🛳️

## ⚠️ Disclaimer:  
**This dataset is NOT real data from the Titanic ship.**  
This dataset is **simulated**, created for the purpose of data analysis and visualization practice. The intention of this project is to explore how various factors such as age, family size, gender, and embarkation point affected the likelihood of survival. This data should **not** be considered authentic or representative of real Titanic passengers.

---

## 🚀 Project Overview  
This project analyzes a **simulated Titanic dataset** to uncover trends and insights related to passenger survival rates. Through various visualizations, we aim to understand how different factors like age, gender, family size, embarkation point, and fare distribution influenced survival chances during the Titanic disaster.

The analysis includes interactive graphs and statistical methods to answer the following key questions:

- How did **age** impact survival rates?
- Did passengers with **larger families** have higher survival rates?
- How did a passenger's **title** (Mr., Mrs., Miss., etc.) affect their chances of survival?
- Did the **embarkation point** (Cherbourg, Queenstown, Southampton) play a role in survival chances?
- Was there a relationship between **fare** and survival?
- How did **gender** influence survival chances?
- What correlations exist between different variables in the dataset?
- Where is the **missing data** in the dataset?

---

## 🔍 What’s Inside?  
The repository includes a **Jupyter Notebook** that contains step-by-step analysis of the Titanic dataset. The following visualizations are generated as part of the exploration:

### 1. **Survival by Age Groups**  
This **bar graph** shows the survival rates of passengers grouped by their **age**. The age categories are typically divided into children, young adults, adults, and elderly passengers. This visualization helps us identify if younger passengers had higher survival rates or if age played a significant role in determining survival chances.

### 2. **Survival by Family Size**  
This analysis shows how the **family size** of passengers (number of siblings, spouses, parents, or children aboard) influenced their survival chances. A **bar graph** is used to demonstrate whether passengers with larger families had better chances of survival, possibly due to family grouping during evacuation.

### 3. **Survival by Title**  
This **bar graph** compares the survival rates based on the **title** of passengers (Mr., Mrs., Miss., Dr., etc.). Social status or title could have influenced survival chances, so this graph aims to explore whether titles like "Mrs." or "Dr." were associated with better survival odds compared to others.

### 4. **Survival by Embarkation Point**  
This **bar graph** compares the survival rates of passengers based on the **embarkation point** (Cherbourg, Queenstown, Southampton). The location where passengers boarded the ship might have influenced their survival chances, based on factors such as proximity to lifeboats or available resources.

### 5. **Survival by Fare Distribution**  
Here, we examine how the amount of **fare** paid by passengers correlates with their survival chances. Higher fares could reflect first-class passengers who might have had better access to lifeboats and more favorable evacuation conditions, which could translate to higher survival rates.

### 6. **Survival by Gender**  
This **bar graph** compares the survival rates between **male** and **female** passengers. Historically, women and children were given priority in lifeboats, and this visualization helps us assess whether gender played a significant role in survival rates.

### 7. **Correlation Heatmap**  
The **correlation heatmap** shows the relationship between various numerical features in the dataset. By examining the correlations between variables such as **age**, **fare**, **family size**, and **survival**, we can better understand how these factors are related to one another and what patterns emerge.

### 8. **Missing Values Heatmap**  
This **heatmap** highlights where **missing data** exists in the dataset. Understanding the locations of missing values is important for data preprocessing, as missing values can significantly impact the accuracy of any model or analysis. This heatmap guides us in addressing missing data appropriately.

---

## 🌟 Key Insights from the Visualizations
- **Missing Data**: The heatmap of missing values helps identify which columns are incomplete, which is crucial for data cleaning before modeling.![DATASCIENCE-Task-2-output(Missing Values Heatmap)](https://github.com/user-attachments/assets/d344ad4f-ff96-4fad-823b-ca81072aa323)
- **Age**: The **age groups** analysis may reveal that children had higher survival rates, potentially due to prioritization in lifeboats.
  ![DATASCIENCE-TASK-2-Survival by Age Group](https://github.com/user-attachments/assets/a08420f9-e952-480b-84e2-5e8772df0134)
- **Family Size**: Larger families might have had better survival chances, either due to support in evacuation or the survival of family units together.
  ![DATASCIENCE-TASK-2-Survival by Family Size](https://github.com/user-attachments/assets/715c8e84-3bac-46e4-895f-b8b17a42073a)
- **Title**: Certain titles, especially those associated with higher social status (e.g., "Mrs." or "Dr."), might have had higher survival rates due to perceived importance.![DATASCIENCE-TASK-2-Survival by  Title](https://github.com/user-attachments/assets/43446a23-73f0-4915-a13a-de79dfd52620)
- **Embarkation Point**: Passengers boarding from **Cherbourg** might have had better survival rates than those from Southampton, based on their proximity to available lifeboats.![DATASCIENCE-TASK-2-Survival by Embarking Point](https://github.com/user-attachments/assets/ae797719-a6e1-4536-a325-bb03c2fc78af)
- **Fare**: **Higher fares** might correlate with better survival rates, indicating a connection between class (first-class passengers) and access to lifeboats. ![DATASCIENCE-TASK-2-Survival by Fare Distribution](https://github.com/user-attachments/assets/3a19cf6a-9790-4531-8db0-7f7065faad19)
- **Gender**: **Females** likely had a higher survival rate compared to males, in line with historical reports prioritizing women and children. ![DATASCIENCE-TASK-2-Survival by gender](https://github.com/user-attachments/assets/cd6df55e-c069-42b9-88a8-3a2e44597e04)
- **Correlation Heatmap**: The correlation between **age**, **family size**, and **fare** might reveal important relationships that helped determine survival.![DATASCIENCE-TASK-2-Correlation Heatmap](https://github.com/user-attachments/assets/871919e6-acf6-41d8-bed6-471d430501b6)

---

## 🧩 Technologies Used  
- **Jupyter Notebook** 📓 for interactive development and exploration.  
- **Python** 🐍 for data processing and analysis.  
- **Pandas** 🐼 for data manipulation and cleaning.  
- **Matplotlib** and **Seaborn** 🎨 for creating static visualizations.  
- **Numpy** for the Arrays Operations .

---

## 📁 Dataset  

[Dataset.csv](https://github.com/user-attachments/files/18085172/Dataset.csv))


**Note**: The data used in this project is **simulated** and does not represent real Titanic passenger data. The dataset is intended for educational purposes and practice in data analysis.  

---

## 🎥 Watch the Project in Action  
You can see the visualizations and explore the analysis through this interactive demo:



[Sample Video of Code](https://github.com/user-attachments/assets/339cc5c8-8eea-4367-aebe-883dc96cd28f)



---

## 🚀 Conclusion  
This project provides insights into the factors that might have influenced survival aboard the Titanic (simulated dataset). By visualizing key factors like **age**, **family size**, **gender**, **fare**, and **embarkation point**, we uncover trends and relationships that could have affected the likelihood of survival.  

Through detailed analysis and visualizations, this project highlights the power of data storytelling to explore historical events, even with simulated data.


## 💬 Contribute & Feedback  
Feel free to open issues, ask questions, or suggest improvements. Contributions are always welcome!

--
