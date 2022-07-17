# Hospital No-Show Appointment Analysis
Exploration and Analysis of a Sample Dataset from an Hospital whose intent is to get to to know some patterns about Patients who don't show up on their appointment dates.

## Introduction
This project was initially inspired by **Udacity** in the **Nanodegree program**. It was the first project of 3 (do watch out for the remaining 2) and was meant to put to practice **Exploratory Data Analysis** in the real sense of it. However, i took it further than there by **Analysing and Visualizing** the clean dataset in Power BI. Do check the uploaded files for the <a href = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/No-Show%20Appointment%20Report.pbix"> .pbix file</a>. Please note that the full documentation can be accessed in the <a href = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/Investigate_a_Dataset.ipynb"> **investigate-a-dataset.ipynb** </a>file. The major part of the project was done using **jupyter notebook** (see notebook in the files section) deploying some python libraries (pandas, numpy, matplotlib, re and seaborn), while further exploration was done in Power BI with some visuals (see .pbix file)

This documentation is sectioned as follows:
* Data Gathering
* Data Wrangling
* Exploratory Data Analysis
* Data Ingestion and Transformation
* Data Modeling
* Report Background Design
* Data Visualization
* Conclusion


### Data Gathering
As stated above, Udacity provided me with the dataset for this projeect. However, the dataset is publicly available on <a href = "https://www.kaggle.com/datasets/joniarroba/noshowappointments">kaggle.com </a> and can be checked up on the files section of this repo. It samples little above 110,000 patients (after cleaning and invalid data removed) with primarily 12 attributes about them. 


### Data Wrangling
The dataset, after importing was checked for some quality issues. After running some **descriptive statistics (with .describe() method) and informational statistics (using the .info() method)**, i discovered some quality issues in the dataset. Some of which were <u/>invalid data, wrong datatypes, not too descriptive columns, inconsistent naming </u> conventions among others. These were all cleaned using different methods and techniques as are available in the pandas library. See the .html file for the details

### Exploratory Data Analysis
The Dataset was explored to get answers to some specific questions. These questions include:
* Does the difference between ScheduledDay and AppointmentDay significantly impact Show-Up possibility?
* What Age-group are more likely to show up for their appointment?
* Does receiving sms impact show-up rate?
* Is there a relationship between the weekday of appointment and the possibility of show-up?

The above questions were explored in the dataset for possible patterns and/or answers. Some of the answers are stated in the conclusion part of this doc. (See also the .ipynb file)


### Data Ingestion and Transformation
After a keen exploratory analysis in the jupyter, i went on to run further exploration and descriptive analysis in Power BI. Although this is out of the project, but I saw it essential for a clearer visualization of happenings within the dataset as well as a cleaner revelation of what's inherent. The dataset was imported into Power BI and transformed using Power Query <a href = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/No-Show%20M%20Query.txt"> (See the .txt files for the M codes) </a>

### Data Modeling
Additional tables were needed for analysis and segmentation. Such tables included the Date table, segmenting the patients into genders, age brackets and other dimensions for analysis. A data model was created out of the loaded tables in Power BI. 

<img src = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/Data%20Model.JPG" width = "500" height = "340" > 

### Report Background Design 
The report layout was designed in Power Point. Inspiration for the design was gotten from <a href = "www.novypro.com/inspiration"> Novypro </a>. 

<img src = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/No-Show.png" width = "500" height = "340">

### Data Visualization
The dataset was visualized in Power BI. I did a lot of summary statistics on the dataset to have an idea of patients distribution by the dimensions (attributes). This, i paid attention to since major exploration had been done in the jupyter notebook. Click <a href = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/No-Show%20Appointment%20Report.pbix"> here </a> to view the visualizations. 

### Conclusion
There were quite a few limitations to a full exploration of the dataset and to answer completely questions on why a patient would appear or not on their appointment date. Although there were records of whether a patient attended or not, the reasons for not attending couldnt be substantiated as that wasnt captured in the dataset provided. <br>

Further notes on the insights can be found on the <a href = "https://github.com/Id-Analyst/Hospital-No-Show-Appointment-Analysis/blob/main/Investigate_a_Dataset.ipynb"> **Jupyter Notebook** file </a>
