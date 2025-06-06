# Retail Sales-Data-Analysis-Project
The **Retail Sales Analysis Project** is a comprehensive and automated Project that utilizes various technologies and tools to provide valuable insights into customer buying patterns and seasonal trends. The project involves six major steps:
### 1. Amazon Web Services (AWS):
   
   Created an AWS S3 bucket and uploaded raw files securely. Implemented roles and policies for secure access and user-specific operations.

### 2. Snowflake (SQL):
   Established table creation and storage integration with AWS.
   Connected AWS S3 to Snowflake for continuous data upload tracking. Set up a snowpipe to ingest files and copy data into existing tables.

### 3. Jupyter Notebook (Python):
   
   Established a connection between Snowflake and Jupyter Notebook.
   Conducted Exploratory Data Analysis (EDA), including data cleaning and analysis. Stored cleaned data back into Snowflake using the snowflake-python package.

### 4. Jupyter Lab (Python):
   Automated the EDA process using jupyter_scheduler and jupyterlab-scheduler.
   Enabled scheduled refreshes in Jupyter Lab to avoid repetitive commands.

### 5. Snowflake (SQL):
   Created a master table and implemented Key Performance Indicators (KPIs) using cleaned data.
   
### 6. Power BI:
   Connected clean data, master table, and KPIs from Snowflake to Power BI.
   #### Utilized DAX, measures, new columns, and parameters in Power BI to create an intuitive and insightful dashboard.

   Overall, this project combines AWS, Snowflake, Jupyter Notebook, Jupyter Lab, and Power BI to streamline retail data analysis, from data ingestion and cleaning to visualization and insights generation.

  ### Datasets: 
  This dataset contains household-level transactions over two years from a group of 2,500 households who are frequent shoppers at a retailer. It contains all of each household’s purchases, not just those from a limited number of categories.


