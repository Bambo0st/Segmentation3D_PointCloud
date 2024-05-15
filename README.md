# Semantic Segmentation of 3D Point Cloud

This project focuses on semantic segmentation of 3D point cloud data. Semantic segmentation is the task of classifying each point in a point cloud into one of several predefined categories or classes. This README provides an overview of the project structure and how to use the provided files for training and testing.

## Overview

The project consists of the following main components:
- **Final_train:** Contains the final training dataset for semantic segmentation.
- **Final_test:** Contains the final testing dataset for semantic segmentation.

## Dataset
The dataset used for this repo is the H3D Benchmark Dataset. You can access the dataset [here](https://ifpwww.ifp.uni-stuttgart.de/benchmark/hessigheim/subscribe.aspx).

## Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Bambo0st/Segmentation3D_PointCloud
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Segmentation3D_PointCloud
    ```

3. **Open the folder in your Jupyter environment.**

4. **Run Final_train.ipynb:**
    - Open Final_train.ipynb and replace the data file name with your file name.
    - Run the notebook. This generates a random forest model saved as a joblib file.

5. **Run Final_test.ipynb:**
    - Open Final_test.ipynb and replace the data file name with your file name.
    - Run the notebook to see the evaluations of predictions made by the model.

## Contributor

- [Adithya Nagaraja Somasalle](https://github.com/Bambo0st)
