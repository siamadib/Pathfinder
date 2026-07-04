# 🧭 Pathfinder - Graph Traversal & Pathfinding Visualizer

An interactive **Pathfinding Algorithm Visualizer** built with **HTML, CSS, and JavaScript**. This project demonstrates how different graph traversal and shortest path algorithms explore a grid to find a route between two nodes.

## 🚀 Features

- 🔍 Visualize multiple pathfinding algorithms
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Dijkstra's Algorithm
  - A* Search Algorithm

- 🧱 Interactive Grid
  - Draw and erase walls
  - Add weighted terrain (cost ×5)
  - Move Start and End nodes

- ⚡ Animation Controls
  - Adjustable visualization speed
  - Animated node exploration
  - Animated shortest path

- 📊 Live Statistics
  - Current algorithm status
  - Nodes visited
  - Path length
  - Total path cost

- 🎲 Utility Tools
  - Random terrain generator
  - Clear path
  - Clear entire board

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

---

## 📖 Algorithms Included

### 🔹 Breadth-First Search (BFS)
- Explores nodes level by level.
- Finds the shortest path in an unweighted graph.
- Ignores terrain cost.

### 🔹 Depth-First Search (DFS)
- Explores as deep as possible before backtracking.
- Does not guarantee the shortest path.
- Ignores terrain cost.

### 🔹 Dijkstra's Algorithm
- Finds the minimum-cost path.
- Considers weighted terrain.
- Guarantees the optimal path.

### 🔹 A* Search Algorithm
- Uses a heuristic (Manhattan Distance).
- Faster than Dijkstra in most cases.
- Finds the optimal path while considering terrain cost.

---

## 🎮 How to Use

1. Open `pathfinder.html` in your browser.
2. Choose a pathfinding algorithm.
3. Select a drawing tool:
   - Wall
   - Terrain
   - Start Node
   - End Node
   - Erase
4. Design your grid.
5. Adjust animation speed.
6. Click **Visualize** to watch the algorithm in action.

---

## 📊 Visualization Legend

| Color | Meaning |
|--------|---------|
| 🟦 Cyan | Start Node |
| 🟨 Amber | End Node |
| ⬛ Dark | Wall |
| 🟫 Brown | Weighted Terrain |
| 🟩 Light Cyan | Visited Node |
| 🟨 Yellow | Final Path |

---

## ⏱️ Time Complexity

| Algorithm | Time Complexity | Shortest Path |
|-----------|-----------------|---------------|
| BFS | O(V + E) | ✅ (Unweighted) |
| DFS | O(V + E) | ❌ |
| Dijkstra | O((V + E) log V) | ✅ |
| A* | Depends on heuristic | ✅ |

---

## 📚 Learning Objectives

This project helps visualize and understand:

- Graph Traversal
- Shortest Path Algorithms
- Greedy Algorithms
- Heuristic Search
- Grid-Based Pathfinding
- Animation using JavaScript
- DOM Manipulation

---

⭐ If you found this project helpful, consider giving it a star!
