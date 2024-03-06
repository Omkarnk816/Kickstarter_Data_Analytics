# kickstarter-data-analysis
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project’s initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.
# Introduction:
The Kickstarter [Raw_data](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/tree/main/Raw_Data) consists of crowdfunding projects that are posted on Kickstarter platform and also the datas are available on Kaggle.
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

 * We instantly notice that most projects are put on Kickstarter for about 5 weeks and almost all projects are live between 1 and 9 weeks (so a bit more than 2 months).

 * The proportion between successful and failed projects varies over time: Projects with a short run time (1–4 weeks) succeed relatively more often compared to projects that are launched with a medium to long run time (5–13      weeks). This insight could support the hypothesis that project are not more likely to succeed the longer they are live as one might have assumed beforehand 
 <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/cd2ec8be-016e-4ab7-91b9-898f9046c5de" />
</p>

* Projects with lower funding goals tend to have higher success rate.However,setting a realistic funding goal is crucial as projects with overly ambitious goals may struggle to attract backers.
* The goal amounts above the $45,000 show a decline in success rate, and increase in cancellation and failure rates.

   <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/31572411-1435-4c63-bf6b-5ec25c931ff4" />
</p>

* Categories with the performance arts are succeeding more than the Technology genre where the pledged amount is considered to be higher and backers demographics are more oriented towards the categories related to the arts,games rather then technology,film,Video etc.


   <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/ed9bb42a-d6d0-4012-8920-c77c7d14d8a4" />
</p>

* Let’s have a look at the relationship between a project’s goal and the actual amount pledged. It is quite obvious that a project is labelled as successful if
 amount pledged ≥ goal and unsuccessful if amount pledged < goal.The following graph visualizes both the goal and amount pledged for each project and the individual state of the project
* It can be seen that the accumulated amount of the total goal sharply increases in 2013 and has its peak in 2015 before it slowly decreases. On the other hand, the accumulated amount of pledges for each year steadily decreases but rather linearly. It actually decreased slightly from 2015 to 2017.More projects, more goals. However, this is just one component contributing to the increase in accumulated goals. Not only more projects launched over the years, but the average goal per project also increased over the years.

## Dashboard Overview [Link](https://github.com/Omkarnk816/Kickstarter_Data_Analytics/blob/main/InteractiveDashboard.xlsx)

   <p align="center">
  <img src="https://github.com/Omkarnk816/Kickstarter_Data_Analytics/assets/162085882/b96366dd-6a88-47ed-9b1f-064e8a910781" />
</p>













