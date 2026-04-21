Graph Neural Network (GCN) on Karate Club Dataset

This project demonstrates how to build and train a Graph Convolutional Network (GCN) using PyTorch Geometric on the classic Karate Club dataset.
It includes graph visualization, node classification, and embedding analysis.

🚀 Features
📊 Graph-based data processing using GNNs
🧠 Node classification with GCN
📉 Training with loss & accuracy tracking
🎥 Animation of learning over epochs
🌐 Graph visualization using NetworkX
📦 3D embedding visualization
🛠️ Tech Stack
Python
PyTorch
PyTorch Geometric
NetworkX
Matplotlib
NumPy
Optuna (for hyperparameter tuning - optional)
📂 Dataset
Karate Club Dataset
Contains:
34 nodes (members)
156 edges (relationships)
Each node has feature vectors and labels
⚙️ Installation
pip install torch torch_geometric optuna networkx matplotlib
▶️ How It Works
1. Load Dataset
Load graph using KarateClub()
Extract:
Node features
Edge indices
Labels
2. Data Processing
Convert data into DataFrames for inspection
Random labels assigned for experimentation
3. Model Architecture
GCN Layer → extracts graph features
Linear Layer → performs classification
GCNConv(input_features, hidden_dim)
Linear(hidden_dim, num_classes)
🧠 Model Training
Loss Function: CrossEntropyLoss
Optimizer: Adam
Epochs: 200
📈 Training Results
Epoch	Loss	Accuracy
0	1.46	20.59%
100	0.44	94.12%
190	0.14	97.06%

✔ Model successfully learns node classification patterns.

📊 Visualizations
🔹 Graph Structure
Nodes colored by labels
Layout using spring layout
🔹 Training Animation
Shows how predictions improve over time
🔹 3D Embeddings
Final node embeddings visualized in 3D space
📸 Sample Outputs

(Add screenshots here from your notebook)

Graph visualization
Training animation
3D embedding plot
📈 Key Learnings
How GNNs process relational data
Difference between traditional ML and graph-based learning
Importance of node embeddings
Visualization of graph learning
