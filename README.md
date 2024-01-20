# Analyzing Swiggy : Bangalore delivery

### Dashboard Link : https://www.novypro.com/project/analyzing-swiggy--bangalore-delivery--outlet

## Problem Statement

The online food ordering market includes foods prepared by restaurants, prepared by independent people, and groceries being ordered online and then picked up or delivered. The first online food ordering service, World Wide Waiter (now known as Waiter.com),
was founded in 1995. Online food ordering is the process of ordering food from a website or other application. The product can be either ready-to-eat food or food that has not been specially prepared for direction consumption.

Do ETL : Extract-Transform-Load the dataset and find some
information from this large data. This is form of data mining.
What all information can be achieved by mining this data, would be
explained in class by the trainer
Find key metrics and factors and show the meaningful relationships between attributes.
Do your own research and come up with your findings.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Transform the data and make "use first row as header"

    In the dataset there are Five column.

        • Shop Name : The name of the restaurant or food outlet on Swiggy.

        • Cuisine : The type of cuisine offered by the restaurant, such as Indian, Chinese, Italian, etc.

        • Location : The geographical location or address of the restaurant.

        • Rating : A numerical value representing the average rating given by users for the restaurant's services.

        • Cost_for_Two : The estimated cost for two people to have a meal at the restaurant.

     

- Step 3 : Change the datatype according to use.

- Step 4 : Split Cuisine by comma seprated and got the different connection.

- Step 5 : add a new column "cost_for_one"

           cost_for_one =  AVG(Cost_for_Two)/2

- Step 6 : split the location by comma seprate and add a new column "Location.2" and group the location in four sector.

- Step 7 : make the BI report and publlished on BI service.

 
 # Report Snapshot (Power BI DESKTOP)

 

![homepage](https://github.com/Abhisharma001/Swiggy-Bangalore-insights/assets/63649579/331dcd30-c2bb-4193-8b88-1af9beb76722)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] slicer 
    • Total Shop  
    • Total Cuisine 
    • Avg Rating in Bangalore
    • Avg cost for one person 
           
### [2] Stacked Bar graph
    • Top 5 Shop By Rating
    • Bottom 5 Shop by Rating 
  
  ### [3] Tree map
    • Top Favorite Food 
  
 ### [4] Shop VS cost_for_one
    • user can find easy filter out low to high as per choice 
 
 ### [5] Rating By Location
    • we can easy to identified area wise Avg rating  

## Contributor
- Abhishek Sharma 

 
 ![powerbi-logo](https://github.com/Abhisharma001/Swiggy-Bangalore-insights/assets/63649579/6b31960b-2b0e-4891-adea-b38febedf7e3)
