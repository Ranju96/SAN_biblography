# SAN_biblography

## Introduction
In this analysis, we visualized a bibliographic graph representing the relationships between papers, authors, and citations in a heterogeneous network. By considering multiple types of nodes and different types of edges, we constructed a comprehensive network. Using appropriate visualization tools, we displayed the graph, highlighting the connections and structure of the network. This visualization provides insights into the interplay between papers, authors, and citations in the academic domain. By classifying nodes based on the number of topics or papers and applying clustering algorithms, we can identify thematic clusters and uncover patterns in the field of study.

## dataset
ACM.csv ,from kaggle


# Methodology
## 1.Plot bibliographic graph(or its subgraph) for a hetrogenous network and visualize it.
1.	Data Collection: Gather the bibliographic data, including information such as authors, papers, citations, and additional metadata.

2.	 Data Preprocessing: Clean and organize the bibliographic data. This may involve tasks such as standardizing author names, resolving inconsistencies, and creating a structured dataset.

3.	 Network Construction: Convert the bibliographic data into a network representation. In a heterogeneous network, you would have multiple types of nodes (e.g., authors, papers) and different types of edges (e.g., co-authorship, citation).

4.	Subgraph Selection: Determine the specific subgraph you want to visualize. It could be a specific author's network, a subset of papers, or a specific topic-related subgraph.

5.	 Network Visualization: Use appropriate tools or libraries to visualize the selected subgraph. Some popular libraries for network visualization include NetworkX, Gephi, and Cytoscape.

6.	 Layout Algorithms: Apply layout algorithms to position the nodes and edges in the visualization. Commonly used layout algorithms include Force-directed, Circular, and Fruchterman-Reingold. These algorithms aim to create visually appealing and informative network layouts.

7.	Node and Edge Customization: Customize the visualization by assigning colors, sizes, labels, and other visual attributes to nodes and edges. This customization can help highlight important information or relationships in the network.

8.	 Interactivity: Enhance the visualization by adding interactive features. For example, you can allow users to click on nodes to view additional details or hover over edges to see citation information.

9.	 Analysis and Insights: Analyze the visualized subgraph to gain insights about the bibliographic relationships within the network. This could involve identifying clusters, influential authors or papers, and exploring patterns of collaboration or citation.

## 2.Node and edge classification Number of topics or papers (similarity in biblographic graph like topic modeling Use any classifier or clustering(preferable)

To classify nodes and edges in a bibliographic graph based on the number of topics or papers, we can employ various algorithms and techniques. Here are some commonly used ones:

1.	K-means Clustering: K-means is a popular unsupervised clustering algorithm that can group nodes or edges based on their similarity. In this case, we can use the number of topics or papers as features and apply K-means to cluster the nodes or edges into distinct groups.

2.Spectral Clustering: Spectral clustering is another clustering algorithm that uses the eigenvectors of a similarity matrix to partition nodes or edges into clusters. It can be effective in capturing complex patterns in the data and can be applied to classify nodes or edges based on the number of topics or papers.

## Coclusion

The analysis explored variable distributions, performed clustering on a bibliographic subgraph, and visualized the connections between papers and citations. It offers insights into variable frequencies, paper grouping based on titles, and the overall bibliographic network. This provides a foundation for further exploration of the underlying patterns.
