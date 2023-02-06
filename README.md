# Capstone-1-EDA-on-Global-Terrorism-Analysis
This project is based on the database maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START).



**INTRODUCTION**

The Global Terrorism Database(GTD) is an open-source database which contains information about the terrorist activity around the world from 1970 to 2017. Even though we observe these news often we do not give much of an attention to the matter as the news are scattered or we neglect as it is not affecting us. We choose this project so that we can provide some insight on this topic, so that we can gather some valuable data and provide it with some visualization using interactive graphs. Visualizing the data make it more easy to understand where the activity is more, which group we have to look for, what all weapons are trending in the market etc.

After analysing the dataset and making the large csv file into the required shape, using data wrangling, we were able to reduse the dataset into 16 relevent column of datas. The columns contain data based on year, number of organisation, type of attack, weapons used, targeted individuals etc. A total of 14 questions were made which we find to be relevent and important for the analysis. Pandas and Numpy libraries were used to develop the code and different visualization tools like Seaborn , Matplotlib and Plotly were used to plot the graphs.


**PROBLEM STATEMENT**

The GTD includes systematic data on domestic as well as international terrorist incidents that have occured during this period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START), headquartered at the University of Maryland. In this project we have explored and analysed the data and the findings has been visualized using graphs.


**DATASET INFORMATION**

Analysing the dataset gives us clear cut idea of what we are dealing with. Here we observe that the dataset is not perfect as there is a lot number of unfilled datas and many sub columns which is having very limited number of data. The dataset has to be cleaned before using it, under Data Wrangling section we cleaned the data, reduced the dataset into a limited number of colums from which we can easily analyse the data. Deleted unnecessary columns and created new columns from the existing ones, missiing/null value in the column where cleared. After the process of cleaning we took 16 most relevent columns and 181691 rows for the analysis. The columns contain data based on year, number of organisation, type of attack, weapons used, targeted individuals etc.


**ANALYTICS/GRAPHS USED** 

The analytics were done using Python libraries like Pandas and Numpy. First the codes were created for extracting the the required data and for visualizing it graphs were used. Python libraries like Matplotlib.pyplot, seaborn, plotly were used for visualization. Line, bar, and pie charts are mainly used in which line and bar using plotly gives us more of an interactive type graph, when we place the cursor on the graph it will show us the exact value for it. Stacked bar graph is used when we had multiple data to be plotted in the same bar. By using the explode function in pie chart the visualization were made better by taking the part of the whole pie highlighted.



**CONCLUSION**
