# Diabetes Prediction Model

This machine learning model predicts whether a patient has diabetes or not based on their medical information. The model is built using the Support Vector Machine (SVM) algorithm.

## Problem Statement

Given the following medical conditions of a female patient:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skinfold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)

The objective is to predict whether the patient has diabetes or not.

- 1: Diabetes
- 0: Non-Diabetes

## Installation

To run the model, make sure you have the following dependencies installed:

- numpy
- pandas
- scikit-learn

You can install them using the following command:
- pip install numpy pandas scikit-learn


## Usage

1. Clone the repository or download the source code files.
2. Ensure that the dataset file "diabetes.csv" is present in the same directory as the source code.
3. Run the "diabetes_prediction.py" file to train the model and save it.
4. The trained model will be saved as "model.pkl" in the same directory.

## Data

The dataset used for training the model is stored in the "diabetes.csv" file. It contains the following columns:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (1: Diabetes, 0: Non-Diabetes)

## Model Evaluation

After training the model, the training and test accuracies are calculated and displayed.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify and use the code according to your needs.

Please note that this model provides predictions based on the given features, but it should not be used as a substitute for professional medical advice. Consult a healthcare professional for accurate diagnosis and treatment of diabetes.

## Acknowledgments

The model implementation is based on the concepts and techniques learned from various machine learning courses and tutorials.

## Contact

For any questions or inquiries, please contact [your email address].



