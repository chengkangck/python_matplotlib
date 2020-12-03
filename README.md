# python_matplotlib
1. Data analysis and visualization concepts

Data analysis refers to the process of analyzing a large amount of collected data with appropriate statistical analysis methods, extracting useful information and forming slices to analyze the data in detail and summarize the process

Collect data-  extract information- form samples

Data visualization: Use graphics to display data, and intuitively observe the relationship between data is the data visualization process.

Data visualization: Use graphics to display data, and intuitively observe the relationship between data is the data visualization process.

2. Data analysis visualization process

　　Define analysis goals---data collection and preprocessing---data analysis and mining---data visualization

　　Data cleaning: refers to the last procedure to find and correct identifiable errors in data files, including checking data consistency, handling invalid values and default values, etc.
 
3. Common data visualization forms and tools

Common forms of visualization:

　　Basics: Statistical graphs (histogram, line graph, pie graph)

　　　　　 distribution diagram (heat diagram, scatter diagram, bubble diagram)
     
     
 Common tools:

　　Analysis tools: pandas, Scipy, numpy, sklearn

　　Drawing tools: matplotlib, Pychart, reportlab

　　Platform tools: Jupyter Notebook, Pycharm
  
  
Foundation drawing:

　　 Histogram: The distribution of data can be transmitted intuitively. Function: plt.hist(data, bins)

　　Bar graph: Show the size of the same type of data and the difference between the data. Function: plt.bar(data,datatype)

　　 Line chart: usually shows continuous data that changes with time, so it is very suitable for displaying the trend of data within a period. Function: plt.plot(X,Y)

　　Pie chart: It is often used to display the size of each item in a data series and the proportion of the sum of each item. Function: plt.pie(data,datatype)

Scatter chart: refers to the distribution of data points on the plane of the rectangular coordinate system in the regression analysis. The scatter chart represents the general trend of the dependent variable changing with the independent variable. Based on this, you can choose a suitable function to simulate the data points. Together. Function: plt.scatter(data_X, data_Y)

Box plot: also known as box-and-whisker plot, box plot, is a statistical chart used to show the dispersion of a group of data, mainly used to reflect the characteristics of the original data, the main display values ​​are: upper edge and lower edge Outliers (points) in the upper quartile of the median and lower quartile. Function: plt.boxplot(data)

　　Polar graph: used to show the distribution of data in polar coordinates, mostly used to display data with a little periodicity. Function: plt.subplot(111, projection ='polar').plot(theta, r)

　　 Ladder chart: It is a method of expressing numerical changes in irregular and intermittent steps. It can not only reflect the trend of data development like a line chart, but also reflect the duration of the data state. Function: plt.step(year, height)

Advanced graph:

　　 Stacked chart: It is often used to comprehensively display the trend of different categories of indicators and the trend of the sum. Function: plt.bar(datatype, data_y, bottom = data_x, color ='r', label ='name')

　　 Block diagram: Different data sets can be displayed in blocks to facilitate comparison of the level of a specific attribute of similar data. Function: plt.bar(datatype, data_y, bottom = data_x, color ='r', label ='name')

　　 Bubble chart: It can be used to show the relationship between three variables. Function: plt.bar(x, data_x, label="name", fc ='r', width = width)
