# 🛒 Sales Data Analysis Pipeline

This project is a complete **Sales Data Analysis Pipeline** built using:
- **Python (Pandas, Matplotlib)**
- **PostgreSQL Database**
- **Tkinter GUI for Dashboard**

It showcases the **end-to-end process** of **Extracting, Cleaning, Loading sales data into PostgreSQL** and **visualizing sales trends through an interactive dashboard**.

---

## 🛠️ Key Features
✅ **Data Extraction & Cleaning:**
- Loaded sales data from CSV.
- Cleaned and transformed the data using **Pandas** (Handled missing values, date conversions, etc.).
- Stored the cleaned data into **PostgreSQL database** using **SQLAlchemy**.

✅ **Interactive Tkinter Dashboard:**
- **Monthly Sales Trend Visualization** using **Matplotlib**.
- **Country-wise Monthly Sales Visualization**.
- **Clear Graphs Button** to **remove existing plots** for a smooth UI experience.
- **Light Gray Background** for better UI.

✅ **Database Integration:**
- PostgreSQL Database connection with **Python (SQLAlchemy + psycopg2)**.

---

## 📊 Visualizations in Dashboard
- **Monthly Sales Trend** (Line Chart).
- **Country-wise Monthly Sales Trend** (Selectable Dropdown).
- **Clear Graphs Button** to Reset View.

---

## 🚀 How to Run the Project
### 1️⃣ Setup PostgreSQL Database
- **Create a PostgreSQL database** called `sales_data`.
- **Create a PostgreSQL user** and **replace credentials** in `sales_etl.py` and `sales_dashboard.py` if using real credentials.


### 2️⃣ Install Dependencies
pip install pandas matplotlib sqlalchemy psycopg2 pillow

### 3️⃣ Run Data Cleaning & Load into Database

python sales_etl.py
### 4️⃣ Run Tkinter Dashboard

python sales_dashboard.py


## ⚙️ Dependencies
- **Python 3.x**
- **Pandas**
- **Matplotlib**
- **SQLAlchemy**
- **psycopg2**
- **Pillow**
- **Tkinter (comes pre-installed with Python)**

  ---

## 💡 Why This Project Matters
This project simulates a real-world data pipeline, demonstrating:

- Data Extraction, Cleaning, and Loading into a database.
- Building a GUI dashboard for interactive data visualization.
- Combining Python libraries like Pandas, SQLAlchemy, Matplotlib, and Tkinter into a complete pipeline.
--This is the type of project data engineers and analysts work on in the industry. It’s a great addition to your portfolio and demonstrates both technical and problem-solving skills.


---

## 📈 Future Scope
| Feature                          | Description                                                   |
|-----------------------------------|---------------------------------------------------------------|
| **Yearly Sales Visualization**   | Add the option to view **yearly sales trends**.               |
| **Top Cities / Countries Chart** | Display **top-performing cities and countries by sales**.     |
| **Category-wise Sales Breakdown**| If data allows, show **sales based on product categories**.    |
| **Product-level Analysis**       | Analyze **individual product performance over time**.         |
| **Sales Forecasting (Basic Prediction)** | Add **simple linear regression or moving average** forecasting for **future sales**. |
| **Improved Dashboard UI**        | **Enhance Tkinter dashboard** with better **layout, frames, and modern themes**. |
| **Deploy as Desktop App (EXE)**  | Convert **Tkinter dashboard into a standalone application (.exe)** using **PyInstaller**. |
| **Dockerize the Pipeline**       | Containerize the **ETL & Dashboard using Docker** to **make deployment easier**. |

 ---
 
## 📧 Contact
Feel free to reach out if you have any questions or need help with the project!

---

## 🏁 Conclusion

This **Sales Data Analysis Pipeline** project demonstrates the **end-to-end data engineering process**, starting from **data extraction, cleaning, and loading (ETL)** to **building an interactive visualization dashboard** using **Tkinter and Matplotlib**.

It showcases **how data can be transformed into actionable insights** through **a well-structured pipeline and an intuitive dashboard interface**.  
This project **serves as a strong foundation for real-world data engineering and analytics work**, while also **highlighting the importance of integrating databases (PostgreSQL) with Python-based data analysis tools**.

The **dashboard can be expanded** with **additional features** like **yearly trends, product-level analysis, and forecasting**.  
This **project is an excellent starting point** for **learning data pipelines, database integration, and dashboard development**, which are **key skills in Data Engineering roles**.

---


