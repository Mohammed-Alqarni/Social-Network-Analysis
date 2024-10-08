# **Social Network Analysis and Clustering of Country Relationships Using Graph Theory**

## **Project Title**  
Uncovering Global Patterns with Network Clustering:  
**Leveraging Community Detection to Understand International Relations and Key Influencers**

## **Overview**  
This project applies **graph theory** and **social network analysis (SNA)** techniques to analyze the relationships between countries. By visualizing these connections and using community detection algorithms, we aim to identify key clusters (communities) of countries and highlight the most influential ones. The project uses network centrality measures and visualizations to provide insights into international relations and global interactions.

## **Problem Statement**  
- Understand the relationship dynamics between countries using **network analysis**.
- Identify **key clusters** of countries with strong interrelations.
- Highlight **influential countries** based on centrality measures.

## **Project Goals**  
1. **Visualize country connections** using graph-based techniques.
2. Implement **community detection algorithms** (Louvain, Greedy Modularity, Girvan-Newman) to reveal clusters of countries.
3. Analyze **centrality measures** (Degree Centrality, Betweenness Centrality, Closeness Centrality) to identify influential countries.
4. Provide **visual representations** (MatrixPlot, CircosPlot, and custom graph visualizations) to illustrate the global relationship network.

## **Data Understanding**  
The dataset represents relationships between different countries. Each row in the dataset shows a connection between two countries.
- **Columns**:  
  - **Source**: The first country in the relationship.  
  - **Target**: The second country in the relationship.  
- **Dataset Summary**:  
  - The data contains 501 relationships between 60 countries.  
  - Highly connected countries indicate a high degree of influence or interaction.

## **Technical Tools & Libraries**
- **Libraries**:  
  - **NetworkX** for building and analyzing the network graph.  
  - **Matplotlib** and **Seaborn** for visualizations.  
  - **Community-Louvain** for community detection.
  
- **Algorithms Used**:  
  - **Louvain Method** for modularity-based community detection.  
  - **Greedy Modularity** for detecting clusters.  
  - **Girvan-Newman** for hierarchical community detection.
  
- **Visualization Techniques**:  
  - **MatrixPlot**, **CircosPlot**, and custom **network visualizations**.

## **Project Workflow**

1. **Data Cleaning**:  
Focused on the **Source** and **Target** columns, removing unnecessary data.

2. **Network Graph Construction**:  
Created a graph using **NetworkX**, with nodes as countries and edges representing relationships, visualized with a **spring layout**.

3. **Centrality Analysis**:  
Calculated key metrics:
   - **Degree Centrality**: Countries with the most connections.
   - **Betweenness Centrality**: Countries that bridge others.
   - **Closeness Centrality**: Countries that spread information efficiently.

4. **Community Detection**:  
Used the **Louvain Method** and **Greedy Modularity** to detect country clusters.

5. **Visualization**:  
Produced custom network graphs, highlighting influential countries, and used **PyVis** for interactive visuals.

## **Expected Outcomes**
1. **Clusters of countries**: We expect to uncover groups of countries with stronger interrelations, forming communities.
2. **Influential countries**: The analysis will reveal the most central countries in the network, likely global influencers based on their connectivity.
3. **Enhanced visual representations**: The project will produce clear, visually engaging graphs for interpreting global relationships.


## **Results and Visualizations**
The project outputs include:
- **Network graphs** with influential nodes highlighted.
- **Community clusters** of countries.
- **Centrality metrics** such as Degree, Betweenness, and Closeness.

## **Contact Information**
For any questions or further information, please contact:

- **Name:** [Mohammed Alqarni]
- **Email:** [M30.alqarni@gmail.com]

