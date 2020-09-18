# Meet-up-Network-Analysis

## Motivation:
There are lot of platforms for people organizing and attending events and social functions. meetup.com is a website for people organizing and attending regular or semi-regular events (meetups). 
The relationships amongst users, who goes to what meetups are a social network. It got my attention and interest for analyzing social gatherings and most influential meetups. We can use the data for graph-based analysis.

## Dataset:
The source of dataset for my analysis is from Kaggle (https://www.kaggle.com/stkbailey/nashville-meetup). This dataset was primarily generated for the network analysis with NetworkX. The dataset contains below information. I have pulled out required datasets for the necessary analysis. 
1.	member-edges.csv, member.csv: Edge list represents a member-to-member graph. Weights between the edges represents shared group membership. 
2.	rsvps.csv: It represents event attendance data.

## Research questions:
The project is focused on analyzing the meetup network data and find the most influential network groups. We work through the basics of graph theory and extract meaningful insights about the meetup groups. Here, the aim is to understand the analysis and get answers to the following research questions:
1.	who are the most influenced people in the network? 
2.	People influencing the transfer of information in the network.
3.	People who are having best performance in the network communities. 
4.	Visualizing the meetup communities.


## Methodologies:
Below are the planned methods to achieve the goals:
1.	Closeness Centrality 
2.	Betweenness Centrality 
3.	Eigenvector Centrality
4.	Using bipartite graph to find the meetup communities.

## References and Resources: 
1.	Networkx - https://networkx.github.io/documentation/stable/
2.	Kaggle - https://www.kaggle.com/stkbailey/nashville-meetup
