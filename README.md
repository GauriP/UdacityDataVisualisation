# UDACITY DATA VISUALISATION PROJECT
## Understanding relationship between access to books and reading scores 

#### GAURI PHATAK

##### JUNE 2017

##DATASET USED: 

The main dataset with score values and country information:

Pisa2012 Dataset. Link to: https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true

Data to understand the region the country belongs to was extracted from here:
www.statvision.com/webinars/countries%20of%20the%20world.xls




## Summary

In the plot created we try and understand a relationship between the number of books students have access to at home 
and their reading scores based on tests by PISA2012 dataset.

### Understanding relation between number of books and reading score

Looking at the plots above we can understand that in most cases (Regions and Countries) the reading scores increases 
with increase in number of books available to the students.
We also so there is no significant increase in the reading score for students who have more than 500 books at their disposal.
There are couple of things to note after considering the correlation in the variables above.
Firstly, students with more books might in general have access to better education and opportunities to learn assuming their
family can afford those many books. 
Secondly the larger number of books might indicate that the family from which the child comes might be encouraging and 
pushing the child to learn using books. 

### Understanding relation between reading score for different genders

In the 2nd graph we can see the mean reading score for girls and boys seperately. This gives us an idea about the reading 
capability for both the genders for each country in the dataset. 


##DESIGN CHOICES:
I wanted to create an interactive graph, but did not burden the page with too many variables. I wanted to understand how having access to books affects the reading scores for students from different countries. 
Having data from all the countries might have been to crowded on one graph. Hence I decided to take advantage of the animation capabilities of dimple and divided the countries into different regions.
##FEED BACK:

##RESOURCES:

http://dimplejs.org/advanced_examples_index.html

https://d3js.org/

https://github.com/PMSI-AlignAlytics/dimple/wiki

https://stackoverflow.com/questions/25416063/title-for-charts-and-axes-in-dimple-js-charts/25422021

https://stackoverflow.com/questions/23291200/dimple-js-how-can-i-change-the-labels-of-a-chart-axis-without-changing-the-data
