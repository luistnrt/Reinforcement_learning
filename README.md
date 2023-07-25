# Reinforcement_learning
RL in Trading (Portfolio Abgabe: Pascal Breucker und Luis Steinert

--- 

This repository contains code for training and evaluating reinforcement learning models (A2C and PPO) on a custom environment for a RL Trading Agent. Traded Stock Apple: 'AAPL'. The project is structured as follows:

## Files:

1. `train_single_stock_project.ipynb`: 
   - This Jupyter notebook contains the code for training and evaluating the A2C and PPO models on a custom environment.
   - The notebook also includes the plots of the second model trained with a different reward function in the custom environment.

2. `custom_environment_project.py`:
   - This Python file contains the custom environment used for training the reinforcement learning models (A2C and PPO) in the `train_single_stock_project.ipynb` notebook.

3. `Eval and Tests`:
   - This directory contains the code and data for training the second set of A2C and PPO models with a different reward function in the custom environment.
   - The resulting plots and evaluation metrics of these models are displayed at the end of the `train_single_stock_project.ipynb` notebook.

4. `data_extractor.py`:
    - We modified this script from Github in order to downlaod the Data for the Apple stock through YahooFinance. 
    - From 1980-12-12 until present. However, only data starting from 2010-01-01 was used in the training of the models.  
    - `import yfinance as yf`

## Documentation 

Following information are added for claritiy of the code: 
    - The code consists of two different sets of custom_environments `custom_environment_project.py`and `custom_environment.py` and trainings & evaluating notebooks `train_single_stock.ipynb` and  `train_single_stock_project.ipynb`.
    - Different Reward functions and Regularizations + other feats were used in both sets in order to show the difference. 
    - The Output of the Jupyter Notebook `train_single_stock_project.ipynb` also contais the plots from the other project in oder to showcase both results. 
    - See RL_Trading_Agent_Abgabe3.docx for further details. 


## Bibliography

1. ByFinTech, B. Y. (2023, 4. Juni). Deep reinforcement learning for automated stock trading. Medium. https://towardsdatascience.com/deep-reinforcement-learning-for-automated-stock-trading-f1dad0126a02
2. Gym trading environment. (o. D.). Gym Trading Env. https://gym-trading-env.readthedocs.io/en/latest/
3. Custom Environment: https://github.com/Chubbyman2/reinforcement-learning-stock-trader/blob/a905f76fd39585b70fe1a30c4ff18b0964b16e3b/custom_environment.py
4. Wang, L. (2022, 3. Januar). Reinforcement Learning and Stock Trading | Medium. Medium. https://letian-wang.medium.com/from-reinforcement-gamer-to-reinforcement-trader-8b0a7ef8b53f
