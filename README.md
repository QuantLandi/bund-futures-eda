# Brief description
The purpose of this project is to perform a univariate, bivariate and
multivariate exploratory data analysis on Euro-Bund futures 5-min data from
May 2016 to Sep 2017. Euro-Bund futures are the futures contract on the 10yr
bond issued by the German government. A futures contract is the commitment
to buy or sell some given underlying product at a certain date.

# Software and libraries

- R
- ggplot2
- reshape2
- plotly
- dplyr

# How to clone and watch the project
```
git clone https://github.com/QuantLandi/bund-futures-eda.git
cd bund-futures-eda
```

# Data source
The dataset starts on 12th May 2016 and ends on 29th Sep 2017. It is a subset
of a proprietary dataset belonging to the independent quantitative trading
research project FQT Research, whose owners kindly agreed to be used for the
scope of this project. It contains a few missing dates due to some server-side
connection issues in some occasional circumstance. The dataset can be found in
the file bund5min.csv
