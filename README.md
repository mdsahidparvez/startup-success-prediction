# Startup Success Prediction (Group M)

Predicts if startups succeed (acquired) or fail (closed) using ML models.

## Group Members
- Bhavinkumar Patel: Business Understanding, Data Collection, Data Preparation
- Renzo Vizarreta Figueroa: Feature Engineering, Feature Selection, Data Splitting
- Athena Nove Dela Fuerta: Data Visualization, Model Assessment
- Md Sahid Parvez: Model Selection/Training, Model Evaluation, Prediction

## Dataset
[Kaggle Startup Success Prediction](https://www.kaggle.com/datasets/manishkc06/startup-success-prediction)

## Features (49 total): agefirstfundingyear, relationships, fundingrounds, fundingtotalusd, milestones, hasVC, hasangel, avgparticipants, istop500, status (target)

## Models Used
- ExtraTreesClassifier (feature importance)
- KNeighborsClassifier
- Full ML pipeline with preprocessing

## Key Findings
- Visualizations show relationships between funding/milestones and success
- Outlier removal improved model performance
- Feature selection using chi2 and ExtraTrees

## Installation
pip install pandas numpy seaborn matplotlib scikit-learn statsmodels scipy


## Usage
1. Clone repository: `git clone https://github.com/yourusername/startup-success-prediction-group-m.git`
2. `cd startup-success-prediction-group-m`
3. Open `Group-M.ipynb`
4. Run all cells - loads `./startup_data.csv` automatically

## Results
- Visualizations: funding/milestones vs success patterns
- Outlier removal via IQR method
- Feature selection: chi2 + ExtraTrees
- Model evaluation: accuracy, precision, recall, F1, confusion matrix

**Portfolio Project** | Sydney, NS, Canada | Data Engineering Applicant
