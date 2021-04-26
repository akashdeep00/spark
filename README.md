spark Word Count program

Compile the above program using the command given below
scalac -classpath "spark-core_2.10-1.3.0.jar:/usr/local/spark/lib/spark-assembly-1.4.0-hadoop2.6.0.jar" SparkPi.scala

jar -cvf wordcount.jar SparkWordCount*.class spark-core_2.10-1.3.0.jar/usr/local/spark/lib/spark-assembly-1.4.0-hadoop2.6.0.jar

spark-submit --class SparkWordCount --master local wordcount.jar

$ cd outfile 
$ ls 
Part-00000 part-00001 _SUCCESS




By setting "inferSchema" and "header" to true, we can let spark know that first row in data in header 
 Infer schema will automatically guess the data types for each field.
 
 
 
 
 
 
