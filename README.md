# SocialNetworkAnalysis


<h3>Purpose of the research:</h3> 
<p>This research uses big data, graph theory and sociology to study the influence analysis under the scenario of big social data. This research focuses on two aspects: 
<li>1. To determine the influential users at micro and macro level engagement. 
<li>2. Another key area is to understand the human sentiments shown in such networks for a political decision. 
  
<h3>Approach: </h3>
<p>To understand the communication and interaction in a social network by understanding the social structures present in a network for influence. Graph database (Neo4j) stores information as a graph which stores the nodes and its relationships. Different centrality measures and community detection algorithms are used to predict the influential users and communities in their network. </p>
  
1. The micro analysis measures identify top influential users, top connectors users based on who posted it, the retweets and in reply relationships. 
2. The macro analysis community detection algorithm determines the different communities based on users who retweets and sharing common interests.
3. These networks are used to analyse the negative or positive influence they are making in those networks by estimating the sentiments in their tweets present, using AFINN lexicon a python package which determines the sentiments by giving each word a numeric score.
4. The visualization of data is a way to relate the results in an easy and efficient manner based on the graph algorithms. The tool used to visualize the graph data is Neo4j. The important features such as the centrality score of nodes in a graph can be visualized best on the graphs.
