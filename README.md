# 📊 Human Resource Management Analytics Dashboard in R

This project is a fully interactive HR Analytics dashboard built using **R** and **Shiny**. It provides insightful visualizations and department-wise employee analytics to support data-driven decision-making in HR management.

---

## 📁 Dataset

- **Name:** HR_Analytics.csv  
- **Records:** 1480  
- **Features:** 38  
- **File path:** `/R-project/HR_Analytics.csv`

---

## 🚀 Features

- **Overview Panel**
  - Total employees, average salary, and average age
  - Distribution plots for age, gender, education, satisfaction, training, etc.
- **Employee Engagement Panel**
  - Job involvement by department, gender, marital status, and job level
  - Work-life balance, years with current manager
- **Attrition Analysis Panel**
  - Attrition trends by age, gender, experience, department, and job role
- **Time & Department-based Analysis**
  - Performance and engagement breakdowns across selected time periods
  - Filter by department and compare metrics over time

---

## 🛠 Technologies Used

- `R` (v4.5 or higher)
- Libraries:
  - `shiny`
  - `shinydashboard`
  - `dplyr`
  - `ggplot2`
  - `lubridate`
  - `scales`

---

## ⚙️ Setup Instructions (Local)

1. **Install R and RStudio**  
   - [Download R](https://cran.r-project.org/)  
   - [Download RStudio](https://www.rstudio.com/products/rstudio/download/)

2. **Clone this Repository / Place the Files**
   - Ensure `app.R` and `HR_Analytics.csv` are in the same working directory.

3. **Install Required Packages**  
   In RStudio Console, run:
   ```r
   install.packages(c("shiny", "shinydashboard", "dplyr", "ggplot2", "lubridate", "scales"))


4. **Run the App**

   * Open `app.R`
   * Click **Run App** in RStudio
     *(or run `shiny::runApp("path/to/app.R")` from console)*

---

## 📎 Dashboard Video
You can checkout the dashboad [here](https://drive.google.com/file/d/1gkWjqX8q14v4BBC01laVnzzIvKPp710W/view?usp=sharing)
---

## 📥 License

This project is open-source and free to use for educational or non-commercial purposes.
