[README .md](https://github.com/user-attachments/files/33707065/README.2.md)
# Data Science

A collection of Jupyter notebooks covering core data analysis and machine learning algorithms, from regression and classification to clustering, tree-based models, and deep learning.

> **Status:** Work in progress

## Notebooks

| Notebook | Topic | Type |
|----------|-------|------|
| [`dataAnalysis.ipynb`](./dataAnalysis.ipynb) | Exploratory data analysis and data preparation | Analysis |
| [`linear_regression.ipynb`](./linear_regression.ipynb) | Linear regression | Supervised, regression |
| [`logistic_regression.ipynb`](./logistic_regression.ipynb) | Logistic regression | Supervised, classification |
| [`kNearest.ipynb`](./kNearest.ipynb) | k-Nearest Neighbors | Supervised |
| [`svm.ipynb`](./svm.ipynb) | Support Vector Machines | Supervised |
| [`decision_tree_random_forest.ipynb`](./decision_tree_random_forest.ipynb) | Decision trees and random forests | Supervised, ensemble |
| [`kmeans.ipynb`](./kmeans.ipynb) | K-Means clustering | Unsupervised |
| [`deeplearning.ipynb`](./deeplearning.ipynb) | Neural networks and deep learning | Deep learning |

## Repository Structure

```
data-science/
├── data/                              # Datasets used in the notebooks
├── dataAnalysis.ipynb
├── decision_tree_random_forest.ipynb
├── deeplearning.ipynb
├── helper_functions.py                # Reusable helper functions
├── kNearest.ipynb
├── kmeans.ipynb
├── linear_regression.ipynb
├── logistic_regression.ipynb
└── svm.ipynb
```

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
git clone https://github.com/Abrashid10/data-science.git
cd data-science

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
```

> If your deep learning notebook uses PyTorch instead of TensorFlow, install `torch` instead.

### Run a notebook

```bash
jupyter notebook
```

Then open any notebook from the list above. Datasets are loaded from the `data/` folder, and shared utilities live in `helper_functions.py`.

## Topics Covered

- **Data analysis:** cleaning, exploring, and visualizing data
- **Regression:** linear regression
- **Classification:** logistic regression, k-NN, SVM, decision trees, random forests
- **Clustering:** K-Means
- **Deep learning:** neural networks

## Roadmap

- [ ] Add a short description and results summary to each notebook
- [ ] Add a `requirements.txt`
- [ ] Document the source of each dataset in `data/`
- [ ] Add model evaluation comparisons across algorithms
- [ ] Add more algorithms (PCA, gradient boosting, hierarchical clustering)

## Author

**Abdallah**  
GitHub: [@Abrashid10](https://github.com/Abrashid10)

## License

Add a license of your choice (for example MIT) and update this section.
