# Zomato | Data Manipulation and Reporting with Power BI <br>
## High Level Business Requirement: <br>
Zomato is a restaurant search and discovery service. Operating in several countries worldwide, they provide detailed information and customer reviews of various restaurants. The owners of Zomato, want to unearth
the hidden anomalies in their business data. The final objective is to analyze the data in a way which helps them to accurately judge their business performance. <br>
## Objective: <br>
The objective of this project is to develop an interactive Power BI report for Zomato, enabling detailed analysis of restaurant data across continents. This report will help identify hidden anomalies, track business performance, and provide insights through dynamic visualizations, filters, and drill-down capabilities accessible via web and mobile platforms. <br>
<br>
The data (sample) is currently available in the form of a few excel files with each file containing information about several restaurants operating in a specific continent. The clients want to create a consolidated and interactive Power BI report from where they can easily analyze the following information: <br>
<br>
1)	Total number of restaurants across continents, countries and cities. <br>
2)    The ability to view information at a global level. But at the same time, the ability to go down to granula level as well. <br>
3)    Top performing restaurants by average customer ratings. <br>
4)    Top performing restaurants by least average cost. <br>
5)    Ability to filter and view the restaurant details (address, cuisines served …) on the basis of: <br>
      a.	Geographic dimensions like continent, country and city. <br>
      b.	If the restaurant offers services like, online delivery or table booking. <br>
6)    Top ranking restaurants by the number of cuisines they serve. <br>
7)    They want to create a multi-page report which matches with the company’s theme and where navigation between pages has been made very easy. <br>
8)    They want their users to be able to access this report using a web browser as well as their phone devices. <br>

## Tool Used: Power BI <br>

## High Level Steps:
To achieve the above-mentioned requirements, following are some of the high-level steps that need to be performed. <br>
## Data Import:
1)    Import data from all the available Excel files (mentioned below) into Power BI. <br>
a.	Africa <br>
b.	Asia <br>
c.	Country-Code <br> 
d.	Europe <br>
e.	NAM <br>
f.	SAM <br>
g.	Oceania <br>
h.	Fact Table <br>
## Data Transformations
1)    Some of the values in the “City” column, mentioned below, needs to be corrected. <br>
a.    The word “city” needs to be taken off from every city name (wherever appears). <br>
b.    “Sí£o Paulo” should be corrected to “São Paulo”. <br>
c.    “Cedar Rapids/Iowa City” should be corrected to “Cedar Rapids”. <br>
d.    “ÛÁstanbul” should be corrected to “Istanbul”. <br>
              2)    Remove the columns which are not used. <br>
              3)    Make separate columns to show the “Restaurant Name” and the “Restaurant Address”. <br>
              4)    Create a separate table from where you get the list of cuisines served by each restaurant. <br>
              5)    The “Country-Code” table must contain only unique and non-blank values (as it’s adimension table). <br>
## Data Modeling
1)	 Model your data according to the reporting requirements.
2)	While creating relationships, choose the appropriate “Cardinality” and the “Cross filter direction”
                   so that the aggregations can happen accurately at the report level.

## Other Data Manipulations
1)    There is a list of geographic columns. Go through the list and categorize them appropriately. <br>
2)    Create a user-defined hierarchy and include all the geographical dimensions in there. <br>
3)    Group the countries into appropriate continents. <br>
4)    Create following measures in appropriate tables. <br>
a. Restaurant Count <br>
b. Average Cost <br>
c.  Average Rating  <br>
d.  Cuisine Count <br>
5)    Wherever needed, lookup the continent column from the “Country Code” table. <br>

## Data Visualization
1) Create the following visuals. <br>
A) Card visual <br>
    i. Average Cost <br>
    ii. Average Rating <br>
    iii. Restaurant Count <br>
B. Map visual <br>
    i. Geography hierarchy <br>
    ii.Restaurant Count <br>
C. Column Chart <br>
    i. Average rating <br>
   ii.Country <br>
D. Slicer showing list of rating colours <br>
E. Slicer showing list of counties <br>
F. Slicer showing list of cities <br>
G. Grid showing list of restaurants <br>
H. Gauge showing selected restaurant’s average rating <br>
I. Gauge showing selected restaurant’s average cost <br>
J. Card showing the selected restaurant’s address <br>
K. Grid showing the selected restaurant’s list of cuisines <br>
L. Publish the report on to a service account and create a public link. <br>

## Expected Outcome: <br>
A consolidated, interactive Power BI dashboard providing deep insights into restaurant performance, enabling Zomato to detect anomalies, track trends, and enhance decision-making. <br>

## Key Achievements: <br>
•	Successfully developed a multi-page Power BI dashboard aligning with business requirements. <br>
•	Implemented advanced DAX measures to calculate restaurant count, average ratings, and pricing trends. <br>
•	Enabled deep-dive analysis through drill-down and filtering functionalities. <br>
•	Improved data accuracy and reporting efficiency by automating data cleaning and transformations. <br>
•	Delivered a scalable and visually engaging report, enhancing business decision-making at Zomato. <br>






