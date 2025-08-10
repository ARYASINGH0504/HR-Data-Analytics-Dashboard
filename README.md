
# HR Data Analytics Dashboard

An interactive Power BI dashboard built using the `hrdata.csv` dataset, designed to provide deep insights into workforce performance, attrition patterns, and employee satisfaction levels. The project aims to help HR professionals make informed, data-driven decisions for improving employee retention and organizational efficiency.

---

## 1. Project Overview

This dashboard offers a comprehensive visualization of HR data, enabling:

* Monitoring of key workforce KPIs (total employees, attrition rate, active workforce, average age).
* Analysis of attrition patterns across departments, education fields, genders, and age groups.
* Understanding of workforce demographics and satisfaction trends to identify retention opportunities.

The solution was built entirely in **Power BI** using **Power Query** for transformation and **DAX** for calculated metrics.

---

## 2. Dataset Description

The dataset contains detailed employee records, covering demographic, educational, professional, and satisfaction-related attributes.

**Dataset File:** `hrdata.csv`
**Number of Records:** 1,470
**Number of Fields:** 35

**Key Columns Include:**

* `Age`, `Gender`, `MaritalStatus` – Demographic information
* `Department`, `EducationField` – Organizational and educational background
* `JobRole`, `TotalWorkingYears`, `YearsAtCompany` – Career and experience data
* `JobSatisfaction`, `EnvironmentSatisfaction`, `WorkLifeBalance` – Satisfaction metrics
* `Attrition` – Target variable indicating whether an employee left the company

---

## 3. Key Insights Delivered

The dashboard provides:

* **KPI Cards:** Total employees, attrition count, attrition rate, average age.
* **Attrition Analysis:**

  * By department
  * By education field
  * By gender and age group
* **Workforce Demographics:** Distribution by gender and age range.
* **Job Satisfaction Analysis:** Comparison of satisfaction scores across job roles.

---

## 4. Project Workflow

1. **Data Loading:** Imported `hrdata.csv` into Power BI Desktop.
2. **Data Cleaning & Transformation:**

   * Removed duplicates
   * Standardized categorical values
   * Handled null or missing entries
   * Created calculated columns for age group segmentation
3. **Data Modeling:** Established relationships between categorical and numerical attributes.
4. **Measure Creation:** Used **DAX** for KPIs (attrition rate, average age, active employee count).
5. **Dashboard Design:**

   * KPI cards for quick stats
   * Clustered bar charts for attrition patterns
   * Donut charts for demographic breakdown
   * Slicers for interactive filtering

---

## 5. Tools & Technologies Used

* **Power BI Desktop** – Dashboard design and visualization
* **Power Query** – Data transformation and cleaning
* **DAX** – Custom measures and calculated fields
* **CSV Dataset** – HR analytics data

---

## 6. How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Load the provided `hrdata.csv` file.
4. Click **Refresh** to populate all visuals.
5. Use interactive slicers to filter by department, age group, gender, and more.

---

## 7. Potential Use Cases

* Identifying attrition hotspots within the organization.
* Understanding the relationship between satisfaction levels and attrition.
* Supporting HR strategic planning through evidence-based insights.
* Benchmarking departmental performance in employee retention.

---

## 8. Sample Dashboard Screenshot

Below is a preview of the HR Data Analytics Dashboard created in Power BI:

![HR Dashboard Screenshot](path_to_screenshot.png)

---

## 9. License

This project is licensed under the MIT License. You are free to use, modify, and distribute it with attribution.

---

If you give me your **dashboard screenshot image**, I can prepare a version where it is already embedded and linked so it appears directly on your GitHub page.
Do you want me to add that image for you?
