# Sentiment Analysis using LSTM  

This repository implements a **binary sentiment analysis model** using **Long Short-Term Memory (LSTM)** networks. The goal is to classify text sentiment as either **positive (1)** or **negative (0)** based on a labeled dataset.  

## Repository Structure  

### Directories:  
- **`Model/`** – Contains the LSTM model implementation, training scripts, and evaluation code.  
- **`Dataset/`** – Placeholder for the dataset used in this project. The dataset is hosted externally due to file size limitations.  

### Files:  
- **`SentimentAnalysis.ipynb`** – Jupyter Notebook with the end-to-end implementation of the model.  
- **`README.md`** – Documentation for the repository.  
- **`environment.yml`** – Conda environment file for setting up dependencies.  

## Dataset Description  

The dataset consists of text samples labeled with sentiment values:  
- **`SentimentText`** – The input text for sentiment classification.  
- **`Sentiment`** – The target class label:  
  - `0` → Negative sentiment  
  - `1` → Positive sentiment  

### Sample Data:  

| SentimentText                                | Sentiment |
|---------------------------------------------|-----------|
| is so sad for my APL friend.............    | 0         |
| I missed the New Moon trailer...           | 0         |
| This is amazing!                           | 1         |

The dataset can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1mqkz5eH49-rlsttReeibubkp1WHi2Uc4?usp=sharing).  

## Features  

- Binary sentiment classification (**positive** or **negative**).  
- Built with LSTM for improved handling of sequential text data.  
- Preprocessing steps for text cleaning and tokenization.  
- Uses **bi-directional LSTM**, **dropout**, **batch normalization**, and **global pooling** for better performance.  
- Training and evaluation scripts are included in the `Model` directory.  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/masoumehkhaleghian/SentimentAnalysis.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd SentimentAnalysis
   ```

3. Set up the Conda environment:  
   ```bash
   conda env create -f environment.yml
   conda activate sentiment_analysis
   ```

4. Download the dataset from [Google Drive](https://drive.google.com/drive/folders/1mqkz5eH49-rlsttReeibubkp1WHi2Uc4?usp=sharing) and place it in the `Dataset` directory.  

5. Download the trained model from [Google Drive](https://drive.google.com/drive/folders/1WXBjiLZZuGenHb-31dWZ4Byu87vjCrE2?usp=sharing) and place it in the `Model` directory.  

## Usage  

1. Open and run `SentimentAnalysis.ipynb` to preprocess data, train the model, and evaluate its performance.  
2. Use the trained model to predict sentiment for new text samples.  

This repository is intended for researchers, data scientists, and developers interested in **natural language processing (NLP) and deep learning**. Contributions and improvements are welcome.
