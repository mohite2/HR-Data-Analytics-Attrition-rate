### The purpose of this assignment is to get practice with interactivity using the ipywidgets interface and to think carefully about how our data (and its types) can effect our design choices.

You can use "ipywidgets.interact" or if you want more practice, place construct your widgets and layout by hand like is discussed in the prep notebook with the Michigan dataset.

In addition to the code gone over in class, you may want to check out the supplementary notebooks attached at the bottom of week 5's webpage for some histogramming hints.

#### Using traitlets and/or widgets build a notebook that:

Allows the user to change the x and y fields on a scatter plot from the UFO dataset.  Here the "fields" are the names of the columns in the dataset.  (Do you want the user to be able to pick any 2 columns?  Or only certain columns?  Why or why not?). You must support the selection of at least 1 categorical column and at least 1 numerical column in for each of x and y.  Note: you don't have to support both axis having a categorical variable (unless you really want to!).

Allows the user to pick their colormap.  In class we used the log of the duration in seconds as our color scaling, you can use this or something else (or if you *really* want to get fancy you can let the user decide by using a widget!)

#### Build a second widget that displays binned, aggregate values of a column where you can change:

The field to "bin".  (Do you want the user to be able to pick any 2 columns?  Or only certain columns?  Why or why not?). You must support the selection of at least 1 categorical column and at least 1 numerical column.

For numerical variables: The number of bins.
