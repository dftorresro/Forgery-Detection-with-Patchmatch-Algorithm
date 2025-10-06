# Image Pattern Analysis and Modification

This repository contains the code and example outputs for a project focused on image pattern recognition and manipulation using advanced computer vision techniques.

## Project Overview

The core of this project is the Jupyter notebook `PF - IMA202a (v2.3 Patchmatch)` which contains the implementation of the Patchmatch algorithm—an efficient random search algorithm to find approximate nearest neighbor matches between image patches. 

This Jupyter notebook includes the following:
- Detailed explanation of the Patchmatch algorithm.
- Implementation of the algorithm in Python.
- Visualization of the algorithm's process and results.
- Optimizations and modifications to the original algorithm for improved performance.

### `512x512_squares.png`

An example image provided to showcase the result of the algorithm. The image contains a noisy background with clearly marked white squares, used for testing the pattern recognition capabilities of the Patchmatch implementation more focused on time consumption.

## How to Run the Project

To run the project, you will need Jupyter or an equivalent service that can execute `.ipynb` notebook files. Ensure you have all the necessary dependencies installed by running:

```bash
pip install -r requirements.txt
```

Open the Jupyter notebook and execute the cells in sequence to see the algorithm in action.

## Dependencies

- Python 3.x
- NumPy
- OpenCV
- Matplotlib
- Jupyter

A `requirements.txt` file should be included that lists the precise versions of these dependencies.
