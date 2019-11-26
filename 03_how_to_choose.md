# How to Choose the Type of Data Visualization

## Contents:

### 1.	Questions to Help Determine the Best Type of Visualization to Use

### 2.	General Types of Visualization – Description and/or Example and Key Uses

   a.	Text

   b.	Tables and Heatmaps

   c.	Graphs

### 3.	Types of Graphs – Description and/or Example and Key Uses

   a.	Line
   
   b.	Slopegraph
   
   c.	Bar
   
   d.	Area
   
   e.	Scatterplot
   
   f.	Dot Plots
   
   g.	Strip Plots
   
   h.	Vertical Box & Whisker Plots
   
   i.	Small Multiples aka Trellis charts

   j.	Sparklines

   k.	Maps

### 4.	Visualizations to Avoid

   a.	Pies and Donuts 
   
   b.	3D 
   
   c.	Double-Axis 
   
   d.	Radar charts 
   
   e.	Violins
   

## Questions to help you determine which type of visualization to use:

*	How will the information be used?

*	Which visualization will allow you to clearly convey your message?

*	What is the most direct display of information that people need?


## General Types of Visualization – Description and/or Example and Key Uses

   ### **Text**
   
      Example: **21%**

      Simple text is useful when you have one or two numbers to show.

   ### **Tables and Heatmaps**
   
       *Tables*
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/TABLE.PNG "Table Example")

       Tables are likely the most useful in the following situations:
       * When the goal of the visualization is to look up individual values
       * When the user needs a one-to-one comparison or to compare pairs of related variables
       *	When the goal of the visualization is to communicate to a diverse audience where each will look for their row or column of interest 
       *	Information needs to be read, such as across rows or down columns
       *	Precision is important
       *	You have multiple data sets with different units of measure
       *	You want to combine summary and detailed information
       

       Tables are likely too detailed and time consuming for your reader to use during a live presentation.

       *Heatmaps*
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/HEATMAP.PNG "Heatmap Example")

       Definition: a heatmap is a variation on a table emphasizing the magnitude of the entries using intensity of color, such as through conditional formatting in Microsoft Excel.

       Heatmaps can ease the reading of tables for low and high values.

   ### **Graphs**
   
       Graphs are likely the most useful in the following situations:
       *	The goal of the visualization is to examine large datasets at once
       *	When the primary goal of the visualization is to discern patterns, an overall shape, and/or relationships, including trends over time 
       *	When the viewer is interested in exceptions within patterns
       *	When the goal of the visualization is to examine a set of quantitative values as a whole
       *	When the goal of the visualization is to see the differences and similarities between two datasets

