# Machine Learning Practice

### A structured, hands-on journey from ML fundamentals to production-ready machine learning.

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Learning%20%26%20Practice-informational)]()

**Author:** Md. Shagor Ali

---

## About This Repository

Welcome to my **Machine Learning Practice** repository. This is my
organized workspace for learning, implementing, experimenting with, and
documenting Machine Learning concepts using Python.

The repository follows a beginner-to-advanced roadmap, combining
mathematical intuition, hands-on Jupyter notebooks, data analysis, model
evaluation, and end-to-end projects. It will evolve as I study new
topics and improve my implementations.

### Goals

-   Build a strong foundation in ML concepts and mathematics.
-   Implement algorithms and workflows using Python and Scikit-learn.
-   Practice data cleaning, exploratory data analysis (EDA), and feature
    engineering.
-   Evaluate models correctly and understand their limitations.
-   Build portfolio-ready projects using real-world and Kaggle datasets.
-   Develop reproducible ML workflows and learn model deployment
    fundamentals.
-   Document learning progress, experiments, and useful references.

## Repository Structure

``` text
machine-learning-practice/
├── data/                   # Local datasets (not committed)
│   └── .gitkeep
├── notebooks/              # Learning notes, EDA, experiments, algorithms
├── src/                    # Reusable Python modules
│   └── __init__.py
├── tests/                  # Tests for reusable code
│   └── .gitkeep
├── ml_env/                 # Local virtual environment (Git-ignored)
├── .gitignore
├── requirements.txt
└── README.md
```

> Notebooks and folders will be added progressively. The `data/`
> directory is Git-ignored to avoid committing large or restricted
> datasets. Download datasets from their original sources and follow
> their licenses and terms.

## Tech Stack

  Purpose                            Tools
  ---------------------------------- ---------------------------
  Language                           Python
  Numerical & scientific computing   NumPy, SciPy
  Data analysis                      Pandas
  Visualization                      Matplotlib, Seaborn
  Traditional ML                     Scikit-learn
  Notebooks                          Jupyter Notebook, IPython
  Model persistence                  Joblib
  Progress utilities                 tqdm
  Version control                    Git, GitHub

Additional tools will be introduced when needed, including XGBoost,
LightGBM, CatBoost, imbalanced-learn, Optuna, SHAP, LIME, statsmodels,
Prophet, PyTorch, TensorFlow, MLflow, and Weights & Biases.

## Getting Started

### 1. Clone the repository

``` bash
git clone https://github.com/YOUR_USERNAME/machine-learning-practice.git
cd machine-learning-practice
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Create and activate a virtual environment

Ubuntu / Linux:

``` bash
python3 -m venv ml_env
source ml_env/bin/activate
```

Windows (PowerShell):

``` powershell
py -m venv ml_env
.\ml_env\Scripts\Activate.ps1
```

### 3. Install dependencies

``` bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Register and launch Jupyter

``` bash
python -m ipykernel install --user --name ml_env --display-name "Python (ML Practice)"
jupyter notebook
```

Choose the **Python (ML Practice)** kernel for the repository notebooks.

### 5. Deactivate the environment

``` bash
deactivate
```

## Machine Learning Roadmap & Progress

This roadmap is a study guide, not a requirement to master everything
before building projects. I aim to learn concepts, practice code,
evaluate results, and document insights as I progress.

### Phase 1 --- Foundations

-   [ ] **01. Introduction to Machine Learning** --- AI/ML/DL, learning
    paradigms, ML lifecycle, applications, challenges, development
    environments.
-   [ ] **02. Python for Machine Learning** --- Python fundamentals,
    data structures, functions, OOP, exceptions, files, modules,
    iterators, decorators, type hints, `venv`, `pip`, Git.
-   [ ] **03. Mathematics for ML** --- Linear algebra, calculus,
    probability, statistics, optimization, loss functions, entropy,
    cross-entropy, KL divergence.

### Phase 2 --- Data Processing & Exploration

-   [ ] **04. NumPy** --- Arrays, indexing, broadcasting, vectorization,
    aggregation, linear algebra, random numbers.
-   [ ] **05. Pandas** --- Series/DataFrames, loading, cleaning,
    filtering, grouping, joining, reshaping, dates, categorical data.
-   [ ] **06. Data Visualization** --- Matplotlib, Seaborn,
    distributions, categorical and multivariate plots, correlations.
-   [ ] **07. Exploratory Data Analysis (EDA)** ---
    Univariate/bivariate/multivariate analysis, target analysis, missing
    values, outliers, leakage, insights.
-   [ ] **08. Data Preprocessing & Feature Engineering** --- Imputation,
    scaling, encoding, transformations, feature creation, pipelines,
    `ColumnTransformer`.

### Phase 3 --- Core Supervised Learning

-   [ ] **09. Supervised Learning Fundamentals** --- Features/target,
    data splitting, cross-validation, bias-variance, overfitting,
    baselines, reproducibility.
-   [ ] **10. Linear Regression** --- Simple/multiple/polynomial
    regression, OLS, MSE, gradient descent, residuals, regularization.
-   [ ] **11. Logistic Regression** --- Binary/multiclass
    classification, sigmoid/softmax, log loss, regularization,
    calibration.
-   [ ] **12. K-Nearest Neighbors (KNN)** --- Distance metrics,
    classification/regression, choosing K, scaling, dimensionality.
-   [ ] **13. Support Vector Machines (SVM)** --- Margins, support
    vectors, kernels, C/gamma, SVC, SVR.
-   [ ] **14. Naive Bayes** --- Bayes theorem, conditional independence,
    Gaussian/Multinomial/Bernoulli variants, smoothing, text
    classification.
-   [ ] **15. Decision Trees** --- CART, Gini, entropy, information
    gain, pruning, tree constraints, feature importance.
-   [ ] **16. Ensemble Learning** --- Voting, bagging, Random Forest,
    Extra Trees, boosting, AdaBoost, GBM, XGBoost, LightGBM, CatBoost,
    stacking, blending.

### Phase 4 --- Unsupervised & Other Learning Paradigms

-   [ ] **17. Clustering** --- K-Means, hierarchical clustering, DBSCAN,
    HDBSCAN, OPTICS, Mean Shift, GMM, spectral clustering, evaluation.
-   [ ] **18. Dimensionality Reduction** --- PCA, SVD, LDA, Kernel PCA,
    t-SNE, UMAP, random projection, autoencoders.
-   [ ] **19. Association Rule Learning** --- Market Basket Analysis,
    Apriori, FP-Growth, Eclat, support, confidence, lift.
-   [ ] **20. Anomaly & Novelty Detection** --- Z-score/IQR, Isolation
    Forest, LOF, One-Class SVM, Elliptic Envelope, evaluation.
-   [ ] **21. Semi-Supervised & Self-Supervised Learning** ---
    Pseudo-labeling, self-training, label propagation, consistency,
    contrastive learning, masked prediction.
-   [ ] **22. Reinforcement Learning Fundamentals** --- Agents,
    environments, MDPs, rewards, Bellman equations, bandits, Q-Learning,
    SARSA, DQN, policy gradients, PPO.

### Phase 5 --- Evaluation & Optimization

-   [ ] **23. Model Evaluation Metrics** --- Regression (MAE, MSE, RMSE,
    R²); classification (precision, recall, F1, ROC-AUC, PR-AUC, MCC);
    clustering metrics.
-   [ ] **24. Regularization & Generalization** --- Bias-variance,
    L1/L2, Elastic Net, early stopping, learning/validation curves,
    model complexity.
-   [ ] **25. Hyperparameter Optimization** --- Grid/random search,
    Bayesian optimization, Optuna, Hyperopt, successive halving,
    Hyperband, nested CV.
-   [ ] **26. Feature Selection** --- Filter, wrapper, embedded methods,
    RFE/RFECV, Lasso, permutation importance, SHAP.

### Phase 6 --- Specialized ML Domains

-   [ ] **27. Time Series ML** --- Trend/seasonality, stationarity, time
    splits, lag features, ARIMA/SARIMA, Prophet, forecasting, drift.
-   [ ] **28. Imbalanced Learning** --- Under/oversampling, SMOTE
    variants, class weights, focal loss, thresholding, PR-AUC,
    leakage-safe resampling.
-   [ ] **29. Recommender Systems** --- Content-based/collaborative
    filtering, matrix factorization, ALS, hybrid systems, cold start,
    ranking metrics.
-   [ ] **30. NLP with Traditional ML** --- Text preprocessing,
    tokenization, BoW, n-grams, TF-IDF, text classification, sentiment,
    embeddings, topic modeling.
-   [ ] **31. Traditional ML for Computer Vision** --- Image features,
    color histograms, HOG, SIFT/SURF concepts, LBP, PCA, SVM-based
    image/face recognition.
