# Deep-Learning-for-Financial-Time-Series

CQF Final Project

In recent years, deep learning for analyzing equity data has become more popular,
given the increasingly large amount of data sources being compiled and
the proliferation of relatively inexpensive compute power available to train such
models via GPUs. This has given rise to a plethora of systematic trading strategies
to determine buy and sell opportunities.
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
