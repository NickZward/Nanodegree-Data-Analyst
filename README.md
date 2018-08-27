# Nanodegree-Data-Analyst
Projects for my [Udacity Data Analyst Nanodegree](https://eu.udacity.com/course/data-analyst-nanodegree--nd002)

### Project 1: Explore Weather Trends
In this project, I will analyzed local and global temperature data and compared the temperature trends where I live to overall global temperature trends. My goal was to create a visualization and prepare a write up describing the similarities and differences between global temperature trends and temperature trends in the closest big city to where I live. To do this, I followed the steps below:

- Extract the data from the database. I had to export the temperature data for the world as well as for the closest big city to where I live. There was a list of citites in the city_list table. In order to interact with the database I had to write a SQL query.

- Download the CSV file and open it in Excel in order to create a line chart that compared my city's temperatures with the global temperatures. I had to make sure to plot the moving average rather than the yearly averages in order to smooth out the lines, making trends more observable.

- After creating the line chart, I made observations about the similarities and differences between the world averages and my city’s averages, as well as overall trends. 

[Link to report](https://github.com/NickZward/Nanodegree-Data-Analyst/blob/master/Project%201/Project%201%20report.pdf)

[Data used](https://github.com/NickZward/Nanodegree-Data-Analyst/blob/master/Project%201/results.csv)

### Project 2: Investigate a Dataset
For this project I chose one of Udacity's curated datasets and investigated it using NumPy and Pandas. The database I investigated was about medical appointment no show. The database contained 300k medical appointments and its 15 variables (characteristics) of each. The most important one if the patient show-up or no-show the appointment. To answer some questions using this database I had to go through the entire data analysis process, starting by posing a question and finishing by sharing my findings.

After completing the project, I felt comfortable with:

- Knowing all the steps involved in a typical data analysis process.
- Posing questions that can be answered with a given dataset and then answering those questions.
- Knowing how to investigate problems in a dataset and wrangle the data into a format you can use.
- Have practice communicating the results of your analysis.
- Be able to use vectorized operations in NumPy and pandas to speed up your data analysis code.
- Be familiar with pandas' Series and DataFrame objects, which let you access your data more conveniently.
- Know how to use Matplotlib to produce plots showing your findings.

[Link to report](https://github.com/NickZward/Nanodegree-Data-Analyst/blob/master/Project%202/Investigate%20a%20dataset%20-%20No-show.ipynb)

[Data used](https://www.kaggle.com/joniarroba/noshowappointments)
