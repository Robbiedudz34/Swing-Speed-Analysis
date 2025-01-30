# Swing-Speed-Analysis
A quick analysis of variables that can impact game performance, dependent on swing speed. Applicable to MLB data found from baseball savant.
These files are Python compatible with the default .csv file attached as 2024_ssa_analysis. Save these files to the same folder in your file organizer to access the files for yourself.

The main feature of the code is a segment that determines the true best fit line based on the scatterplot data. Many people will choose linear regression because it makes the most sense without a visual. Once seeing the data in the scatterplots, we see that many fall into Quadratic, Exponential, or Logarithmic lines of best fit. There is a section of code that determines the line of best fit for any pairing of variables.

# Significant Variables
This script takes data from the given .csv file (input another if applicable) to determine all statistically significant variables from the line of best fit metrics R and R^2. These are important for knowing what we are looking for in the data, and how well it determines outcomes in the game itself. Without it, we are blindly assuming that the data we chose is the best output of data. It is not so simple.

# Scatterplot Visuals
This script takes data from the given .csv file (input another if applicable) to produce the visual analysis of the line of best fit based on the data. These allow for trends to be seen as we compare to individual players who are clear outliers. There are 32 variables to be paried (992 pairings) in the default .csv file.
