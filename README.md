# Student Performance Prediction

## Project Overview

This project aims to predict student academic performance based on various features such as study hours, attendance, participation in extra activities, and more. Using supervised learning techniques, we classify students into performance categories (e.g., Grade A, B, C).

## Dataset

The dataset includes attributes like:

- Student Age
- Gender (Sex)
- High School Type
- Scholarship status
- Additional Work
- Sports Activity
- Transportation
- Weekly Study Hours
- Attendance
- Reading, Notes, Listening in Class, Project Work scores
- Final Grade (target variable)

Dataset source: [Link to dataset or mention if it's from Kaggle/other source]

## Methodology

- Data preprocessing (handling missing values, encoding categorical variables, scaling)
- Feature engineering
- Model training using Logistic Regression (multiclass classification)
- Model evaluation using accuracy, classification report, confusion matrix
- Feature importance analysis
- Data visualization (line charts, scatter plots) for insights

## Usage

1. Clone the repository.
2. Place the dataset CSV file in the `data/` folder or adjust the file path in the script.
3. Install required Python libraries (e.g., pandas, scikit-learn, seaborn, matplotlib).
4. Run `model.py` or Jupyter Notebook for training and evaluation.

```bash
pip install -r requirements.txt
python model.py
