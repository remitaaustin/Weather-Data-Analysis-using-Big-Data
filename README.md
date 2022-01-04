# Weather Data Analysis using Big Data
Large Scale Data Processing (CSE3025) J Component

### ● To find the hottest, coldest day from the data depending on temperature and comparing precipitation levels to find whether a particular day received light, moderate or heavy rains using Map-Reduce Programming:
&emsp;&emsp;1. Download the weather_data.txt dataset and MyMaxMin.java file.\
&emsp;&emsp;2. Open Eclipse software and open the java file. Build the path by configuring it and adding the necessary external jar file libraries in the classpath of the program.\
&emsp;&emsp;3. Now when the project shows no syntax errors, export the temperature.jar file from the main class of the program and store it in the system.\
&emsp;&emsp;4. Now in the terminal, give the commands start-dfs.sh and then start-yarn.sh to initiate Hadoop in the system.\
&emsp;&emsp;5. Open the localhost page and browse the file system.\
&emsp;&emsp;6. Now, copy the weather dataset file into HDFS using the hdfs dfs –put command.\
&emsp;&emsp;7. Finally, run the jar file by giving hadoop jar temperature.jar MyMaxMin [path for weather_data.txt in HDFS] [path for the output file in HDFS].\
&emsp;&emsp;8. Once the program runs successfully, browse the file system and go to the output file. Now download the part-r-00000 file from HDFS and the output for the program would be displayed here.

### ● Naïve Bayesian Classifier Implementation for Weather Prediction:
&emsp;&emsp;1. Download the new_dataset.csv dataset and simplenaivebayes.py file.\
&emsp;&emsp;2. Open the python file that contains code to find probabilities using the Naive Bayes classifier.\
&emsp;&emsp;3. And execute in python idle.

### ● Rainfall Prediction Using Linear Regression Model:
&emsp;&emsp;1. Download the weather.csv dataset and main.py file.\
&emsp;&emsp;2. Open the python file that contains code to find rainfall prediction using the linear regression model.\
&emsp;&emsp;3. And execute in python idle.
