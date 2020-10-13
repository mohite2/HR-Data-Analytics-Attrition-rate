Homework #6 (Due in 2 weeks)
In this assignment you'll be building a "dashboard" interface for the buildings dataset which provides the user with a linked view of this dataset.  The purpose of this assignment is to get some "hands-on" practice linking different facets of a dataset in a dashboard to provide the user a way to interactively browse their data.

Build a dashboard for the buildings data (see CSV file attached).

Left component:
Grid heat map
Rows are congressional district
Columns are the governmental department (Agency Name) (note, the agency names might overlap with your plot -- there are ways around this or you can leave as is)
Values are sum of total square footage for that set of criteria
Right component:
line plot
x is the year
y is total square footage acquired that year
These two should be linked so that you can select cells and that will update the square footage plot.
Things to think about:
Can you keep the x and y ranges static on the line plot?
Can you change the style?
In your write-up please address:

Any data transformations or rescalings you did for your plot
How you dealt with NaN's (empty entries) in your dataset
Any aesthetic choices you made (colors, layout, plot size, label size) and why, and what you'd like to experiment with if you had more time.
20 points for grid heatmap, 20 points for line plot, and 20 points for accurate linkage between the two.  40 points for writeup.
