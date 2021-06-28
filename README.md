<h1>Detecting outliers in data with Boostrapping</h1>
-----------------------------------------------------
The data consists of wwind and wave measurements, which are in principle linearly correlated. 
The data does not contain outliers, so outliers were manually added to the data.
Then subsamples of the data were taken, and a line was fit to these sub samples (i.e. bootstrapping). Then by looking a the histogram of all the slopes obtained from the sub samples, we were able to detect outliers. <br>
From this simple analysis, we can see that this technique does indeed detect outliers. However, it will not necessarily pick up how many outliers the data set has, unless each outlier is very different from one another.