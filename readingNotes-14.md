# reading 14

## matplotlib

- pyplot is a module in matplotlib used to add plot elements

### plot()

- if only 1 set of values is given it will be the "y"

- fmt = format and chamges how data is shown

- keyword arguments take precedent over fmt

- alpha: adjusts transparency of line

- markevery: adjusts how often a marker is placed.

- zorder: identifies which line shows on top if multiple lines cross (higher number goes on top)

- xlabel/ylabel: can change anything about labels (size, trasparency, color, style, weight, font, etc)

- title: can change anything about title of plot

- show: displays figure. nothing else will run until figure is closed unless .show is set to false

- grid() is used if you want to show gridlines. can use either "minor" or "major"

- xlim/ylim() are used to set x and y axis-range

- legend() is used to add label to plot

- ncol: changes the number of coumns in a legend

- loc: changes where on the plot the legend is located

- any new legend will override all other legends

### Ticks

- ticks are markers used to show space on axis'

- "major" and "minor" ticks

- xticks/yticks can change the location and labels of ticks.

## Seaborn

- statistical plotting library

- visualization library

- distplot()

- jointplot()

[Table of Contents](README.md)
