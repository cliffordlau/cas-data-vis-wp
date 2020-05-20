# How to design the visualization
In this section we provide some keys on how to design a data visualization to render a crisp graphic that highlights the message.
Some main techniques described in this section are related to decluttering to remove what's not needed and to accentuating to highlight what is crucial.

## It is Important to Declutter
Clutter is the enemy in a graphic. Lines, colors, fonts, etc. in default graphic programs tend to be overly busy and thus not enable the audience to process the message to efficienly process the message. One needs to expend the effort to declutter data vis in order to maximize the message delivery effectiveness.

**Cognitive load** is discussed in (Knaflic, YYYY). Taking in information consumes brain power. A viewer has limits on their short-term working memory. Since viewers can only store three to four chunks of information at a time, that means cluttered and poorly designed data vis increase a viewer's 'cognitive load' and reduce what can be retained. It is up to the data vis designer to use create with the audience's cognitive load in mind, lest the message gets lost or takes more time and energy away from other information they could absorb. Decluttering reduces cognitive load by minimizing what the brain needs to see and process, which enables the reader to see the data more. Think 'less is 'more'.

**Data-to-Ink Ratio** is discussed in *The Visual Display of Quantitative Information* (Tufte, 2001). This means that each dot of 'ink' on the visual is valuable, and can be used to describe data or to clutter a visual. The author should create data vis with a high ratio of data *most relevant* to the message, compared to the amount of 'ink' used for text, lines, borders, or color/shading.

**How to Declutter** - 	Remove the following entirely, or use gray to tone-down their cognitive load:
* Borders; generally not needed and only clutter data ink from view
* Axis lines; the eye automatically sees a line created by the vertical or horizontal labels, or bars
* Gridlines; only keep if they serve a clear purpose
* Axis tick marks; keep the categorical label but remove the horizontal or vertical line marks '-' themselves
* Gray out data or text that is not the *focus* of the visual 
* Use shorter axis-names
* Omit Legends; Label data directly* 
* Combine the Title and the Message, or use callout box to clearly share the taekaway message for the reader
		
**Legends** are commonly used in graphs. However, the viewer must move their eyes back and forth from the graphed data to the legend, which takes time and increases cognitive load. If possible, place the label describing the data directly adjacent to the data. Another tip in this regard is to use the same color, weight, line-type, etc. for the text of the data label as for the data itself. This approach may not work for all graph types or data, however, if the lines in a line graph are crossing eachother. 

**Y-axis labels** should not use vertical text. It is common to see y-axis labels that are oriented at a 90-degree angle from the x-axis, reading upwards. Who reads this way? Vertical orientation is more difficult to read and is a form of cognitive load; at a minimum it slows down the users ability to quickly identify the axis. Instead, try arranging the vertical-axis label horizontally at the top left of the axis, or simply include the vertical axis label in the graph title.
		
	
## How to Accentuate to Make the Data ‘Pop’
We have nany tools to draw our viewers attention and  

**Gestalt principles** (from the Gestalt School of Psychology, 1912). These principles have identified how the brain works to visually connect things together and make sense of our world. The following principles apply:
	* Proximity. The closer things are together, the brain naturally groups them together. We can design our data vis to direct our viewer to see the patterns or data the way we want them to.
	* Similarity. Objects with similiar size, color, shape, font, or angular orientation are perceived by the brain to be part of the same group. 
	* Enclosure. Using some type of border or shading can render data to be grouped together. The brain will attempt to enclose things that aren't even necessarily fully enclosed by a solid line. The brain will likely 'fill in' a dashed line to perceive it as ecnlosing something if it can be interpreted that way. 
	* Continuity.  The brain may perceive a border to exist when objects are lined up (e.g. bars lined up along the x-axis could render a graph's x-axis border).
	* Connection. This principle is commonly used in line graphs to literally 'connect the dots' for the viewer. (consider example of 4 dots  shown twice; once with vertical lines connecting two dots and another with horizontal lines connecting)
	
**Pre-attentive Attributes** (*Show Me The Numbers*, Stephen Few). The human eye and brain are programmed to perceive a specific set of visual attributes very quickly and with a high rate of accuracy.
	
Attributes of Form
* Length. Can be quantitatively perceived.
* Width. Can be quantitatively perceived, but limited in accuracy.
* Size. Can be quantitatively perceived, but limited in accuracy.
* Shape. Cannot be quantitatively perceived.
* Orientation in 2D. Cannot be quantitatively perceived.
* Enclosure. Cannot be quantitatively perceived.
* Spatial position in 2-Dimensions. We perceive and contrast vertical and horizontal position fairly well, in two dimensions. Our brains do not consistently or accurately perceive location in threee dimensions as well as two dimensions. This is why 3D graphs are to be avoided.
	
Attributes of Color
		** Hue refers to color. Hue can be described by the location on a standard color wheel. Color combinations that work well together, and are distinct enough from one another, can be found on the website ColorBrewer.org.
		** Intensity refers to 'fullness' of a color (saturation), and lightness or darkness of a given color.
		
![Some Examples of Preattentive Attributes](pictures/PAA.png)
	
				
* Note that area, volume, angle, and depth are all omitted from preattentive attributes, since the human eye cannot easily decipher differences. This is why we should generaly avoid pie charts, 3D charts, area, and bubble charts. There are some exceptions, and some designers would say it might be ok to use pie charts with only two variables, or using treemap and bubble charts sparingly, but only to show generalities rather than precise differentiation between very similar quantities.

Appendix
Some authors have attempted to rank the efficiency at which the eye can distinguish values, by mode of visualization.
Below is a summary of Hierarchy of comparisons of magnitude:
* Position along common scale
* Position along non-aligned scale
* Direction/Angle
* Area
* Color and Shading saturation
* Color hue
* Volume
Hierarchy of identifying Categories
* Spatial Region
* Color
* Motion
		* Shape
