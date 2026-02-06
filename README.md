# 6DATA007W.Y_DS-A_Final_Project_Interim2
Understanding the dynamics of Crime through data: A case study of London (UK)
Second stage of my Final year project with preliminary analysis of crime dataset from January 2024 to December 2025.

This repository has the Crime dataset scraped from the London datastore. It contains the count of crime, the types, the years and the months.
The data was recorded at borough level which is good for analysis and this was it is also possible to compare different boroughs and
other socio-economic datasets also set at borough level to find relationships.

From initial analysis, the years and months are put together (January 2024 is 202401) and are along the X axis, meaning that the dataset had to be reshaped.
This is so that analysis is done more efficiently when merging datasets as most datasets on socio-economic factors are in the long format.
There were also strange values recorded for BoroughName and were labelled as "Unknown". Using the Excel filter, they were deleted so that what remained
was all the confirmed boroughs and crime types as well as their crime count.
