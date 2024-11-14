<img src="https://i.ibb.co/2vfkHVB/UDEMY-Projects-img.jpg" width="1500" alt="Description of image">

<br></br>

The project aim to gain insights from data and key factors that encourge the users to get the subscriptions of udemy courses.and more areas
to improve courses design for the target users.






***

 <div align= "start">
  
  &nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/Ksw7GWz/list.png" width="50" alt="list" border="0"></a> <div/>

  <div align= "start">
  
- ## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Prerequisites](#Prerequisites)
4. [Project Structure](#ProjectStructure)
5. [Methodology](#Methodlogy)
6. [Data Visualisation](#Visualisation)
7. [Key Findings](#KeyFindings)
8. [Recommendations](#Recommendations)
9. [Conclusion](#Conclusion)
10. [Contributors](#Contributors)

 <div/>







***


<div align= "start">
 
  &nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/x2mBdn3/file.png"  width="50" alt="file" border="0"></a> <div/>
  
<div align= "start">


 
- ## **Project Overview**
[**Udemy**](https://www.udemy.com/), Inc. is an education technology company, founded in May 2010 by **Eren Bali**.Udemy Provide the educational courses in different subjects/area.so in this project we are going to explore and anlalyze a dataset of udemy.this dataset related to subject buisness.we have explored all the important field like number of subscribers,price and much more.In this project we have used power-bi Desktop for intractive data visulaizations and easy data transformation.we have also used power-bi dashboard and Quick Measures for correlations calculations. for complex The final objective is to understand the courses purchases patterns of user.what are the key factors increase the interest of users to join the course or take subscription of that particuler course in udemy. 
 <div/>

 
<br></br>






***


<div align= "start">
&nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/D9vKsxH/dataset.png" alt="dataset" border="0"  width="50"></a> <div/>
 

  
 <div align= "start">
   
- ## **Dataset**
 &nbsp; &nbsp; **Dataset Structure -**

 | Column Name       | Data Type | Description                              |
|-------------------|-----------|------------------------------------------|
| `course_id`              | Integer   | Unique identifier for each entry         |
| `course_title`            | String    | title of course   |
| `url`          | String    | course link             |
| `is_paid` | Boolean     |course type paid or not |
| `price`            | Integer      | price of the course                  | 
|`num_subscribers`|   Integer|subscribers for each course|
|`num_reviews`| Integer| review for the course|
| `num_lectures` | Integer     |total lecture on that course |
| `level`            | String      | level of course (begineer,intermediate,expert)   | 
|`content_duration`|   Float|Total duration in hours|


 To more about the dataset  go through the link.you can also download the dataset 🔗  -> [kaggle](https://www.kaggle.com/datasets/arzubesiroglu/udemy-courses-dataset) 
  
  </div>



  

***



<div align= "start">
 
&nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/9TTK8Gc/icons8-requirements-64.png" width="50" alt="icons8-requirements-64" border="0"></a>

</div>



<div align= "start">
  
 - ## **Prerequisites**
   Before running the analysis, ensure that you have the following skills:

- `Power Bi Desktop`
- `Data visualization`
- `ETL(Extract transform load)`
- `Statistics`
- `Kaggle`

</div>


***






<div align= "start">
 
&nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/DDYn9zS/icons8-structure-48.png" width="50" alt="icons8-structure-48" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />
</div>



<div align= "start">
  
 - ## **Project Structure**


- **dataset/**
- 
  - `udemy_dataset/`: Contains the structure dataset.
   
- **Data Visualisations/**
  
  - `Udemy Data Visualisations.pdf`: Data Visualisation in .pdf format.
  - `Udemy Data Visualisations.pbix`: Data Visualisation in .pbix format.
 
  - 
- **report/**
  - `Udemy Data Report.pdf`: contains details report in .pdf format.
  - `Udemy Data Report.pbix`: contains details report in .pbix format.


- `requirements.txt`: software requirements.
- `README.md`: This file.
  
   </div>



***


<div align= "start">

<a href="https://imgbb.com/"><img src="https://i.ibb.co/SyNZJd3/icons8-skills-64.png" width="50" alt="icons8-skills-64" border="0"></a>

</div>


<div align= "start">

- ### **Methodology**
  In the field of data analytics/data science a analyst need to  follow some steps like probelm statements,data extraction,data transfromations and data loading we called the process ETL(Extract transform load) and also Descriptive analytics.so in this project we have followed these setps in power bi.I have provided a file of Udemy_da_powerbi.pdf that contain all streps in pictures to picture that we have used in this analysis project.in the down below the basic method we have followed in each step-
  
  #### 1. Problem Definition
  The goal is understanding the key factor or key points that encourge the users to take the Udemy subscriptions.
  
  ##### Task List
  
  

  #### 2. Data Collection
  **Tools** -  *Poer-Bi Data Source*
  We have downloaded the dataset from the open source machine learning aand data scienece websites [kaggle](https://www.kaggle.com/datasets/arzubesiroglu/udemy-courses-dataset) and also imported in power bi using excel workbook.

  #### 3. Data Preprocessing
  **Tools** - *Power-BI Query Editor*
   - Removing nan values,empty,duplcates
   - drop unuseful columns like url etc.
   - add two new columns month,year by using published_time field

  ### Data Visualisations
 **Tools** - *Power BI DashBoard*

  
  

</div>





 

