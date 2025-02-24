# Week 2: Classical ML & Intro to System Design Fundamentals

## Goal
- Understand supervised/unsupervised algorithms in scikit-learn.
- Grasp model evaluation, hyperparameter tuning.
- Learn basic ML system design: how training data flows, how models might scale, how to handle large data.

## Monday: Supervised Learning (Regression)
**Topics:**
- Linear Regression, Ridge, Lasso.

**Notebook (02_classical_ml_system_design.ipynb):**
- Train & evaluate on California Housing or Boston dataset.
- Compare metrics (MSE, MAE, R²).

## Tuesday: Supervised Learning (Classification)
**Topics:**
- Logistic Regression, Decision Trees, Random Forest, SVM.

**Notebook Tasks:**
- Use Iris or Titanic.
- Check accuracy, confusion matrix, precision, recall, F1.

## Wednesday: Hyperparameter Tuning & Model Selection
**Topics:**
- GridSearchCV, RandomSearchCV, cross-validation.

**Notebook Tasks:**
- Tune a Random Forest or SVM.
- Compare best parameters vs. defaults.

## Thursday: Unsupervised Learning & Basic ML System Design
**Topics:**
- K-Means, PCA, dimension reduction.
- Intro to ML system design: data ingestion, feature store, offline vs. online training, model hosting.

**Notebook Tasks:**
- Cluster data (e.g., Iris) with K-Means, visualize with PCA.
- Write a short outline (1–2 paragraphs) on how you’d design a system if data is huge (streaming, partial fit, etc.).

## Friday: Mini-Project – Classical ML Pipeline
- Create a pipeline that loads data → cleans → trains models → tunes hyperparams → evaluates.

**System Design Reflection:**
- Where do the data come from?
- How often do you retrain?
- How to handle large datasets?

## Weekend
**Consolidation:**
- Finalize the pipeline in your notebook.

**ADHD Tip:**
- Use a 3-task daily list (e.g., “Tune Random Forest,” “Write system design outline,” “Push to GitHub”).
