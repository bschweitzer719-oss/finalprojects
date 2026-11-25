
# finalprojects 
The objective of this project is to describe the package at two distinct levels: a technical perspective and a perspective tailored to the R community. First, the technical perspective will concentrate on the package’s internal architecture; second, the R community perspective will highlight usability, documentation, and integration with existing R workflows.

# Personal Motivation
As an immigrant, I am concerned about immigration detention in the United States. This inspired me to use ICE Detention Data to analyze detention trends from 2014 to 2025.

# Two Visuals Analysis Approaches
# 1. Linear Regression of ICE Detentions by Fiscal Year
The linear regression analysis indicates that the detention rate reached their highest level in 2019, suggesting a higher frequency of arrests during that year. This spike may be attributed to intensified law enforcement initiatives, changes in policy, or an increase in reported incidents. Over the subsequent years, the model shows a gradual decline in detention rates, reaching a lower level by 2025. The downward trend could reflect the effectiveness of reforms, improved community policing, or shifts in crime patterns.

# 2.The plot shows Total Detention counts by Country
The geom_point plot shows that Mexico, represented by the blue point, has the highest total number of detentions among the countries displayed. This pattern can be plausibly explained by Mexico’s proximity to the United States, which allows a larger volume of cross‑border movement and thus raises the likelihood of detentions. Ecuador, often referred to in the data as the “brown point", shows a markedly lower number of citizens detained by U.S. Immigration and Customs Enforcement (ICE).

# Technical Communication 1
On the total detention by country, ice detention dataset holds yearly detention figures, arranged by fiscal year and the detainee’s country of birth. This arrangement lets analysis look at temporal trends and compare how people from various regions are treated. Prior to any statistical work, the dataset was examined with the head() function to see the initial entries and with str() to verify data types and variable labels.

# Technical Communication 2, Generic Function
The generic functions print(), summary(), and plot() were used on the detention dataset. They invoked class‑specific methods, enabling the data to be shown in a clear format, automatically calculating essential descriptive statistics, and visualizing it over fiscal years. This method mainly aims to simplify routine data exploration and offer a uniform interface for analysts handling various data structures.

# Technical Communication 3, Comparison of S3 and S4 Object
To investigate R's object-oriented frameworks, I constructed both an S3 object and an S4 object derived from the ICE detention dataset. The S3 object employed an informal class assignment via class(), whereas the S4 object was formally specified with setClass(). I tested generic functions such as print() to illustrate method dispatch. The S4 approach offered a more robust structure through predefined slots and type validation.

# Package Installation
devtools::install_github("/finalprojects")
library(finalprojects)

# Benefit to the R Community
Because R packages are viewed as the best method for packaging and sharing R code and data for reuse by others, particularly students and novice R programmers, this package addresses several issues. It shows how to employ devtools to install a new package straight from a GitHub repository. It also assists users in dividing functions into separate packages and offers experience in crafting machine‑readable metadata
You can install the development version of finalprojects like so:

# Data Source
https://usafacts.org/articles/what-is-ice-and-what-does-it-do/
# Html Project Link
file:///C:/Users/User/OneDrive%20-%20University%20of%20South%20Florida/LIS4370/finalprojects/ICE_Detention_Report.html
ICE Detention Data Analysis Tools

# The complete project is available on Wordpress.com 
https://discoverantilleancuisine.wordpress.com/2026/11/24/fall-2026-lis4370-final-project-ice-detention-data-analysis-tools/

