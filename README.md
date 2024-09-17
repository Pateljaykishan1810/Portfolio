<!-- Centered Cover Page -->

<div align="center">

# Project - Part #1  
## AWS Data Analytic Platform for The City of Vancouver  

Group 5  
Lam Thi Thu Thao (2238441)  
Gurleen Kaur Khosa (2308084)  
Jaykishan Ashokkumar Patel (2237183)  
Ugochukwu Nwosu (2214378)  

University Canada West  
BUSI 653: Cloud Computing Technologies (HBD-SUMMER24-07)  
Mahmood Mortazavi Dehkordi  
August 27, 2024  

</div>

---

# Abstract
This report presents the implementation of the Data Analytic Platform (DAP) for the City of Vancouver. The report covers the DAP design and implementation for four datasets from the City of Vancouver’s Open Data Portal:

1. 3-1-1 Service Requests Regarding "Abandoned Non-Recyclables—Small Case"
2. Business Licences in Downtown Vancouver
3. Animal Control - Lost and Found
4. Rental Standards

The proposed platform uses services provided by AWS, including S3 for data storage, AWS Glue for ETL processes, Athena for data analysis using SQL, and EC2 instances with Apache for data publishing. Key procedures like data ingestion, data cleaning, data structuring, and analysis were incorporated into the platform to improve the current system. The project is easily expandable and inexpensive to implement, with an estimated annual cost of USD 413.76, which is feasible and beneficial to improve the efficiency of waste management and decision-making.

---

# Contents

1. Abstract
2. Introduction
3. DAP Design and Implementation (Steps 1-13) - Ugochukwu Nwosu
4. DAP Design and Implementation (Steps 1-13) - Gurleen Kaur Khosa
5. DAP Design and Implementation (Steps 1-13) - Lam Thi Thu Thao
6. DAP Design and Implementation (Steps 1-13) - Jaykishan Ashokkumar Patel
7. DAP Estimated Cost
8. Conclusion
9. References

---

# Introduction
The City of Vancouver stands in a position where data-driven insights can significantly enhance decision-making, public service delivery, and resource utilization. The Data Analytic Platform (DAP) provides a foundation for integrating, processing, and visualizing vast datasets collected from different sources. Through this platform, city officials can make informed decisions that will improve the lives of residents, enhance city planning, and improve public services.

The DAP enables the transformation of large datasets into actionable insights. By aggregating data from various departments, the city can gain a comprehensive view of operations, identify trends, and anticipate challenges. The platform also promotes transparency and accountability by offering easy access to city achievements and programs.

The following steps detail the implementation and migration of the Data Analytic Platform to AWS:

### Table 1: Steps for Designing and Implementing the Platform

| Steps                                    | Description |
|------------------------------------------|-------------|
| **Data Analytical Question Formulation** | Identifying critical questions the platform needs to answer, aligning with the city's strategic goals. |
| **Data Discovery**                       | Identifying and gathering relevant datasets from various sources within the city's departments. |
| **Data Storage Design**                  | Designing a robust storage solution, including data lakes, databases, and warehouses. |
| **Dataset Preparation**                  | Cleaning and formatting data to ensure consistency and accuracy before ingestion. |
| **Data Ingestion**                       | Ingesting prepared data into the platform using batch processing or real-time streaming. |
| **Data Storage**                         | Storing ingested data in designed storage solutions for easy access and analysis. |
| **Data Pipeline Design**                 | Designing pipelines to automate data extraction, transformation, and loading (ETL). |
| **Data Cleaning**                        | Further cleaning data within the platform to maintain quality and remove inconsistencies. |
| **Data Structuring**                     | Structuring data into optimal formats and creating data models for analysis. |
| **Data Pipeline Implementation**         | Implementing designed pipelines to ensure continuous and efficient data processing. |
| **Data Analysis**                        | Extracting insights from structured data using analytical tools and methods. |
| **Data Visualization**                   | Visualizing analysis results through dashboards and reports for easy understanding and action. |
| **Data Publishing**                      | Publishing insights and visualizations, making them accessible to stakeholders for decision-making. |

---

# Example Data Analysis Process - Dataset 1: 3-1-1 Service Requests (By Ugochukwu Nwosu)

## Step 1: Data Analytical Question Formulation
The main analytical question for this dataset is how well the City of Vancouver handles abandoned non-recyclable service requests. This dataset is relevant to the city's waste management program, particularly for non-recyclable items.

<!-- Include images here as needed, for example: -->
![S3 Bucket Example](https://github.com/yourusername/yourrepository/blob/main/images/s3-bucket.png)

---

# Conclusion
The AWS-based Data Analytic Platform for the City of Vancouver is designed to enhance efficiency, reduce costs, and offer valuable insights into the city's operations. This project lays a scalable and flexible foundation for future data-driven decisions.

# References
- Recycle BC. (2024). "Annual Waste Management Report."
- IMD. (2024). "Descriptive Data Analysis: A Guide."

---

