# Logistic Regression: Banking Marketing Campaign

[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-logistic-regression-project/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-logistic-regression-project/actions/workflows/codespaces/create_codespaces_prebuilds)

A comprehensive machine learning project focused on binary classification using logistic regression. This project analyzes a banking marketing campaign dataset to predict whether customers will subscribe to a term deposit, demonstrating essential machine learning techniques from data preprocessing to model optimization.


## Project Overview

This project analyzes banking marketing campaign data to predict customer subscription behavior for term deposits. The dataset provides hands-on experience with:

- Data loading and preprocessing
- Feature encoding for categorical variables
- Train-test split methodology
- Baseline model establishment
- Logistic regression implementation
- Hyperparameter optimization with GridSearchCV
- Model evaluation and performance analysis
- Confusion matrix interpretation
- Threshold tuning for business optimization


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you loose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (dependencies are pre-installed)

3. **Start Working**
   - Open `notebooks/mvp.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook

### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.10

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/mvp.ipynb
   ```


## Project Structure

```
├── .devcontainer/        # Development container configuration
├── assets/               # Generated plots and visualizations
├── data/                 # Data file directory
├── models/               # Trained models and preprocessing components
│
├── notebooks/            # Jupyter notebook directory
│   ├── mvp.ipynb         # Assignment notebook (incomplete)
│   └── solution.ipynb    # Complete solution notebook
│
├── .gitignore            # Files/directories not tracked by git
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## Dataset

The dataset contains banking marketing campaign data with customer information and campaign outcomes. Key features include:

- **Demographics**: Age, job, education, marital status
- **Financial**: Default history, housing loan, personal loan
- **Campaign**: Contact method, duration, previous campaigns
- **Economic**: Employment variation rate, consumer price index
- **Target**: Binary outcome (yes/no) for term deposit subscription

**Source**: The dataset is loaded from the 4GeeksAcademy GitHub repository and represents real banking marketing campaign scenarios.


## Learning Objectives

1. **Data Preprocessing**: Load data from URL and save local copies
2. **Feature Engineering**: Encode categorical variables for machine learning
3. **Baseline Establishment**: Create random and constant prediction baselines
4. **Model Training**: Implement logistic regression with scikit-learn
5. **Hyperparameter Optimization**: Use GridSearchCV for optimal parameters
6. **Model Evaluation**: Analyze performance with accuracy and confusion matrices
7. **Business Optimization**: Tune decision thresholds for specific business needs
8. **Model Persistence**: Save trained models and preprocessors for deployment


## Key Results

The project demonstrates significant improvement over baseline models:

- **Random Model**: ~50% accuracy (baseline)
- **Constant "No" Model**: ~88% accuracy (majority class baseline)
- **Basic Logistic Regression**: ~90% accuracy
- **Optimized Logistic Regression**: ~91% accuracy

The analysis reveals that while the model achieves high overall accuracy, it struggles with the minority class (customers who say "yes"), highlighting the importance of threshold tuning for imbalanced classification problems.


## Technologies Used

- **Python 3.11**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning algorithms and tools
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **NumPy**: Numerical computing
- **Jupyter**: Interactive development environment


## Contributing

This is an educational project. Contributions for improving the analysis or adding new insights are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

