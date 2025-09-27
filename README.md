# Salary-Analytics-and-Forecasting-using-Python-Pandas-Visualization-
This project analyzes employee salary credit dates over multiple years and predicts the next year’s salary dates based on historical trends. Using Python and Pandas, it merges year-wise salary data, calculates year-over-year differences, generates visualizations of monthly trends, and forecasts the upcoming year’s salary dates.


# Salary Analytics & Forecasting Web App

[**Try it live on Hugging Face Spaces →**](https://yatin1106-salaryforecasting.hf.space/)

---

## **Overview**

The **Salary Analytics & Forecasting Web App** allows companies to analyze historical salary credit data and forecast the next year’s salary dates using Python, Pandas, and visualizations. By uploading multiple CSVs for different years, users can track trends, detect anomalies, and predict future salary credit dates in an interactive, easy-to-use interface.

This web app is designed for HR, payroll, and finance teams in companies of any size to optimize salary planning and reporting.

---

## **Key Features**

1. **Data Upload & Cleaning**

   * Upload CSVs for multiple years with employee salary data.
   * Automatically formats dates and merges datasets by unique employee identifiers.

2. **Trend & Distribution Analysis**

   * Visualizes monthly salary credit trends using bar charts.
   * Detects unusual delays or early credits with distribution histograms.

3. **Year-over-Year Comparison**

   * Calculates day differences in salary credit dates for consecutive years.
   * Highlights employees with irregularities.

4. **Forecasting Next Year**

   * Predicts salary credit dates for the upcoming year using historical averages.
   * Adds a `Predicted_2026` column for each employee.

5. **Export Results**

   * Download the analyzed and forecasted dataset as a CSV for reporting.

---

## **How to Use**

1. Prepare CSV files for each year with columns:

   * `Name`
   * `Account_Number` (unique for each employee)
   * `Salary_Credit_Date`

2. Open the [web app](https://yatin1106-salaryforecasting.hf.space/)
3. Upload your CSV files.

4. Click **Run Analysis** to see:

   * Trend visualizations
   * Year-over-year differences
   * Predicted next-year salary dates

5. Download the results as CSV.

---

## **Optional Enhancements**

* Alerts for unusual delays or early payments
* Sophisticated forecasting using **moving averages, exponential smoothing, or ARIMA models**
* Interactive dashboards for management reporting

---

## **Technologies Used**

* Python 3
* Pandas for data processing
* Matplotlib & Seaborn for visualization
* Gradio for web interface deployment

---

## **Takeaway**

This web app is a **lightweight, interactive payroll analytics tool** that helps companies track salary trends, detect anomalies, and plan future salary outflows efficiently—all without complex ERP software.

[**Access the live app here →**](https://huggingface.co/spaces/yatin1106/salaryforecasting)


