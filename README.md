# Capstone-1-EDA-on-Global-Terrorism-Analysis
This project is based on the database maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START).

![pttp-begum-gucuk-terrorism-poster](https://user-images.githubusercontent.com/124442638/216917557-f1d1c5c1-62ca-4508-a3c2-725e417fafed.jpg)

**INTRODUCTION**

The Global Terrorism Database(GTD) is an open-source database which contains information about the terrorist activity around the world from 1970 to 2017. Even though we observe these news often we do not give much of an attention to the matter as the news are scattered or we neglect as it is not affecting us. We choose this project so that we can provide some insight on this topic, so that we can gather some valuable data and provide it with some visualization using interactive graphs. Visualizing the data make it more easy to understand where the activity is more, which group we have to look for, what all weapons are trending in the market etc.

After analysing the dataset and making the large csv file into the required shape, using data wrangling, dataset was reduced into 16 relevent column of datas. The columns contain data based on year, number of organisation, type of attack, weapons used, targeted individuals etc. A total of 12 questions were made which i found to be relevent and important for the analysis. Pandas and Numpy libraries were used to develop the code and different visualization tools like Seaborn , Matplotlib and Plotly were used to plot the graphs.


**PROBLEM STATEMENT**

The GTD includes systematic data on domestic as well as international terrorist incidents that have occured during this period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START), headquartered at the University of Maryland. In this project i have explored and analysed the data and the findings has been visualized using graphs.


**DATASET INFORMATION**

Analysing the dataset gives the clear cut idea of what we are dealing with. Here it is observed that the dataset is not perfect as there is a lot number of unfilled datas and many sub columns which is having very limited number of data. The dataset has to be cleaned before using it, under Data Wrangling section we cleaned the data, reduced the dataset into a limited number of columns from which we can easily analyse the data. Deleted unnecessary columns and created new columns from the existing ones, missiing/null value in the column where cleared. After the process of cleaning we took 16 most relevent columns and 181691 rows for the analysis. The columns contain data based on year, number of organisation, type of attack, weapons used, targeted individuals etc.

Dataset :-
[csv file for Global Terrorism Analysis](https://drive.google.com/file/d/1rvuudnuWpWDeJLqfLvfjoFkyyN_1CpJ6/view?usp=share_link)



**ANALYTICS/GRAPHS USED** 

The analytics were done using Python libraries like Pandas and Numpy. First the codes were created for extracting the the required data and for visualizing it graphs were used. Python libraries like Matplotlib, seaborn, plotly were used for visualization. Line, bar, and pie charts are mainly used in which line and bar using plotly gives us more of an interactive type graphs, when we place the cursor on the graph it will show us the exact value for it which make it easy for the end user to understand. Stacked bar graph is used when we had multiple data to be plotted in the same bar. By using the explode function in pie chart the visualization were made better by taking the part of the whole pie highlighted.

Some of the graphs used are:

#**Word Cloud**

![Screenshot (19)](https://github.com/cltgoutham/Capstone-1-EDA-on-Global-Terrorism-Analysis/assets/124442638/bc30717e-7c83-4765-b566-f5a1fc978069)

 #**Bar Graph: Using Plotly**
![1](https://user-images.githubusercontent.com/124442638/216913495-54382616-9253-4e8b-93a8-4e10f998c2f0.png)

#**Pie Chart**

![Screenshot (21)](https://github.com/cltgoutham/Capstone-1-EDA-on-Global-Terrorism-Analysis/assets/124442638/ab4cdbae-a304-43ad-a21c-494f7f8ea52d)


![3](https://user-images.githubusercontent.com/124442638/216914530-b92b42f7-0b34-4aeb-8cb9-c7de8c58cc9c.png)


#**Line Graph: Using Plotly**
![2](https://user-images.githubusercontent.com/124442638/216914503-7b48fdd8-b411-4069-84af-e2fad1465f04.png)



 #**Stacked Bar Graph**
![4](https://user-images.githubusercontent.com/124442638/216914548-56d4cf91-f552-42e7-b7cb-d56e5a7fe020.png)


**CONCLUSION**

The project was completed by answering the questions and ploting the graphs.



