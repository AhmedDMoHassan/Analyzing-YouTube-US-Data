# YouTube Data US Dataset

> ***Please note: every image here is just a small fraction of the reality of the visuals, so please visit the links to engage in an interactive
environment with the visuals and download the data.***

## **First Insight “number of videos uploads and views in each state”:**

Link to the Dashboard: https://public.tableau.com/views/numberofvideosuploadsandviewsineachstate/eachstatenumberofvideosuploadsandnumberofviews?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 

![image](https://user-images.githubusercontent.com/105866130/218258238-25d79cd7-0b70-4bab-8e5b-90c2bd640a3c.png)


Finding/summary: in this dashboard, we could clearly see in each state and over the years the distribution of both the number of the number of views and the number of uploads with each category.in the right corner, It is clear from the relation between the publish year and the median number of views that there was a decline in the number of views from 2006 to 2010, then small fluctuations occurred till 2016, and finally a huge jump in the views till 2018; moreover, the highest number of views was in 2006 with 258506 views in the entertainment category in the “NV (Nevada)” state.

Design: I chose to build the line chart with the median and the moving average to decrease the noise of the graph and make it more comprehensible. Plus, I added the option of making the year filter available to every graph and make the map a filter to see the distribution of the categories “likes to dislikes proportion” and the “median number of views” for each state to make the dashboard more interactive. likes to dislikes proportion is a calculated field that I built to assess in my work.

## **Second Insight “Relation Between N. of Views and AVE N. of Comments”:**

Link to my second worksheet “Line chart”: https://public.tableau.com/views/RelationBetweenN_ofViewsandAVEN_ofComments/Relationbetweenn_ofviewsandaven_ofcomments?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 

![image](https://user-images.githubusercontent.com/105866130/218258282-133eeca0-ee91-4c36-9a9e-64b64c4619e1.png)

Finding/summary: From the Line Chart, we could see that over the years the general trend was a positive (direct) relation between the number of views and the average number of comments. However, there was a huge fluctuation area in the number of comments till the number of views reached 40 million views. 

Design: I chose to use the Moving average to decrease the noise in the line chart but maintaining the trend. I used the publishing years filter to look closely on this trend and how it started increasing then decreasing. Also, I removed the SUM aggregation on the Views to plot it as discrete. I chose to use a Line Chart as it is the best to see the relation between to variables.

## **Third Insight “US Map with N. Of Both Likes and Dislikes and N. Of Categories Uploads”:**

Link to my third worksheet “Map”: https://public.tableau.com/views/USMapwithN_OfBothLikesandDislikesandN_OfCategoriesUploads/USmapwiththenumberofbothLikesanddislikes?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 

![image](https://user-images.githubusercontent.com/105866130/218258352-65de3064-e6de-44b0-93db-e8dc75409d67.png)

Finding/summary: from the map, we could clearly see that “CA (California)” is the highest state in likes, with about 106 million like for the uploaded videos and only 3.6 million dislikes, and California pioneer category is entertainment. Plus, it is noted that “MS (Mississippi State)” is the lowest in Likes, only 29561 likes, and the leading (only) category there is also entertainment. 

Design: I chose to use the map as it is the best to represent the states. Also, I used A ToolTip to visualize the number of videos uploads of each category for each state. Besides, I used the filter of months to see the distributions of the uploads, likes, and dislikes over the months.

