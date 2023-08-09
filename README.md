# Stock-Market-Analyser


![Stock Market Analyzer](images/stock_analyzer.png)

The Stock Market Analyzer is a project that uses Long Short-Term Memory (LSTM) neural networks to analyze and predict stock prices. This repository contains the code and resources needed to train and utilize the LSTM model for stock market analysis.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Data Collection](#data-collection)
  - [Data Preprocessing](#data-preprocessing)
  - [Model Training](#model-training)
  - [Prediction](#prediction)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Stock market analysis and prediction have always been challenging tasks due to the volatile and complex nature of financial markets. This project aims to provide a tool for analyzing historical stock price data and making short-term predictions using LSTM, a type of recurrent neural network well-suited for sequential data.

The project involves data collection, preprocessing, model training, and prediction phases. The LSTM model learns patterns from historical stock prices and attempts to predict future price movements.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (>= 3.6)
- Git

### Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/stock-market-analyzer.git
cd stock-market-analyzer
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

### Data Collection

To collect stock market data, you can use various data sources such as Yahoo Finance, Alpha Vantage, or other financial APIs. Update the data collection script (`collect_data.py`) with the desired stock symbols, date range, and data source.

```bash
python collect_data.py
```

### Data Preprocessing

Data preprocessing is crucial for preparing the collected data for training the LSTM model. Run the preprocessing script (`preprocess_data.py`) to clean, normalize, and transform the data.

```bash
python preprocess_data.py
```

### Model Training

Train the LSTM model using the preprocessed data. The architecture and hyperparameters of the model can be configured in the `train_model.py` script.

```bash
python train_model.py
```

### Prediction

Use the trained LSTM model to make predictions on unseen data. Update the `predict.py` script with the necessary inputs and run it.

```bash
python predict.py
```

## Results
![1](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/29fc1f43-8c30-4477-83b7-c7ef4063d8a7)
![2](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/a63c4610-6102-4e99-8d17-6fab566ada98)
![3](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/d1175c8f-3dab-4c58-952c-5daf3b89b616)
![4](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/56f6ed1c-efaa-4f4f-8e9b-99ed29e5a425)
![5](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/43bcdb24-ef75-4abc-a926-63e8a8d5bbb9)



## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, please create a pull request or open an issue in this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Disclaimer**: Stock market prediction is inherently uncertain and comes with risks. The predictions made by this model should not be used as the sole basis for financial decisions. Always consult with financial professionals before making investment choices.
