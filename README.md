# Multivariate Time-Series Forecasting for Atmospheric Magnetic Waves

## Context

This project is a vital component of ongoing research dedicated to atmospheric magnetic waves. Atmospheric magnetic waves play a crucial role in understanding the Earth's magnetic field, providing valuable insights into geophysical phenomena. Recording data about atmospheric magnetic waves, however, poses significant challenges.

### Background

Atmospheric magnetic waves, also known as geomagnetic waves, are variations in the Earth's magnetic field caused by various factors, including solar activity and interactions with charged particles in the Earth's atmosphere. These waves carry essential information about the Earth's magnetosphere and can influence a range of geophysical processes.

### Challenges in Data Recording

Recording accurate and reliable data about atmospheric magnetic waves is challenging due to the intricate nature of the Earth's magnetic field. Sensors detecting magnetism can often be influenced by external factors, leading to anomalous values. These anomalous readings may arise from various sources, including nearby electronic devices, geological structures, or even solar events.

### Project Solution

This project addresses the challenges associated with recording atmospheric magnetic wave data by employing advanced machine learning techniques, specifically Long Short-Term Memory (LSTM) networks. The LSTM model not only captures the complex temporal dependencies within the data for accurate forecasting but also excels in detecting anomalous data points, providing a solution to the issues faced in traditional data recording methods.

## Project Description

The project focuses on forecasting atmospheric magnetic wave data spanning 30 years, providing a valuable tool for understanding complex temporal patterns in the Earth's magnetic field. The LSTM model was trained on a comprehensive dataset and demonstrated exceptional performance in both anomaly detection and forecasting future values.

## Key Features

- **LSTM Autoencoder Model:**
  - Implemented a deep learning model using Keras with LSTM layers to capture intricate temporal dependencies in the atmospheric magnetic wave data.

- **Anomaly Detection:**
  - Utilized the trained model to identify anomalous data points (outliers) with high accuracy, crucial for detecting unusual patterns in the magnetic wave dataset.

- **Forecasting:**
  - Achieved accurate multivariate time-series forecasting, providing valuable insights into the future behavior of atmospheric magnetic waves.

- **Client Collaboration:**
  - This project was conducted in collaboration with a client pursuing a Geo Physics master's research. The outcomes directly contributed to her research on atmospheric magnetic waves.

## Results

The LSTM model exhibited exceptional performance, achieving a 98% accuracy rate on the test data. This high accuracy in both anomaly detection and forecasting highlights the effectiveness of the proposed approach.

## Usage

### Dependencies

- Python 3.x
- NumPy
- Keras
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

