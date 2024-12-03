
![Pasted image 20241203144129](https://github.com/user-attachments/assets/db4bb05f-b31e-4eb4-854c-ccaa3d88b627)


# Real-Time Water Sensor Data Pipeline with Azure

## **Project Description**

This project demonstrates building a **real-time data pipeline** using **Azure Services** to ingest, process, and store water sensor data from multiple European countries. The pipeline ensures that only newly added records are fetched and processed in real time, eliminating redundant computations and manual intervention. This approach maximizes resource utilization and reduces computational costs while maintaining a seamless flow of data for analysis.

---

## **Business Overview**

In an era where massive data volumes are generated every second, real-time data pipelines have become critical for organizations aiming to gain a competitive edge. This project highlights the use of **Azure cloud services** to build a scalable, automated pipeline capable of processing real-time data with minimal manual effort. By capturing only incremental data, the solution optimizes costs and ensures efficient data management for immediate availability of actionable insights.

---

## **Key Features**

1. **Real-time Data Ingestion:**  
   - Data is extracted from the **Azure SQL Database** in real time, capturing only newly added records based on timestamps.

2. **Automation:**  
   - Configured triggers automatically detect and ingest new data without manual intervention, streamlining the entire process.

3. **Cost Efficiency:**  
   - Only incremental data is stored, reducing storage and processing costs significantly.

4. **Scalable and Seamless Flow:**  
   - The pipeline efficiently manages high volumes of streaming data, ensuring continuous processing without disruption.

---

## **Tech Stack**

- **Programming Languages:** SQL, Scala  
- **Services:**  
  - Azure Managed SQL Server Database  
  - Azure Logic Apps  
  - Azure Blob Storage  
  - Azure Data Lake Storage Gen2  
  - Azure Data Factory  
  - Azure Databricks  
  - Power BI  

---

## **Data Description**

The dataset includes over one million rows of aggregated water sensor data from multiple European countries, spanning several years. Key parameters include:  
- Country and water body categories  
- Measured determinands and their concentration levels (min, max, mean, median)  
- Quality samples conducted at specific timestamps  

---

## **Approach**

1. **Data Ingestion:**  
   - Use **Azure Logic Apps** and **Azure Data Factory** to ingest new data from the SQL database into **Azure Blob Storage**.

2. **Real-time Triggering:**  
   - Triggers automatically detect and retrieve newly added records without reprocessing existing data.

3. **Data Storage and Transformation:**  
   - Store incremental data in **Azure Data Lake Gen2** and transform it using **Azure Databricks**.

4. **Visualization:**  
   - Processed data is visualized in **Power BI**, providing insights into water quality trends and determinands across Europe.

---

## **Key Insights**

- Analyze real-time water quality metrics across European monitoring sites.  
- Detect and track changes in determinand concentrations over time.  
- Enable proactive decision-making with immediate data availability.

---

## **How to Run the Project**

1. **Set Up Azure Services:**
   - Create instances for Azure Logic Apps, Data Factory, Blob Storage, and SQL Server.

2. **Configure Pipelines and Triggers:**
   - Set up ADF pipelines and logic app triggers to fetch and process new records.

3. **Process and Store Data:**
   - Use Databricks for data transformation and store processed data in Azure Data Lake.

4. **Visualize Insights:**
   - Connect **Power BI** to transformed datasets for analysis and reporting.

---

## **Contact**

For any questions or feedback, feel free to reach out!
