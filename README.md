# SocialNetworkAnalysis


<h3>Purpose of the research:</h3> 
<p>This research uses big data, graph theory and sociology to study the influence analysis under the scenario of big social data. This research focuses on two aspects: 
<li>1. To determine the influential users at micro and macro level engagement. 
<li>2. Another key area is to understand the human sentiments shown in such networks for a political decision. 
  
<h3>Approach: </h3>
<p>To understand the communication and interaction in a social network by understanding the social structures present in a network for influence. Graph database (Neo4j) stores information as a graph which stores the nodes and its relationships. Different centrality measures and community detection algorithms are used to predict the influential users and communities in their network. </p>

<h3> Methods Used: </h3>
1. The micro analysis measures identify top influential users, top connectors users based on who posted it, the retweets and in reply relationships. 
2. The macro analysis community detection algorithm determines the different communities based on users who retweets and sharing common interests.
3. These networks are used to analyse the negative or positive influence they are making in those networks by estimating the sentiments in their tweets present, using AFINN lexicon a python package which determines the sentiments by giving each word a numeric score.
4. The visualization of data is a way to relate the results in an easy and efficient manner based on the graph algorithms. The tool used to visualize the graph data is Neo4j. The important features such as the centrality score of nodes in a graph can be visualized best on the graphs.
  
  
<h3> Results: </h3>
![[alt text](https://user-images.githubusercontent.com/33175569/145479674-d3dbdc3f-8c3f-47a7-b8b9-4a07c16fc79d.png)

  
![alt text](https://user-images.githubusercontent.com/33175569/145479713-bccf725f-918c-476a-b501-0627fd8daba7.png)
![output3](https://user-images.githubusercontent.com/33175569/145479720-78fb56ef-1e77-4b60-abe3-79c46906973b.png)
![Recommendation2_Yelp](https://user-images.githubusercontent.com/33175569/145479732-55337ef8-aa80-4c3a-9372-7a70383fbde3.PNG)
![Topics_Yelp](https://user-images.githubusercontent.com/33175569/145479744-a1ddf91c-f55b-41a5-af5c-6f92064c1d34.PNG)
![YElp_jsondata](https://user-images.githubusercontent.com/33175569/145479756-c1fb1751-b44e-4414-9996-36c697c12e58.PNG)
![Yelp_Neo4j_output](https://user-images.githubusercontent.com/33175569/145479637-7a78a593-d0f4-4ad8-8021-eb515e031280.PNG)
  

