# Airline Loyalty Program Data Visualization

This repository contains a Jupyter Notebook (`a.ipynb`) focused on **data visualization and exploratory analysis** of airline loyalty program data.  
The notebook uses **Python**, **pandas**, and several popular visualization libraries to generate insightful plots and highlight trends in customer loyalty data.

---

## 📌 Overview

The notebook walks through the process of:
- Loading and preprocessing loyalty program enrollment data
- Exploring patterns across provinces and enrollment years
- Creating multiple visualizations, including:
  - **Ridgeline plots** for yearly enrollments per province  
  - **Treemaps** for enrollment distribution  
  - **Geospatial visualizations** using `cartopy`  
- Identifying trends and insights that could help in understanding user engagement across regions and time.

---

## 📂 File Contents

- **`a.ipynb`** – The main Jupyter Notebook containing:
  1. **Library Installation & Setup**  
     Uses `%pip install joypy`, `%pip install squarify` to ensure required packages are available.  

  2. **Data Loading & Cleaning**  
     Loads the loyalty history dataset into a pandas DataFrame and performs necessary transformations.  

  3. **Visualizations**
     - **Ridgeline Plot** – Shows the distribution of enrollments per year across provinces using `joypy`.  
     - **Treemap** – Displays province-wise and year-wise enrollment breakdown using `squarify`.  
     - **Geospatial Map** – Uses `cartopy` to map provincial data on a geographic projection.  

  4. **Exploratory Analysis & Insights**  
     Includes code cells that analyze trends, detect patterns, and summarize results with visual context.

---

## 🛠️ Dependencies

This project uses the following libraries:

- `pandas`
- `matplotlib`
- `seaborn`
- `joypy`
- `squarify`
- `numpy`
- `cartopy`

Install them with:

```bash
pip install pandas matplotlib seaborn joypy squarify numpy cartopy