## Types of Graphs – Description and/or Example and Key Uses

   ### **Line**
   
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/LINE.PNG "Line Graph Example")
       Line graphs imply continuous data or a connection between the points. Line graphs can include a shaded range or confidence interval around an average.

       Line graphs are likely the most useful when:
       *	Showing data over time 
       *	Combining a deviation relationship (such as a difference from plan) and time series
       *	Viewing cumulative distributions or multiple related histograms on a single graph, especially for a limited number of distributions; also called frequency polygons.

   ### **Slopegraph**
   
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/SLOPEGRAPH.PNG "Slopegraph Example")

       Slopegraphs can be useful when showing data for just two time periods and you want to easily show relative decreases, increases or differences across categories between the two time period points.

       Slopegraphs might not be indicated if many of the lines are overlapping.

   ### **Bar Charts**

       #### ***Vertical Bar Chart***
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/VERTICAL_BAR.PNG "Vertical Bar Chart Example")

       Vertical bar charts are useful for time series graphs where you want to focus on the comparison between values of individual points, rather than on the overall pattern of values over time. Vertical bar charts can also be useful in showing deviation relationships (e.g., difference from plan) at a point in time. 

       Multiple series bar charts can be useful, but too many series may obscure the insights you are trying to show. The relative order of categorization is important. See example in attached Excel workbook. 

       #### ***Stacked Vertical Bar Charts*** 
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/STACKED_VERTICAL_BAR.PNG "Stacked Vertical Bar Chart Example")

       Use caution in using stacked vertical bar charts, as it can be hard to compare sizes or values, especially if the baseline is different. Thus, stacked vertical bar charts are best if there’s a key category you are focusing on and that it’s positioned as the bottom set of bars as in the example. Consider using absolute numbers in stacked vertical bar charts or using stacked vertical bars that each sum to 100%.

       #### ***Waterfall Chart*** 
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/WATERFALL.PNG "Waterfall Chart Example")

       Waterfall charts are useful for emphasizing the pieces of a stacked vertical bar chart or to show a starting point, incremental increases and decreases, and an ending point.

       #### ***Histogram*** 
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/HISTOGRAM.PNG "Histogram Example")

       A histogram is a vertical bar chart used to display a distribution.

       #### ***Horizontal Bar***
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/HORIZONTAL_BAR.PNG "Horitzontal Bar Chart Example")

       Horizontal bar charts are great for displaying categorical data, especially if focusing on the largest or smallest category is important. If that’s the case, be sure to sort from largest or smallest respectively to show ranking relationships between the categories.

       #### ***Stacked Horizontal Bar Chart*** 
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/STACKED_HORIZONTAL_BAR.PNG "Stacked Horizontal Bar Chart Example")

       Stacked horizontal bar charts displaying absolute numbers or individual bars that sum to 100% can be useful for:
       *	Showing parts of a whole
       *	Featuring totals and providing an approximate sense of the parts

       As an alternative, consider pulling the stacked bars apart into a single ranking horizontal bar chart whose percentage totals add to 100%.

   ### **Area**
   
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/AREA.PNG "Area Chart Example")

       Area graphs can be useful for comparing numbers of much different magnitudes.

   ### **Scatterplot**
   
       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/SCATTERPLOT.PNG "Scatterplot Example")

       Scatterplots are useful when you are interested in the relationship between two variables or correlations between items. Use care when using scatterplots as they are not well understood by all audiences. Consider using two horizontal bar charts side-by-side organized in the same order, also called a table lens as an alternative.

   ### **Dot Plots**
   
       Dot plots are useful for nominal comparative relationships where you want to highlight differences that would be hard to see in a bar graph that must have a zero baseline. These are also useful for showing time series data not representing consistent intervals of time.

       Example ![alt text](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/DOT_PLOT.PNG "Dot Plot Example")

   ### **Strip Plots**
   
       Strip plots are useful for displaying a distribution of relatively few points when the individual values are important to show. Vertical strip plots can be used to show distributions of relatively few points over time.

   ### **Vertical Box & Whisker Plots**
   
       Vertical box & whisker plots display a large amount of data in a single box: highest and lowest values, the spread of values from highest to lowest, the median, the spread from the 25th to 75th percentiles, and the 25th and 75th percentiles.

       Vertical box & whiskers plots are valuable in showing distribution changes over time. Use box & whisker plots with care as percentiles are not readily understood by all audiences; consider simplifying to a high, median, and low box plot without whiskers

   ### **Small Multiples or Trellis Charts**
   
       Small multiples or trellis charts can be useful for finding pattern in very complex data.

   ### **Sparklines**
   
              Sparklines can be valuable for seeing trends or highlighting minimum and maximum values.

   ### **Maps**
   
       Maps are valuable for displaying geospatial information. Points on maps show the precise location of information. You can use varying sizes or intensities of points on a map to increase the information included.

       If there are too many values to show individual points on a map, you can use color intensity for various geographical regions or lines of various thicknesses to show information related to routes.

## Visualizations to Avoid

 ### **Pie and Donut Charts**
 
       It is not easy for the eye to accurately compare relative sizes of pie slices; consider horizontal stacked bar charts instead.

 ### **3D Graphs and Elements**

       It is not easy to compare relative values three dimensionally. Consider bubble plots with varying sized bubbles for a 3rd dimension and varying color intensities for a 4th dimension but use care in readability for all.

 ### **Double-Axis**

       Charts with two different axes can take too much time to interpret. Consider not showing second y-axis, but labeling the data points directly instead. Alternatively, consider separating the graphs vertically with the same x-axis and different y-axes.

 ### **Radar Charts**

       Radar charts are too confusing for the most viewers.
 
 ### **Violin Plots**

       Because these plots look like Christmas ornaments or body parts, they can distract the audience from the information they provide. Consider using stacked histogram
