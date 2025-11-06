# Churn detection using Machine Learning
This repo shows a pipeline of training, tuning, evaluating and exporting a model that detects possible churners among a bank's clients.

It's my first pipeline done with my own hands.

---

## Technologies used:

- **Model** ─ [`sklearn.ensemble.RandomForestClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- **Encoding** ─ [`sklearn.preprocessing.OneHotEncoder`](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
- **Cross-validation** ─ [`sklearn.model_selection.StratifiedKFold`](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedKFold.html)
- **Baseline** ─ [`sklearn.dummy.DummyClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyClassifier.html)

## Libraries 📖
- Kagglehub
- Pandas
- Scikit-learn
- Pickle (python built-in module)

## How to run
**1.** Clone the repository
   ```bash
   git clone https://github.com/ryannfoliveira/churn-detection
   ```
**2.** Go to the folder
   ```bash
   cd churn-detection
   ```
**3.** Install the libraries (preferably inside a virtual environment)
   ```bash
   pip install -r requirements.txt
   ```
**4.** Run the notebook
   ```bash
   jupyter notebook churn_detection.ipynb
   ```

---

### Notes and apologies
In this pipeline, I've ignored many sacred decrees of ML Engineering, since this is my first project.
To experienced developers: I ask for your forgiveness. 🙏🤠☕

Feedback is always welcome!
