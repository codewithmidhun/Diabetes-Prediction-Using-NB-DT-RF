# Diabetes Prediction using Naive Bayes, Decision Tree, and Random Forest

This repository contains Python code for predicting diabetes using three different machine learning models: Naive Bayes, Decision Tree, and Random Forest. The models were trained and tested on the Pima Indians Diabetes Database.

## Dataset
The dataset used for this project is located at `/kaggle/input/pima-indians-diabetes-database/diabetes.csv`. It is the Pima Indians Diabetes Database, which includes various health-related features to predict the onset of diabetes.

## Models Performance

### Naive Bayes
- Training Accuracy: 75.53%
- Testing Accuracy: 80.52%

### Decision Tree
- Training Accuracy: 77.16%
- Testing Accuracy: 77.27%

### Random Forest
- Training Accuracy: 76.02%
- Testing Accuracy: 79.22%

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python diabetes_prediction.py
   ```

## File Structure
- `diabetes_prediction.py`: Main script for training and testing the models.
- `requirements.txt`: List of Python packages required for the project.
- `/kaggle/input/pima-indians-diabetes-database/diabetes.csv`: Dataset file.

## Note
Make sure to have Python installed on your system along with the required dependencies listed in `requirements.txt`. You can install them using the provided command.

Feel free to explore and modify the code to experiment with different models or further improve the accuracy of the predictions. If you have any questions or suggestions, please open an issue or submit a pull request. Happy coding!
