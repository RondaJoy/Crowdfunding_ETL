
**UCB Data Analysis Group Project 2**
## Crowdfunding ETL with Import to Postgres Database

---------------
### Purpose:  

Build an ETL pipeline using Python, Pandas, and Regex to extract and transform the data. Once transformed, export to CSV and use the CSV file data to create an ERD and a table schema. The last step is to upload the CSV file data into a Postgres database.  

In this repo you will find our updated and clean crowfunding data. We accomplished this by studying the data that was provided to us and we separated the data into multiple dataframes using the category and subcategory IDs. We had to do this in order to combine all of the spreadsheets and be able to make the data easily accesssible. The final section of this repo contains all of the updated spreadsheets in the crowfunding database that has all of the relevant tables. We also decided to do both the panda and regex contact databases as a bonus. 

--------------
### Contents of Repository:
- Code Scripts
  - 1 x .ipynb python notebook, shared (ETL_Mini_Project_JBailey_MBernstein_JDemler_RHinz.ipynb)
  - 1 x .sql database schema (crowdfunding_db_schema.sql)
  - 1 x .sql database (crowdfunding_db.sql)
- ERD Files
  - 1 x ERD visual (crowdfunding_project_2_ERD.png)
  - 1 x ERD text to use in QuickDBD (crowdfunding_ERD_text.docx)
- **FOLDER:** Resources
  - 2 x .xlsx data files for import (contacts.xlsx | crowdfunding.xlsx)
  - 4 x .csv data files, code exports (category.csv | subcategory.csv | campaign.csv | contacts.csv)
- 1 x README file

-------------------
### Contributors:
Jessica Bailey  
Michael Bernstein  
Joe Demler  
Ronda Hinz  


------------------
### License:
[MIT](https://choosealicense.com/licenses/mit/)
