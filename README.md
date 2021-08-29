# Module_13_Challenge

---

## Alphabet Soup Funding Success

This model has been created to determine the success of startup companies that have been funded by Alphabet Soup, a venture capital firm.  The model begins with a csv file containing the information on more than 34,000 previous organizations that have been funded by the firm.  Using machine learning techniques, and the information from the csv file, this binary classifier model with help predict the success of the startup business.

---

## The Analysis

Based on the original model and the two alternative models, the highest accuracy achieved was only 73%.  Based on these results, it would be recommended that the original model be based on additional data so it can be improved.

Original Model:

    *Hidden layers = 2
    *Epochs = 50
    *Activation of output layer = sigmoid
    *The model's accuracy = 73%
    *The model's loss was = 56%

Alternative Model 1:

    *Hidden layers = 3
    *Epochs = 50
    *Activation of output layer = sigmoid
    *The model's accuracy = 73%
    *The model's loss was = 55%

Alternative Model 2:

    *Hidden layers = 4
    *Epochs = 100
    *Activation of output layer = sigmoid
    *The model's accuracy = 73%
    *The model's loss was = 56%


---
## Technologies

This module utilizes Pandas 3.7 with the following libraries:

    import pandas as pd
    from pathlib import Path
    import tensorflow as tf
    from tensorflow.keras.layers import Dense
    from tensorflow.keras.models import Sequential
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler,OneHotEncoder

---

## Usage

To run this model, clone the repository and launch it using the command line and typing 'jupyter lab'.

---

## Contributors

This model has been brough to you by Abolla, Risk Management Associate

---

## Licenses

MIT