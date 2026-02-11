# 📈 Linear Regression Project

## Overview
This repository contains an end-to-end **linear regression analysis** project.  
The goal is to explore the relationship between variables, build a linear regression model, and evaluate its assumptions and performance using statistical diagnostics.

The project emphasizes **statistical reasoning**, correct model specification, and interpretation rather than applying many models.

---

## Dataset
The dataset consists of structured numerical and categorical variables describing customer behavior.  
Each row represents a single observation (customer), and the target variable represents a continuous outcome suitable for linear regression.

- **Unit of observation:** individual customer  
- **Target variable:** continuous (regression)  
- **Predictors:** numerical features related to customer behavior  

```python
import pandas as pd

df = pd.read_csv("Ecommerce Customers")
df.head()
```

Project Structure
├── 03-Linear Regression Project.ipynb
├── Ecommerce Customers
├── README.md

03-Linear Regression Project.ipynb — main analysis notebook

Ecommerce Customers — dataset used in the project

README.md — project documentation


