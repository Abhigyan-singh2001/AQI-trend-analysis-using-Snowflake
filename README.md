# AQI-trend-analysis-using-Snowflake
🚀 **Built an interactive AQI Trend Analyzer using Snowflake & Streamlit** to track air quality across Indian cities with real-time data ingestion and dynamic visualizations.

** Demo Links **
https://drive.google.com/file/d/1ii3fag77m0MPnOrmPPqxtmHg8UnXPFIa/view?usp=drive_link
https://drive.google.com/file/d/1Spu96mOst5g15BbIu33m6hFUjFF9dfsi/view?usp=drive_link
## **🔹 Project Overview**
This project fetches real-time **Air Quality Index (AQI)** data from **data.gov.in**, processes it in **Snowflake**, and presents insights through an interactive **Streamlit dashboard**.

### **🔹 Key Features:**
✅ **Layered Architecture in Snowflake**  
- **Raw Schema:** Ingests raw JSON data from **data.gov.in**.  
- **Clean Schema:** Stores pre-processed, wide-format tables.  
- **Consumption Schema:** Fact & dimension tables for analysis.  
- **Publish Schema:** Powers the Streamlit app.

✅ **Automated Data Ingestion & Updates**  
- Integrated with **data.gov.in API** for direct data retrieval.  
- **Scheduled Snowflake tasks & cron jobs** for automatic updates every **45 minutes**.

✅ **Optimized Performance with Warehouses & Querying**  
- Created **Adhoc Warehouse** for exploratory queries.  
- Built **Streamlit Warehouse (Small & Medium size)** for optimized dashboard performance.  
- Efficiently queries **56K+ rows** for real-time insights.

✅ **Interactive Streamlit Dashboard**  
- Displays real-time AQI data for various Indian cities.  
- Enables users to explore trends, filter locations, and visualize changes over time.

## **🚀 Tech Stack & Tools**
🔹 **Snowflake** – Data ingestion, transformation, and storage  
🔹 **Streamlit** – Web app for interactive AQI analysis  
🔹 **Python** – Data fetching, API integration, and visualization  
🔹 **SnowSQL** – Querying and managing Snowflake schemas  
🔹 **data.gov.in API** – Fetching real-time AQI data
