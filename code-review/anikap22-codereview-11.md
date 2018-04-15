[Problem 1]. *Combining scatterplot coordinates with further styling of the markers using size or color variation can provide additional information about the points. In this plot, the y position should correspond with the size of markers. Do you think this is a useful way to emphasize information in a plot? Could it possibly be misinterpreted or misleading in some way? Did your peer create plot as instructed, and did they use the same method as you?*

This is useful by emphasizing points with large y values. However, it can also be misleading because it uses two types of emphasis (higher position and larger points) which might make it look twice as important as it is. The plot was created as instructed. They used `toyplot` while I tried `matplotlib`. 

[Problem 2]. *Here points are also colored using a colormap mapping to the x value of the points, and the size is random. There is not likely to be a good reason to make the size of points random in a real plot, but it does make for an interesting looking figure here. Think of and describe an example scatterplot in which there are 4 values you wish to represent, and you would use size, color, and x, and y coordinates to display information about all four.*

An example of a scatterplot in which there are 4 variables could be showing tree position using the x,y coordinates, species with a color, and DBH using the size. 

[Problem 3]. *Modifying the placement of tick marks and axes labels is often a difficult task, and is done a bit differently in every plotting library. It is important that ticks marks are spaced out and made to an appropriate size to be readable. Did your peer add tick marks as described? Did they use a different method than you did?*

Yes, they did make the tick marks as expected. They used a different method by using `toyplot.locator.Uniform` to set the ticks rather than `matplotlib` which allows you to specify the number.

[Problem 4]. *Barplots are used to show a distribution of binned data points. The default styling of barplots is often used, but modifying the size of bins, their color, or the spacing between them can often make for a much nicer looking plot. Did your peer bin the data into 15 bins? Did they apply a colormap to the bars? Given this distribution, which type of colormap do you think would be most appropriate, i.e., a linear map, a diverging map?*

Yes, they put the data into 15 bins. They also applied the color map. A divergining map makes the most sense since you want to show common values in one color and less common values in another color. (Unless you wanted to emphasize outliers on one side or the other).

[Problem 5]. *Creating plot layouts that combine multiple plots onto a single canvas is an important skill to learn to begin to make complex plots that display a lot of information. This plot should show a histogram on the left, and a corresponding scatterplot on the right. The density of points should match up between the two. Which of the two plots do you think is more informative about the distribution of the data? Did your peer use a different method than you did, and how do they differ?*

The histogram is more useful to determine the number of points at each level. However, the scatterplot is more useful for seeing the x distribution of those data as well as how uniformly the points are distributed within the plot. My peer used a different method because they made a cartesian canvas.