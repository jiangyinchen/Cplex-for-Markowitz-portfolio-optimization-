# Cplex-for-Markowitz-portfolio-optimization-
Use Cplex to solve Markowitz portfolio optimization, which is related to quadratic contraints.

The SP500_preparation file aims to download the stocks's data from the yahoo.com. And then choose 49 best ones from the 500 stocks.

The 49StocksCovariance file aims to calculate the covariance of the 49 chosen stocks.

The OptimizationUsingCplex aims to process the optimization among the 49 stocks.
The optimization minimized the risk while keeping the return equal to 5%.
In the Markowitz portfolio optimization,the risk of a portfolio contains quadratic elementS. And Cplex could help solve the optimization problem with quadratic constrains.

Although there are a lot of deficiencies in the project, I hope it could help you learn more about Cplex. Thanks!
