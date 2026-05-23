
# Assignment 1 — Introduction to Machine Learning (Formative I)

- **Student:** Gaddiel Irakoze
- **Notebook:** [Assignment1_GaddielIrakoze.ipynb](Assignment1_GaddielIrakoze.ipynb)

**Purpose (for the grader)**

- This notebook compares two perspectives on supervised classification: (1) classical machine learning models implemented using scikit-learn, and (2) a three-layer feed-forward neural network implemented from first principles using NumPy. The notebook is written as a concise technical report so the grader can validate methodology, experiments, and conclusions.

**What to look for (quick map)**

- **Dataset & preprocessing:** dataset choice, motivation, cleaning, feature engineering, and train/validation split are grouped under the Introduction / Data section near the top of the notebook.
- **Classical models:** implementations, hyperparameter variants, and evaluation (accuracy, precision, recall, F1, confusion matrices) are in the Classical Models section.
- **Neural network from scratch:** architecture, activation functions, loss, vectorized forward/backward passes, training loop (SGD/batch GD), learning curves, and experiments appear in the Neural Network section.
- **Comparison & discussion:** consolidated results table, confusion matrices, and a short analytical discussion (strengths, weaknesses, and reasons for performance differences) are in the final Results & Discussion section.

Files and important artifacts

- `Assignment1_GaddielIrakoze.ipynb` — Main deliverable. Please open in Google Colab for best reproducibility.
- `data/wine_fraud.csv` — Dataset used (cite information and source in the notebook). If a different dataset is selected, the notebook states its source and reasoning.

How to run (recommended)

1. Open `Assignment1_GaddielIrakoze.ipynb` in Google Colab.
2. If prompted, install required packages by running the first code cell. Typical packages used are:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

3. Run the notebook from top to bottom. The notebook is organized to run end-to-end without manual edits; any random seeds are fixed for reproducibility.

Grading checklist (where the rubric maps to evidence)

- **Notebook organization, documentation & citations:** The notebook is structured as Introduction → Data → Classical Models → Neural Network → Experiments → Results & Discussion → References. Each code block is preceded by an explanatory Markdown cell describing intent and interpretation.
- **Classical Model Implementation & Experimentation:** At least two classifiers are trained with 2–3 hyperparameter variations; evaluation metrics and confusion matrices are reported for each experiment in the Classical Models section.
- **Neural Network From Scratch:** A three-layer (input → hidden → hidden → output) network is implemented using NumPy. Forward and backward passes are vectorized; cross-entropy (or binary cross-entropy) loss is used; training is performed with SGD/batch GD. Learning curves (loss and accuracy) and experiments that vary learning rate / hidden units / epochs are included.
- **Evaluation & Comparative Analysis:** A results table compares models on accuracy, precision, recall and F1-score; confusion matrices and learning curves are included. The Discussion interprets differences and connects results to bias/variance considerations.
- **Academic integrity:** Dataset sources and any adapted code or references are cited in the References section.

References

- Assignment brief: `Formative1_instructions.txt`
- scikit-learn documentation: https://scikit-learn.org/stable/


