# Customer Analysis in the Marketing Strategy of Huawei: A Social Network Analysis Approach
Social media analysis helps Huawei better understand their targeted audience, evaluate the impact of marketing campaigns and enhance their business. In this report, I used social network analysis techniques to study the Huawei's customer connecting pattern. This report is based on the data from Huawei Social Network Data on Kaggle platform. Data Link: https://www.kaggle.com/datasets/andrewlucci/huawei-social-network-data

#### Exploratory Data Analysis
I initialized the analysis by exploring the properties of these three platform, including  diameter, density, clustering coefficient and average degree.
Chart 1 Network Fundamental Features
Metric	Facebook	Instagram	Twitter
Number of Vertices	1000	1000	1000
Number of Edges	50153	4933	250315
Diameter	3	5	2
Density	0.1004	0.0098	0.5011
Clustering Coefficient	0.1002	0.0083	0.5012
Average Degree	100.306	9.866	500.63

Colons can be used to align columns.

| Metric        | Facebook      | Instagram  | Twitter |
| ------------- |:-------------:| -----:| --------:|
| Number of Vertices | 1000 | 1000 | 1000 |
| Number of Edges     | 50153      |   4933 | 250315|
| Diameter | 3      |   5 | 2|
| Density | 0.1004      |    0.0098 | 0.5011|
| Clustering Coefficient | 0.1002      |    0.0083 | 	0.5012|
| Average Degree | 	100.306  |   	9.866  | 	500.63 |



Diameter measures the longest shortest path between any two nodes in a network. Twitter has the shortest diameter of 2 and the largest density of 0.511, indicating that the nodes in the network are closely connected; while Instagram has the largest diameter of 5 and the lowest density of 0.0098, suggesting the network is less connected to each other. 
With a high clustering coefficient of 0.5012 and high average degree of 500.63, the Twitter network is highly interconnected and there are many closely-knit communities within the network. The Instagram has the lowest clustering coefficient and the lowest average degree, indicating that it is a sparse and disconnected network. There are few connections between nodes, and the nodes tend to be relatively isolated. This can result in low overall network efficiency and communication between nodes may be limited. 

 


