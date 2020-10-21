# Financial Planning (Unit 5 Homework)


### Part 1: Personal Finance Planner

In this section, I needed to create a personal financial plannning prototype for a credit union that includes stocks, bonds, and cryptocurrencies. I extracted price data for Ethereum and Blockchain from the Alternative Free Crypto API and extracted stock and bond price data from the Alpaca API. Below is a table of each asset class and its value.

| Asset class | # of units owned | Value as of Oct 15,2020 |
| ------ | ----------- |----------- |
| Blockchain  | 1.2 | $15277.45 |
| Ethereum | 5.3 | $2088.04 |
| Stocks    | 50 | $17375.50 |
| Bonds    | 200 |  $23594.00 |


![piechart](https://i.ibb.co/J79j2hg/Screenshot-22.png)


Then I needed to conduct a savings health analysis based on the average monthly household income of each credit union member of $12,000. I built an if statement to check whether the portfolio value of cryptocurrency, stocks and bonds is less than, equal to or greater to the emergency fund amount (also defined as 3 times the average monthly household income). In this particular instance, the credit union has reached its financial goal with a portfolio value higher than the emergency fund requirement. 

### Part 2: Retirement Planning

I used a Monte Carlo Simulation to get to the following simulation results for a retirement portfolio of 40% bonds and 60% stocks:

- With an initial investment of $20,000 for 30 years, There is a 95% chance that the portfolio will end in the range of $42,163.54 and $251,722.03

- If we increase this intital investment to $30,000 for 30 years, There is a 95% chance that the portfolio will end in the range of $63,245.31 and $377,583.05

- If  we wanted to retire in 5 years time, we can increase the intial investment to $60,000 and adjust the composition to 95% stocks and 5% bonds. There is a 95% chance that the portfolio will end in the range of $53,455.12 and $81,453.74

- If  we wanted to retire in 10 years time with the same intial investment of $60,000 and the same composition of 95% stocks and 5% bonds. There is a 95% chance that the portfolio will end in the range of $56,858.82 and $100,168.99


