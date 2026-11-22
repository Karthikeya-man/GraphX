# GraphX
GraphX – Graph Traversal Algorithm Visualizer

An interactive web application to visualize Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms step by step.

🚀 Overview

GraphX is an interactive, browser-based learning platform designed to help students understand graph traversal algorithms through visualization.

Users can create custom graphs, select a traversal algorithm, choose a starting node, and watch how BFS and DFS explore the graph in real time. The application displays the queue, stack, visited nodes, traversal order, highlighted pseudocode, and plain-English explanations at every step.

✨ Features

- Interactive Graph Builder: Create, edit, drag, rename, and delete nodes and edges.
- BFS Visualization: Understand Breadth-First Search using a Queue (FIFO).
- DFS Visualization: Explore Depth-First Search using a Stack (LIFO).
- Step-by-Step Execution: Start, pause, resume, reset, and move through algorithm steps.
- Live Algorithm State: View the current node, queue/stack, visited nodes, and traversal order.
- Pseudocode Highlighting: Follow the exact algorithm line being executed.
- Step Explanations: Understand what happens at every stage in simple English.
- Practice Arena: Test your knowledge with random questions and three difficulty levels.
- Dark & Light Themes: Switch between themes.
- Responsive Design: Works on desktop, tablet, and mobile devices.
- Keyboard Shortcuts: Control the visualizer quickly using keyboard commands.

🛠️ Tech Stack

Technology| Purpose
HTML5| Web page structure
CSS3| Styling, themes, and animations
JavaScript (ES6)| Graph logic and algorithms
SVG| Interactive graph rendering
Google Fonts| Typography
LocalStorage| Saving theme preferences

No frameworks, backend, database, or external graph libraries are required.

🧠 Algorithms Implemented

1. Breadth-First Search (BFS)

- Uses a Queue (FIFO).
- Explores nodes level by level.
- Visits neighboring nodes before moving deeper.

Time Complexity: "O(V + E)"
Space Complexity: "O(V)"

2. Depth-First Search (DFS)

- Uses an explicit Stack (LIFO).
- Explores one path as deeply as possible.
- Uses backtracking when it reaches a dead end.

Time Complexity: "O(V + E)"
Space Complexity: "O(V)"

Where:

- "V" = Number of vertices (nodes)
- "E" = Number of edges

⌨️ Keyboard Shortcuts

Shortcut| Action
"Space"| Start / Pause
"→"| Next Step
"R"| Reset
"Delete"| Remove Node
"Esc"| Cancel

💻 Getting Started

No installation or additional dependencies are required.

1. Clone the repository:
   
   git clone https://github.com/your-username/GraphX.git

2. Open the project folder:
   
   cd GraphX

3. Open the "index.html" file in your browser.

That's it! Start building graphs and exploring BFS and DFS.

🎯 Learning Objectives

GraphX aims to make graph traversal easier to understand by helping learners:

- Understand how BFS and DFS work internally.
- Differentiate between Queue and Stack operations.
- Visualize node discovery and traversal order.
- Understand DFS backtracking.
- Experiment with custom graphs.
- Practice algorithm-related questions.

🔮 Future Improvements

- Implement Dijkstra's Shortest Path Algorithm.
- Add cycle detection and connected components.
- Implement topological sorting.
- Add previous-step and step-slider controls.
- Save, export, and share custom graphs.
- Introduce an expanded Learning Hub.
- Add user accounts and leaderboards.
- Migrate to React, TypeScript, and Tailwind CSS.

👨‍💻 Project Information

Project Name: GraphX
Category: Educational Technology / Algorithm Visualization
Domain: Data Structures and Algorithms
Developed By: G. Bhagath

📚 References

- Introduction to Algorithms – Cormen, Leiserson, Rivest, and Stein.
- Algorithms – Robert Sedgewick and Kevin Wayne.
- The Algorithm Design Manual – Steven S. Skiena.
- "MDN Web Docs" (https://developer.mozilla.org/)
- "VisuAlgo – Graph Traversal" (https://visualgo.net/en/dfsbfs)

---

GraphX – Learn. Build. Visualize. Understand.
