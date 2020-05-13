# How to Choose the Type of Data Visualization
Now that we have established the audience and the message, it is time to design the visualizations. This section will help identify which forms are best, depending on the data and message. 

### 1.	Determine the Best Type of Visualization to Use
Many authors have described which graph to choose depending on the situation and what is intended to be shown. The designer can experiment and decide which type of visualization to use. The guide below should help, although the ultimate judge will be the audience and how well they get the message. Try creating multiple versions for a given task, and ask a trusted colleague for feedback about which works best for the intended message. 


### 2.	Types of Visuals and Key Uses

    Line
      1. Standard Line Graph - Time series and trends, parts-to-a-whole, distribution, 
      2. Slopegraph - comparison of multiple variables at once, for two points in time 
      3. Sparklines - small version of minimalist line graph, shows changes in value over time at-a-glance
      
    Bar (Verical or Horizontal)
      1. Ranking or simple value comparison
      2. Parts-to-a-whole, including stacked bars to show shares of sub-categories within a categorical variable
      3. Histogram - distribution of values
         
    Scatterplot 
      1. Exploratory data analysis
      2. Correlation between two variables
      3. Time series
            
   Text - when a key single value is all that needs to be communicated. 

   Table - best to be used only for a lookup reference table rather than communicating a message, since tables get cluttered so easily. However, a heatmap table is a variation on a table with color-intensity-encoded cells to highlight high and low values, however, can be used effectively to communicate a message

Small Multiples (i.e., Trellis charts) - can be used with any type of data vis, to compare many variables or categories at once, to observe relationships or correlation of each combination of categories at the same time.
   
 Of course there are others, such as maps to compare states, box plot and violin charts to show ditributions, etc.

### 3.	Visualizations to Avoid
Many common visuals do not actually communicate the message effectively. Some reasons include scientific understanding about how the human eye works and what is most quickly, easily, and effectively deciphered. Below are some common graph types, with a brief description of why they should be avoided.

   a.	Pie, Donuts, and Radar - the human eye is not well suited to decipher angle and area
   
   b.	3D - due to the perspective, these graphs easily convey misleading information
   
   c.	Area - the human eye does not decipher area effectively
   
   d. Double-Axis - too much for a reader to process quickly and effectively 
   
     
### Questions to help determine which type of visualization to use:

*	What is the **simplest** way the information can be conveyed?

*	Have I tried other ways of displaying the information?

*	Have I shown a draft visualization to another person for feedback on how effective it conveys the message?


