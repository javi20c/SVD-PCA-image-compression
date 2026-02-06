# Image Processing Analysis🐔
### Mathematical Foundations for Data Compression and Dimensionality Reduction

## Project Overview

Modern data science relies on linear algebra to handle high dimensional information efficiently. This project demonstrates the practical application of Singular Value Decomposition and Principal Component Analysis to process images. It bridge the gap between abstract mathematical theorems and computational implementation through a series of experiments focused on data compression and feature identification.

## Key Features

* Image Compression via SVD: Implements matrix decomposition to approximate images using a reduced number of singular values while maintaining visual integrity. 
* Dimensionality Reduction with PCA: Applies covariance matrix analysis to project high dimensional data into a lower dimensional space. 
* Theoretical and Practical Analysis: Includes a detailed breakdown of the mathematical properties of matrices and their behavior in a computational environment. 
* Performance Evaluation: Compares the efficiency and reconstruction error of different compression levels.

## Tech Stack

* Language: Python 3. Libraries: NumPy, Pandas, Matplotlib, and Scikit-learn. 
* Environment: Google Colab. Version Control: Git and GitHub.

## Technical Implementation

* Applied Singular Value Decomposition to decompose image matrices into U, Sigma, and V transpose components.
* Calculated the explained variance ratio to determine the optimal number of principal components for data reconstruction.
* Utilized Matplotlib to visualize the trade off between compression ratio and image quality.
* Optimized numerical operations using vectorized NumPy functions to ensure scalability with larger datasets.

## Screenshots

<div align = "center">
  <img src = "https://github.com/user-attachments/assets/3c9f8f47-5c69-4fe1-9b64-a992111a9c99" width = "575" alt = "PCA"/>
  <img src = "https://github.com/user-attachments/assets/959bd66d-88e5-4293-9c42-a72962040fe4" width = "250" alt = "3D" />
</div>

## How to Run

1. Clone this repository: git clone https://github.com/javi20c/SVD-PCA-image-compression.git
2. Open the .ipynb file in Google Colab or a local Jupyter Notebook environment.
3. Install the dependencies using: pip install -r requirements.txt.
4. Execute the cells in order to see the analysis and visualization results.

Developed by [**Andy Cobeña**](https://www.linkedin.com/in/andy-cobe%C3%B1a-3a329a306/) - *Data Science and Artificial Intelligence Engineering Student @ ESPOL*🎓
