# 🚚 Optimization of Last-Mile Delivery Routes using VRP

> Real-world delivery route optimization using Vehicle Routing Problem (VRP), OpenStreetMap road networks, and OR-Tools in Bengaluru.

---

## 📌 Project Overview

This project focuses on solving the **Last-Mile Delivery Optimization Problem** using the **Vehicle Routing Problem (VRP)** approach.

Using real-world road network data from Bengaluru (Indiranagar region), the system generates optimized delivery routes that minimize total travel distance while efficiently covering all delivery locations.

The project combines:
- Optimization Techniques
- Graph Algorithms
- Statistical Analysis
- Geographic Data Processing
- Data Visualization

---

## 🎯 Objectives

- Minimize total delivery distance
- Optimize vehicle routes
- Improve delivery efficiency
- Analyze delivery demand distribution
- Compare optimized vs random routing
- Perform scalability analysis using multiple vehicles

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Implementation |
| OSMnx | Road Network Extraction |
| NetworkX | Graph Operations |
| OR-Tools | Vehicle Routing Optimization |
| Matplotlib | Data Visualization |
| Pandas & NumPy | Data Processing |

---

## 🌍 Real-World Dataset

- Road network extracted using **OpenStreetMap**
- Bengaluru (Indiranagar region)
- Building footprints converted into delivery points
- Real shortest-path routing used instead of Euclidean distance

---

## 📊 Statistical Analysis

### Delivery Distance Statistics

| Metric | Value |
|---|---|
| Mean Distance | 594.82 m |
| Standard Deviation | 273.01 m |
| Minimum Distance | 31.18 m |
| Maximum Distance | 1382.01 m |

### Key Insights
- Most deliveries occur near the warehouse
- Delivery demand is highly localized
- Delivery time increases with distance
- Optimized routes significantly reduce travel cost

---

# 📈 Results & Visualizations

## 🚦 Optimized Vehicle Routes
Efficient delivery paths generated using VRP optimization.

![Optimized Routes](images/routes.png)

---

## 📍 Delivery Density Heatmap
Shows high-demand delivery regions near the warehouse.

![Heatmap](images/Delivery_Density_Heatmap.png)

---

## 📉 Delivery Distance Distribution
Histogram showing localized delivery demand.

![Histogram](images/Distance_Distribution.png)

---

## 🔄 Random vs Optimized Routing
Comparison showing distance reduction after optimization.

![Comparison](images/Route_Optimization_Comparison.png)

---

# ⚙️ Methodology

1. Extract Bengaluru road network
2. Identify building locations
3. Generate delivery demand points
4. Compute shortest-path distance matrix
5. Apply Vehicle Routing Problem (VRP)
6. Optimize routes using OR-Tools
7. Visualize optimized delivery paths

---

# 📌 Mathematical Model

The problem is modeled as a **Vehicle Routing Problem (VRP)**.

### Objective:
Minimize total travel distance:

\[
\min \sum_{i \in N}\sum_{j \in N} d_{ij}x_{ij}
\]

Where:
- \(d_{ij}\) = shortest path distance
- \(x_{ij}\) = routing decision variable

---

# 🚀 Key Achievements

✅ Real-world route optimization  
✅ Reduced delivery distance  
✅ Efficient vehicle utilization  
✅ Statistical analysis & visualization  
✅ Practical logistics optimization system  

---

# 🔮 Future Improvements

- Real-time traffic integration
- Dynamic order allocation
- Time-window constraints
- AI-based route prediction
- Large-scale fleet optimization

---

# 📂 Project Structure

```bash
VRP-Last-Mile-Delivery-Optimization/
│
├── notebooks/
├── images/
├── report/
├── README.md
└── requirements.txt

```

---

# ▶️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/krishnapatel-dev/VRP-Last-Mile-Delivery-Optimization.git
```

---

## Navigate to Project Directory

```bash
cd VRP-Last-Mile-Delivery-Optimization
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside:

```bash
notebooks/
```

---

# 📁 Dataset Information

The project uses:
- OpenStreetMap (OSM) road network data
- Real-world building footprints
- Simulated delivery demand generation

### Included CSV Files

| File | Description |
|---|---|
| `locations.csv` | Delivery location coordinates |
| `distance_matrix.csv` | Shortest path distance matrix |
| `building_delivery_data.csv` | Processed delivery dataset |
| `large_delivery_data.csv` | Extended delivery simulation data |

---

# 📌 Problem Complexity

The Vehicle Routing Problem (VRP) is an **NP-hard optimization problem**.

Challenges include:
- Route optimization
- Multiple vehicle allocation
- Distance minimization
- Scalability handling
- Real-world road constraints

This project uses heuristic optimization methods from **Google OR-Tools** to generate near-optimal solutions efficiently.

---

# 🧠 Skills Demonstrated

- Optimization Algorithms
- Graph Theory
- Geographic Data Processing
- Statistical Analysis
- Data Visualization
- Python Programming
- Real-World Problem Solving

---

# 💡 Engineering Applications

This project can be applied in:
- Quick Commerce Delivery
- Food Delivery Systems
- Logistics Optimization
- Smart City Transportation
- Fleet Management Systems
- E-commerce Delivery Platforms

---

# 📚 References

- OpenStreetMap
- Google OR-Tools Documentation
- OSMnx Documentation
- NetworkX Documentation

---

# 👨‍💻 Contributors

| Name | Contribution |
|---|---|
| Patel Krishna | VRP Modeling, Optimization & Analysis |

---

# ⭐ Why This Project Stands Out

✔ Real-world optimization problem  
✔ Uses actual geographic road networks  
✔ Strong visualization and analytics  
✔ Industry-relevant logistics application  
✔ Practical implementation using advanced Python libraries  

---

# 📜 License

This project is licensed under the MIT License.

---

# 🙌 Acknowledgment

Developed as part of the course:

**Statistical Methods and Optimization Techniques (25MTCSE102)**  
JAIN (Deemed-to-be University)

---

# 🌟 Support

If you found this project useful, consider giving it a ⭐ on GitHub.
