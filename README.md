# Programing for Cultural Heritage Final Project

## Porject Title: Information Dashboard for UNESCO Intangible Cultural Heritage List

## Link to the dashboard: https://public.tableau.com/app/profile/jiacheng.chen/viz/pfch_ICH_project/Dashboard1?publish=yes

## Introduction

This project intends to create an informative dashboard of the UNESCO Intangible Cultural Heritage list, to help users better navigate the richness of intangible cultural heritage through countries, preservation lists, and primary concepts. Intangible cultural heritage refers to various traditional cultural expressions that have been handed down from generation to generation by people of all ethnic groups and are closely related to the lives of the masses (e.g., folklore activities, performing arts, traditional knowledge, and skills, as well as associated instruments, objects, handicrafts, etc.) and cultural spaces (i.e., places where traditional cultural activities are held regularly or where traditional cultural expressions are concentrated, both spatially and temporally). 

## Data Source

The datasets used in this project were taken from the *UNESCO Intangible Cultural Heritage List website* (https://ich.unesco.org/en/lists?text=&multinational=3&display1=candidature_typeID#tabs) and from the simplified dataset compiled in *Dive into intangible cultural heritage!*(https://ich.unesco.org/en/dive).

## Data Cleaning 

This project uses python and pandas to perform the data cleaning work, please refer to the **ich_dataCleaning.ipynb** file under this repo for the specific code.

## About the Dashboard

This dashboard consists of 4 main parts. The first is a world map, which not only shows the ICH list of a particular country but also shows the distribution of a particular ICH across borders by selecting it. Secondly, a pie chart presents the statistics under each UNESCO ICH list (including Representative List, Register Good Safeguarding Practices, and Urgent Safeguarding List), which can also be used as a filter to help users select the specific ICH items in the list they want to know about. Third, a bubble map below the pie chart shows the types and numbers of ICH concepts in color and size. Finally, when the user is interested in a particular ICH item, they can click on the circle and see the specific name and a short description in the "detail information" table on the right or click on the link to access the particular UNESCO page for more detailed information.


