# Intro to Data Driven Analysis Project

The Brooklyn Gentrification project is one of the early projects that I worked on during my school year.
The scope of this project is to create a data science pipeline that allows users to understand a
real world problem or phenomenon through visualizations that feeds o a realistic data source. The
focus should be on analyzing real life data to make some meaningful interpretations and conclusions.

## Expectation
* Data in a relational database. You will need to submit the database schema, as well as data ingestion scripts.
* Python notebook as the primary implementation. This should have following components:
    - A data import component. This component should pull the data from the database into the Python environment. Note that you will need to demonstrate that you are manipulating data in the database itself (through embedded SQL) and not just pulling all the data into the notebook (no SELECT * FROM table). Bulk importing will result in loss of points.
    - A data analysis component. This is where you will perform various types of analyses (including basic histogramming, plotting, etc., and optionally advanced predictive analytics, clustering, etc.). You are allowed to use any Python package discussed in class.
    - A visualization component. This is where you will utilized the visualization capabilities of the MatplotLib library to show the output of your analyses. Choose the visualization outputs wisely! They should support your starting question and should allow you to draw conclusions. In some cases, it might make sense to put data on a map. In other cases, an interactive portal, where users can "play" with the data would be useful. 