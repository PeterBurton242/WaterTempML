# 🌊 Water Temperature Forecasting with LSTM

This project uses historical ocean water temperature data to train a deep learning model (LSTM) to forecast future water temperatures. The implementation is done in Python using PyTorch Lightning and is fully contained in a single Jupyter Notebook.

> **Notebook**: [`WaterTempProj.ipynb`](./WaterTempProj.ipynb)

---

## 📈 What It Does

- Loads and preprocesses raw water temperature data
- Converts it into time series sequences for supervised learning
- Builds and trains an LSTM model using PyTorch Lightning
- Evaluates the model and plots predictions vs. actuals

---

## 🧪 Requirements

To run the notebook locally, install the following Python packages:


##📁 Dataset

The dataset (44007h2019-2023.txt) is a raw historical log from a water temperature buoy. This file must be uploaded manually when prompted in the notebook (via files.upload() in Colab)

##🧠 Model

* Architecture: LSTM with multiple layers and a dense output
* Framework: PyTorch Lightning
* Input: 10-step time window of normalized water temperatures
* Output: 1-step forecast
* Loss Function: Mean Squared Error (MSE)

## 📊 Output

The notebook includes:
* Time series plots of raw and normalized temperature data
* Training and validation loss curves
* Final model predictions compared to ground truth


## 🚀 How to Use
* Clone this repository
* Open WaterTempProj.ipynb in Jupyter or Colab
* Upload the dataset when prompted
* Run all cells to train and evaluate the model
