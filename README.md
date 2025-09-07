# Computer Parts Price Prediction - Regression Project

This project demonstrates a regression model to predict the total price of a computer based on its components: Processor, GPU, RAM, Storage, PSU, and Motherboard.  
---

## The workflow includes  
- data cleaning 
- model training
- prediction
- evaluation metrics
- decision-making 

---

## Dataset
- Synthetic dataset created for demonstration purposes.
- Features: Processor, GPU, RAM, Storage, PSU, Motherboard
- Target: Total price of the computer
- Dataset undergoes **cleaning** to remove missing values and duplicates before modeling.

---

## Libraries
```python
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
