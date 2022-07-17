# Hospital No-Show Appointment Analysis
Exploration and Analysis of a Sample Dataset from an Hospital whose intent is to get to to know some patterns about Patients who don't show up on their appointment dates.

## Introduction
This project was initially inspired by **Udacity** in the **Nanodegree program**. It was the first project of 3 (do watch out for the remaining 2) and was meant to put to practice **Exploratory Data Analysis** in the real sense of it. However, i took it further than there by **Analysing and Visualizing** the clean dataset in Power BI. Do check the uploaded files for the .pbix file. Please note that the full documentation can be accessed in the **investigate-a-dataset.html** file. The major part of the project was done using **jupyter notebook** (see notebook in the files section) deploying some python libraries (pandas, numpy, matplotlib, re and seaborn), while further exploration was done in Power BI with some visuals (see .pbix file)

This documentation is sectioned as follows:
* Data Gathering
* Data Wrangling
* Exploratory Data Analysis
* Data Ingestion and Transformation
* Data Modeling
* Report Background Design
* Data Visualization
* Recommendation and Conclusion


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

The above questions were explored in the dataset for possible patterns and/or answers. Some of the answers are stated in the conclusion part of this doc. (See also the .html file)


### Data Ingestion and Transformation
After a keen exploratory analysis in the jupyter, i went further to run further exploration and descriptive analysis in Power BI. Although this is out of the project, but I saw it essential for a clearer visualization of happenings within the dataset as well as a cleaner revelation of what's inherent. The dataset was imported into Power BI and transformed using Power Query (See the .txt files for the M code)

