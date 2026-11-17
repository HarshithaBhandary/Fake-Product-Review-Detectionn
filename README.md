# Fake-Product-Review-Detectionn

# Fake Product Review Detection System

A machine learning-based web application that helps identify fake and genuine product reviews using Natural Language Processing (NLP) and sentiment analysis.

## About the Project

Online shopping platforms contain thousands of customer reviews. However, some reviews may be misleading or fake, making it difficult for customers to make informed purchasing decisions.

This project aims to analyze product reviews and predict whether a review is genuine or fake using machine learning techniques.

## Features

- Fake and genuine review classification.
- Text preprocessing and feature extraction using TF-IDF.
- Sentiment analysis of customer reviews.
- Multiple machine learning models.
- Amazon and Flipkart review data collection.
- User-friendly web interface.
- Prediction results and trust score visualization.

## Technologies Used

**Frontend**
- React.js
- Tailwind CSS

**Backend**
- Python
- Flask

**Machine Learning**
- Scikit-learn
- TF-IDF
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

**Other Tools**
- Pandas
- NumPy
- Git and GitHub

## Machine Learning Models

The project uses multiple machine learning algorithms to classify product reviews:

- Logistic Regression
- Random Forest
- Support Vector Machine
- XGBoost

## Model Performance

| Model | Accuracy | F1 Score | ROC-AUC |
|---|---:|---:|---:|
| Logistic Regression | 85.74% | 85.66% | 92.12% |
| Random Forest | 86.04% | 86.03% | 93.23% |
| XGBoost | 86.94% | 86.90% | 93.50% |

*Results are based on the project's recorded model evaluation.*

## Project Structure

```text
fake_review_detector/
│
├── app.py
├── scraper/
│   └── scrape_amazon.py
├── model/
│   ├── train_model.py
│   └── fake_review_model.pkl
├── templates/
├── static/
└── README.md
```

*Update this structure to match your actual project files.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/HarshithaBhandary/Fake-Product-Review-Detectionn.git
```

### 2. Navigate to the project folder

```bash
cd fake_review_detector
```

### 3. Create a virtual environment

```bash
python -m venv fake_review_env
```

### 4. Activate the environment (Windows)

```bash
fake_review_env\Scripts\activate
```

### 5. Install dependencies

```bash
pip install flask pandas numpy scikit-learn joblib beautifulsoup4 requests
```

### 6. Run the application

```bash
python app.py
```

Open your browser and visit:

http://127.0.0.1:5000

## Future Enhancements

- Improve scraping reliability.
- Support additional e-commerce platforms.
- Improve prediction accuracy with larger datasets.
- Enhance the user interface and result visualization.

## Author

**Harshitha Bhandary**

- GitHub: https://github.com/HarshithaBhandary
- LinkedIn: https://linkedin.com/in/harshitha-bhandary-86b426249
