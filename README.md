# Binary-Classification-Dataset-For-GENDER

## Dataset Description

This dataset is intended for binary gender classification tasks. It contains anthropometric measurements of individuals along with their gender labels. The features in this dataset include height, hand length, and foot length, which are commonly used for biometric gender classification.

- **Gender Labels:** The dataset uses numeric labels where 1 represents male and 2 represents female.
- **Features:**  
  - HEIGHT (in millimeters or as recorded)  
  - HAND_LENGTH  
  - FOOT_LENGTH  

The dataset can be utilized for training and evaluating machine learning models in binary classification problems related to gender prediction based on physical measurements.

## Dataset Structure

The dataset is provided in a tabular format (CSV or similar) with the following columns:

| Column      | Description                     |
|-------------|---------------------------------|
| GENDER      | Gender label (1=male, 2=female) |
| HEIGHT      | Height measurement              |
| HAND_LENGTH | Length of the hand              |
| FOOT_LENGTH | Length of the foot              |

Each row represents an individual sample with corresponding features and gender label.

## Label Encoding

| Label | Gender |
|-------|--------|
| 1     | Male   |
| 2     | Female |

## Usage

You can load the dataset using popular data science libraries such as pandas in Python and use it for training classification models.


## Label Encoding

| Label | Description |
|-------|-------------|
| 1     | Female      |
| 0     | Male        |

## Usage

To use this dataset for training a gender classification model, load the data and labels, preprocess as needed, and feed them into your machine learning pipeline.


## Dataset link
https://gist.github.com/jtrive84/c87434e3d7838a49fbc5263f9af96bbc
