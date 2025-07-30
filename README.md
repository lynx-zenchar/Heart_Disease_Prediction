# Heart_Disease_Prediction

This project explores the UCI Heart Disease dataset to identify key risk factors and build a predictive model to determine whether a patient has heart disease based on clinical features.

It is a a data science project focused on building binary classification models to predict the presence of cardiovascular disease (CVD) using clinical data from the UCI Heart Disease dataset. The project includes exploratory data analysis, model development, evaluation, and ethical considerations relevant to clinical applications.

---

## Files

- **CDV_risk.ipynb** — Jupyter Notebook containing all data preprocessing, exploratory data analysis (EDA), modeling, evaluation, and visualization code.
- **Predicting_Cardiovascular_Disease_Risk_Using_Clinical_Data__A_Binary_Classification_Approach.pdf** — Research paper documenting methodology, results, and conclusions.
- **requirements.txt** — Python packages and dependencies required to run the notebook.
- **README.md** — This file.

---

## Installation

To set up the environment, it is recommended to use a virtual environment:

```bash
python -m venv heartenv
source heartenv/bin/activate  # On Windows: heartenv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

---

## Usage

1. Clone the repository:

```bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies (see Installation section above).
3. Launch the Jupyter Notebook:

```bash
jupyter notebook CDV_risk.ipynb
```

4. Run the notebook cells sequentially to reproduce the analysis.

## Data

The dataset is automatically fetched within the notebook using the ucimlrepo Python package. No manual download is necessary.

## Project Highlights

* Binary classification using Logistic Regression and Random Forest to predict CVD presence.
* Performance evaluation including accuracy, precision, recall, F1-score, ROC curve, and AUC.

* Ethical considerations discussed regarding the application of machine learning in healthcare.
* Complete reproducible pipeline documented in the notebook and research paper.

## Contact

For questions or feedback, please contact Matthew Jacob A. Eleazar at [matteleazar@gmail.com].