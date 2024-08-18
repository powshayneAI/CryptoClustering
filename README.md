# CryptoClustering

For this challenge we were tasked with using the KMeans command to help identify
and predict fluctuations within the income/prices of cryptocurrencies.
These predictions were made strictly with unsupervised learning, the
predictions lacking any form of validity as the data is not labeled as correct.

Most of the data is created using 'getdummies' commmands, which created dummy variables.

A hiccup I ran into was using 'random_state'. Unlike the data that was depicted 
within the outline notebook file provided, the random-state utilized produced different
outpus in my own progression of the challenge.

This is shown within the dataframes with the 'crypto_cluster' column.


Some other commmands we utilized were those of plotting line graphs to provide an elbow
plot, which used variables for 'intertia' and 'k'. These line graphs were elbow plots.

Alternately, we also created scatterplots that we were able to separate into alternate
colors by utilizing the variable of 'c' which was for the 'crypto_cluster' column, and
'colormap' which gave a pre-made palette like 'rainbow' or 'winter'.