# How to Choose the Type of Data Visualization
Now that we have established the audience and the message, it is time to design the visualizations. This section will help identify which forms are best, depending on the data and message. 

### 1.	Determine the Best Type of Visualization to Use
Many authors have described which graph to choose depending on the situation and what is intended to be shown. The designer can experiment and decide which type of visualization to use. The guide below should help, although the ultimate judge will be the audience and how well they get the message. Ask yourself: "What is the message?". Try creating multiple versions for for that message, and ask a trusted colleague for feedback about which works best for the intended message.


### 2.	Overview of Main Types of Visuals and Key Uses

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

   Table - best to be used only for a lookup reference table rather than communicating a message, since tables get cluttered so easily. However, a heatmap table is a variation on a table with color-intensity-encoded cells to highlight high and low values, however, can be used effectively to communicate a trend or relationship as a message.

   Small Multiples (i.e., Trellis charts) - can be used with any type of data vis, to compare many variables or categories at once, to observe relationships or correlation of each combination of categories at the same time.
   
 Of course there are others, such as maps to compare states, box plot and violin charts to show ditributions, etc.

### 3.	Visualizations to Avoid
Many common visuals do not actually communicate the message effectively. Some reasons include scientific understanding about how the human eye works and what is most quickly, easily, and effectively deciphered. Below are some common graph types, with a brief description of why they should be avoided.

   a.	Pie and Donuts - the human eye can not accurately compare angles and area of pie or donut slices. Try stacked bar.
    
   b.	3D - due to the perspective, the human eye cannot accurately compare relative values three dimensionally. Try using color.

   c.	Area - the human eye does not decipher area effectively. Try vertical bars.
   
   d.   Double-Axis - too much for a reader to process quickly and effectively. Try separating the graphs vertically with the same x-axis and different y-axes.

     
### Questions to help determine which type of visualization to use:

*	What is the **simplest** way the information can be conveyed?

*	Have I tried other ways of displaying the information?

*	Have I shown a draft visualization to another person for feedback on how effective it conveys the message?


## EXAMPLES

   ![Text](Choosing%20Pics/TABLE.PNG)
   Simple text is useful when you have one or two numbers to show.
   
          
  ![Table](Choosing%20Pics/TABLE.PNG)

 
  ![Heatmap](Choosing%20Pics/HEATMAP.PNG)    
   
   Heatmaps can ease the identification of low and high values, or reveal data patterns.
   
   ![Line](Choosing%20Pics/LINE.PNG)
       
Line graphs imply continuous data or a connection between the points. Line graphs can include a shaded range or confidence interval around an average.

Line graphs are best for:
       * Time series
       * Combining a deviation relationship (such as a difference from plan)
       * Viewing a (smoothed) cumulative distribution, or multiple related histograms on a single graph.

   ![Sparklines](Choosing%20Pics/Sparklines.PNG)
   
   Sparklines can be valuable for seeing trends or highlighting minimum and maximum values. Typically used in a minimalist way.
              
   ![Slopegraph](Choosing%20Pics/SLOPEGRAPH.PNG)
   
Slopegraphs can be useful when showing data for just two time periods and you want to easily show relative decreases or increases among several categories.

Slopegraphs can get cluttered, and should hence be avoided when there are too many overlapping lines.

  ![Vertical Bar Example](Choosing%20Pics/VERTICAL_BAR.PNG)
       
Vertical bar charts are useful for time series graphs where you want to focus on the comparison between values of individual points, rather than on the overall pattern of values over time. Vertical bar charts can also be useful in showing deviation relationships (e.g., difference from plan) at a point in time. 

Avoid using more than 3 sub-categories within bars, as this may obscure the intended message. 

   #### Stacked Vertical Bar Charts
   ![Stacked Vertical Bar Example](Choosing%20Pics/STACKED_VERTICAL_BAR.PNG)
       
Use caution in using stacked vertical bar charts, as it can be hard to compare sizes or values, especially if the baseline for a given 'stack' is not the same. Thus, stacked vertical bar charts are best if there’s a key category you are focusing on and that it’s positioned as the bottom set of bars as in the example. Consider using absolute numbers in stacked vertical bar charts or using stacked vertical bars that each sum to 100%.

  
   #### Histogram
   ![Histogram](Choosing%20Pics/HISTOGRAM.PNG)
       
       A histogram is a vertical bar chart used to display a distribution.

   #### Horizontal Bar
   ![Horiz](Choosing%20Pics/HORIZONTAL_BAR.PNG)
       
Horizontal bar charts are great for displaying categorical data, especially if using the categories to rank the values. Horizontal bars are also useful for long category names that won't fit as well for a vertical bar format.

   ![Stacked Horizontal Bar](Choosing%20Pics/STACKED_HORIZONTAL_BAR.PNG)
   
   ![Alternative Sacked Horizontal Bar](Choosing%20Pics/ALTERNATIVE_STACKED_HORIZONTAL_BAR.PNG)
       
  Stacked horizontal bar charts displaying absolute numbers or individual bars that sum to 100% can be useful for:
       * Showing parts of a whole
       * Featuring totals and providing an approximate sense of the parts

   As an alternative, consider pulling the stacked bars apart into a single ranking horizontal bar chart whose percentage totals add to 100%.
   
  ![Waterfall](Choosing%20Pics/WATERFALL.PNG)
       
   Waterfall charts are useful to show a starting point, incremental increases and/or decreases, and an ending point.  
   
   ![Scatterplot](Choosing%20Pics/SCATTERPLOT.PNG)
       
Scatterplots are useful to show the relationship between two variables or correlations between items. Use care when using scatterplots as they are not well understood by all audiences. Consider using two horizontal bar charts side-by-side organized in the same order, also called a table lens as an alternative.


   ![Dot Plot](Choosing%20Pics/DOT_PLOT.PNG)
       
Dot plots are useful for nominal comparative relationships where you want to highlight differences that would be hard to see in a bar graph that must have a zero baseline. These are also useful for showing time series data not representing consistent intervals of time.

 
   ![Boxplot](Choosing%20Pics/boxplot_iris.png)
    
Box & whisker plots display a large amount of distribution data in a single graphic: the highest and lowest values, the spread of values from highest to lowest, the median, and the 25th and 75th percentiles. Use box & whisker plots with care as percentiles are not readily understood by all audiences; consider simplifying to only show what is neededa high, median, and low box plot without whiskers
          
   ![Violin](Choosing%20Pics/violin_iris.png)
   
Violin plots provide a truer shape of the distribution than a boxplot.
 
   ![Map](Choosing%20Pics/USMap.PNG)
Maps are valuable for displaying geospatial information. One can use intensities of color of a state or region on a map to reveal the data.
     

 

(MOVED FROM PREV SECTION)

#### Tables

 Tables are likely the most useful in the following situations:
       * When the goal of the visualization is to **look up individual values**
       * When the user needs a one-to-one comparison or to compare pairs of related variables
       * When the goal of the visualization is to communicate to a diverse audience where each will look for their own value
       *	Information needs to be read, such as across rows or down columns
       *	Precision is important, as opposed to a general sense of the data from a graph
       *	You have multiple data sets with different units of measure
       *	You want to combine summary and detailed information
       
 Tables are likely too detailed and time consuming for your reader to use during a live presentation.
       
       
 
   
      
