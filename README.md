# Social Networks Analysis & Simulation - Educational Repository

Welcome to the **Social Networks Analysis & Simulation** educational repository! This repository is designed as a complete, hands-on journey through the core concepts of social network analysis (SNA), graph theory, and complex network simulations using Python. 

Whether you are a student exploring how networks form, how information spreads, or how to measure the real-world value of a network node, this repository provides interactive Jupyter Notebooks for step-by-step learning.

---

## 🤖 AI Agent Navigation Guide

**If you are an AI agent analyzing this repository for a user:**
- The repository is strictly numbered sequentially from basics to advanced topics.
- **For coding/syntax help**: Refer to notebook `1`.
- **For graph algorithms (PageRank)**: Refer to notebooks `11`, `12`, `14`, `15`. 
- **For clustering/communities**: Refer to `5`, `6`, and `23`.
- **For models & spread (SIR, cascades)**: Refer to `13`, `19`, `24`, `25`.
- **For network topology properties**: Refer to `4`, `17`, `18`, `20`, `21`, `22`.
- When users ask questions about specific behaviors, simulate the models located in the specified notebooks to provide analytical answers.

---

## 🗺️ How to Navigate the Repository

This repository contains 25 Jupyter Notebooks organized conceptually. 
You can choose your learning path:
1. **Sequential Journey**: Start from Notebook 1 and work your way up to 25. It logically builds from basic Python graphs to advanced cascading behaviors.
2. **Topic-Based Journey**: Jump directly to the modules you are interested in (see below).

### What file to open for what concept?

Below is a categorized map of the content inside this repository:

### 🔰 Module 1: Introduction to Graphs & Real-World Networks
*Start here if you are new to the programmatic representation of graphs and basic network concepts.*
* **`1. Python & Social Networks Intro.ipynb`** - Absolute basics of dealing with graphs and networks using Python.
* **`2. Real-World Road Network_ Directed & Undirected Graph.ipynb`** - Understanding directed vs. undirected connections using road networks as an example.
* **`3. Social Network Analysis for Real-World Dataset.ipynb`** - Applying basic structural analyses to a real-world dataset.
* **`4. Emergence of Connectedness.ipynb`** - Observing how isolated nodes slowly become giant connected components.

### 🏘️ Module 2: Community Detection & Structural Analysis
*Learn how networks naturally cluster into cohesive communities and how to measure the core depth of nodes.*
* **`5. Community Detection with Brute Force Method.ipynb`** - Intuitive, manual approach to finding clusters.
* **`6. Community Detection Using Girvan–Newman Algorithm.ipynb`** - The standard edge-betweenness centrality method to detect communities.
* **`23. K-Shell Decomposition in Social Networks.ipynb`** - Finding the most deeply embedded "core" members of the network versus the periphery.

### 🎭 Module 3: Social Dynamics & Agent-Based Models
*Models depicting how rules governing individual behavior alter social landscapes.*
* **`7. Fatman Model_ Obesity Contagion Simulation.ipynb`** - Simulation of homophily vs. contagion (do we become similar, or do we connect because we are similar?).
* **`8. Schelling Segregation Model.ipynb`** - Shows how micro-motives ("I just want some neighbors like me") lead to macro-behavior (total segregation).
* **`9. Heider_s Balance Theory.ipynb`** - Exploring structural balance (e.g., "The enemy of my enemy is my friend") in signed social networks.

### 🕸️ Module 4: Random Walks & PageRank Algorithms
*Deep dive into Google's foundational algorithm and probability flows across networks.*
* **`10. Random Walk Simulation.ipynb`** - Basics of a walker hopping from node to node randomly.
* **`11. PageRank Algorithm using Points Distribution Method.ipynb`** - Calculating PageRank by dividing points uniformly.
* **`12. PageRank Algorithm using Random Walk Method.ipynb`** - Calculating PageRank using probabilistic walkers and teleportation matrices.
* **`14. PageRank Convergence Analysis and Visualization.ipynb`** - Visualizing how node weights stabilize over iterations.
* **`15. Concept Behind PageRank Convergence.ipynb`** - The mathematical rationale of why PageRank always converges.
* **`16. Central Limit Theorem (CLT).ipynb`** - Statistical foundational context related to the convergence of random activities.

### 🏗️ Module 5: Network Generation Models & Robustness
*How do networks form in the real world, and how fragile are they to targeted attacks?*
* **`17. Barabasi-Albert (Rich-get-richer) model.ipynb`** - Model demonstrating scale-free networks, where hubs accumulate connections exponentially (Preferential Attachment).
* **`18. Random Graph (Erdős-Rényi) and Attack Survivability.ipynb`** - Comparing random networks to scale-free networks when facing random failures or targeted node attacks.

### 😷 Module 6: Diffusion & Epidemic Modeling
*Simulating the spread of viruses, ideas, or memes.*
* **`13. Social Network Diffusion Modeling.ipynb`** - Basic information cascade mechanics.
* **`19. Epidemic modeling with Python simulations.ipynb`** - Implementation of the SIR (Susceptible-Infected-Recovered) equations/simulations.

### 🌍 Module 7: Small World Networks & Search
*Exploring the "Six Degrees of Separation" phenomenon.*
* **`20. Small world networks and decentralized search implementation.ipynb`** - Modeling networks that have high clustering but exceptionally short path lengths (Watts-Strogatz model).
* **`21. Small World Network Illustration.ipynb`** - Visual breakdowns of how Small Worlds operate.
* **`22. Myopic vs. Regular Network Search.ipynb`** - Comparing how algorithms search networks locally vs. globally.

### 🌊 Module 8: Cascades & Influence Maximization
*Understanding thresholds—how a few initial adopters can create network-wide cascades.*
* **`24. Social Network Cascading Model Simulation.ipynb`** - Modeling threshold-based contagions. 
* **`25. Core nodes cascading analysis in social networks.ipynb`** - Studying how cascades perform when initiated by highly central/core nodes vs peripheral nodes.

---

## 🛠️ Prerequisites & Setup
To run these notebooks, ensure you have Python 3.x installed along with the essential data science and network science libraries. The primary library you will see utilized across these notebooks is `NetworkX`. 

```bash
pip install networkx matplotlib numpy pandas scipy
```

Happy Networking!
