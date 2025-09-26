# maze-solver-AI

Maze-solving that reads a **text-based maze**, finds a path from **start (A)** to **goal (B)** using **breadth-first search**, prints the solved maze in the console, and exports a **PNG image** showing explored cells and the solution path.

## ✨ Features
- 🔎 **Breadth-First Search** (queue frontier) to guarantee the shortest path  
- 🖨️ Prints maze & solution to the console using ASCII characters  
- 🖼️ Exports a PNG image visualizing:
  - Walls (dark gray)  
  - Start (red) & Goal (green)  
  - Solution path (light yellow)  
  - Explored cells (yellow)  
- 💡 Single-file implementation for easy reading and running  

## 🛠 Requirements
- Python 3.8+
- Pillow>=9.0

## 🚀 Usage

1. **Clone the repo** and move into the project folder:
```bash
git clone https://github.com/<your-username>/maze-solver-ai.git
cd maze-solver-ai
```
2. **Install dependencies**(requires Python 3.8+):
```bash
pip install -r requirements.txt
```
3. **Run the solver** with one of the sample mazes:
```bash
python maze.py mazes/maze1.txt
```
Replace maze1.txt with any of the provided sample files (maze2.txt, maze3.txt, maze4.txt) or with your own custom maze file.

## Maze file format
- Use plain text.
- A marks the start; B marks the goal.
- Spaces ( ) are walkable.
- Any other character is treated as a wall.
- Each line is a row in the maze; lines may have varying lengths.

**About This Project**
Built originally in 2023, uploaded to GitHub in 2025.
  — Eyoab T.
