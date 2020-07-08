---
title: "Sudoku Solver"
excerpt: "Web app to detect, extract and solve a sudoku puzzle from an image.<br/><img src='/images/sudoku_solver.png'>"
collection: portfolio
---

[*Project link*](https://github.com/piyushsoni27/sudokuSolver/tree/c9494395a3c76ee1e47ababd40490bce32524399)

- A Flask app which can detect Sudoku from the uploaded image by applying adaptive thresholding, morphological operations and taking largest contour (assuming major part of image contains Sudoku).
- Once sudoku is detected in the image, digits present in each cells are extracted and recognized with the help to digit  recognizer machine learning model.
- Used MNIST Handwritten digits dataset with CNN network with accuracy of 98.2% on test set.
- **Technologies:** Python, Flask, OpenCV, Keras
