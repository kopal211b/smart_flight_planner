# ✈️ Smart Flight Planner

**Smart Flight Planner** is an intelligent and interactive web-based flight pathfinding system that computes optimal flight routes based on user preferences like cost, travel time, or number of stops. It visualizes routes on a map and simulates real-world airline networks with smart pathfinding algorithms and interactive UI.

---

## 🔍 Features

- 🧠 **Pathfinding Algorithms**:  
  - **BFS**: Routes with **minimum stops**  
  - **Dijkstra's**: Routes with **minimum cost**  
  - **Dijkstra's**: Routes with **minimum time**

- 🗺️ **Interactive Map Visualization** using **Leaflet.js**
- 🧾 **Dynamic Results Panel**: Displays optimized path details and travel summary
- 🌐 **City-to-Airport Mapping** with backend API integration
- 📦 **Clean modular backend** with support for future data scaling
- 📊 **Before vs Optimized Path** comparison for better decision-making

---

## ⚙️ Tech Stack

| Frontend        | Backend        | Algorithms      | Mapping         |
|-----------------|----------------|------------------|------------------|
| HTML, CSS, JS   | Python + Flask | BFS, Dijkstra, A* | Leaflet.js       |

---

## 🚀 Getting Started

### 🛠️ Prerequisites

- Python 3.10+
- Flask
- Pandas, NumPy
- Node.js (optional, for bundling static assets)

### ⚙️ Setup Instructions

```bash
# Clone the repository
git clone https://github.com/kopal211b/smart_flight_planner.git
cd smart_flight_planner

# (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the Flask server
python app.py
