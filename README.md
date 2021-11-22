# Data-115-Fall-2022
visualization


[caption label](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/fish%20habit.png)


This shows the differnt habit types and how many times they show up in the data. 


[caption label](https://raw.githubusercontent.com/gabiisaak/Data-115-Fall-2022/main/fish%20depth.png)


This shows the relshinship between the min and max depth the fish was found in and the habit habit type.

Motivation: You should describe the question you set out to answer at the start of the project or
what led you to the specific dataset that you selected.
When starting this project I wanted to look into coral. I thought maybe something about coral bleaching or common types of coral in differnt regins. While looking for data about coral I came across this data set about hawaiian fish. My family loves to go to hawiia and snokel so I could relate to the fish names I was seeing and all the data. This data also contained info on the habit types of each fish alonf with tons of other data. From looking at this data set I came up with a new question of weather there could be a common facter of the type of habit type to another aspect of the data like size, depth, or species.

•Data Process: The centerpiece of your writeup should be a comprehensive discussion of your
process for sourcing, collecting, cleaning, and transforming the raw data into your final dataset. The
instructions should be clear enough that someone else could reproduce your process based on just the
ReadMe file to obtain the same final results. Note that this doesn’t necessarily have to be more than
a couple of sentences but it should be complete.
To start off with I downloaded my dataset into an excle file from National Oceanic and Atmospheric Administration site. The dataset need to no cleaning in excle, the only step I had to take was saving it as a CSV file. I then uploaded the data into RStudio. Once the dataset was into RStudio I deleted 27 columes from the main dataset. The dataset had a ton of infomation that some of it was not relivent to what I was looking at so to make it easyier to read all the data if I got rid of a few clomnes. My next step was to run a summary of my new dataset. This was to try to iddentfiy any outliers or concertins in the data. The summary bruoght up a few max numbers that I wanted to look into. I looked into the count, sand, size, MA, and lmax. Count and size was the only ones that I foudnd any concer with as being an outlier. Looking closer in thhe rows of data with the iutliers the numbers made sense so I decided to keep them in the dataset. From there the dataset was to big to take a closer look in to I took a random sample of a 1000 to look fourth into. The orginal dataset had 23000+ rows of data so 1000 is just barly 4% of the whole data but this 4% still includes all ten of the habit types to look into and around 62% of the species in the orginal dataset.

•Visualization: The ReadMe should contain at least one visualization summarizing the data. The
visualizations should follow the principles of good figure design and be sufficiently documented to
explain what they are demonstrating.


•Analysis: Finally, the ReadMe should describe the results of at least one method from this course
that you applied to the dataset and what you learned from it. This can be anything from a simple EDA
technique like identifying outliers, making a box plot of a column, evaluating the summary statistics
(Tukey’s 5 numbers), to one of the regression models from supervised learning, or one of the clustering
methods from unsupervised learning. This is not an exhaustive list of possibilities and as with the
previous components doesn’t need to be long or drawn out.
