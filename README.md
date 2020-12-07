## CIS-4400-PROJECT
The ETL(Extract, Transform, Load) documentation for the project will provide a guide on how to install necessary softwares, extract data, transform data based on the project's requirements and finally load it into the the MySQL database. Please carefully read the bullet points under the extraction subheading as they provide important information about the current data available. 

### Installation:
  1. Install any python IDE that you are comfortable using. Here we used Anaconda Navigator- Jupyter Notebook as it was more user friendly and provided useful information about errors with each line of code. Use the link below to install Anaconda Navigator- Jupyter Notebook onto your operating system: 
 
      https://docs.anaconda.com/anaconda/install/
      * Once installed, you can launch jupyter notebook from your terminal simply by writing: < jyputer notebook >
      
  2. Install MySQL onto your operating system. This will be the database you are using for the project. The links below will take you to the installation page for MySQL. We have also included a Youtube video if you need more instruction on how to properly download the server onto your operating system. 
   * If using a MacOS please update to the latest software, if not, download archived versions of the MySQL server.
   * DO NOT FORGET THE PASSWORD you set for the MySQL server.
   
      ##### Download MySQL sever 
      https://dev.mysql.com/downloads/mysql/
      ##### Video on installation
      https://www.youtube.com/watch?v=UcpHkYfWarM&t=819s&ab_channel=ProgrammingKnowledge
  
  3. Install MySQL Workbench- visual database design tool.
  
      https://www.mysql.com/products/workbench/
 
## ETL 
### Extract Data 

Due to lack of open data about certain information we required for this project, some data required manual entry into an excel spreadsheet that was later converted into a csv file. Below you will see a list of all our sources, if it required manual data entry, and a link to a google drive with all of the csv files. 

  1. CITY MD 
      https://www.citymd.com/all-locations
      *Entered manually 
  2. COVID Testing Sites (Hospital Data)
      https://www.nychealthandhospitals.org/covid-19-testing-sites/
      *Entered manually 
  3. Brooklyn Zipcodes 
      http://www.brooklynproperty.com/Brooklyn/ZipCodes.htm
      *Entered manually 
  4. Urgent Cares 
     https://hifld-geoplatform.opendata.arcgis.com/datasets/urgent-care-facilities
     *Filtered by Brooklyn
  5. Demographic 
     http://www.infoshare.org.remote.baruch.cuny.edu/main/directip.aspx
      *Entered Manually
      * Only available through Baruch database
  6. Google Drive of all CSV files 
     https://drive.google.com/drive/folders/1X9nXOWXyw5CiBI0H4ejPDxVI8lLUXRhU?usp=sharing

### Transform Data 
  1. Open jupyter notebook and create a Python 3 file in the same folder as all your downloaded csv files.
  2. Code example of transforming the data:
      *https://github.com/cis4400group6/CIS-4400-PROJECT/blob/main/Transforming_Data.png

### Load Data
  1. Load data by creating tables in mysql and load the transformed data from above into the tables using Python code. 
  2. Code example of loading the data:
    *https://github.com/cis4400group6/CIS-4400-PROJECT/blob/main/Loading_Data.png
    
## Full Code 
  * Please see the comments in the code to see what it does and what it is for. 
  * https://github.com/cis4400group6/CIS-4400-PROJECT/blob/main/ETL_Group%20Project.ipynb
  
## Questions?
If you have any questions about the project or technical issues please feel free to email:
  * talita-elena.vuvunikyan@macaulay.cuny.edu
  * Zainab.salahudin@baruchmail.cuny.edu
  * samanthaberenzon@gmail.com
  * tajinurjafarli@gmail.com
