# Wine Quality Predictor 🍷

## What's this about?
Can chemistry predict taste? This project uses neural networks 
to predict wine quality scores based on 11 chemical properties — 
no sommelier needed.

## Dataset
Kaggle — Wine Quality Dataset (1143 wines, 11 features)
Quality score ranges from 3 to 9.

## What I built
- 3 layer neural network with Dropout (prevents memorization)
- StandardScaler on both features AND target (regression requirement)
- model.train() / model.eval() switching for proper evaluation
- Train/test split for honest accuracy measurement

## Results
- Test Loss: 0.52
- Sample prediction: 5.24 vs actual 5.00 (0.24 off)

## Tools
Python, PyTorch, Pandas, Scikit-learn

## What I learned
Regression is different from classification in 3 key ways —
normalize the target variable, use MSELoss, and never use 
Sigmoid at the output. Also learned that model.eval() is not 
optional when using Dropout.
