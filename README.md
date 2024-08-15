
# COVID-19 Project: Implementing a Data Engineering Pipeline within Azure Data Factory

## 1. Introduction 
The project utilized data from [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data) to track daily cases, deaths, and hospital admissions related to COVID-19 in Europe.
Data include 4 csv files : <b> <i> Cases and Deaths, Hospitalizations, Testing, Country. </i> </b>

### Technologies used

- Azure Data Factory, 
- Azure Data Lake Storage
- Azure SQL Database
- PowerBI 

## 2. Implementation overview 
- The data flow involves fetching files from <b>the Our World in Data </b> to a data lake storage account using <b> HTTP Connector </b>.
- Data processing occurs in Azure Data Factory through the implementation of <b>data pipelines and data flow </b>.
- The transformed data is subsequently published to the <b>Azure SQL Database</b> as Data warehouse.
- The final step entails visualizing the data in <b>Power BI</b>, retrieving it from the SQL Database.

<img src = ./img/covid.png >

## 3. Data model
<img src = ./img/covid_dia.png >

## 4. Visualize 

Data Warehouse to be built with the following data
to aid Reporting on Trends
- Confirmed cases
- Mortality
- Hospitalization/ ICU Cases
- Testing Numbers

<img src = ./img/covid_dash1.png>
<img src = ./img/covid_dash2.png>