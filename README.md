# UFO Javascript Analysis

## Overview of Project

### Purpose

The purpose of this project is to create a dynamic webpage by using javascript. A table is created to organize UFO data that is stored as
a javascript array, or list. Once the webpage detects user input, the table contents are updated depending on which filter criteria was entered 
by the user. This table is in an HTML file for easy viewing, and it's customized using Bootstrap.

## Results

There are five search criteria's available to filter the table data, they are date, city, state, country, and shape.
Each of these fields have placeholder text in them to provide an example like so:


![UFO_Table.PNG](/resources/UFO_Table.PNG)

The table has the ability to take these multiple search criteria at the same time, and they are not all required. For example, you can filter
just two criteria like shape and date only while leaving the rest in default. For example, input "light" in the shape field and "1/4/2010" in
the date field. 

The results are:

![Filter_Table.PNG](/resources/Filter_Table.PNG)



## Summary

One of the drawbacks to this user-input based design is that there can be user error. The user may try filtering the table with a different
format that is not recognized. For example, they may enter "1/01/2010" which returns an empty table but if they use "1/1/2010", it returns 
some results. We can add more interactive filtering available for users like a drop down with available choices. We can also add a sort feature 
to organize a data in a specific way the user chooses.