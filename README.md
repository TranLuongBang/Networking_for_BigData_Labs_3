# Networking for Big Data Laboratory

Data:

https://drive.google.com/drive/folders/1YMwwPoekwJrw_-UYkZYUkTFqC8bqAy0F?usp=sharing


_________________________________________________

Assignment

## **Statistical Analysis**

A) Extract 1 million of packets from the available data, replicate the statistical analysis observed during Lecture 2.

FOLLOW the LIST!

      1) Extract general info from your trace using capinfos;

      2) Time Evaluation between Sequential and Parallel reading;

      3) Extract the IP which generates the highest amount of sender traffic, evaluate the bit rate (0.1 sec) for the 6 IP addresses mostly used as endpoint;

      4) Top 5 Destination IP (received bytes) and Top 5 Source IP (sent bytes);
      
      5) Evaluate bitRate considering all the trace with 3 different sampling rate;

      6) GeoLocal Referenciation of the 5 sessions with the highest amount of traffic generated;

      7) 10 Protocol mostly used;

      8) Port Scanner evaluation (10 Ports mostly used);

      9) InterArrival Time boxplot between TCP and UDP Sessions;
      
      10) Develope your own analysis (e.g. Topology of the network using networkx or evaluation about a variable such as TTL) (BONUS)




## **Machine Learning**

B) Using the same dataset, you can cut the time interval as you want trying to replicate or Supervised or Unsupervised classification problem.

Summarizing results according to the accuracy and other metrics related to the label(**) considered, you can add the more variables w.r.t. 
the paper analyzed but remember you must work with flow based features.


**You can both replicate DSCP analysis or change the label for example classify TCP and UDP. You have complete freedom about the label and the algorithm for classification



