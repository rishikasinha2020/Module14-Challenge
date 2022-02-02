Deliverable 1: Change Trip Duration to a Datetime Format
   # Refer to "citibike_201908_updt.csv" under "Bike Sharing" Folder for output.
   # Refer to "NYC_Citibike_Challenge.ipynb" under "Bike Sharing" for solution code.
Deliverable 2: Create Visualizations for the Trip Analysis
Deliverable 3: Create a Story and Report for the Final Presentation

Before You Start
In Deliverable 1, you’ll use Pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes. Using Tableau instead of Pandas to change the datatype of the "tripduration" column to a "Date and Time" will not produce the same visualizations in Deliverable 2. Trying to change the datatype by creating a calculated field may take more time for the less experienced Tableau user than the steps in Deliverable 1.

Once you change the datatype, you’ll export the DataFrame as a CSV file to use for the visualizations in Deliverable 2. If you export the new CSV file into the same Tableau workbook you used in this module, the "Average Trip Duration" and "Bike Utilization" graphs will be greyed out, and you won’t be able to use them because the datatype for the "tripduration" column has changed. Therefore, we recommend creating a new Tableau workbook to create the visualizations in Deliverable 2, and then you’ll have to recreate the two visualizations from the module in this new Tableau workbook that you’ll use for the Story in Deliverable 3. If you'd like to use the "Bike Utilization" graph in your Story for Deliverable 3, then we suggest creating a new column that contains the converted datatype of the "tripduration" column in Deliverable 1.

Deliverable 1
Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

Deliverable 1 Requirements(Fulfilled)
You will earn a perfect score for Deliverable 1 by completing all requirements below:

1. The data in the "tripduration" column is converted to a datetime datatype and has the correct time format
2. The DataFrame is exported as a new file without the index column

   # Refer to "citibike_201908_updt.csv" under "Bike Sharing" Folder for output.
   Bike Sharing\citibike_201908_updt.csv
   # Refer to "NYC_Citibike_Challenge.ipynb" for solution code.
   Bike Sharing\NYC_Citibike_Challenge.ipynb


Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:

How long bikes are checked out for all riders and genders.
How many trips are taken by the hour for each day of the week, for all riders and genders.
A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

Deliverable 2 Requirements
You will earn a perfect score for Deliverable 2 by completing all requirements below:

1. There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour
    
Refer to #Image of the deliverable requirement: Resources\Trip by weekday per hour.PNG

2. There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender
    
Refer to #Image of the deliverable requirement: Resources\By gender and number of bikes.PNG

3. A heatmap is created showing the number of bike trips for each hour of each day of the week https://public.tableau.com/app/profile/rishika.sinha2706/viz/Module14-Challenge-Tripsbyweekdayperhour/Tripsbyweekdayperhour?publish=yes
   
 Refer to #Image of the deliverable requirement: Resources\Module14- Deliverable2_Trips by Day per hour.PNG

4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
    
Refer to #Image of the deliverable requirement: Resources\By gender,weekday and hours.PNG

5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
   
Refer to #Image of the deliverable requirement: Resources\Gender and weekday.PNG

Deliverable 2 all five requirements filfiled with this dashboard story containing all the charts.
https://public.tableau.com/app/profile/rishika.sinha2706/viz/Module14-NYCCitibikesanalysis/NYCCitibikeanalysis?publish=yes



Deliverable3:

Some additional Visualizations that were created using Tablaeu found here
https://public.tableau.com/app/profile/rishika.sinha2706/viz/Module14-BikeSharing-TopEndingLocation/BikeSharingStory?publish=yes


This written analysis has the following:

Overview of the statistical analysis:

Pupose of this analysis is to provide below:
     1: Change Trip Duration to a Datetime Format
     2: Create Visualizations for the various Trip Analysis
     3: Create a Story and Report for the Final Presentation

Results & Summary:

There are at least seven visualizations for the NYC Citibike analysis.

Some additional Visualizations that were created using Tablaeu found here

https://public.tableau.com/app/profile/rishika.sinha2706/viz/Module14-BikeSharing-TopEndingLocation/BikeSharingStory?publish=yes
https://public.tableau.com/app/profile/rishika.sinha2706/viz/Module14-NYCCitibikesanalysis/NYCCitibikeanalysis?publish=yes




"# Challenge-14" 
