# 🎓 Data Analysis and Visualization of Students Exam Scores: Extended Dataset

This project presents a comprehensive data analysis and visualization of the **Students Exam Scores: Extended Dataset**, aimed at uncovering meaningful insights into student performance metrics through the application of core statistical techniques.

---

## 🎯 Project Objectives

- 🔍 Perform initial data exploration to understand structure and contents  
- 🧹 Clean the dataset by handling missing values  
- 🔢 Identify and isolate numerical features for statistical analysis  
- 📁 Save the cleaned dataset for future applications  
- 📊 Compute summary statistics such as **mean**, **mode**, and **standard deviation**  
- 📈 Visualize data distributions using histograms  
- 🔄 Overlay **normal distribution curves** to assess conformity with Gaussian patterns  
- 🧠 Interpret statistical results in an educational context  

---

## 🛠️ Tools & Libraries Used

This project was developed using the following Python libraries:

- `pandas` – for data manipulation and analysis  
- `numpy` – for numerical operations and statistical computations  
- `matplotlib` – for creating visualizations

---

## 🔎 Workflow Overview

1. **Data Import & Preview**  
   The dataset is loaded into a pandas DataFrame and previewed using `.head()` to understand its initial structure.

2. **Data Cleaning**  
   Missing values (NaNs) are identified and removed using `.dropna()` to ensure analysis accuracy.

3. **Feature Selection**  
   Numerical columns are filtered using `.select_dtypes()` to focus analysis on quantifiable data.

4. **Saving Cleaned Dataset**  
   The cleaned numerical dataset is exported as `cleaned_Original_data.csv` using `.to_csv()`.

5. **Statistical Analysis**  
   Key metrics such as **mean**, **mode**, and **standard deviation** are calculated using pandas and numpy.

6. **Summary Statistics Display**  
   The results are printed to allow easy interpretation of central tendencies and variability.

7. **Data Visualization**  
   Histograms are plotted for all numerical columns to visualize frequency distributions.

8. **Normal Distribution Overlay**  
   Theoretical Gaussian curves are generated and overlaid on histograms to evaluate normality.

9. **Result Interpretation**  
   Each numerical column is interpreted in terms of its statistical values, identifying trends and variances in student scores.

---

## 📊 Key Findings & Insights

- **Mean**: Represents the average performance of students across each subject.
- **Mode**: Highlights the most frequently occurring score, giving insight into common achievement levels.
- **Standard Deviation**: Measures the spread of the data, indicating consistency or disparity in student performance.
- **Normal Distribution Analysis**: Helps assess whether the data follows a bell-shaped curve, which is essential for advanced statistical modeling.

---

## 🌍 Real-World Relevance

This project reflects practical implications in the education sector:

- 📚 Understand variations in student performance to guide curriculum improvements
- 🎯 Identify target areas for academic interventions and policy support
- 📈 Prepare for predictive modeling by evaluating distributional assumptions
- 🏫 Reveal potential socio-economic disparities based on score patterns

---

## ✅ Conclusion

The project demonstrates how fundamental statistical techniques can be used to derive actionable insights from educational data. Through data preprocessing, exploratory analysis, and visualization, we gain a comprehensive understanding of student score distributions.

These insights not only provide a foundation for further statistical modeling but also open doors to deeper analyses such as **correlation studies**, **predictive analytics**, and **machine learning applications** in educational performance forecasting.

---

## 📂 Dataset Information

- **Source**: [Kaggle – Students Exam Scores Dataset](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)
- **Format**: CSV
- **Content**: Student-level exam scores and demographic attributes

---

## 👨‍💻 About the Author

**Soyam Kapoor**  
Final-year AI & ML enthusiast with a passion for data science, statistical analysis, and impactful visualization. I'm dedicated to transforming raw datasets into meaningful stories that inform better decisions.

- 🔗 [LinkedIn](https://www.linkedin.com/in/soyamkapoor)  
- 💻 [GitHub](https://github.com/SoyamKapoor)  
- 🧾 [Portfolio](https://soyam.vercel.app/) 

---

_“Transforming numbers into knowledge — one dataset at a time.”_
