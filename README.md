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

```bash
pip install torch pytorch-lightning pandas scikit-learn matplotlib
