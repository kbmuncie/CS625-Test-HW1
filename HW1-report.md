# Homework 1: Tool Setup

**Kaitlyn Muncie**  
CS 625, Fall 2026  
Due: Sunday, September 6, 2026

## Git, GitHub

### Q1 - URL of GitHub Repo

https://github.com/kbmuncie/CS625-Test-HW1

This is the repo I have created under my private account as directed.

### Q2 - Pull Command

Pull requests and commands send remote changes to local. I requested a pull in the Source Control section of Visual Studio Code locally.

### Q3 - Local Commits

Local commits send local changes to remote. If a committed change on the local machine does not updated on GitHub.com, the user may have forgotten to push the commit. The origin/main branch will not see the changes if it is not synced. I used the same section for pull commands to push the changes. I then synced the remote and local main branches in my repo.

## Markdown

### Q1 - Bulleted List

To make a bulleted list, I used dashes (-) in front of the line items as shown below.

- Cats
- Dogs
- Birds

This list is different than a numbered list because the line items above are unordered.

### Q2 - Markdown Paragraph

This paragraph contains several key **Markdown** syntax that will allow me to convey my understanding of Markdown's capabilities. This includes **bold**, *italics*, and even ***bold italics***. In several reports, especially technical reports, we will need to convey when something is `code` versus plain text and sometimes even use code blocks. We can also include a [link](https://www.instagram.com/p/DVnmDVhk8bc/) through embedding it much like in HTML.

Code blocks can be used as shown below:

<html>
      <head>
      A Code Block
      </head>
    </html>

### Q3 - Animal Image

I added an image I found through Google Images of a cat at a computer.
![Cat at a Computer](/Image%20Files/cat-image-cs625.jpg "Cat at a Computer")

## Tableau

### Q1 - Region Other Than the South

I chose to use the East region instead of the South.

![Sales in the East](/Image%20Files/Sales%20in%20the%20East.png "Sales in the East")

## Google Colab

### Q1 - URL of Google Colab Notebook

[Colab Link](https://colab.research.google.com/drive/142Rdnk3XN43bILqDC2jGTiX5_XqQHPqx?usp=sharing)

## Python/Seaborn

### Q1 - First Penguin Image

The first figure from the penguin data: ![Seaborn Penguins 1](/Image%20Files/Seaborn-Figure-1.png)

This first figure showcases the depth and length of the penguin species' bills as a scatterplot. You can see two large groupings with outliers across both areas of measurement.

### Q2 - Second Penguin Image

The second figure from the penguin data: ![Seaborn Penguins 2](/Image%20Files/Seaborn-Figure-2.png)

The second figure is a bar chart with three species of penguin's body mass data for comparison. The Gentoo species has the largest body mass per the data whereas the Adelie and Chinstrap species of penguin have nearly identical body mass measurements.

### Q3 - Outer Parenthesis

When I removed the outermost parenthesis and appended the `.add(so.Bar(), so.Agg())` portion to the first line, it showed the same chart. This showcased the use of Python to reduce long lines of code and create "implicit line continuation." (Python Morsels 2021)

## Observable and Vega-Lite

### Q1 - markCircle to markSquare

When I changed markCircle() to markSquare(), the plots changed shape from circles to squares.

### Q2 - markCircle to markPoint

When I changed markCircle() to markPoint(), the plots shape went from filled circles to outlined circles instead. When I followed the original Observable files' instructions to pass an option of {shape: "diamond"} to markPoint(), the outlined circles became outlined diamond shapes. 

### Q3 - Swap X and Y Axes on Scatterplot

To swap the x and y axes on the scatterplot, I just needed to adjust the `fieldQ(Origin)` data for each axis. `the x().fieldQ("Acceleration")` became `x().fieldQ("Miles_per_Gallon")` and `vl.y().fieldQ("Miles_per_Gallon")` became `vl.y.().fieldQ("Acceleration")`. Vega-Lite looked into the established data from the cars.json file to get the data associated with each object's `Miles_perGallon` and `Acceleration` key/values.

### Q4 - Remove fieldN(Origin)

![VegaLite BarChart Changed](/Image%20Files/VegaLite-BarChart-1.png "VegaLite BarChart Changed")

Interestingly, when I removed the line `vl.y().fieldN("Origin")`, the bar chart became soley focused on the count of records, rather than the count of records per country of origin. This chart only used the x-axis so there was no code or data referenced to create other bars in the chart.

## References

*Eavery report must include a References section that lists the webpages and URLs that you consulted while completing the assignment. Replace the items below with the references you consulted - these are just examples.* ***Everyone will use some reference to complete these assignments (even I would). You will lose points on your assignment if you do not include the references you used.***

* Breaking up long lines of code in Python, <https://www.pythonmorsels.com/breaking-long-lines-code-python/>
* A Taste of Observable, <https://observablehq.com/@observablehq/a-taste-of-observable>
* Charting with Vega-Lite, <https://observablehq.com/@observablehq/vega-lite>