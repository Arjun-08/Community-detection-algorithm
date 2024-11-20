# Community Detection Algorithms 

This repository contains the implementation for the **Community Detection Algorithms** . The implementation explores community detection in graphs using the **Girvan-Newman** and **Louvain algorithms**. 

## Dataset
The assignment utilizes the following datasets:
1. **Wiki-Vote dataset**: [Link](https://snap.stanford.edu/data/wiki-Vote.html)
2. **Feather-LastFM-Social dataset**: [Link](https://snap.stanford.edu/data/feather-lastfm-social.html)

## Objectives
The assignment addresses the following tasks:
1. Implement the **Girvan-Newman Algorithm** from scratch and detect communities in the given datasets.
2. Devise an **automated stopping criterion** for the Girvan-Newman algorithm.
3. Visualize the resulting dendrogram to determine an appropriate stopping criterion.
4. Apply the **Louvain algorithm** for community detection and display the communities obtained after the first iteration.
5. Identify the **best decomposition** of nodes into communities.
6. Compare the **running times** of the Girvan-Newman and Louvain algorithms.
7. Discuss which algorithm performs better and justify the evaluation.


## Key Results
- **Girvan-Newman Algorithm**:
  - Used edge betweenness centrality to iteratively remove edges.
  - Visualized communities using NetworkX and Matplotlib.
  - An automated stopping criterion was implemented to balance computation time and result quality.
  - Resulting dendrograms assisted in determining the number of communities.

- **Louvain Algorithm**:
  - Maximized modularity to identify communities in the graph.
  - Demonstrated faster computation compared to the Girvan-Newman algorithm.
  - Provided robust and modularity-optimized community detection.

- **Comparison**:
  - The Louvain algorithm outperformed the Girvan-Newman algorithm in efficiency, especially for larger datasets.
  - Girvan-Newman offered finer-grained community detection but was computationally expensive.
 


