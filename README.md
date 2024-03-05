# kickstarter-data-analysis
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project’s initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.
# Introduction:
The Kickstarter raw(file) consists of crowdfunding projects that are posted on Kickstarter platform and also the datas are available on Kaggle.
 ## Data Cleaning
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

 * Implemented **filters** and **iferror** function to clean data that helped in replacing the errors with "str_value" to optimize the analysis.
 
 * **Handling Null** by mode values.

 <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/a1a922b3-2a9a-41b6-80fc-8c5501f5f90e" />
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/e5cf74ea-560c-44e6-91a1-f5d84f9f23e4" />
</p>
   
 * Converting epoch time to default Date format(The formula: =(A1/86400)+25569),Removing unwanted attributes to reduce the data size.

 <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/590a7759-304c-416d-9c45-062af814514a" />
</p>
 
 ## Data Extract and Transform
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
 
 * Utilized **Power Query** to extract and transform the data, then transferred the data to **Power Pivot** for further exploration and updation in dataset.
 
 * Power Pivot manages **Data modelling** from different sources to make connections using **keys**.
  <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/1bdebbb6-1bc8-46f3-96b3-1871a8da83ca" />
</p>
 

 * Pivot Table visualize important KPIs for rapid decision-making with slicers for interacive Visualization.
  <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/729e8498-c4ed-4526-9d6e-64f917df03ea" />
</p>
 
## Analyses derived from the dataset
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

  <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/fc07ff3a-1d98-4bb9-9f81-524806e9d92e" />
</p>

 <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/cd2ec8be-016e-4ab7-91b9-898f9046c5de" />
</p>









