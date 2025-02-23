# Car Price Prediction Using Deep Learning

This project implements a deep learning model using TensorFlow to predict car prices based on various features such as years, mileage, horsepower, and more. The dataset consists of several car specifications, and the task is to predict the car's current price.

## Project Overview

The project follows a simple yet effective pipeline:

1. **Data Preprocessing:** The dataset is cleaned, and features are normalized to ensure better model performance.
2. **Model Building:** A deep neural network is built using TensorFlow and Keras, with three hidden layers.
3. **Model Training:** The model is trained on 80% of the dataset, validated on 10%, and tested on the remaining 10%.
4. **Model Evaluation:** The model is evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
5. **Visualization:** Training loss curves and a comparison between predicted and actual prices are visualized using Matplotlib.

## Project Structure

- `train.csv`: The dataset containing car features and target price.
- `model.py`: The script to build, train, and evaluate the model.
- `visualizations/`: Folder containing the model architecture visualization and bar graph for predicted vs actual prices.
- `README.md`: This file describing the project.

## Requirements

- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Seaborn

Future Work

Experiment with different model architectures and hyperparameters to improve accuracy.
Add more features (e.g., brand, car condition) to the dataset for better predictions.
Explore other machine learning models (e.g., Random Forest, Gradient Boosting) for comparison.

Acknowledgments

Thanks to the TensorFlow and Keras documentation for providing easy-to-follow tutorials and examples.
The project could be further improved with a larger dataset and more features.

You can install the required packages using the following:

```bash
pip install -r requirements.txt

tensorflow
pandas
numpy
matplotlib
seaborn
