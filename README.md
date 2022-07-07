# Word-Count-in-Hadoop
Implementation of Word Count java program in HDFS

Here are the commands to run this file in Ubuntu

To put the files in a specific directory
hadoop fs -put '/home/hdoop/input2.txt' /WordCountTutorial/Input

To run the jar file
hadoop jar '/home/hdoop/firstTutorial.jar' WordCount /WordCountTutorial/Input /WordCountTutorial/Output

To see the output 
hdfs dfs -cat /WordCountTutorial/Output/part-r-00000



