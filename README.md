# TimeSeriesAnalysis
The main goal is to understand temporal data trends and patterns, enabling informed decisions and predictions about the system's behavior over time.

**Overview:**
This GitHub repository explores using time series analysis for human activity recognition based on accelerometer data. 

**Project Goal:** 
The project aims to differentiate between walking, running, climbing up, and climbing down activities using features extracted from visibility graphs.

**Data:** 
Accelerometer data for two subjects performing the aforementioned activities is used.

**Methodology:**

1. **Data Preprocessing:** 
    - Select a sample size of 1024 data points from each subject for each activity.

2. **Visibility Graphs:**
    - Apply both Natural Visibility Graph (NVG) and Horizontal Visibility Graph (HVG) to each accelerometer signal (X, Y, Z) for each activity. 
    - This results in 48 graphs (2 subjects * 3 directions * 4 activities).

3. **Graph Analysis:** 
    - For each graph, compute network metrics including average degree, network diameter, and average path length.

4. **Data Visualization:**
    - Create scatter plots of average degree vs network diameter for each activity (walking/running vs climbing up/down).
    - Generate separate plots for each accelerometer axis (X, Y, Z) and visibility graph method (NVG, HVG).

**Technical Stack:**

* Programming Language: Python
* Data Manipulation/Analysis: NumPy, Pandas
* Data Visualization: Matplotlib
* Network Analysis/Graph Operations: NetworkX, ts2vg

**Invitation to Explore:**

Feel free to explore the code for a detailed look at the implementation and results. 
-  The code provides further details on the process.
-  If you encounter any problems or have questions, please refer to the provided documentation or contact the repository owner.

