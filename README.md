# UDACITY DATA VISUALISATION PROJECT
## Understanding relationship between access to books and reading scores 

#### GAURI PHATAK

##### JUNE 2017

## DATASET USED: 

The main dataset with score values and country information:

Pisa2012 Dataset. Link to: https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true

Data to understand the region the country belongs to was extracted from here:
www.statvision.com/webinars/countries%20of%20the%20world.xls


## Summary

In the plot created we try and understand a relationship between the number of books students have access to at home 
and their reading scores based on tests by PISA2012 dataset.


## DESIGN CHOICES:

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

### Design decision: 
I wanted to create an interactive graph, but did not burden the page with too many variables. I wanted to understand how having access to books affects the reading scores for students from different countries. 
Having data from all the countries might have been to crowded on one graph. Hence I decided to take advantage of the animation capabilities of dimple and divided the countries into different regions.
Initialy I had just the country split for the data, but later I added gender split for each country as a sub graph. This gave a good understanding of male female scores for each region potrayed in the data. 

## FEED BACK:

Feedback 1:
Gauri,

Really nice work!

I like the animation and how you can compare outcomes in countries in a specific region.

One thing I'd suggest is eliminating the bottom graph of test scores based on gender. The top chart is sufficient to explain to the viewer the main focus of your visualization, the relationship between reading scores and access to books. Also, When focusing on the top chart I can't read the bottom chart because it is outside of my field of vision. That's why I recommend removing it to make the visualization simpler for the viewer.

If you are interested in communicating the relationship between gender and test scores you could publish that chart separately.

Andrew

Feedback 2:

Hi Gauri,

Really nice work! I like to click on the bars in the right to compare different regions. The animation was good and I am starting to wonder, is having more than 500 books really a good thing? Because most of the countries show that there is actually a decrease of mean score when having more than 500 books.

For the bar graph in the bottom, I would recommend using a grouped bar plot, for which you can compare the gender difference easily. Unless what you really want is to compare the difference between different countries, in which case, using the mean of male and female makes more sense.

Wolf

Feedback 3:

Hi Gauri,

Thanks a lot for the feedback and appreciation :slight_smile:

I really liked your visualization and the use of animation in the charts. Also the fact that you can choose regions in the world whose scores you want to check makes it pretty interesting.

The visualization makes it easy to understand the relationship between the number of books owned at home and the reading score across various regions and also how gender have an impact on the reading scores across various regions as well. I liked your visualization and it clearly depicts the findings it wants to communicate to the reader, so there's nothing from my end which I would like to add more on to it.

All the best and good luck for your submission!!

Thanks 
Ruchita

Feedback 4:  ( Received in person)

I like the visualisation. It gives me an understanding of how the data is distributed for different countries. I like the fact that the gender chart is present. It gives country by country analysis for the scores between girls and boys. 


Update based on the Feedback:

Based on the feedback there is not a lot I can update in my Visualisation. As for Andrews suggestion with the gender chart, it is a part of the visualisation design. I wanted to show  the details for each country for both boys and girls, for the choosen region. 


## RESOURCES:

http://dimplejs.org/advanced_examples_index.html

https://d3js.org/

https://github.com/PMSI-AlignAlytics/dimple/wiki

https://stackoverflow.com/questions/25416063/title-for-charts-and-axes-in-dimple-js-charts/25422021

https://stackoverflow.com/questions/23291200/dimple-js-how-can-i-change-the-labels-of-a-chart-axis-without-changing-the-data
