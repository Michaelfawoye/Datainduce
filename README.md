# Data Analyst Job Application Analysis
![](data_analyst.jpeg)

## Introduction:
This is a Power Bi project on Data Analyst Recruitment overview, using the United States 2019 Data Analyst Job dataset. The project is to analyze and derive insights to answer crucial questions that can aid HR hiring decisions.

_Disclaimer: All datasets and reports do not represent any company and/or institution. Consider this just a review of United State 2019 Data Analyst Job dataset to demonstrate capabilities of **Power Bi**_

## Problem Statement:
1. What is the Selection Ratio? 
1. What is the Hire-Rejection Ratio?
1. Which is the most hired job title and which city being in high demand?

## Skills/Concept demonstrated:
- Bookmarking
- DAX
- Modelling
- Filters
- Tooltips
- Button
- Shape
- Image

## Modelling:
![](Model.PNG)

The model is a **Flat schema**. There are just two tables that are related while others exist in isolation. The only dimension table is joined to the fact table with a **many-to- one relationship**.

## Visualization:
The report comprises of a single page, visualizing the Data Analyst job in United States in 2019. You can interact with the report [here](https://app.powerbi.com/view?r=eyJrIjoiYWQxNDU4MDAtYTQ5MC00YTI5LWExMWEtYzk2MDNhN2Q5ZjM1IiwidCI6IjM3NmQ3YjgwLTljNWEtNGMxNy05OWY1LTQ4MmJjYTY3MWQ4MCJ9&embedImagePlaceholder=true)

![](Full_Dashboard.PNG)

**Features:**
- Slicer (Tiles) to display and filter month.
- Slicer (Dropdown) to display and filter Job Title and Job Location
- The four buttons of “[Selection Ratio (SR), Hire-Rejection Ratio(H/R), Job Title and Cities]” to navigate corresponding visuals.

## Analysis:
### Application Headcount:
![](Headcount.PNG)

The total applications received in 2019 across all data analyst job titles amount to approximately **33K** while the total Hired applicants amount to **7,002** representing approximately **21%** of the total received applications.

### Monthly Headcount:
![](Monthly_Headcount.PNG)

More than **2000** applications are submitted each month of the year **2019**. The month of **February have the lowest submitted applications (2,312)** while the month of **July have the highest number of applications (3,138)**.

### Selection Ratio:
Top 5 Application Cities          | Top 5 Cities By Selection Ratio
:--------------------------------:|:----------------------------------------:
![](Top_5_Application_Cities.PNG) | ![](Top_5_Cities_By_Selection_Ratio.PNG)

Apparently, for every month in 2019, New York, NY have the highest number of applicants for data analyst job **(4,650)** and as well the most hired in term of headcount **(1,015)**. The displayed 5 cities top the table when compared against the overall received applications for the year but apparently, reverse is the case when compared to the level of rejection.

### Hire-Rejection Ratio:
#### Comparison
Top Cities by Selection Ratio                 | Top Cities by Hire Rejection Ratio
:--------------------------------------------:|:----------------------------:
![](Tooltip_Selection_Ratio.png)              | ![](Hire_Rejection_Ratio.png)

The selection ratio took into consideration the hired and the overall received applications which might not actually be the right indicator when compared to the hire-rejection ratio which set the total number hired against the total number rejected as evident in the above image. The selection ratio ranked New York, NY above others because it hired approximately 1k applicants of 4.7k total applicants but the hire-rejection ratio ranked Novato, CA because 8 out of 14 total applications were hired. This means they have more hired than rejection and this portray to certain extent quality of application.

### _Most In-demand Data Analyst Job_
![](In_Demand_Job_Title.PNG)

### _Top 3 Cities for each In-demand Job Title_
![](In_Demand_Cities.PNG)

Of the approximately 7k total hired in 2019, Digital Marketing Data Analyst Hired **1,820** applicants which makes it the most sort after in the top 3 cities of **New York, NY, Chicago, IL and San Francisco, CA**.

## Conclusion:
- New York have the highest number of applicants as well as the total number hired in the 2019 data analyst job application
- Novato, CA have the most quality applicants considering the hire-rejection ratio
- Digital Marketing Data Analyst is the most sort after analyst job title in most of the United States cities.

## Recommendation: 
For robust analytics, the datasets should include the demographic of the applicant to discover the gender with the most involvement and to deduce the average age of applicants. The included demographic was added subjectively because it seems relevant to draw a robust conclusion.  Also, the datasets of the previous years will be required for comparison so as to bring to light the trends in data analyst job.

## Thanks for reading :+1:
