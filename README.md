# UC Berkeley BioE C242 Course Repository

This repository contains the coursework for BioE C242 at UC Berkeley, focusing on Machine Learning, Statistical Models, and Optimization for Molecular Problems, taught by Prof. Teresa Head-Gordon. Here, you will find both the homework assignments and the final project for this course.

## Course Structure

- **Homeworks**: Jupyter notebooks for each homework assignment (HW1 to HW9), covering various aspects of machine learning and molecular modeling.
- **Final Project**: A comprehensive project utilizing ML models to predict the anti-HIV benefits of drugs. The project includes:
  - Jupyter notebook (`BioE 242 - Final Project.ipynb`)
  - Project Presentation (`BioE C242 - Final Project Presentation.pdf`)
  - Progress Report (`C242Project-ProgressReport.pdf`)

## Final Project Overview

The final project aims to develop ML and DL algorithms capable of predicting the anti-HIV benefits of various compounds, utilizing a dataset provided by the National Cancer Institute. Techniques used include:

- **Graph Neural Networks (GNNs)**: For processing molecular structures as graphs.
- **Random Forest and XGBoost Classifiers**: For benchmarking and predictive modeling.
- **MLP (Multi-Layer Perceptron)**: For deep learning predictions.

The models are evaluated using the ROC AUC metric, focusing on their ability to handle the imbalanced nature of the dataset, which contains a small proportion of active molecules.

## Tools and Libraries

- [**PyTorch**](https://pytorch.org): An open-source machine learning library used for applications such as computer vision and natural language processing, particularly well-suited for deep learning models.
- [**PyTorch Geometric (PyG)**](https://pytorch-geometric.readthedocs.io/en/latest/#): A library built on top of PyTorch, designed to create, train, and test deep learning models on graphs and other irregular structures.
- [**RDKit**](https://www.rdkit.org): An open-source cheminformatics software.
- [**Scikit-Learn (sklearn)**](https://scikit-learn.org/stable/): A machine learning library for Python. It features various classification, regression, and clustering algorithms.
- [**XGBoost**](https://xgboost.readthedocs.io/en/stable/#): An optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.

## References

For detailed insights and techniques applied in the projects and homeworks, please refer to the official documentation and studies listed in the `BioE C242 - Final Project Presentation.pdf`.
