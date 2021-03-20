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
the derivation file is shown as 数学推导.pdf
### 3.2 Empirical Analysis
1. results about VWAP method
![image](https://user-images.githubusercontent.com/77960694/111874524-bbafde00-89d0-11eb-9f51-3ee2b4c967e0.png)
![image](https://user-images.githubusercontent.com/77960694/111874538-c8343680-89d0-11eb-9a52-e64b82be4834.png)
![image](https://user-images.githubusercontent.com/77960694/111874548-d2563500-89d0-11eb-8e1d-e9eff5c15f38.png)
![image](https://user-images.githubusercontent.com/77960694/111874565-da15d980-89d0-11eb-894e-4901dee2de2a.png)
![image](https://user-images.githubusercontent.com/77960694/111874572-e306ab00-89d0-11eb-9a62-ee6c46202e9d.png)
![image](https://user-images.githubusercontent.com/77960694/111874577-eac64f80-89d0-11eb-8352-044204ac14a5.png)
![image](https://user-images.githubusercontent.com/77960694/111874586-f0bc3080-89d0-11eb-9c48-f4bfc120a00e.png)
2. results about IS method and comparing
![image](https://user-images.githubusercontent.com/77960694/111874623-02053d00-89d1-11eb-9915-dbddc968398a.png)
![image](https://user-images.githubusercontent.com/77960694/111874632-0af60e80-89d1-11eb-8825-ecc15a183a41.png)


