# Tableau_CitiBike
![NYC Citibike](https://github.com/SoonaBritney/Tableau_CitiBike/blob/main/img_citibike.JPG "NYC CitiBike")

## Table of Contents
1. Project Overview
2. Resources
3. Objectives
4. Summary
5. Challenge Overview
6. Challenge Objectives 
7. Challenge Summary
8. Limitations

## Project Overview
In this module, we worked with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, we learned how to import, style, and portray data accurately. Then, we created worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Resources
For this project, we used data from the Citi Bike program in New York City. The data we downloaded was contained in a flat file, a CSV. We went to the Citi Bike System Data page. This link took us to an index of trip data, Download Citi Bike trip history data. We scrolled down the list to 201908-citibike-tripdata.csv.zip, then downloaded and saved on our computer.

1. Data Source: [201908-citibike-tripdata.csv](https://www.citibikenyc.com/system-data),  [downloadable files of Citi Bike trip data](https://s3.amazonaws.com/tripdata/index.html)
2. Software: Tableau, Python (Using VS Code or Jupyter Notebook)

## Objectives
1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in Tableau.
3. Use Tableau worksheets to display data in a professional way.
4. Portray data accurately using Tableau dashboards.

## Summary
1. Import data into Tableau 
In Tableau, we have a variety of different options when it comes to data sources. We can have flat files such as CSV, PDF, and TXT files, as well as other data sources like databases and data streams. (These will mostly be SQL databases.)
2. There are two primary ways that Tableau connects to the data we provide: through live data or extract data. Both have their benefits and uses:
3. Live data is primarily databases such as MySQL and Microsoft SQL Server. Live data is just what it sounds like: live data. This type of data is updated every time we view the dashboard, since it’s possible that the data has changed in our database.
4. Extract data is primarily when we use files such as CSV, TXT, or PDF. These files remain unchanged unless we pull a new extract of the data. For example, if we update the file, we would have to update it in Tableau as well. For our analysis, we imported the CSV file, which contains all the data we needed for this project. Therefore, we technically worked with extracted data for our project.
5. Create and style worksheets, dashboards, and stories in Tableau.
6. Use Tableau worksheets to display data in a professional way.
The best visualizations have a clear purpose and work for their intended audience. What will we be trying to say with this dashboard? Are we presenting a conclusion or a key question?
7. In addition to knowing what we're trying to say, it's important to know who we're saying it to. Does our audience know this subject matter extremely well or will it be new to them? What kind of cues will they need? Thinking about these questions before we head into the design phase can help us create a successful dashboard.
8. Designing data visualizations is a huge field within the data industry, with some jobs devoted to making visualizations look better. While we don’t need to know everything about designing worksheets, we should be familiar with some best practices. The Tableau website provides information about best practices for effective dashboards.
9. Portray data accurately using Tableau dashboards.


## Challenge Overview
In this challenge, we put together our final presentation and analysis for investors. We selected the questions we wanted to answer, conducted independent research, crafted our story in Tableau, and then created our written analysis.

### Challenge Background:
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

1. Show the length of time that bikes are checked out for all riders and genders
2. Show the number of bike trips for all riders and genders for each hour of each day of the week
3. Show the number of bike trips for each type of user and gender for each day of the week.

### Challenge Objectives
1. Deliverable 1
- Using Panda, create a code to convert the Tripduration datatyle from integer to DateTime format (e.g. 393 sec  ==> MM:SS format 1970-01-01 00:06:33) 
[NYC_CitiBike_Challege,ipynb](https://github.com/SoonaBritney/Tableau_CitiBike/blob/main/NYC_CitiBike_Challenge.ipynb)
[Old CSV file](https://github.com/SoonaBritney/Tableau_CitiBike/blob/main/NYC_CitiBike_Challenge.ipynb)
[New CSV file - clould not upload to GitHub, since the file size is 169,667 MB](https://github.com/SoonaBritney/Tableau_CitiBike/edit/main/README.md)

2. Delieveble 2
- Import the new CSV (201908-citibike-tripdata_datetime.CSV) into Tableau 
- professionally and accurately visualize the worksheets in Tableau  
(1) There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour (10 pt)
(2) There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender (10 pt)
(3) A heatmap is created showing the number of bike trips for each hour of each day of the week (10 pt)
(4) A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender (10 pt)
(5) A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender (10 pt)

3. Deliverable 3:
- Utilize previously created Tableau worksheets to create a new story.
- Create a Tableau story based on starting a bike-sharing company in Des Moines.


## Challenge Summary

[Here is the live Demo]:

For this portion of the presentation, we worked with a team that is trying to answer core questions about opening a bike-sharing business in Des Moines.

Our goal is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. So we wanted to format our story so it was persuasive. We also wanted to include information about both New York City and Des Moines—after all, the investors will need to understand how the Citi Bike data for New York City applies to our proposal.

Our proposal can be found on tableau public
Our analysis can be found here

## Limitations
One thing to note about Tableau Desktop is that it does cost money every month. However, you can choose to do a 14-day free trial, which allowed us to complete the work in this module without being charged.
