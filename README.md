# Assignment 1 — Introduction to Machine Learning (Formative I)

- **Author:** Your Name(s)
- **Notebook:** [Assignment1_GaddielIrakoze.ipynb](Assignment1_GaddielIrakoze.ipynb)
- **Instructions:** [Formative1_instructions.txt](Formative1_instructions.txt)

## Overview

This repository contains the deliverables for Formative I: a single Google Colab notebook that compares classical machine learning classifiers with a three-layer neural network implemented from scratch using NumPy. The goal is to demonstrate understanding of both perspectives, report experiments, and provide clear documentation and interpretation.

## Included Files

- [Assignment1_GaddielIrakoze.ipynb](Assignment1_GaddielIrakoze.ipynb) — Main notebook (runs end-to-end in Colab).
- [Formative1_instructions.txt](Formative1_instructions.txt) — Assignment brief and rubric.
- [data/wine_fraud.csv](data/wine_fraud.csv) — Dataset included for this assignment (replace or cite alternate dataset if you choose a different one).

## Notebook Structure

The notebook is organized to read like a short technical report with the following sections:

1. **Introduction & Dataset selection** — dataset description, justification, preprocessing and train/validation split.
2. **Classical ML models** — at least two classifiers (e.g., logistic regression, decision tree, SVM, random forest) with 2–3 hyperparameter variations each and evaluation (accuracy, precision, recall, F1, confusion matrix).
3. **Neural network from scratch** — a 3-layer feed-forward network (Input → Hidden (ReLU) → Hidden (ReLU) → Output (Sigmoid/Softmax)), with forward propagation, backpropagation, training loop (SGD or batch GD), experiments varying learning rate / hidden units / epochs, and learning curves.
4. **Comparison & Discussion** — results table comparing models, discussion of strengths/weaknesses, and possible reasons for performance differences.
5. **References** — citations for dataset and algorithms.

## Requirements

The notebook requires common Python data science libraries. Install locally or let Colab handle packages. Typical dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

If you use additional libraries, list them in the notebook prior to execution.

## How to run

- Open the notebook in Google Colab (recommended) or run locally in Jupyter.
- If running locally, ensure the working directory is the repository root so the notebook can access `data/wine_fraud.csv`.
- Run all cells top-to-bottom; the notebook is designed to run end-to-end without manual interruption.

## Evaluation & Deliverables

- Produce evaluation metrics for each model: **Accuracy, Precision, Recall, F1-score, Confusion matrix**.
- For the scratch neural network show: training loss and accuracy curves across epochs, confusion matrix, and at least 2–3 experiments varying hyperparameters.
- Include a results comparison table and a short written discussion interpreting findings.

## Submission

- Submit a single Google Colab notebook file named following the convention: `Assignment1_FirstnameLastname.ipynb`.
- The notebook must include your name(s) in a top Markdown cell and run end-to-end without errors.

## Rubric Highlights (what to focus on)

- Clear organization and academic-style explanations with citations (see rubric in [Formative1_instructions.txt](Formative1_instructions.txt)).
- At least two classical models with hyperparameter variations and full metric reporting.
- A working from-scratch 3-layer neural network with correct forward/backward passes and training curves.
- A comparison table and insightful discussion linking results to model behavior.

## References

- Assignment brief: [Formative1_instructions.txt](Formative1_instructions.txt)
- scikit-learn documentation: https://scikit-learn.org/stable/
- (If you use a dataset from UCI) UCI Machine Learning Repository: https://archive.ics.uci.edu/

If you'd like, I can also scaffold the notebook sections, add a `requirements.txt`, or draft the initial Colab notebook cells. Which would you prefer next?

