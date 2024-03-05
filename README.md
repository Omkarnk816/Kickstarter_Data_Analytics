# kickstarter-data-analysis
A project for analyzing the Kickstarter crowdfunding data to a actionable insights,data-driven decisions etc from the visualizations of interactive Dashboard.
# Introduction:
The Kickstarter raw(file) consists of crowdfunding projects that are posted on Kickstarter platform and also the datas are available on Kaggle.
 ## Data Cleaning
 ![image](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/fcaa51c0-abae-4ce6-81e6-8deb0c462600)

 -Implemented **filters** and **iferror** function to clean data that helped in replacing the errors with "str_value" to optimize the analysis.
 
 -**Handling Null** by mode values.

   ![null](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/0cf2450d-fc4b-40ac-b22f-6079f53270ce)                                                                                                         ![Mode](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/c9c84b99-b7e8-4de5-ad1a-f00a992fcb9f)

 -Converting epoch time to default Date format(The formula: =(A1/86400)+25569),Removing unwanted attributes to reduce the data size.
 
 ![converted_date](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/590a7759-304c-416d-9c45-062af814514a)

 ## Data Extract and Transform
  ![image](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/fcaa51c0-abae-4ce6-81e6-8deb0c462600)
 
 -Utilized **Power Query** to extract and transform the data, then transferred the data to **Power Pivot** for further exploration and updation in dataset.
 
 -Power Pivot manages **Data modelling** from different sources to make connections using **keys**.
 
![Query](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/28ac9285-f6b3-4d21-9edd-645b2f90a371)  ![DATaMod](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/e0c08c2f-af74-4598-9ed5-1cea317786d2)

 -Pivot Table visualize important KPIs for rapid decision-making with slicers for interacive Visualization.
 
 ![Pivot](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/729e8498-c4ed-4526-9d6e-64f917df03ea)

## Analyses derived from the dataset












