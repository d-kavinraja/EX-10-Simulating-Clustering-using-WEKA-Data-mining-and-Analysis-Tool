# EX 10: Simulating Clustering using WEKA Data mining and Analysis Tool
## Date: 13.10.2023
## AIM:
To perform a classification technique using WEKA tool
## WEKA:
<div align="justify">
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements.
WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

  ![image](https://github.com/dineshgl/EX-9-Simulating-Classification-using-WEKA-Tool/assets/143793356/c3702dff-f72d-4ba1-9cca-eb444358ab21)

## CLUSTERING:
<div align="justify">
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method, hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset.

## PROCEDURE:
1. In the WEKA explorer select the Preprocess tab. Click on the Open file ... option and select the iris.arff file in the file selection dialog. <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/bd6df0b2-51db-4cee-a6f7-33152b2aac12)
2. Click on the Cluster TAB to apply the clustering algorithms to our loaded data. Click on the Choose button. Now, select EM as the clustering algorithm. <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/34796748-9934-4cf0-9ce9-9b8204adb904)
3. In the Cluster mode sub window, select the Classes to clusters evaluation option <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/658892f7-e190-4264-a5ae-175bb6e64a2b)
4. Click on the Start button to process the data. After a while, the results will be presented on the screen. <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/a9b44cbc-15db-4821-8dc7-7a22cd5999a4)
5. From the output screen, you can observe that − There are 5 clustered instances detected in the database. The **Cluster 0 represents setosa**, **Cluster 1 represents virginica**, **Cluster 2 represents versicolor**, while the last two clusters do not have any class associated with them. <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/5e2ee384-d8fc-45c3-ac20-fb716fd8cf5b)
6. To visualize the clusters, right click on the EM result in the Result list. <br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/4078b056-ad78-4f6d-b86c-a1dc8e8b9f9e)
7. Select Visualize cluster assignments.<br>
![image](https://github.com/dineshgl/EX-10-Simulating-Clustering-using-WEKA-Data-mining-and-Analysis-Tool/assets/143793356/b28a21b1-4965-412f-8ac2-b8cdc079b703)

## RESULT:
Thus the simulation of clustering technique has been executed using WEKA tool successfully.

