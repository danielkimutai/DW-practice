# DW-practice
Implementing a simple datawarehouse

Scenario
You are a data engineer hired by a solid waste management company. It collects and recycles solid waste across major cities in the country of Brazil. They operate hundreds of trucks of different types to collect and transport solid waste. The company would like to create a data warehouse so that it can create reports like:

 - Total waste collected per year per city
- Total waste collected per month per city
- Total waste collected per quarter per city
- Total waste collected per year per trucktype
- Total waste collected per trucktype per city
- Total waste collected per trucktype per station per city
- 
You will use your data warehousing skills to design and implement a data warehouse for the company.

### Sample data ; 
![image](https://github.com/user-attachments/assets/569a3eab-12bf-49e5-ba23-eb22de76d471)

## Designing a data schema 
<img width="422" alt="image" src="https://github.com/user-attachments/assets/e55356cd-a3df-448f-9922-7c3ed27df5a2">

## Creating Fact and Dimension Tables 
- ### creating date dimension table
  <img width="498" alt="mydimdatetable" src="https://github.com/user-attachments/assets/64edc5bb-2298-4213-afdc-06da23834a01">
- ### creating waste type dimension table
   <img width="493" alt="mydimwastetable" src="https://github.com/user-attachments/assets/6b221fa7-84db-4293-9d24-3ba0f5e9b6a6">
- ### creating zone  dimension table
    <img width="499" alt="mydimzonetable" src="https://github.com/user-attachments/assets/9d3e93f9-fb38-4545-a2ce-60b00e6dfd4e">
- ### creating fact table
    <img width="500" alt="myfacttripstable" src="https://github.com/user-attachments/assets/4b0db5e8-edda-4fba-875b-34e90c38acd7">

## Uploading data from flat files /to the created tables 

-### Loading  data to the  waste type fact table 
![Screenshot 2024-08-19 223232](https://github.com/user-attachments/assets/76bce3b1-d8a6-4a4c-8400-a4964b83f061)
- ### Loading data to the station/zone dimension table
- <img width="344" alt="dimstation" src="https://github.com/user-attachments/assets/138dd947-8e93-4e43-9841-6cf7cecace62">
- ### loading data to the  date dimension table
   <img width="679" alt="DimDate" src="https://github.com/user-attachments/assets/84bbf3da-7f27-4ce8-9efd-fe66d62e2c53">
- ### loading data to the truck  type
- <img width="694" alt="dimtruck" src="https://github.com/user-attachments/assets/03926cde-7958-4491-9fae-b72f98f2c528">

  
- 



  











