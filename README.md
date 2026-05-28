# Machine Learning Explained

A collection of interactive web tools for exploring machine learning algorithms step by step. Each tool breaks down a core ML concept into transparent, visual calculations — no black boxes.

🔗 **Live:** [abka0002.github.io/Machine-Learning-Explained](https://abka0002.github.io/Machine-Learning-Explained/)

## Available Tools

| Tool | Description |
|------|-------------|
| [Data Preparation & Feature Engineering](https://abka0002.github.io/Machine-Learning-Explained/DataPreparationAndFeatureEngineering/) | Interactive pipeline covering EDA, data types, imputation, scaling, encoding, and feature selection with the Heart Failure dataset |
| 🇩🇪 [Datenaufbereitung & Feature Engineering](https://abka0002.github.io/Machine-Learning-Explained/DataPreparationAndFeatureEngineeringGerman/) | Vollständige Pipeline von Datentypen über EDA bis zu Imputation, Skalierung, Kodierung und Merkmalsauswahl — alles mit dem Heart-Failure-Datensatz. App komplett auf Deutsch. |
| [Linear Regression](https://abka0002.github.io/Machine-Learning-Explained/LinearRegression/) | Simple and multiple Linear regression Deployment |
| 🇩🇪 [Lineare Regression](https://abka0002.github.io/Machine-Learning-Explained/LinearRegressionGerman/) | Einfache und Multiple Lineare Regression mit Bewertungsmetriken, Regularisierung, Grid Search und K-Fold-Kreuzvalidierung. App komplett auf Deutsch. |
| [η² Categorical Numerical Associations](https://abka0002.github.io/Machine-Learning-Explained/CategoricalNumericalAssociations/) | An interactive explainer — effect size for categorical → numerical associations |
| [Bias and Variance tradeoff](https://abka0002.github.io/Machine-Learning-Explained/BiasAndVariance/) | Bias–Variance & Generalization Explorer |
| [Grid search and K-Fold Cross Validation](https://abka0002.github.io/Machine-Learning-Explained/GridsearchCrossValidation/) | Discover how GridSearchCV from Scikit-Learn calculates the mean and standard deviation of validation folds to find the best α for a Lasso regression Model, and how refit=True fully leverages your training data. |
| [Sklearn Pipeline](https://abka0002.github.io/Machine-Learning-Explained/SklearnPipeline/) | Explaining How can sklearn pipeline Chaining preprocessing steps and a model into a single, reproducible workflow. |
| [PCA (SVD & Eigendecomposition)](https://abka0002.github.io/Machine-Learning-Explained/PCAandSVDorEigendecomposition/) | Explaining Principal Components Analysis (PCA) by two Mathematical equivalent Approaches; Singular Value Decomposition (SVD) and Eigendecomposition of the standardized covariance matrix. |
| [SMOTE & SMOTE-NC](https://abka0002.github.io/Machine-Learning-Explained/smote/) | Step-by-step walkthrough of synthetic oversampling for imbalanced datasets, covering both continuous and mixed-type features |
| [Softmax Regression (Multinomial Logistic Regression)](https://abka0002.github.io/Machine-Learning-Explained/SoftmasRegression/) | Step-by-step walkthrough and live simulator of the fowrward pass (Predictions) and the backward pass (training (error backpropagation)). |
| 🎓 [Classification — Guided Tour (English)](https://abka0002.github.io/Machine-Learning-Explained/ClassificationTour/) | 11-tab interactive course with a 12-step guided tour: logistic regression, BCE training, confusion matrix, decision boundary, P/R/F1 trade-offs, ROC & PR curves, imbalanced data (SMOTE, undersampling, class weighting), multiclass softmax (forward + backward pass), and macro vs. weighted multiclass evaluation. |
| 🎓 [Klassifikation — Geführte Tour (Deutsch)](https://abka0002.github.io/Machine-Learning-Explained/ClassificationTourGerman/) | Vollständig deutsche Version derselben App: 11 Tabs mit 12-Schritte-Tour zu logistischer Regression, BCE-Training, Konfusionsmatrix, Entscheidungsgrenze, P/R/F1-Trade-offs, ROC- & PR-Kurven, unausgewogenen Daten (SMOTE, Undersampling, Klassengewichtung) und Mehrklassen-Softmax. |
| 🎓 [KNN — Guided Tour (English)](https://abka0002.github.io/Machine-Learning-Explained/KNNTour/) | 6-tab interactive course with a 6-step guided tour on K-Nearest Neighbors: the lazy instance-based learner, live single predictions, the four Minkowski-family distance metrics (Euclidean, Manhattan, Minkowski, Chebyshev) with proof of the Chebyshev limit, choosing *k* via 5-fold CV on Wisconsin Breast Cancer, and uniform vs. distance-weighted voting for classification and regression. |
| 🎓 [KNN — Geführte Tour (Deutsch)](https://abka0002.github.io/Machine-Learning-Explained/KNNTourGerman/) | Vollständig deutsche Version derselben App: 6 Tabs mit 6-Schritte-Tour zu K-nächsten Nachbarn: der faule instanzbasierte Lerner, eine einzelne Vorhersage live, die vier Distanzmetriken der Minkowski-Familie (Euklid, Manhattan, Minkowski, Tschebyschew) mit Beweis des Tschebyschew-Grenzwerts, Wahl von *k* mittels 5-facher CV auf Wisconsin-Brustkrebs sowie uniforme vs. distanzgewichtete Abstimmung für Klassifikation und Regression. |
| [Attention Is All You Need](https://abka0002.github.io/Machine-Learning-Explained/AttentionAndTransformer/) | Interactive guide to the Transformer architecture — self-attention, multi-head attention, positional encoding, encoder-decoder, and masking |
| [GPT-Decoder Simulator](https://abka0002.github.io/Machine-Learning-Explained/GPTDecoderSimulator/) | Complete data flow with mathematical examples |
| [RAG-System Simulator](https://abka0002.github.io/Machine-Learning-Explained/RAGSystemSimulator/) | Retrieval-Augmented Generation· Step-by-Step |
| [Low-Rank Adaptation (LoRA) LLMS](https://abka0002.github.io/Machine-Learning-Explained/LowRankAdaptationLLMS/) | LoRA (Low-Rank Adaptation, Hu et al. 2021) is a parameter-efficient fine-tuning method that freezes a pre-trained model's weights and learns a small rank-r update on the side. |
| [RAG & Fine-Tuned LLM Evaluation Guide](https://abka0002.github.io/Machine-Learning-Explained/RAGFineTunedEvaluation/) | Evaluating Retrieval-Augmented Generation Systems and Fine-Tuned Large Language Models. An introduction with examples, mathematical derivation, and discussion of common evaluation metrics.|

## About

These tools are designed for students and practitioners who want to go beyond using ML libraries as black boxes. Each app lets you follow the actual math behind an algorithm — see how distances are computed, how neighbors are selected, and how new samples are generated.

All tools run entirely in the browser. No server, no installation, no sign-up required.

## Tech Stack

Pure HTML, CSS, and JavaScript — no build step, no frameworks, no dependencies.

## Contributing

Contributions are welcome. To add a new tool, create a folder with an `index.html` inside it and open a pull request.

## License

MIT
