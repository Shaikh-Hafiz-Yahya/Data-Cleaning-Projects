# 🛒 Retail Customer Data Preprocessing

This project demonstrates the end-to-end cleaning process of a messy retail dataset. Ensuring data quality is essential for accurate sales forecasting and customer segmentation.

### 🛠️ Key Tasks Performed:
* **Duplicate Management:** Identified and removed duplicate records based on `Customer_ID` to ensure data integrity.
* **Text Standardization:** Fixed inconsistent string formatting in the `City` column (e.g., "karachi" to "Karachi") and used `.strip()` to remove trailing spaces from the `Name` column.
* **Outlier Handling:** Detected and corrected unrealistic entries in the `Age` column (e.g., 250 years) using logical thresholding.
* **Missing Value Imputation:** Handled null values in the `Spent_Amount` column by applying the **Mean** imputation technique.

### 📂 File Structure:
* `messy_customer_data.csv`: Original dataset containing various data entry errors.
* `After_Cleaning_customer_data.csv`: Final processed dataset ready for analysis.
* `Data_Cleaning_Logic.ipynb`: Jupyter Notebook containing the Python/Pandas source code.
