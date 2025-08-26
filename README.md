# NetMob 2024 Data Challenge – Data Processing & Visualization

This repository contains the data processing and visualization workflows developed for the **[NetMob 2024 Data Challenge](https://netmob.org/www24/)**, organised by the **[DIME (World Bank)](https://www.worldbank.org/en/about/unit/unit-dec/impactevaluation)**.  
The dataset is provided by **[Cuebiq](https://cuebiq.com/)** and accessed securely through the Spectus **Clean Data Room** using **SQL queries** executed within **Python Jupyter Notebooks**.

The repository documents the entire workflow — from raw data extraction, aggregation, and transformation, to visualization and exploratory analysis.  
> **Note:** All notebook cell outputs have been removed to maintain **data privacy**.

---

## 📄 Data Paper  
For full details about the dataset and methodology, please refer to the official data paper:  
[**[The NetMob2024 Dataset](https://arxiv.org/abs/2410.00453)**]

---

## 📂 Repository Structure

```bash
├── Code/
│   ├── query_data_use/        # Main SQL + Python scripts for data access
│   ├── data_viz/              # Visualization scripts and notebooks
│
├── README.md                  # Project overview
```

---

## 🛠️ Data Access & Processing

- **Data Source:** Spectus (Qubique) Mobility Data
- **Access Method:** SQL queries via Spectus Clean Data Room
- **Environment:** Python + Jupyter Notebooks

**Key Features of Data Processing:**

- Aggregation performed at multiple **spatial resolutions**:
  - **H3 Level 7**
  - **Geohash Level 3 & 5**
- Temporal aggregation at different levels:
  - **3-hourly**
  - **Daily**
  - **Weekly**
  - **Monthly**
- Locations covered:
  - **Colombia**
  - **India**
  - **Indonesia**
  - **Mexico**

The main processing pipeline focuses on efficient querying, data cleaning, and summarizing mobility patterns for large-scale spatio-temporal analysis.

> ⚠️ **Note**: Data access requires authorized credentials from Spectus Clean Data Room.
Ensure you have the proper access rights before running the query notebooks.







