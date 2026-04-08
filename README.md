# Student-Performance-Analysis-Dashboard
This project is an interactive Student Performance Analysis Dashboard designed to analyze and visualize academic data.  It helps in:  Understanding student performance across multiple subjects Identifying trends in exam scores Classifying based on grades Detecting weak and strong performers Providing predictive insights using. machine learning


##  Overview

This project is an interactive **Student Performance Dashboard** built using Python and Streamlit. It analyzes student data, visualizes academic performance, and provides insights to help understand strengths and weaknesses across subjects.

The dashboard includes data visualization, filtering options, and a basic machine learning model to predict future performance.

##Features

*  **Performance Dashboard**

  * Displays average marks, top score, and attendance

   **Grade Classification**

  Categorizes students into grades (A, B, C, D)
 **Visualizations**

  * Bar Chart (Subject Performance)
  * Line Chart (Exam Trends)
  * Pie Chart (Grade Distribution)
  * Heatmap (Student vs Subject Performance)

* 🔍 **Filters**

  * Filter by student, subject, and grade

*  Machine Learning**
  * Linear Regression model to predict exam scores
*  **Insights**
  * Identifies top-performing and low-performing students
  * Provides basic improvement suggestions


## Technologies Used

* **Python**
* **Streamlit**
* **Pandas**
* **NumPy**
* **Plotly**
* **Seaborn**
* **Matplotlib**
* **Scikit-learn**


##  Project Structure

```
├── app.py          # Main Streamlit application
├── README.md       # Project documentation
```

##  How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-dashboard.git
cd student-dashboard
```

### 2. Install dependencies

```bash
pip install streamlit pandas numpy plotly seaborn matplotlib scikit-learn
```

### 3. Run the application

```bash
streamlit run app.py
```
### 4. Open in browser

http://localhost:8501

# Dataset
* The dataset is **synthetically generated** using NumPy
* Includes:

  * Student names
  * Subjects
  * Exam scores (4 exams)
  * Attendance
  * Grades

# Objective

The objective of this project is to analyze and visualize student performance using data-driven techniques. It provides an interactive dashboard to identify trends, strengths, and weaknesses. Additionally, it uses machine learning to predict future academic performance.

# Future Improvements

* Add real dataset integration (CSV upload)
* Improve UI/UX design
* Add advanced ML models
* Include student comparison feature
* Add login/authentication system

#Contribution
Feel free to fork this repository and improve the project!



