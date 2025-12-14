# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a comprehensive NetworkX tutorial in Japanese, consisting of 12 Jupyter Notebook chapters covering graph analysis from beginner to advanced levels.

## Development Commands

```bash
# Install dependencies
pip install networkx matplotlib numpy pandas scipy

# Run Jupyter
jupyter notebook
# or
jupyter lab
```

## Repository Structure

- `01_introduction.ipynb` - `04_graph_attributes.ipynb`: Beginner level (basics, graph types, attributes)
- `05_graph_generators.ipynb` - `08_centrality.ipynb`, `10_visualization.ipynb`, `11_io_operations.ipynb`: Intermediate level (algorithms, visualization, I/O)
- `09_clustering_communities.ipynb`, `12_advanced_topics.ipynb`: Advanced level (community detection, network flow)
- `A1_pluralistic_ignorance.ipynb`: Appendix - Pluralistic ignorance simulation with agent-based model
- `A2_spiral_of_silence.ipynb`: Appendix - Spiral of silence theory simulation
- `A3_friendship_paradox.ipynb`: Appendix - Friendship paradox analysis and visualization
- `A4_six_degrees.ipynb`: Appendix - Six degrees of separation and small-world networks
- `A5_weak_ties.ipynb`: Appendix - Strength of weak ties theory and bridge detection
- `A6_structural_holes.ipynb`: Appendix - Structural holes theory and brokerage analysis
- `A7_information_cascades.ipynb`: Appendix - Information cascades and social contagion models
- `A8_echo_chambers.ipynb`: Appendix - Echo chambers, filter bubbles, and opinion polarization
- `A9_preferential_attachment.ipynb`: Appendix - Preferential attachment and scale-free networks
- `A10_homophily.ipynb`: Appendix - Homophily, assortativity, and social segregation
- `A11_diffusion_of_innovations.ipynb`: Appendix - Diffusion of innovations, Bass model, and critical mass

## Chapter Structure Convention

Each notebook follows a consistent structure:
1. Learning objectives (学習目標)
2. Explanations with code examples
3. Practical examples (例題)
4. Practice problems (練習問題) with solutions in `<details>` tags
5. Chapter summary (章のまとめ)

## Content Guidelines

- All content is written in Japanese
- Each chapter includes 3+ practice problems with model answers
- Visualizations use matplotlib with `%matplotlib inline`
- Standard imports: `import networkx as nx`, `import matplotlib.pyplot as plt`, `import numpy as np`, `import japanize_matplotlib`
