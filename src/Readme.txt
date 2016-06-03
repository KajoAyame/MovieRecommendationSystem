Assume that you have installed the spark in the machine.
Under spark environment (or have set the scala/spark path):
Use “scalac MovieRecommendation.scala” to create jar file.
and then use “spark-submit <jar_name>.jar” to run.

If you cannot run by the above steps, try the following:
“spark-shell” to enter the spark shell.
In spark shell:
“:load MovieRecommendation.scala” (“MovieRecommendation.scala” must be in the same directory of spark-shell)
Copy the code from line 28 to line 79, then paste it to the shell directory
