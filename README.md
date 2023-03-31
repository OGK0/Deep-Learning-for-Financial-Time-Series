# Deep-Learning-for-Financial-Time-Series

CQF Final Project

The objective of this study was to produce a model in order to predict
positive moves (up trend) using the Long Short-Term Memory (LSTM) model
and other recurrent neural architectures. The models were tested on equity data,
in this case daily technical indicator data from January 1, 2017 - December
31, 2022 for Eastman Chemical Company (NYSE:EMN). Eastman Chemical
specializes in developing chemicals for a wide range of applications such as
adhesives, fibers and building materials. The goal of
this exercise was to build a deep learning model that could predict opportunities
to buy EMN stock on a daily basis, with a binary decision [0,1]. In this case,
the model would predict that stock should be bought at the opening price, held
for the day and sold at the market close price [1] or do nothing [0].

Based on experimenting with approx. 40 model architectures, and using neural architecture search,
here are the results for a Dense-GRU combination that had the optimal annual returns 
in the backtesting period from November 2021 through December 2022.

![Dense_GRU_Strategy_Stats](https://user-images.githubusercontent.com/33669038/229205109-aaae74b9-2831-4200-b3cd-c597a6da3bc4.png) 
![Dense_GRU_Cum_Returns](https://user-images.githubusercontent.com/33669038/229205153-de49e777-8fb2-465c-8861-84b2590695cc.png)
