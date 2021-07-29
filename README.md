# D3-Challenge

For this challenge, the context was that we accepted a data visualization position for a major metro paper. We were tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand our findings.
"The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System."
The data set included with the assignment is based on 2014 ACS 1-year estimates from the US Census Bureau, but you are free to investigate a different data set. The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

Core Assignment:  

I analyzed data for two of the variables, prcentage of smokers vs. median age.
Using D3 techniques, I created a scatter plot that represents each state with circle elements. I pulled in the data from data.csv by using the d3.csv function. 
I included state abbreviations in the circles, created and situated axes and labels to the left and bottom of the chart.

(Note: You'll need to use python -m http.server to run the visualization. This will host the page at localhost:8000 in your web browser.)

For the second (bonus) part of the assignment, I will do the following:


1. More Data, More Dynamics
Include more demographics and more risk factors. Place additional labels in scatter plot and give them click events so that users can decide which data to display. Animate the transitions for the circles' locations as well as the range of the axes. 

2. Incorporate d3-tip
Add tooltips to circles and display each tooltip with the data that the user has selected. Use the d3-tip.js plugin developed by Justin Palmer.
