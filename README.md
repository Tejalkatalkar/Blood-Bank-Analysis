# Blood-Bank-Analysis
### *Blood Bank Analysis Overview**  

This project focuses on analyzing a blood bank database to gain insights into its operations, distribution, and services offered. The dataset includes vital information such as blood bank locations, components available, categories, and operational details. We aim to explore the dataset using SQL queries and visualize the findings using Jupyter Notebook.

---

### **Project Files**

| **File Name**        | **Description**                          |
|----------------------|--------------------------------------------|
| `blood_bank.csv`     | Dataset containing blood bank information |
| `Blood_Bank_Analysis.ipynb` | Jupyter Notebook for analysis     |
| `SQL Queries.sql`    | SQL queries used for data extraction      |

---

### **Requirements**
1. **Software Tools Needed:**
   - **Jupyter Notebook**: For data analysis and visualization (`pip install notebook`).
   - **MySQL Workbench**: For executing SQL queries and managing the database.
   - **Python Libraries:**  
     - `pandas`
     - `matplotlib`
     - `seaborn`
     - `mysql-connector-python`
   
2. **Dataset**
   - A CSV file (`blood_bank.csv`) containing columns like:
     - `Blood_Bank_Name`, `State`, `District`, `City`, `Pincode`, `Mobile`, `Email`
     - `Category`, `Blood_Component_Available`, `Apheresis`, `Date_License_Obtained`


### **Questions Explored**
Here are the key questions analyzed in the project:

1. **How have the number of blood banks in each state changed over time?**
   - Visualized using a **line graph**.

2. **What is the distribution of blood bank categories?**
   - Presented as a **donut chart**.

3. **Which district has the highest number of blood banks?**
   - Visualized using a **bar chart**.

4. **What types of blood components are available in blood banks?**
   - Presented with a **pie chart**.

5. **What is the geographical distribution of blood banks?**
   - **Scatter plot** of latitude and longitude.

6. **How is service time distributed across blood banks?**
   - Visualized as a **bar chart**.


### **How to Open the Project**

1. **Load the Database in MySQL Workbench**
   - Import the `blood__bank__analysis.csv` into a MySQL database using the "Data Import Wizard."
   - Create tables as required for analysis.

2. **Run the SQL Queries**
   - Execute queries from `SQL Queries.sql` in MySQL Workbench to extract data.

3. **Open the Jupyter Notebook**
   - Launch Jupyter Notebook with `jupyter notebook` in the terminal.
   - Open `Blood_Bank_Analysis.ipynb`.
   
4. **Execute Cells**
   - Run the cells sequentially to connect to the database, retrieve data, and generate visualizations.

### **Conclusion**
The Blood Bank Analysis provided valuable insights into the distribution and services offered by blood banks. Key findings include:
- **Geographical Coverage:** Certain states and districts have a significantly higher concentration of blood banks.  
- **Service Availability:** Not all blood banks offer comprehensive blood components, and only a subset provides apheresis services.  
- **Operational Trends:** Service times and license dates revealed trends in blood bank establishment over time.

This project successfully combined SQL and Jupyter Notebook to analyze the dataset and visualize the insights, demonstrating the power of database-driven data science projects.