## EXAMPLES

   ### Text
   
      Example: **21%**

      Simple text is useful when you have one or two numbers to show.
    
   #### Tables
             
   ![Table Example](Choosing%20Pics/TABLE.PNG)

   #### Heatmaps
       
       Heatmaps can ease the reading of tables for low and high values.
       ![Table Example](Choosing%20Pics/HEATMAP.PNG)
  
   ### Line
      ![Line Example](Choosing%20Pics/LINE.PNG)
       Example ![Line Graph Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/LINE.PNG)
       Line graphs imply continuous data or a connection between the points. Line graphs can include a shaded range or confidence interval around an average.

       Line graphs are likely the most useful when:
       *	Showing data over time 
       *	Combining a deviation relationship (such as a difference from plan) and time series
       *	Viewing cumulative distributions or multiple related histograms on a single graph, especially for a limited number of distributions; also called frequency polygons.

   ### Slopegraph
     ![Slopegraph Example](Choosing%20Pics/SLOPEGRAPH.PNG)
       Example ![Slopegraph Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/SLOPEGRAPH.PNG)

       Slopegraphs can be useful when showing data for just two time periods and you want to easily show relative decreases or increases among several categories.

       Slopegraphs can get cluttered, however, there are many overlapping lines.

   
   #### Vertical Bar Chart
      ![Slopegraph Example](Choosing%20Pics/VERTICAL_BAR.PNG)
       Example ![Vertical Bar Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/VERTICAL_BAR.PNG)
       

       Vertical bar charts are useful for time series graphs where you want to focus on the comparison between values of individual points, rather than on the overall pattern of values over time. Vertical bar charts can also be useful in showing deviation relationships (e.g., difference from plan) at a point in time. 

       Multiple series bar charts can be useful, but too many series may obscure the insights you are trying to show. The relative order of categorization is important. See example in attached Excel workbook. 

   #### Stacked Vertical Bar Charts
   
       Example ![Stacked Vertical Bar Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/STACKED_VERTICAL_BAR.PNG)

       Use caution in using stacked vertical bar charts, as it can be hard to compare sizes or values, especially if the baseline is different. Thus, stacked vertical bar charts are best if there’s a key category you are focusing on and that it’s positioned as the bottom set of bars as in the example. Consider using absolute numbers in stacked vertical bar charts or using stacked vertical bars that each sum to 100%.

   #### Waterfall Chart
   
       Example ![Waterfall Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/WATERFALL.PNG)

       Waterfall charts are useful for emphasizing the pieces of a stacked vertical bar chart or to show a starting point, incremental increases and decreases, and an ending point.

   #### Histogram
   
       Example ![Histogram Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/HISTOGRAM.PNG

       A histogram is a vertical bar chart used to display a distribution.

   #### Horizontal Bar
   
       Example ![Horizontal Bar Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/HORIZONTAL_BAR.PNG)

       Horizontal bar charts are great for displaying categorical data, especially if focusing on the largest or smallest category is important. If that’s the case, be sure to sort from largest or smallest respectively to show ranking relationships between the categories.

   #### Stacked Horizontal Bar Chart
   
       Example ![Stacked Horizontal Bar Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/STACKED_HORIZONTAL_BAR.PNG)

       Stacked horizontal bar charts displaying absolute numbers or individual bars that sum to 100% can be useful for:
       *	Showing parts of a whole
       *	Featuring totals and providing an approximate sense of the parts

       As an alternative, consider pulling the stacked bars apart into a single ranking horizontal bar chart whose percentage totals add to 100%.

   ### Area
   
       Example ![Area Chart Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/AREA.PNG)

       Area graphs can be useful for comparing numbers of much different magnitudes.

   ### Scatterplot
   
       Example ![Scatterplot Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/SCATTERPLOT.PNG)

       Scatterplots are useful when you are interested in the relationship between two variables or correlations between items. Use care when using scatterplots as they are not well understood by all audiences. Consider using two horizontal bar charts side-by-side organized in the same order, also called a table lens as an alternative.

   ### Dot Plots
   
       Dot plots are useful for nominal comparative relationships where you want to highlight differences that would be hard to see in a bar graph that must have a zero baseline. These are also useful for showing time series data not representing consistent intervals of time.

       Example ![Dot Plot Example](https://github.com/cliffordlau/cas-data-vis-wp/blob/master/Choosing%20Pics/DOT_PLOT.PNG)

   ### Strip Plots
   
       Strip plots are useful for displaying a distribution of relatively few points when the individual values are important to show. Vertical strip plots can be used to show distributions of relatively few points over time.

   ### Vertical Box & Whisker Plots
   
       Vertical box & whisker plots display a large amount of data in a single box: highest and lowest values, the spread of values from highest to lowest, the median, the spread from the 25th to 75th percentiles, and the 25th and 75th percentiles.

       Vertical box & whiskers plots are valuable in showing distribution changes over time. Use box & whisker plots with care as percentiles are not readily understood by all audiences; consider simplifying to a high, median, and low box plot without whiskers

   ### Small Multiples or Trellis Charts
   
       Small multiples or trellis charts can be useful for finding pattern in very complex data.

   ### Sparklines
   
              Sparklines can be valuable for seeing trends or highlighting minimum and maximum values.

   ### Maps
   
       Maps are valuable for displaying geospatial information. Points on maps show the precise location of information. You can use varying sizes or intensities of points on a map to increase the information included.

       If there are too many values to show individual points on a map, you can use color intensity for various geographical regions or lines of various thicknesses to show information related to routes.

## Visualizations to Avoid

 ### Pie and Donut Charts
 
       It is not easy for the eye to accurately compare relative sizes of pie slices; consider horizontal stacked bar charts instead.

 ### 3D Graphs and Elements

       It is not easy to compare relative values three dimensionally. Consider bubble plots with varying sized bubbles for a 3rd dimension and varying color intensities for a 4th dimension but use care in readability for all.

 ### Double-Axes

       Charts with two different axes can take too much time to interpret. Consider not showing second y-axis, but labeling the data points directly instead. Alternatively, consider separating the graphs vertically with the same x-axis and different y-axes.

 ### Radar Charts

       Radar charts are too confusing for the most viewers.
 
 ### Violin Plots

       Because these plots look like Christmas ornaments or body parts, they can distract the audience from the information they provide. Consider using stacked histogram


(MOVED FROM PREV SECTION)
#### Tables

 Tables are likely the most useful in the following situations:
       * When the goal of the visualization is to **look up individual values**
       * When the user needs a one-to-one comparison or to compare pairs of related variables
       *	When the goal of the visualization is to communicate to a diverse audience where each will look for their row or column of interest
       *	Information needs to be read, such as across rows or down columns
       *	Precision is important, as opposed to a general sense of the data from a graph
       *	You have multiple data sets with different units of measure
       *	You want to combine summary and detailed information
       
       Tables are likely too detailed and time consuming for your reader to use during a live presentation.
       
       
 ### Graphs
   
       Graphs are likely the most useful in the following situations:
       *	The goal of the visualization is to examine large datasets at once
       *	When the primary goal of the visualization is to discern patterns, an overall shape, and/or relationships, including trends over time 
       *	When the viewer is interested in exceptions within patterns
       *	When the goal of the visualization is to examine a set of quantitative values as a whole
       *	When the goal of the visualization is to see the differences and similarities between two datasets
