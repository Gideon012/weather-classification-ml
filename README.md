Weather Classification Using Machine Learning

 Project Overview

This project explores the use of machine learning to classify weather conditions using weather-related features. A Random Forest classifier was trained and evaluated to investigate how well different weather categories could be distinguished.

The project also examines why accuracy alone is not sufficient for evaluating a classification model.

Objectives

- Build a weather classification model using Python.
- Explore weather-related features and their relationship with weather categories.
- Evaluate model performance using accuracy, precision, recall, F1-score, and a confusion matrix.
- Investigate classification errors and weaknesses in individual classes.
- Compare the original classification task with a simplified three-class task.

## Tools and Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib and Seaborn, if used for visualization

Model Development

The initial model achieved approximately 82% accuracy. Further evaluation using class-level metrics and a confusion matrix revealed weaknesses in distinguishing certain weather categories.

The classification task was subsequently simplified by grouping foggy conditions with cloudy conditions and stormy conditions with rainy conditions.

The revised model was evaluated on three broader categories:

- Cloudy
- Rainy
- Sunny

The revised model achieved approximately 89% accuracy on the three-class task.

Note: The two accuracy scores come from different classification tasks and should not be interpreted as a direct comparison on identical labels.

 Evaluation

The project investigates model performance beyond overall accuracy using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

These metrics help reveal classification errors that an overall accuracy score may conceal.

 Project Structure

text
weather-classification-ml/
├── weather_classification.ipynb
├── README.md
└── requirements.txt


How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook.
4. Ensure the dataset is available and update the dataset path if necessary.
5. Run the notebook cells in order.

Limitations

This project classifies weather categories from available weather-related features. It should not be interpreted as a future-weather forecasting system unless future conditions are explicitly predicted and evaluated.

The model's performance depends on the dataset, feature quality, class definitions, and evaluation method.

Future Improvements

- Test the model on additional and unseen data.
- Improve class-level performance through further experimentation.
- Compare Random Forest with other classification algorithms.
- Develop an interactive application for making predictions.

 Author

Created as part of my hands-on learning journey in Artificial Intelligence and Machine Learning.