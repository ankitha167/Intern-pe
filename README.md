Started the assignment by importing the necessary libraries. Reading the csv file using pandas. Displayed the head , tail of dataset. Used info() function to extract the information from the dataset. describe() function used to give the statistical aspect of the dataset. shape() to know the number of rows and columns.
Data Preprocessing :
 importing datetime to extract information like date , time , month etc. After extracting the needed information using the month column determined made a separate column for season, which specifies the season. 
For the missing or null values substituted the mean of the column. 
Used boxplot to visualize the dependency graph of the variables on the load type. 
Found the correlation matrix and displayed using heatmap. 
Now found the unique values of the output variable (ie) Load Type. the unique values are Light load , Medium Load and Maximum load. 
mapped them to 1 , 2 , 3 respectively. 
Split my dataset into train and test data (80 and 20% respectively)
Used algorithms like random forest, Adaboost and SVM. 
Random Forest gave better accuracy in comparison with the rest. 
Took a custom input and checked using the model 
