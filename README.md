# Weather Data Analysis using Big Data
Large Scale Data Processing (CSE3025) J Component

### To find the hottest, coldest day from the data depending on temperature and comparing precipitation levels to find whether a particular day received light, moderate or heavy rains using Map-Reduce Programming:
● Download the weather_data.txt dataset and MyMaxMin.java file.\
● Open Eclipse software and open the java file. Build the path by configuring it and adding the necessary external jar file libraries in the classpath of the program.\
● Now when the project shows no syntax errors, export the temperature.jar file from the main class of the program and store it in the system.\
● Now in the terminal, give the commands start-dfs.sh and then start-yarn.sh to initiate Hadoop in the system.\
● Open the localhost page and browse the file system.\
● Now, copy the weather dataset file into HDFS using the hdfs dfs –put command.\
● Finally, run the jar file by giving hadoop jar temperature.jar MyMaxMin [path for weather_data.txt in HDFS] [path for the output file in HDFS].\
● Once the program runs successfully, browse the file system and go to the output file. Now download the part-r-00000 file from HDFS and the output for the program would be displayed here.

### Naïve Bayesian Classifier Implementation for Weather Prediction:
● Download the new_dataset.csv dataset and simplenaivebayes.py file.\
● Open the python file that contains code to find probabilities using the Naive Bayes classifier.\
● And execute in python idle.


### Rainfall Prediction Using Linear Regression Model:
● Download the weather.csv dataset and main.py file.\
● Open the python file that contains code to find rainfall prediction using the linear regression model.\
● And execute in python idle.
