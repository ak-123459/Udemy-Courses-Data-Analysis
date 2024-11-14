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
4. [Project Structure](#Project-Structure)
5. [Methodology](#Methodlogy)
6. [Data Visualisation](#Data-Visualisation)
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


- **Main/**

  - `udemy_courses_dataset.csv`: Contains the structure dataset.
   
- **Main/**
  
  - `Udemy Data Visualisations.pdf`: **Data Visualisations** in .pdf format.
  - `Udemy Data Visualisations.pbix`: Data Visualisation in .pbix format.
 
  - 
- **Main/**
  - `Udemy Data Report.pdf`: contains details report in .pdf format.
  - `Udemy Data Report.pbix`: contains details report in .pbix format.

- **Main/**
  - `Project-Udemy-Courses-template.pbit`:template  to use in other power bi Dashboard.


- `requirements.txt`: software requirements.
- `README.md`: This file.
  
   </div>



***


<div align= "start">

&nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/SyNZJd3/icons8-skills-64.png" width="50" alt="icons8-skills-64" border="0"></a>

</div>


<div align= "start">

- ### **Methodology**
  In the field of data analytics/data science a analyst need to  follow some steps like probelm statements,data extraction,data transfromations and data loading we called the process ETL(Extract transform load) and also Descriptive analytics.so in this project we have followed these setps in power bi.I have provided a file of Udemy_da_powerbi.pdf that contain all streps in pictures to picture that we have used in this analysis project.in the down below the basic method we have followed in each step-
  
  #### 1. Problem Definition
  The goal is understanding the key factor or key points that encourge the users to take the Udemy subscriptions.below down are the list of some task that need to focus and show on report.
  
  ##### Task List
    - Descriptive Analytics (Using Card Visuals)
      
      1.Max Lectures
      
      2.Median Reviews
      
      3.Median Course Durations
  
    - Visualizations (Using Charts)
      
      1.Level-wise Subscribers (in %)
      
      2.Level-wise Average Content Duration
      
      3.Median Number of Subscribers Level-wise
      
      4.Price vs. Number of Subscribers Correlation
      
      5.Subscribers vs. Reviews Correlation
      
      6.Year-Month Wise Total Number of Subscribers
      
      7.Year-wise Reviews in Paid vs. Unpaid Courses
      

&nbsp; &nbsp;     
#### 2. Data Collection
  **Tools** -  *Poer-Bi Data Source*
  We have downloaded the dataset from the open source machine learning aand data scienece websites [kaggle](https://www.kaggle.com/datasets/arzubesiroglu/udemy-courses-dataset) and also imported in power bi using excel workbook.

&nbsp; &nbsp;
  #### 3. Data Preprocessing
  **Tools** - *Power-BI Query Editor*
   - Removing nan values,empty,duplcates
   - drop unuseful columns like url etc.
   - add two new columns month,year by using published_time field

&nbsp; &nbsp;
  #### 4.Data Visualisations
 **Tools** - *Power BI DashBoard*
    

&nbsp; &nbsp;
  #### 5. Report Building
  
   **Tools** - *Power BI Report-View*

</div>

***



<div align= "start">


- ## **Data Visualisation**
  
- Check the file 
    [Data Visualisations](#Data-Visualisations)
  
</div>




***




<div align= "start">

&nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/MCtrJKX/find-1.png" alt="find-1" width="50" border="0"></a>

</div>


<div align= "start">


- ## **Key Findings**

  - In the subject of subscriber 68%(7M) user joined in those courses whose provide all level(Begineer-Expert) specializations.
  - in free courses 5x students are subscribes than the paid courses
  - in price vs Subscriber point of view there are little bit positive(0.37) correlationship between them.so we can say when price increase there are little bit 
    also subscriber would be increased.
  - Also when the number of review increased threre are chances of increament of subscribers(Postive Relationship 0.47).
  -  In paid courses, subscribers leave more reviews than in unpaid courses.
  - october,november,february,march these are the months with most subscriber compare to other months.
 
  - 
</div>



***



<div align= "start">

 &nbsp; &nbsp;<a href="https://imgbb.com/"><img src="https://i.ibb.co/q11pdTW/recommended.png" alt="find-1" width="50" border="0"></a>


</div>


<div align= "start">



- ## **Recommendations**

  - Udemy need to be added more courses of All level specializations for particlular subject.this can be beneficial because most of students are intrested in all 
     level specilizations courses.
  - Udemy can be also provide some low durations free courses to attract students for the subscriptions of that paid course. beacuse users most subscribed on free courses compare to paid.
  -    Udemy can highlight most reviews courses as top most this would be crucial for subscribers gaining.\
  -    If Courses uploaded on october novemeber and february,march  can be cruial to gain the more subscribers.
    
</div>





***

<div align= "start">


 &nbsp; &nbsp; <a href="https://imgbb.com/"><img src="https://i.ibb.co/wJ6kKqM/problem-solving.png" alt="problem-solving" width="50" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />
</div>


<div align= "start">

 - ## **Contributors** 
 [**Akash Prasad Mishra**](https://github.com/ak-123459),[**Shivam Tamrakar**](https://github.com/ShivamTamrakar16),[**Rohan Kumar Verma**](https://github.com/Vermaji277001)
   

</div>




 

