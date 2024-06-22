In this project, we will create an ETL (Extract, Transform, Load) pipeline to process COVID-19 data using the technologies mentioned in the job description:

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/8593042a-edf7-4ff9-a813-0b9d75b6833a)


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


5. Loading Data into PostgreSQL
After processing the data and saving it to a CSV file, we'll load it into PostgreSQL using Python and the psycopg2 library.

Python Code to Load Data:

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/b8b93558-e1a6-4221-b101-7d5d070a28ea)

6. Building an API Using FastAPI
Now, we'll use FastAPI to create an API to expose the data we've loaded into the database.

Install FastAPI and Uvicorn:

First, install the libraries using pip:
![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/133cd4a3-3f19-4579-abd6-8ca019ae567c)

FastAPI Code:

We'll write the FastAPI code to expose the data from the database.

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/4d3e07a8-7f3b-4c0f-b781-a8c4f3895d9c)

Run FastAPI Using Uvicorn:

We'll run the FastAPI application using Uvicorn:

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/ee6d0aef-72e5-4cfd-ad40-707be9271397)

7. Building a Dashboard Using Streamlit
Finally, we'll use Streamlit to create a dashboard to display the data.

Install Streamlit:

Install Streamlit using pip:

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/2a574f46-9033-4341-ba85-bb5099ccb31a)

Streamlit Code:

We'll write the Streamlit code to display the data in a dashboard.

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/e918baa3-a61a-4d20-a5ec-f3a7f3bd51fb)


Run Streamlit Application:

We'll run the Streamlit application using the following command:

![image](https://github.com/Hagar-zakaria/Comprehensive-Guide-ETL-Pipeline-with-Python-PySpark-PostgreSQL-FastAPI-and-Streamlit/assets/93611934/41889fac-43d6-4111-ad19-533ea66e5782)


Summary of Steps
1. Setting Up the Database and Tables in PostgreSQL:

- Use Docker to set up a consistent PostgreSQL environment.
- Run commands in PostgreSQL CLI to create the database and tables.

2. Cleaning and Preparing Data Using Pandas:

- Clean the data and save it to a CSV file.

3. Transforming and Aggregating Data Using PySpark:

- Perform transformations and aggregations using PySpark and save the transformed data to a CSV file.

4. Loading Data into PostgreSQL:

- Use Python and the psycopg2 library to load the transformed data into the PostgreSQL database.

5. Building an API Using FastAPI:

- Write FastAPI code to expose the data from the database and run it using Uvicorn.
  
6. Building a Dashboard Using Streamlit:

- Write Streamlit code to display the data in a dashboard and run it using the streamlit run command.