-   [ ] **32. Explainable AI (XAI)** --- Interpretability, feature
    importance, PDP/ICE, SHAP, LIME, counterfactuals, explanation
    limitations.

### Phase 7 --- Advanced, Production & Research

-   [ ] **33. Advanced ML Algorithms** --- GLMs, LDA/QDA, Gaussian
    Processes, HMM/CRF, factorization machines, online/incremental,
    transfer, federated, causal, graph, probabilistic ML.
-   [ ] **34. Scikit-learn in Practice** --- Estimator API,
    transformers, pipelines, model selection, metrics, custom
    transformers/scorers, Joblib, reproducible experiments.
-   [ ] **35. ML Pipelines & Production Engineering** --- Ingestion,
    validation, training/inference, FastAPI/Flask serving, Docker,
    MLflow/W&B, DVC, CI/CD, monitoring, drift, cloud.
-   [ ] **36. Responsible & Trustworthy ML** --- Privacy, bias,
    fairness, consent, differential privacy, robustness, uncertainty,
    human-in-the-loop, model/data documentation.
-   [ ] **37. Deep Learning Foundations (ML → DL)** --- Perceptrons,
    ANN, forward/backpropagation, activations, losses, optimizers,
    regularization, CNN, RNN/LSTM/GRU, attention, Transformers,
    PyTorch/TensorFlow, GPU basics.

### Phase 8 --- Projects & Job Readiness

-   [ ] **38. Machine Learning Projects** --- Beginner, intermediate,
    and advanced projects; model development through deployment.
-   [ ] **39. Kaggle & Research Skills** --- Dataset exploration,
    competitions, baselines, CV strategy, experiment tracking, error
    analysis, ablations, paper reading/reproduction, technical reports.
-   [ ] **40. ML Engineer Interview Preparation** --- ML theory, math,
    Python/NumPy/Pandas, SQL, metrics, leakage, system design,
    deployment, project walkthroughs, resume/portfolio.

## Project Portfolio

Projects will be added as I complete them. Each project should include a
clear problem statement, dataset/source, EDA, preprocessing, baseline,
model comparison, evaluation, conclusions, and reproducible instructions
where applicable.

### Beginner

-   House Price Prediction
-   Student Performance Prediction
-   Salary Prediction
-   Medical Insurance Cost Prediction
-   Used Car Price Prediction

### Intermediate

-   Customer Churn Prediction
-   Credit Risk Classification
-   Loan Approval Prediction
-   Fraud Detection
-   Customer Segmentation
-   Employee Attrition Prediction
-   Sales Forecasting
-   Sentiment Analysis
-   Movie Recommendation System

### Advanced

-   End-to-End ML Model Deployment
-   Imbalanced Fraud Detection Pipeline
-   Time-Series Forecasting System
-   Explainable Credit Risk Model
-   Hybrid Recommendation Engine
-   ML Model Monitoring & Drift Detection
-   Automated ML Training Pipeline
-   Production-Ready ML API with FastAPI

## My Practice Workflow

For each algorithm or project, I aim to follow a repeatable workflow:

1.  Understand the problem and define the target.
2.  Inspect the dataset and perform EDA.
3.  Split data appropriately and prevent leakage.
4.  Build a simple baseline.
5.  Preprocess data and engineer useful features.
6.  Train models and tune hyperparameters using validation/CV.
7.  Evaluate with metrics appropriate to the task.
8.  Analyze errors, limitations, and results.
9.  Save reproducible code, notes, and conclusions.
10. Where relevant, package the model and explore deployment.

## Notebook & Code Conventions

-   Use descriptive notebook names, such as
    `linear_regression_house_prices.ipynb`.
-   Keep experiments and explanations organized by topic.
-   Set random seeds where appropriate and document limitations.
-   Keep datasets, credentials, virtual environments, and large model
    artifacts out of Git.
-   Prefer reusable code in `src/` as practice grows.
-   Record dataset sources and respect licensing/usage terms.

## Progress & Contributions

This is primarily a personal learning repository. Suggestions,
corrections, and learning resources are welcome. If you find an issue,
feel free to open an issue or start a discussion.

## Connect

-   **GitHub:** https://github.com/shagor186
-   **LinkedIn:** www.linkedin.com/in/shagor186

---

**Learn consistently • Practice deliberately • Build projects • Document
progress**