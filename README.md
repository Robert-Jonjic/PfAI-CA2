# Glass Data Analysis and Classification using Neural Networks

This repository contains a Jupyter Notebook demonstrating the analysis, preparation, and classification of glass types using a Dense Neural Network (DNN). The project involves:

- **Data Exploration and Preprocessing (EDA)**
- **Model Development**
- **Model Evaluation**
- **Conclusion**

- Tools and libraries used: Python, TensorFlow/Keras, pandas, NumPy, Matplotlib, and Seaborn.

## Key Features of the Project

### 1. Data Exploration and Preprocessing (EDA)
- Performed an Exploratory Data Analysis (EDA) to understand the dataset.
- Visualized feature distributions and correlations to guide preprocessing.
- Cleaned and prepared the data for neural network input.

### 2. Model Development
- Designed a Dense Neural Network using TensorFlow/Keras.
- Tuned hyperparameters for optimal performance.
- Implemented techniques to prevent overfitting (e.g., dropout, early stopping).

### 3. Model Evaluation
- Evaluated the model's performance using metrics like accuracy, precision, and recall.
- Generated visualizations, including confusion matrices and classification reports.
- Analyzed the model’s predictions to understand its strengths and weaknesses.

## Installation

To run this project, clone the repository and set up the environment as follows:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Robert-Jonjic/PfAI-CA2.git
   cd PfAI-CA2.git
   ```

2. **Set up the environment**:
   - Install Python 3.8.
   - Use `pip` to install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook glass_data_analysis_final.ipynb
   ```

## Results

- The Dense Neural Network achieved high classification accuracy on the glass dataset.
- Insights from the EDA phase informed preprocessing and neural network design, leading to effective predictions.

## Project Structure

- `glass_data_analysis_final.ipynb`: Jupyter Notebook with the complete analysis and model implementation.
- `requirements.txt`: List of Python dependencies required to run the notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.