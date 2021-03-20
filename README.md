# Assignment1
## 1. Idea:
This time is the first time realizing a thesis, which is difficult for me since my programming skills is improving. So I just what to read a thesis about algo trading which is not too much complex and reproduced. So I just find a master's thesis about improving algo trading model.
## 2.Reference
A master's thesis from Shangdong University ：《基于风险平价的算法交易应用探究》\
Year: 2020\
Author: 殷兴鑫
### 2.1 Abstrat & Introduction
This is a master's thesis studying Volume Weighted Average Price(VWAP) algo and Implementation Shortfall(IS) algo alppying in alog trading.The author wants to apply risk parity strategy to improve the IS model and compare it with VWAP, to prove that the improvment is effective.\
Introduction calarified some backgrounds and etc. Here I don't need to tell more about it.
### 2.2 Models about algo trading
A Introduction about VWAP model and IS model.
#### 2.2.1 VWAP
A Introduction to VWAP about its primal principle, relization, pros and cons.
#### 2.2.2 IS and Optimaizaion method
A Introduction to IS with discrete and continuous conditions.\
First consider Almgren-Chriss Model on continuous condition,\
Then the author tried to prove that optimal stochastic strategy of the AC model is exactly the optimal nonrandom strategy of the AC model. \
Finally the author disscussed the model on discrete condition.
### 2.3 Risk Parity
First the author introduced the definition of risk parity and find a equation.\
Then the author introduced two algos to find solutions of the equation.\
Finally the author told us how to apply risk parity to IS strategy.
### 2.4 Empirical Analysis
In this charpter, the Auther use some data analysis to compare the forecasting and trding results of different methods, and draw a conclusion.
## 3.Reproduce
So my work consists of two part: mathematical derivation and empirical analysis.
### 3.1 Mathemetical Derivation
1. derive the method of VWAP
2. derive the method of IS we are going to use
3. derive the algo applying in IS.
### 3.2 Empirical Analysis
1. results about VWAP method
2. results about IS method
3. comparing
