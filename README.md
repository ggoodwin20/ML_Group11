# ML_Group 11_KNN_FINAL
## Group Members: Annie W., Isaiah W., Gordon G.

### This program takes in a dataframe and outputs a line chart visualizing average KNN accuracy scores for each of a range of k-values, averaged over a specified number of repetitions. Each repetition corresponds to a randomly shuffled train/test split, whereby a 20 x 20 (k-value range x # repetitions) matrix of accuracy scores is created. The average accuracy scores across the 20 shuffled train/test splits for each k-value are then plotted in the line chart.

### The dataframe must have a numeric target variable, the name of which will need to be specified in the relevant code sections. User must change code in relevant sections if a different range of k-values and/or number of train/test shuffle repetitions is desired (currently set to k-value range of 1:20 and 20 shuffles). Any changes made will also need to be made to the accuracy score matrix dimensions (k-values x shuffles) 

## Package Requirements

### scipy numpy pandas matplotlib seaborn sklearn pillow yellowbrick ipywidgets
