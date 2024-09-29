# SOM-ALGORITHM

**THIS IS AZIM NIYAZ-22MIS1115 I HAVE IMPLEMENTED SOM ALGORITHM SPECIFICALLY FOR WHITE WINE .**

**Self-Organizing Maps for WHITE- WINE  DATASET**  

**Data Preparation:**
1) Loaded the WHITE Wine dataset.
2) Normalized the data to prepare it for clustering.

**Self-Organizing Map (SOM) Training:**
1) Created a SOM using the MiniSom library.
2) Trained the SOM with the normalized dataset.
3) Identified winning nodes for each data point to understand which clusters (SOM nodes) the wines belong to.
   
**Visualization:**
1) Pie Chart: Visualized the distribution of wine quality scores, indicating the percentage of wines in each quality category.
2) Bar Graph: Showed the number of wines in each SOM cluster, helping to identify which clusters contained the most wines.
3) Line Graph: Displayed the average chemical properties of wines within a specific cluster, providing insight into the characteristics of similar wines.

**Libraries Used:**
1) Pandas: For data manipulation and analysis.
2) NumPy: For numerical computations.
3) Matplotlib: For creating visualizations.
4) MiniSom: For implementing the Self-Organizing Map algorithm.
