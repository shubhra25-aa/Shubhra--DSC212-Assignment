# Spectral Community Detection in Zachary's Karate Club

DSC 212 (Graph Theory) – Research Assignment By Shubhra Narain, IMS25197

In this project, Newman's Spectral Modularity Method is used to divide Zachary's Karate Club network into different communities using NumPy and NetworkX. The network is split based on the leading eigenvector of the modularity matrix. If the eigenvalue is positive, the community is divided according to the signs of the eigenvector; otherwise, it remains unchanged.

The graph is visualised after each split using the same layout. Degree, betweenness, closeness and clustering coefficients are also calculated for all 34 nodes within their respective communities.

After four splits, the network forms five communities of sizes 13, 10, 5, 5 and 1, with modularity increasing from 0 to 0.409. The first split gives the biggest improvement, reaching Q = 0.372. Nodes 1 and 34 remain the most important in terms of degree and closeness, while betweenness and clustering change more as the communities are divided.
