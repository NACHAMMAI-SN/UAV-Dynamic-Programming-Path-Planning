
````markdown
# UAV Dynamic Programming Path Planning

This project applies **Dynamic Programming (DP)** methods to artificially created **Digital Elevation Models (DEMs)** to build a framework for autonomous **Unmanned Aerial Vehicle (UAV)** path planning. The goal is to identify the best, collision-free routes in 3D landscapes.

## Features

- **Terrain Generation**: Uses the **Diamond-Square technique** to generate realistic elevation data with adjustable roughness and predefined obstacles (mountains, hills, etc.).
- **Path Planning**: Supports both **4-connected** and **8-connected** movement patterns using **Forward Dynamic Programming**. The cost function considers:
  - Slope penalties
  - Elevation change penalties
  - Distance
- **Path Optimization & Smoothing**:
  1. Redundant point elimination  
  2. Cubic spline interpolation  
  3. Neighbour averaging for simple smoothing
- **Interactive Visualization**: Built with **Plotly**, offering:
  - Cost maps  
  - Optimized routes  
  - 2D and 3D terrain representations
- **Widget-based Parameter Control**:
  - Slope penalties  
  - Elevation weights  
  - Start and goal positions  
  - Smoothing factors  
  - Terrain roughness
- **Performance Improvements**:
  - Waypoint reduction of 40–60%  
  - Shorter travel distances by 10–20%  

This provides a practical and efficient solution for UAV navigation in 3D environments.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/NACHAMMAI-SN/UAV-Dynamic-Programming-Path-Planning.git
cd UAV-Dynamic-Programming-Path-Planning
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter/Colab notebook and run the cells.

---

## Authors & Affiliations

**A. Mokrane, A. Choukchou Braham, B. Cherki**
Laboratoire d’Automatique de Tlemcen (LAT), University of Tlemcen, Tlemcen, Algeria

---

 
