# Sentiment Analysis using LSTM

This repository implements a binary sentiment analysis model using Long Short-Term Memory (LSTM). The goal is to classify the sentiment of text as either **positive (1)** or **negative (0)** based on the provided dataset.

---

## Repository Structure

### Directories:

- **Model**: Contains the implementation of the LSTM model and related code for training and evaluation.
- **Dataset**: Placeholder for the dataset used in this project. Due to file size limitations, the actual dataset is hosted on Google Drive. [Download the dataset here](https://drive.google.com/drive/folders/1mqkz5eH49-rlsttReeibubkp1WHi2Uc4?usp=sharing).

---

## Dataset Description

The dataset includes two columns:

- `SentimentText`: The input text for analysis.
- `Sentiment`: The target class, where:
  - `0` represents negative sentiment.
  - `1` represents positive sentiment.

### Sample Data:

| SentimentText                                | Sentiment |
|---------------------------------------------|-----------|
| is so sad for my APL friend.............    | 0         |
| I missed the New Moon trailer...           | 0         |
| This is amazing!                           | 1         |

---

## Features

- Binary sentiment classification (**positive** or **negative**).
- Built with LSTM for improved handling of sequential text data.
- Preprocessing steps for text cleaning and tokenization.
- Training and evaluation scripts included in the **Model** directory.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/masoumehkhaleghian/SentimentAnalysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd SentimentAnalysis
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset from [Google Drive](https://drive.google.com/drive/folders/1mqkz5eH49-rlsttReeibubkp1WHi2Uc4?usp=sharing) and place it in the `Dataset` directory.
