# dagvision

---

## 🧠 Problem Statement

Most DAG visualizers are static, lacking intelligent feedback and real-time interactivity. Users have no way to explore anomalies or understand the structure of the graph as it evolves. This project solves the problem by offering a live, AI-powered DAG explorer.

---

## 🎯 Objective

To design and implement an intelligent DAG visualization system that allows users to:
- View dynamic DAGs in real-time
- Analyze transaction behavior using confidence scores
- Detect anomalies automatically
- Perform CRUD operations on transactions
- Receive actionable insights from graph patterns

---

## 🔧 Methodology

- **Frontend:** React.js with Cytoscape.js for graph rendering and UI interaction
- **Backend:** FastAPI REST API that handles CRUD operations and serves data
- **Database:** MongoDB stores nodes and links
- **AI Logic:** Computes confidence scores and detects anomalies
- **Visualization:** DAG layout using dagre algorithm in Cytoscape

---

## 🔬 Tech Stack

**Frontend:** React.js, Cytoscape.js, Tailwind CSS  
**Backend:** FastAPI (Python 3.11+)  
**Database:** MongoDB  


---

## 🌍 Live Demo / Submission Files

📥 Download all project files from this Drive link:  
**[[👉 Click here](https://drive.google.com/your-drive-link-here)](https://drive.google.com/file/d/1UGk-VbcCcMGVk5WIVY24ZLDGHovjW5wa/view?usp=sharing)**  
*(Replace with your actual Google Drive share link)*

---



### Backend (FastAPI):
```bash
cd server
pip install -r requirements.txt
uvicorn main:app --reload
