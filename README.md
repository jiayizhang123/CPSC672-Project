# CPSC672-Project
A Network Analysis of New York Jersey City's Bike Sharing System Bike-sharing systems like Citibike in Jersey City represent complex networks where stations act as nodes and user trips form connections, providing insights into urban mobility patterns in a smaller, more localized setting compared to larger cities.

 #A Network Analysis of New York Jersey City's Bike Sharing System

Bike-sharing systems like Citibike in Jersey City represent complex networks where stations act as nodes and user trips form connections, providing insights into urban mobility patterns in a smaller, more localized setting compared to larger cities. This project analyzes the Citibike trip data from February 2024 to understand the network's topology, community structure, and deviations from randomness. The domain focuses on transportation networks, addressing the problem of identifying efficient usage patterns and potential bottlenecks in a regional public transit supplement.

The network is constructed as a weighted undirected graph with bike stations as nodes and aggregated trips as edges, weighted by trip frequency. Key results include 134 nodes, 2611 edges, a high average degree (38.97), indicating dense connectivity. The degree distribution of Citibike network data shows that the nodes are concentrated in the low range, while there are a few nodes with extremely high degrees(50-83), presenting a clear long tail characteristic. This network has 3 detected communities via Louvain algorithm, suggesting geographic clustering. Compared to  two types of null models, Erdos–Renyi random and Degree Preservation configuration model, the network shows higher clustering and slightly longer paths, implying small-world properties with local clustering due to geographic constraints.

This network analysis could provide optimized station placement suggestions for operators and route recommendations for users in Jersey City. Future work could incorporate temporal dynamics or compare with whole New York data for regional differences, aiding sustainable urban planning in suburban areas.

![alt text](https://github.com/jiayizhang123/CPSC672-Project/blob/main/Community.png?raw=true)
![alt text](https://github.com/jiayizhang123/CPSC672-Project/blob/main/Hub.png?raw=true)
