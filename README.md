<h1> Map Reduce Hadoop </h1>

1) Go to Hadoop sbin
2) start-dfs
3) start-yarn
4) hadoop fs -mkdir /input
5) hadoop fs -put {file path} /input
6) hadoop fs -ls /input
7) hadoop dfs -cat /input/data.txt
8) hadoop jar mapreduce_path.jar wordcount /input /output
9) hadoop fs -cat /out/*
10) localhost:8088
11) localhost:9870
