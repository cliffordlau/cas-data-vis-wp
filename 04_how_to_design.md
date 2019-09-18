# How to design the visualization


## It is Important to Declutter
	* Cognitive load. Taking in information consumes brain power. A viewer has limits on their short-term working memory. Since viewers can only store three to four chunks of information at a time, that means cluttered and poorly designed data vis increase a viewer's cognitive load and reduce what can be retained. It is up to the data vis designer to use create visuals with the audience's cognitive load in mind, lest the message gets lost or takes more time away from other information they could absorb. 
	* High Data-to-Ink Ratio (*The Visual Display of Quantitative Information*, Tufte). This means that each dot of 'ink' on the visual is valuable, and can be used to describe data or to clutter a visual. The author should create data vis with a high ratio of data *most relevant* to the message, compared to the amount of 'ink' (characters, dots, text, lines, borders, or color/shading).
	* How to Declutter. (we need a series of actual simple visuals here to illustrate before-after)
		* Remove entirely or use gray to tone-down
			- Borders
			* Axes
			* Gridlines
			* Axis tick marks; keep the label remove horizontal or vertical line mark '-' itself
			* Gray out data that is the not *focus* of the visual. In this way the color of the main data or categorical subset can be distinguished from other (e.g. state "X" data could be the focus (blue), and compared to countrywide (gray))
		* Combine Title and the Message, or use callout box to clearly share the taekaway message for the reader
		* Use shorter axis-names.
		* Label data directly. Legends are commonly used in graphs. The viewer typically has to move their eyes from the data  to the legend (typically at the bottom) and back. If possible, place the label describing the data directly adjacent to the data. Another tip in this regard is to use the same color, weight, line-type, etc. for the text of the data label as for the data itself.This approach may not work for all graph types or data, however, if the lines in a line graph are crossing eachother. 
		* No vertical text. It is common to see y-axis labels that are oriented at a 90-degree angle from the x-axis, reading upwards. Who reads this way? Vertical orientation is more difficult to read and is a form of cognitive load; at a minimum it slows down the users ability to absorb the axis. One alternative to this is to include the vertical axis label in the title
		
	
## How to Make the Data ‘POP’
	
	* Gestalt principles (need reference; I think it is Gestalt School of Psychology 1912)
	These principles have identified how the brain works to visually connect things together and make sense of our world. The following principles apply:
		* Proximity. The closer things are together, the brain naturally groups them together. We can design our data vis to direct our viewer to see the patterns or data the way we want them to.
		* Similarity. Objects with similiar size, color, shape, font, or angular orientation are perceived by the brain to be part of the same group. 
		* Enclosure. Using some type of border or shading can render data to be grouped together. The brain will attempt to enclose things that aren't even necessarily fully enclosed by a solid line. The brain will likely 'fill in' a dashed line to perceive it as ecnlosing something if it can be interpreted that way. 
		* Continuity.  The brain may perceive a border to exist when objects are lined up (e.g. bars lined up along the x-axis could render a graph's x-axis border).
		* Connection. This principle is commonly used in line graphs to literally 'connect the dots' for the viewer. (consider example of 4 dots  shown twice; once with vertical lines connecting two dots and another with horizontal lines connecting)
	
	* Pre-attentive Attributes (*Show Me The Numbers*, Stephen Few). The human eye and brain are programmed to perceive a specific set of visual attributes very quickly and with a high rate of accuracy.
		* Attributes of Form
			** Length. Can be quantitatively perceived.
			** Width. Can be quantitatively perceived, but limited in accuracy.
			** Size. Can be quantitatively perceived, but limited in accuracy.
			** Shape. Cannot be quantitatively perceived.
			** Orientation. Cannot be quantitatively perceived.
			** Enclosure. Cannot be quantitatively perceived.
		* Attributes of Color
			** Hue. In everyday speak, hue refers to color. Hue can be described by the location on a standard color wheel. Color combinations that work well together, and are distinct enough from one another, can be found on the website ColorBrewer.org.
			** Intensity. In everyday speak, intensity refers to 'fullness' of a color (saturation), and lightness or darkness of a given color.
		* Spatial position in 2-Dimensions. We perceive and contrast vertical and horizontal position fairly well, in two dimensions. Our brains do not consistently or accurately perceive location in threee dimensions as well as two dimensions. This is why 3D graphs are to be avoided.
						
	* To be Avoided
		* Pie Charts. The eye cannot easily distinguish the degree of an angle from another unless they are very different. Similarly, the human eye cannot distinguish the quantitative area of a given shape easily. For thos two reasons, pie charts are commonly used but not effective
	
	* Hierarchy of comparisons of magnitude
		* Position along common scale
		* Position along non-aligned scale
		* Length
		* Direction/Angle
		* Area
		* Color and Shading saturation
		* Color hue
		* Volume
	* Hierarchy of identifying Categories
		* Spatial Region
		* Color
		* Motion
		* Shape
