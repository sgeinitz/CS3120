# CS3120: Machine Learning Lab Notebooks

This repository contains the Jupyter notebooks, datasets, and images used in **CS3120: Introductory Machine Learning**. The labs are designed to give students hands-on practice with core machine learning ideas, from regression and model selection to neural networks and transfer learning.

## Labs

| Lab | Topic | Summary | Notebook | Colab | Kaggle |
| --- | --- | --- | --- | --- | --- |
| 1 | Linear Regression | Introduces linear regression, least-squares fitting, manual training, and why linear models are often stable and interpretable baselines. | [lab01_linear_regression.ipynb](lab01_linear_regression.ipynb) | [Open](https://colab.research.google.com/github/sgeinitz/CS3120/blob/main/lab01_linear_regression.ipynb) | [Open](https://kaggle.com/kernels/welcome?src=https://github.com/sgeinitz/CS3120/blob/main/lab01_linear_regression.ipynb) |
| 2 | Model Tuning and Selection | Covers performance metrics, underfitting vs. overfitting, the bias-variance tradeoff, and cross-validation with the Ames Housing dataset. | [lab02_model_tuning_and_selection.ipynb](lab02_model_tuning_and_selection.ipynb) | [Open](https://colab.research.google.com/github/sgeinitz/CS3120/blob/main/lab02_model_tuning_and_selection.ipynb) | [Open](https://kaggle.com/kernels/welcome?src=https://github.com/sgeinitz/CS3120/blob/main/lab02_model_tuning_and_selection.ipynb) |
| 3 | Artificial Neural Network from Scratch | Builds a simple neural network from scratch, compares it to logistic regression, and then incrementally introduces PyTorch autograd, modules, and optimizers. | [lab03_ann_from_scratch.ipynb](lab03_ann_from_scratch.ipynb) | [Open](https://colab.research.google.com/github/sgeinitz/CS3120/blob/main/lab03_ann_from_scratch.ipynb) | [Open](https://kaggle.com/kernels/welcome?src=https://github.com/sgeinitz/CS3120/blob/main/lab03_ann_from_scratch.ipynb) |
| 4 | Transfer Learning with a CNN | Uses a pre-trained convolutional neural network in PyTorch to apply transfer learning on an image classification task. | [lab04_transfer_learning.ipynb](lab04_transfer_learning.ipynb) | [Open](https://colab.research.google.com/github/sgeinitz/CS3120/blob/main/lab04_transfer_learning.ipynb) | [Open](https://kaggle.com/kernels/welcome?src=https://github.com/sgeinitz/CS3120/blob/main/lab04_transfer_learning.ipynb) |

## Getting Started

### Online
Each lab notebook can be opened directly in **Google Colab** or **Kaggle** using the links above. This is the quickest option if you do not want to configure a local Python environment.

### Local Environment
If you prefer to run the notebooks locally, install Python 3 and the required libraries.

**Clone the repository**
```bash
git clone https://github.com/sgeinitz/CS3120.git
cd CS3120
```

**Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels ipywidgets jupyter torch torchvision
```

**Launch Jupyter**
```bash
jupyter notebook
```

## Repository Structure

- `lab01_linear_regression.ipynb` through `lab04_transfer_learning.ipynb`: The lab notebooks.
- `data/`: Tabular datasets used in the earlier labs.
- `images/`: Figures, illustrations, and image assets used in the notebooks, including the transfer learning image dataset.

## Saving and Submitting Your Work

After completing a lab, share your finished notebook using either a GitHub Gist or a GitHub repository.

### Option A: GitHub Gist

1. **Save your notebook.** In Jupyter or Colab, run all cells and save the notebook (`File > Save`).
2. Go to [gist.github.com](https://gist.github.com).
3. Drag the downloaded `.ipynb` file into the editor.
4. Click **Create secret gist** (or public gist, if you prefer).
5. Copy the resulting URL and submit it.

### Option B: GitHub Repository

1. Create a repository at [github.com/new](https://github.com/new), for example `CS3120-Coursework`.
2. Upload your notebook:
   - Via browser: open the repo, select **Add file > Upload files**, and upload the `.ipynb` file.
   - Via Colab: use `File > Save a copy in GitHub`, authorize GitHub, and choose your repository.
3. Copy the link to the notebook file and submit it.

## Submission Checklist

Before submitting your link:

1. **Run all cells** so outputs are visible.
2. **Answer all questions** in markdown or code cells.
3. **Verify the link** in an incognito or logged-out browser window.
4. **Submit the link** to Canvas.
