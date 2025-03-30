# Breast Cancer Prediction

This project aims to predict the likelihood of breast cancer being malignant or benign using a machine learning model, specifically employing Logistic Regression. It provides an interactive web application built with Streamlit, allowing users to input relevant medical parameters and receive immediate predictions, assisting in early detection and diagnosis.

## Dataset Used

The project leverages the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which contains 569 instances, each described by 30 numerical features computed from digitized images of fine needle aspirate (FNA) of breast masses. These features capture various characteristics of the cell nuclei present in the images, such as radius, texture, perimeter, area, and smoothness. Each instance is labeled as either benign or malignant, providing a basis for supervised learning models.

## Machine Learning Model

- **Logistic Regression**: A statistical method employed to model the probability of a binary outcome, making it well-suited for medical diagnosis applications like this. The model is trained to distinguish between malignant and benign tumors based on the input features from the dataset.

### Model Performance Metrics

- **Accuracy**: 97%
- **Precision**: 97%
- **Recall**: 99%
- **F1-score**: 98%

## Tech Stack

- **Programming Language**: Python

- **Data Analysis and Machine Learning Libraries**: Pandas, NumPy, Scikit-learn

- **Web Framework**: Streamlit

- **Deployment Platform**: Streamlit

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AsmitaMishra24/Breast_Cancer_Prediction.git
2. **Navigate to the Project Directory**:
   ```bash
   cd Breast_Cancer_Prediction
3. **Install Dependencies**:
   Ensure you have Python installed, then execute:
   ```bash
   pip install -r requirements.txt
4. **Run the Application:**:
   ```bash
   streamlit run app.py
   
## Usage

- **Input Data**: Enter the required medical parameters into the application's interface.
- **Receive Prediction**: The application processes the input and displays the probability of the tumor being malignant or benign.
- **Interpret Results**: Utilize the provided visualizations to comprehend the factors contributing to the prediction.

## Contributing

Contributions aimed at enhancing the functionality or accuracy of the model are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. Refer to the LICENSE file for more details. 
   
