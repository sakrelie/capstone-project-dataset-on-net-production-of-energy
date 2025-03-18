# **Capstone Project - Time Series Analysis of Net Production**
📊 *A data processing and visualization project analyzing net production trends over time.*

## **📌 Project Overview**
This project focuses on **cleaning, preprocessing, and visualizing time series data** for `Net production`.  
Key steps include **handling missing dates**, **computing rolling statistics**, and **visualizing trends**.

---

## **🔧 Features & Methodology**

### **1️⃣ Date Column Creation**
- Combines `Year`, `Month`, and `Day` columns into a `Date` column.
- Removes invalid dates and sets `Date` as the **index**.

### **2️⃣ Handling Missing Dates**
- Extends dataset to include **all dates up to today**.
- Fills missing dates with `NaN` values.

### **3️⃣ Rolling Statistics Calculation**
- Computes **30-day rolling mean & standard deviation** for `Net production`.

### **4️⃣ Filling Missing Values**
- Identifies missing `Net production` values.
- Uses rolling statistics to **generate synthetic values**.
- **Linear interpolation** and **backfilling** fill any remaining gaps.

### **5️⃣ Data Visualization**
- **Matplotlib** is used to create a **time series plot** of `Net production`.
- Labels and titles enhance readability.

---

## **📷 Screenshots**
![image](https://github.com/user-attachments/assets/0e04433c-c911-4a08-a7d8-678380fe7121)


---

## **🚀 How to Use**
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/yourusername/Capstone-Project.git
   cd Capstone-Project



