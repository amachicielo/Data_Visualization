# Scientific Data Visualization with Python

A practical notebook covering the main building blocks of scientific plotting with Matplotlib, NumPy, and SymPy—from simple functions to advanced layouts and 3D charts.

## Topics covered

- Figures, axes, labels, legends, annotations, and styling
- Line, logarithmic, twin-axis, and colormap plots
- Subplots, GridSpec, inset axes, and custom layouts
- Three-dimensional plotting
- Inline and interactive notebook backends

## Notebook

Open [plotting-and-visualization.ipynb](plotting-and-visualization.ipynb) to see the explanations, code, and saved chart outputs.

## Run locally

    python -m venv .venv
    # Windows: .venv\Scripts\activate
    # macOS/Linux: source .venv/bin/activate
    pip install jupyter matplotlib numpy sympy pyqt5
    jupyter notebook

Most examples work with Jupyter's inline backend. The optional Qt example needs a desktop environment and PyQt5; skip that cell in headless or cloud notebooks.

## Scope

This repository is an educational visualization reference. It demonstrates breadth with Matplotlib, but it is not a packaged visualization library or production dashboard.
