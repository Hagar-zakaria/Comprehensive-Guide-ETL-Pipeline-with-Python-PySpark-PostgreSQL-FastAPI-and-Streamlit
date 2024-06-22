In this project, we will create an ETL (Extract, Transform, Load) pipeline to process COVID-19 data using the technologies mentioned in the job description:

- Python (with Pandas, NumPy)
- PySpark
- SQL (PostgreSQL)
- FastAPI
- Streamlit
- Docker
- Azure Data Platform (Optional)
- Data Warehousing


Project Steps
1. Setting Up the Environment
Install Required Libraries:

First, we'll install the necessary libraries using pip by using bash;
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/703045a0-acc5-4f62-88d0-98ba369b27ba)

Run PostgreSQL Using Docker:

We'll run PostgreSQL using Docker to have a consistent environment:
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/c96b694e-de5d-458d-a45e-17971ee272b0)

2. Setting Up the Database and Tables in PostgreSQL
The first step is to create a new database and table in PostgreSQL using the following commands:

Commands in SQL :
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/6f6bdf73-da0d-49ef-b974-907d7db83e00)

3. Cleaning and Preparing Data Using Pandas
We'll use Pandas to clean and prepare the data in the first stage.

Pandas Code:
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/a613ebf2-1b47-4c71-8373-cc1565e1b031)

4. Transforming and Aggregating Data Using PySpark
Next, we'll use PySpark to transform and aggregate the data after cleaning it with Pandas.

PySpark Code:
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/3bdc9a6b-ad02-4898-90ab-42459636dfe1)
