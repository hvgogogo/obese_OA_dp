🔬 Fibroblasts Analysis Portal
A comprehensive web-based analysis platform for exploring fibroblast cell populations in obese osteoarthritis (OA) conditions.
🌟 Features

Interactive UMAP Visualization - Explore cell clusters and subtypes
Gene Expression Analysis - Visualize expression patterns across cell populations
Differential Gene Expression - Compare genes between disease conditions
Pathway Enrichment Analysis - Identify significant biological pathways
Cell Trajectory Analysis - Track fibroblast differentiation pathways
Cell-Cell Interaction Networks - Explore intercellular communications

🚀 Quick Start
https://hvgogogo.github.io/obese_OA_dp




📁 Repository Structure
obese_OA_dp/
├── index.html              # Main application page
├── app.js                  # JavaScript application logic
├── style.css               # Styling and responsive design
├── data/                   # Data files
│   ├── UMAP_Visualization.json
│   ├── Gene_Expression.json
│   ├── Marker_Expression.json
│   └── csvs/               # CSV data files
│       ├── DEGs_*.csv      # Differential expression results
│       └── paths_sig_*.csv # Pathway enrichment results
└── assets/
    └── images/
        ├── fig3.png        # Trajectory analysis figure
        └── fig4.png        # Cell interaction figure
