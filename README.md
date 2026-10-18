# 🧠 IdeaVanta

### Connect your notes. Discover relationships. Think in networks.

IdeaVanta is a personal knowledge graph that helps you organize notes, connect ideas, and explore relationships between your learning, projects, and interests.

Instead of keeping information in disconnected lists, MindMesh lets you build a network of connected knowledge.

## ✨ Features

- **Interactive Knowledge Graph** — Visualize notes and the relationships between them.
- **Note Management** — Create, edit, and delete notes.
- **Tags and Organization** — Categorize ideas and keep information organized.
- **Search and Filtering** — Find relevant notes quickly.
- **Idea Connections** — Link related notes and remove connections when needed.
- **Data Export** — Export your knowledge as JSON backups or Markdown.
- **Data Import** — Restore notes from a JSON backup.

## 🛠️ Built With

- **Python** — Core application logic
- **Streamlit** — User interface
- **PyVis** — Interactive graph visualization
- **NetworkX** — Graph and network operations

## 🚀 Getting Started

### Requirements

- Python 3.9 or newer recommended
- pip
- A modern web browser

### 1. Clone the repository

```bash
git clone https://github.com/isha-arjun/MindMesh.git
cd MindMesh
```

2. Install dependencies
```bash
pip install -r requirements.txt
```


3. Run MindMesh
```bash
streamlit run mindmesh_app.py
```

4. Open the app
Streamlit will display a local URL in your terminal, usually:
```bash
http://localhost:8501
Open that address in your browser.

📂 Project Structure
MindMesh/
├── mindmesh_app.py   # Main application
├── requirements.txt  # Python dependencies
├── README.md         # Project documentation
├── LICENSE           # MIT License
└── .gitignore        # Files excluded from Git
```


💾 Data and Privacy
MindMesh currently uses a JSON file for application data in its development environment.
- Export your notes regularly to keep backups.
- Temporary environments such as Google Colab may erase files when the runtime resets.
- Deploying the app publicly does not automatically provide permanent storage.
- Do not upload passwords, API keys, or private notes to a public repository.
Persistent storage and deployment-specific data handling may require additional implementation.
🗺️ Roadmap
Potential improvements include:
- [ ] Persistent database storage
- [ ] Automatic saving and backup improvements
- [ ] Improved mobile-friendly interface
- [ ] Customizable graph layouts
- [ ] Advanced filtering and search
- [ ] Import and export enhancements
- [ ] Public deployment
- [ ] Optional AI-assisted note connections
These are planned possibilities, not claims about features already implemented.
🤝 Contributing
Suggestions, bug reports, and contributions are welcome!
1. Fork the repository.
2. Create a branch for your change.
3. Make and test your improvements.
4. Submit a pull request describing your changes.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
👩‍💻 Project Status
Status: Early prototype
MindMesh is an evolving project exploring visual knowledge management and connected thinking.
Built with AI assistance and a focus on learning, experimentation, and practical software development.

If you find MindMesh interesting, consider starring the repository ⭐
