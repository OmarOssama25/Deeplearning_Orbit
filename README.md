# Deep Learning Orbit Prediction

## Objective
The primary objective of this project is to develop a machine learning model using TensorFlow to predict orbital values based on time series data. This project demonstrates the application of deep learning techniques in analyzing and forecasting sequential data.

## Dataset Description
The dataset used in this project consists of two columns:
1. **time_steps**: The time values ranging from -10 to 10.
2. **y**: The corresponding orbital position values.

The dataset contains 2000 entries, and the task involves building a model to predict the `y` values based on the `time_steps`.

**Sample Data:**

| time_steps | y         |
|------------|-----------|
| -10.000000 | 100.000000|
| -9.989995  | 99.800000 |
| -9.979990  | 99.600200 |
| -9.969985  | 99.400601 |
| -9.959980  | 99.201201 |

The dataset is loaded from a CSV file: `orbit - orbit.csv`.

## Steps to Run the Code

### Running on Google Colab

1. **Open Google Colab**: 
   Visit [Google Colab](https://colab.research.google.com/) and sign in with your Google account.

2. **Upload Notebook**:
   - Click on "File" → "Upload Notebook."
   - Upload the `DeepLearning_Assignment1_Orbit.ipynb` notebook.

3. **Upload the Dataset**:
   - Upload the `orbit - orbit.csv` file to the Colab environment by clicking on the file icon on the left sidebar.

4. **Run the Cells**:
   - Once the notebook is uploaded, execute each cell sequentially by clicking the "Run" button or using `Ctrl + Enter` to run each cell.
   - The notebook will preprocess the data, train the model using TensorFlow, and then display the evaluation metrics and predictions.

## Dependencies and Installation Instructions

### Python Libraries:
The project is built using the following Python libraries. Make sure to install these packages before running the notebook:

- **pandas**: For data manipulation.
- **tensorflow**: For building and training the deep learning model.
- **scikit-learn**: For model evaluation metrics.

### Installation Instructions

### To install the required libraries, use the following commands:
      !pip install pandas tensorflow scikit-learn
