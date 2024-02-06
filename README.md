# SMS Spam Prediction using Support Vector Classification (SVC)

## Overview

This project aims to predict whether an SMS is spam or not using the Support Vector Classification (SVC) algorithm. Support Vector Classification is a supervised learning algorithm that analyzes and classifies data. In the context of this project, it will be employed to classify SMS messages as either spam or non-spam based on the provided dataset.

## Dataset

The dataset used for training and testing the model is available in the `dataset` folder. The dataset contains labeled SMS messages, where each message is tagged as either "spam" or "ham" (non-spam).

## Requirements

Ensure that you have the following dependencies installed:

- Python (version 3.x)
- scikit-learn
- pandas
- numpy

You can install the required packages using the following command:

```bash
pip install scikit-learn pandas numpy
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/sms-spam-prediction.git
```

2. Navigate to the project directory:

```bash
cd sms-spam-prediction
```

3. Run the `sms_spam_prediction.py` script to train the model and make predictions:

```bash
python sms_spam_prediction.py
```

This script will load the dataset, preprocess the text data, train the Support Vector Classification model, and evaluate its performance. It will also prompt you to enter a custom SMS message for prediction.

## Customization

Feel free to customize the project according to your preferences:

- Modify the dataset: You can replace the existing dataset with your own labeled dataset.
- Adjust model parameters: Explore different parameters for the Support Vector Classification model in the `sms_spam_prediction.py` script.
- Enhance preprocessing: Experiment with different text preprocessing techniques to improve model performance.

## Acknowledgments

- The dataset used in this project is sourced from [provide_source_link_here].
- Special thanks to the scikit-learn, pandas, and numpy communities for their valuable contributions.

Feel free to contribute, report issues, or suggest improvements!
