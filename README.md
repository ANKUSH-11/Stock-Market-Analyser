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

To collect stock market data, I used various data source Yahoo Financel APIs. Update the data collection script (`collect_data.py`) with the desired stock symbols, date range, and data source.



### Data Preprocessing

Data preprocessing is crucial for preparing the collected data for training the LSTM model. to clean, normalize, and transform the data.


### Model Training

Train the LSTM model using the preprocessed data. The architecture and hyperparameters of the model can be configured in the `train_model.py` script.
visit keras_model.h5,LSTM model.ipynb


### Prediction

Use the trained LSTM model to make predictions on unseen data. Update the `predict.py` script with the necessary inputs and run it.

```bash
app.py 
```
run it in terminal using "Streamlit run app.py"
## Results
![1 1](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/6de99cfc-1070-4529-a70f-9e537ecf1672)
![2 2](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/4d13eb54-d7a8-43e5-8253-88a050084604)
![3 3](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/82ee197b-7d74-43bf-b5b4-38638cc23fcb)
![4 4](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/e5d616c5-0d0f-42dc-ad33-4a57d3195c2c)
![5 5](https://github.com/ANKUSH-11/Stock-Market-Analyser/assets/84002890/75057ab6-071d-484e-a559-55c9e7095481)





## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, please create a pull request or open an issue in this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Disclaimer**: Stock market prediction is inherently uncertain and comes with risks. The predictions made by this model should not be used as the sole basis for financial decisions. Always consult with financial professionals before making investment choices.
