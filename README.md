# Tweet-Spark-Stream
Demonstrate an application of Spark Streaming on Twitter data, collect real-time posts, and identify the top hashtags that could be useful for understanding the trend among the users.

Created two programs to use spark streaming for real-time Twitter analysis. The first program, Twitter HTTP Client, is used to route Live tweets obtained from Twitter API to a TCP socket server. The second program, Spark Streaming Application, is used to conduct real-time analysis on Twitter data in the TCP socket server. 

Instructions on obtaining access to the Twitter API can be found in the repository in the file named: Twitter API Instructions.pptx

Code files (To work demo, open both files and run 'Twitter HTTP Client.ipynb' first):

Twitter HTTP Client.ipynb
Python Notebook used to route live tweets obtained from Twitter API to a TCP socket server.

Spark Streaming Applications.ipynb
Python Notebook used to conduct real-time analysis on Twitter data in the TCP socket server.
