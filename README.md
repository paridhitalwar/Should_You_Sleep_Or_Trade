# Should You Sleep or Trade Bitcoin?

## Project Overview

This project focuses on analyzing Bitcoin price trends and predicting price movements using various neural network models. The goal is to compare different models' performance in predicting Bitcoin prices and to determine the most effective strategy for investment.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
  - [Convolutional Neural Network (CNN)](#convolutional-neural-network-cnn)
  - [Long Short-Term Memory (LSTM)](#long-short-term-memory-lstm)
  - [Recurrent Neural Network (RNN)](#recurrent-neural-network-rnn)
- [Model Evaluation](#model-evaluation)
- [Volatility Analysis](#volatility-analysis)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset consists of Bitcoin price data over a period of 10 years. The data includes:

- Open, High, Low, Close prices
- Volume
- Date and Time

## Data Preprocessing

1. **Cleaning:** Removing any missing or irrelevant data.
2. **Normalization:** Scaling the data to ensure all features contribute equally to the model.
3. **Splitting:** Dividing the data into training, validation, and testing sets (70%, 20%, 10%).

## Feature Engineering

- **Time-based features:** Hour, day of the week, month, etc.
- **Lagged features:** Previous day prices, moving averages, etc.

## Modeling

### Convolutional Neural Network (CNN)

CNNs are used to capture spatial dependencies in the data. The project implements a CNN model to analyze Bitcoin price trends and predict future prices based on historical data.

### Long Short-Term Memory (LSTM)

LSTMs are a type of RNN capable of learning long-term dependencies. They are particularly effective for time-series forecasting due to their ability to retain information over long periods.

### Recurrent Neural Network (RNN)

RNNs are used to model the sequential nature of the data. They are designed to recognize patterns in sequences, making them suitable for time-series prediction.

## Volatility Analysis

The project also includes an analysis of Bitcoin price volatility. The volatility is calculated and compared across different models and investment strategies:

- **Buy-and-Hold Strategy:** Volatility over 1 year, 6 months, and 3 months.
- **Model Predictions:** Volatility of predictions from CNN, LSTM, and RNN models over the same periods.

## Future Work

Future work could involve:

- Exploring other cryptocurrencies and broader market data.
- Implementing additional neural network architectures.
- Enhancing feature engineering with more sophisticated technical indicators.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](CONTRIBUTING.md) document for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
