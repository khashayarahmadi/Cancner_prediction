## Cancer Prediction with Logistic Regression

This project demonstrates how to use Logistic Regression for cancer prediction using the Pickle5 library for model persistence and the Streamlit library for user interaction.

### Features

- Logistic Regression model for cancer prediction
- Pickle5 library for saving and loading the trained model
- Streamlit library for creating an interactive user interface

### Getting Started

1. Clone the repository: `git clone https://github.com/khashayarahmadi/Cancner_prediction`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the project: `streamlit run app.py`

### Usage

The project provides an interactive interface where you can:

- Upload a CSV file containing patient data
- Select the features to use for prediction
- Train the Logistic Regression model
- Evaluate the model's performance
- Make predictions on new data

### Model Saving and Loading

The trained model is saved using the Pickle5 library, which provides a compact and efficient way to serialize and deserialize Python objects.
Interactive User Interface with Streamlit
The project uses the Streamlit library to create an interactive user interface that allows you to:

Upload a CSV file using a file uploader
Select the features to use for prediction using a dropdown menu
Train the model by clicking a button
Evaluate the model's performance using a confusion matrix and classification report
Make predictions on new data by entering the values in a form
Contributions
Contributions are welcome! Please feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License.
