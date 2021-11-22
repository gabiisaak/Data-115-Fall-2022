# Data-115-Fall-2022

## Motivation: 
When starting this project I wanted to look into coral. 
I thought maybe something about coral bleaching or common types of coral in differnt regins. 
While looking for data about coral I came across this data set about hawaiian fish. 
My family loves to go to hawiia and snokel so I could relate to the fish names I was seeing and all the data. This data also contained info on the habit types of each fish alonf with tons of other data. 
From looking at this data set I came up with a new question of weather there could be a common facter of the type of habit type to another aspect of the data like size, depth, or species.

## Data Process:
To start off with I downloaded my dataset into an excle file from National Oceanic and Atmospheric Administration site. The dataset need to no cleaning in excle, the only step I had to take was saving it as a CSV file. I then uploaded the data into RStudio. Once the dataset was into RStudio I deleted 27 columes from the main dataset. The dataset had a ton of infomation that some of it was not relivent to what I was looking at so to make it easyier to read all the data if I got rid of a few clomnes. My next step was to run a summary of my new dataset. This was to try to iddentfiy any outliers or concertins in the data. The summary bruoght up a few max numbers that I wanted to look into. I looked into the count, sand, size, MA, and lmax. Count and size was the only ones that I foudnd any concer with as being an outlier. Looking closer in thhe rows of data with the iutliers the numbers made sense so I decided to keep them in the dataset. From there the dataset was to big to take a closer look in to I took a random sample of a 1000 to look fourth into. The orginal dataset had 23000+ rows of data so 1000 is just barly 4% of the whole data but this 4% still includes all ten of the habit types to look into and around 62% of the species in the orginal dataset.

## Visualization: 
The ReadMe should contain at least one visualization summarizing the data. The
visualizations should follow the principles of good figure design and be sufficiently documented to
explain what they are demonstrating.
![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Hab.%20Num..png)

This bar chart shows the count of the differnt habit types. It is to show how common the differnt habit types are. as you can see Aggregate Reef and Rock/Boulder are by far the most common.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Wat.%20Dep.%20Hab..png)

This chart shows the relation od the min and max deth that the fish was found in in relation to the habit type. It shows a liner relaship between the min and max depth with a little varinaces in the lower min depth. There is not an obvisy relashiption between the habit type and min or max depth.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Size%20Num..png)

The bar chart shows the frequncey of the size of fish in the dataset. As show the majorty of the fish are from the size 0 to 20. The tail end of this chart included sharks, rays, and other bigger fish that are less common to see.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Size%20Hab.png)

The chart above displays the relashion between the size of the fish and the depth of water the fish was in. It also shows a relashion to the habit type. There is no obivous relation. Not suprising the majority of the data pionts are in between the size 0 to 25. The depth seems to have no relation to the size of the fish. The habity type is also spread out between all depths.

![alt text](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/Hard%20Hab.png)

The graph displays the relation of the percentage of hard colal found by the fish and the size of the fish with relation to the habity type. The higher the precage of hard coral the more come the differnt type of reefs for habity type show up with Aggregate Reef beiung the most present. Another thing the geaph shows is that the bigger the fish is the more likey its habity type is either Aggregate Reef or Rock/Boulder. wicth is not supprise with those two being the most common habity type.


•Analysis: Finally, the ReadMe should describe the results of at least one method from this course
that you applied to the dataset and what you learned from it. This can be anything from a simple EDA
technique like identifying outliers, making a box plot of a column, evaluating the summary statistics
(Tukey’s 5 numbers), to one of the regression models from supervised learning, or one of the clustering
methods from unsupervised learning. This is not an exhaustive list of possibilities and as with the
previous components doesn’t need to be long or drawn out.
