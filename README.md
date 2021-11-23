# Data-115-Fall-2022

## Motivation: 
When starting this project, I wanted to look into coral. 
I thought maybe something about coral bleaching or common types of coral in different regions. 
While looking for data about coral, I came across this data set about Hawaiian fish. 
My family loves to go to Hawaiian and snorkel, so I could relate to the fish names I was seeing and all the data. This data also contained info on the habit types of each fish along with tons of other data. 
From looking at this data set, I came up with a new question of whether there could be a common factor of habit type to another aspect of the data like size, depth, or species.

## Data Process:
To start with, I downloaded my dataset into an excel file from National Oceanic and Atmospheric Administration site. The dataset needs no cleaning in excle. The only step I had to take was to save it as a CSV file. I then uploaded the data into RStudio. Once the dataset was in RStudio, I deleted 27 columns from the primary dataset. The dataset had a ton of information that was not relevant to what I was looking at, making it easier to read all the data if I got rid of a few columns. My next step was to run a summary of my new dataset. This was to try to identify any outliers or concerns in the data. The summary brought up a few max numbers that I wanted to look into. I looked into the count, sand, size, MA, and lmax. Count and size were the only ones that I found any concern with as being an outlier. Looking closer in the rows of data with the outliers, the numbers made sense, so I decided to keep them in the dataset. From there, the dataset was too big to take a closer look into. I took a random sample of 1000 to look fourth into. The original dataset had 23000+ rows of data, so 1000 is just 4% of the whole data, but this 4% still includes all ten habit types to look into and around 62% of the species in the original dataset.

## Visualization: 
![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Hab.%20Num..png)

This bar chart shows the count of the different habit types. It is to show how common the different habit types are. As you can see, Aggregate Reef and Rock/Boulder are by far the most common.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Wat.%20Dep.%20Hab..png)

This chart shows the relation of the min and max depth that the fish was found concerning the habit type. It shows a linear relationship between the min and max depth with a bit of variance in the lower min depth. There is not an apparent relationship between the habit type and min or max depth.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Size%20Num..png)

The bar chart shows the frequency of the size of fish in the dataset. As a show, the majority of the fish are from the size 0 to 20. The tail end of this chart included sharks, rays, and other bigger fish that are less common to see.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Size%20Hab.png)

The chart above displays the relation between the size of the fish and the depth of water the fish was in. It also shows a relation to the habit type. There is no obivous relation. Not surprising, the majority of the data points are in between the size 0 to 25. The depth seems to have no relation to the size of the fish. The habit type is also spread out between all depths.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Hard%20Hab.png)

The graph displays the relation of the percentage of hard coral found by the fish and the size of the fish with relation to the habit type. The higher the percentage of hard coral, the more come the different types of reefs for habit type show up with Aggregate Reef being the most present. Another thing the graph shows is that the bigger the fish is, the more likely its habit type is either Aggregate Reef or Rock/Boulder, which is not surprising, with those two being the most common habit type.

## Analysis: 
The two methods that I ran on this dataset were Tukey's five numbers and identifying outliers. 
I choose to do Tukey's five numbers to get an overall better idea of what the data contains. 
With the dataset being 23000+ rows, this was an import, so I knew what the data should come out to and what to expect. 
The results of Tukey's five numbers were many means that were to be expected and a few max numbers that brought some concern. 
This led me to also look into the outliers to see if it was an incorrect entry or an unnecessary one to include. 
The result of looking at the outliers is that none of them were miss entered. 
A few of them were not single max numbers but a group with the same number. 
The outliers in size were a shark and a manta ray that are expected to be significant.
