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
