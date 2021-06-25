# Solving Probability Problem With Computation Power
This project to demonstrae use of the random generator to generate 20k of samples that emulate the random distribution, and use the result of sampling to calculate the probability. While the traditional method will need to derive from probablity mathematics as in the [birthday paradox](https://en.wikipedia.org/wiki/Birthday_problem).

The project implement a simulation that can assist to study the [birthday paradox](https://en.wikipedia.org/wiki/Birthday_problem). However, for this problem there are some changes to the original problem:

- Assume that birthdays of individuals are uniformly distributed over the 365 days in a year. Further, assume that the year is not a leap year, and that it begins on a Monday. We define a calendar week to be the seven days from Monday to Sunday.

- Suppose there are  𝑛  people in a room. How large does have  𝑛  have to be in order for the probability that there are at least 3 people with their birthdays within the same calendar week to be more than 0.5? You should include a visualisation in your answer.

The Jupyter file included the detail explanation of the code and methods. Overview process:
- Testing the sample size 1000, 20000, 100000 is sufficient to for a reliable random samples yet not over too many samples that may slow down the system.
- With the balance 20000 samples is choosen, the calculation can be determine with the 26 person will be sufficient to get 0.5 chance that 3 person will have same birthday week
- To enhance the simulation, a list and a graph are plotted to allow the user to get the relationship between probability vs number of person in a room.









