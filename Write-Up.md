# tableau-challenge

For this assigment, I took a look at how gender affects tripduration, number of rides, etc. I also took a broad look at the location of the top start and end stations. 

After downloading the data, I had to slim it down because it was way to large to upload to github. I worked with one Csv off the citibike page, the June 2020 file. In excel, I deleted all lines with a start date after 6/5 since 6/1-6/5 was a work week and would be a good set to look at. Then to further slim the file, I uploaded it into Jupyter notebook and took out customers, genders = 0, and anyone born before 1950. I figured riders who habitually use citibike would give more accurate results. 

Then in Tableau Public:
Worksheet 1: I looked at age and average trip duration in minutes. This was a little surprising as the duration doesnt get much longer with younger riders as you would think. 
Wksht 2/3: Male riders have a slightly longer average trip duration along with a significantly higher number of rides in general. 
All of this was put into a gender demographics dashboard. It's obvious that men are more willing to travel by bike in NYC. We could consider though that, if a female is going to ride a bike, she rides for practically the same average time as a male, just maybe not as spontaneously. This would  make sense with a routine trip to work. 

Wksht 4: A line chart showing rides counts at each hour of a 24 hour day. There is a small spike at 8 AM and a large spike at 5 PM which we can assume are due to commutes. 
Wkst 5/8: These are both bar graphs showing the top 15 most popular start and end stations. Worksheets 6 and 9 are maps of each sets. 
Wksht 7: A bar graph of the average trip durations from each starting point. 

Map Story: Since the largest spike of rides occurs at the end of a work day, I thought that the map of the end stations might include more stops outside of the city versus the start stations more within the city. These maps didnt really prove anything and I think its because I didnt include enough datapoints. The top stops are going to occur in Manahattan since it is the most populated borrough of New york, includingwork spaces and dwellings. The top station overall in both areas is the one in Lenox Hill. I am guessing this may be a popular neighborhood to live in for bike riders. 

