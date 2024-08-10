# Adobe
For the Adobe GenSolve Hackathon
# Curvetopia

## Overview

This project provides a set of tools to process, analyze, and visualize curves described in CSV files. It includes functionalities for regularizing curves, detecting symmetries, completing curves, and saving the processed data as plots and SVG files.

## Project Structure

- `main.py`: The main script to process input CSV files and generate output plots and SVGs.
- `src/`: Contains the utility and core processing modules.
  - `utils.py`: Utility functions for reading CSVs, saving plots, and converting paths to SVGs.
  - `regularize.py`: Functions to regularize curves by identifying shapes like lines, circles, and rectangles.
  - `symmetry.py`: Functions to detect symmetries in regularized curves.
  - `completion.py`: Functions to complete curves by connecting their endpoints if necessary.

## Installation

### Prerequisites

- Python 3.x
- `numpy`: For numerical operations.
- `matplotlib`: For plotting curves.
- `svgwrite`: For saving curves as SVG files.
- `cairosvg`: For converting SVGs to other formats (if needed).

### Installation Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/curve-processing.git
    cd curve-processing
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install numpy matplotlib svgwrite cairosvg
    ```

## Usage

### Input Data

Input data should be in CSV format. Each CSV file should contain rows of points belonging to different paths. The format should be:


