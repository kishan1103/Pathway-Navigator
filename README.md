


https://github.com/user-attachments/assets/713e68fb-b3b5-4295-8142-b0314bfb0fd0

# 🧭 Pathway-Navigator

An interactive web-based visualizer for popular Pathway-Navigator algorithms like **Dijkstra**, **BFS**, **DFS**, and a basic **A\*** search. Users can create barriers, set start/end points, and see how algorithms traverse through the grid in real-time.

![Visualizer Preview](./preview.gif) <!-- Optional: Add preview.gif or screenshot.png -->

---

## 🚀 Features

- 🎯 **Algorithm Support**:
  - Dijkstra's Algorithm (Shortest Path)
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Greedy Best-First Search (A\*)

- 🧱 **Drag & Drop**:
  - Move **Start** and **End** nodes easily.
  
- 🧱 **Wall Drawing**:
  - Click or drag to create/remove obstacles.

- 🎥 **Visualization**:
  - Smooth animations for visited nodes and final paths.

- 🔄 **Reset Options**:
  - Clear grid without affecting walls
  - Full reset including walls and visited nodes

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- No frameworks or external libraries — all logic written from scratch.

---

## 📦 Folder Structure

```

├── index.html
├── styles.css
├── script.js
└── preview\.gif  <-- Optional: for GitHub preview

````

---

## 🧪 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/your-username/Pathway-Navigator-visualizer.git
````

2. **Open `index.html` in your browser**

```bash
cd Pathway-Navigator-visualizer
open index.html
```

3. **Start building walls and visualizing paths!**

---

## 🎓 Algorithms at a Glance

| Algorithm | Guarantees Shortest Path | Weighted | Technique      |
| --------- | ------------------------ | -------- | -------------- |
| Dijkstra  | ✅ Yes                    | ✅ Yes    | Greedy         |
| BFS       | ✅ Yes (unweighted)       | ❌ No     | Queue (FIFO)   |
| DFS       | ❌ No                     | ❌ No     | Stack (LIFO)   |
| A\*       | ❌ Not full A\* yet       | ❌ No     | Heuristic Only |

---

## 📌 To-Do (Future Enhancements)

* ✅ Add real A\* with proper g(n) + h(n)
* 🎨 UI improvements (icons, animations)
* 📱 Mobile responsiveness
* ⚙️ Speed slider for animations
* 🌐 Deploy on GitHub Pages

---

## 📸 Demo

Check out the live version: [**Live Demo Here**](https://your-username.github.io/Pathway-Navigator-visualizer)

---

## 🤝 Contributing

Pull requests are welcome! If you have ideas for features or improvements, feel free to fork and submit a PR.

---

## 📄 License

MIT License — free to use and modify.

---
