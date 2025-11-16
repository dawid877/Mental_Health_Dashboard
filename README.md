# Analysis of the suicide attempts in Poland: Power BI Dashboard (2017–2024)

## Overview

This project is an interactive **Power BI** report that presents official statistics on suicide attempts in Poland.  
The dashboard provides insights into:

- **Trends over time** – yearly and monthly changes  
- **Reasons and circumstances** behind suicide attempts  
- **Age groups and gender differences**  
- **Social and employment status** of individuals  
- **Regional distribution** of mental health clinics across Poland  
- **Clinics and mental health facilities** available in each voivodeship, where people in need may seek support  

---

## Data

- **Source:** Official data from the **Polish Police (Komenda Główna Policji)**  
- **Geographical scope:** Poland (national and regional level)  
- **Time range:** **2017–2024**

---

## 📂 Project Structure

The project is structured as follows:

- `Data_wrangling.ipynb` – Loads the raw dataset and performs cleaning and transformation.
- `EDA_Feature_Engineering.ipynb` – Explores the data visually and statistically, and creates new features to improve model performance.
- `Testset_featureeng.ipynb` – Applies the same feature engineering steps to the test dataset to ensure consistency and prevent data leakage.
- `Model_specification.ipynb` – Trains various regression models, evaluates their performance, and compares results using different metrics.
