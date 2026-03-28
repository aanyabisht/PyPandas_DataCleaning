#  Employee Data Cleaning Project (Pandas)

##  Project Overview

This project focuses on cleaning and preprocessing an employee dataset using **Python (Pandas)**.
The dataset contains common employee information such as joining date, age, salary, and city.

The goal of this project is to transform raw and inconsistent data into a clean and structured format suitable for analysis.



##  Dataset Description

The dataset includes the following columns:

* **Joining Date**
* **Age**
* **Salary**
* **City**

The data initially contained:

* Missing values
* Inconsistent date formats
* Duplicate or repeated values

---

##  Data Cleaning Steps

### 
1. Initial Data Exploration

* Checked dataset structure using `.info()` and `.describe()`
* Identified missing values and inconsistent formats

---

### 2. Handling Missing Values

Different strategies were applied based on the data type:

* **Age** → Filled using **Mean / Median**
* **Salary** → Filled using **Mean / Median**
* **Joining Date** → Filled using **Mode** (most frequent date)

> The choice of mean, median, or mode was made based on the nature and distribution of the data.

---

###  3. Date Cleaning

* Standardized multiple date formats into a consistent format
* Handled missing and invalid date values
* Ensured proper datetime conversion using Pandas

---

###  4. Handling Duplicates

* Identified and managed repeated entries
* Ensured data consistency

---

###  5. Data Transformation

* Converted columns into appropriate data types
* Cleaned and formatted text data where required

---

##  Key Learnings

* Handling real-world messy datasets
* Using **Pandas** for data cleaning
* Applying **Mean, Median, Mode** appropriately
* Working with inconsistent date formats
* Debugging data issues like null values and hidden characters

---

##  Tools & Technologies

* Python 
* Pandas 
* Jupyter Notebook / VS Code

---

##  Output

* Cleaned dataset exported as an Excel file using:

  ```python
  df.to_excel('cleaned_data.xlsx', index=False)
  ```

---

##  Future Improvements

* Add data visualization
* Perform exploratory data analysis (EDA)
* Build insights and dashboards

---

##  Conclusion

This project demonstrates the complete process of cleaning and preparing raw data for analysis. It highlights practical problem-solving and real-world data handling skills.

---

⭐ If you like this project, feel free to star the repository!
