# Charts 

## Bar Chart 
- clearest and most straight forward. 
- Load csv file as an txt file in tableau public.
- Uses workbooks and sheets. 
- In tableau data is categorised as an dimension or measure .
- Dimension contains qualitative information (names, dates, geographical data) (rows).
- Measure contains quantitative information (columns).
  
- Automaticaly sorts your data .
- Fonts should be unique throught the presentation.


## Pie Chart 
- Difficult to visualize parts of the charts from largest to smallest.
- Pie charts should be avoided until and unless requested.
- Suited for data that sums up to 100 %.
- cmd + shift + B to enlarge the circle as Tableau makes the  circle to small.
- The 'Color Blind' palette makes sure that the entire audience is included.
- Pie charts are often the preferred choice for non-technical audiences.
  
- Why should you never use a pie chart ? 
  - Data should sum up to a full 100 % 
  - Otherwise it is of no use
  - If the data is more than 100 % do not go for it 
  - Too many categories 
  - No 3d or doughnut
- 6-7 would be maximum 
- Pie charts are useful when:
  - there are 6-7 categories
  - your data Sums up to a 100 %

## Stacked Area Chart 
- Use when your are required to visualize data related with time.
  
- Describe changes over time 
- Display quantative data for three or more numerical variables.
  
- Used to discover trends and patterns in data.
- What makes a good stacked area chart ? 
  - When we have time data 
  - Usesful when we want to compare volume among categories. 
  - Atleast 3 categories are there 
  - When the variables are ordered and numerical. 
  
  - when we have no more than 6-7 categories.
  - The y-axis starts from 0. 
  
## Line Chart 

- Show evolution of one or several quantities. 
  
- Represent time or series data.
- columns: x-axis, rows: y-axis 
- Easy to track progression of a variable over time.
- Tip of the area chart is called a line chart.
- when we have many different variables (3, 5 or 10).
- It is not necessary to start your y-axis in line chart from 0.
  
## Histogram 
- Shows the distribution of a numeric variable.
  
- The Variables range of values is split into intervals, represented by bins.
- The heigh of bins shows the number of observations within an interval. 
- x axis is a number line
- y axis contains frequency.
- one variable only.
- Useful for showing distributions 
- Stick with equal width intervals 
- Start with 0 or include real variables 

## Scatter Plot 
- Shows relationship between 2 numerical variables.

- Can display large no of points.
- Each point is a point on a scatter. 
- To display observation in out chart as a seperate point we must change from 'SUM' to 'Dimension'.
- If we have a large dataset it might result into overplotting. 
- To avoid overplotting we can add a transparency level or 'Opacity' in Tableau.
- If you want to start your chart from 0 just change the limits of x and y axis. 
- Scatter plots cannot explain the origin of the features relationship.