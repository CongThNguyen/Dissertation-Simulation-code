# Taxi-Simulation-code

This code was used in my dissertation project to simulate and generate the data.

The input parameter for the discreete event simulation are: lambda1, lambda2, aban1, aban2, time_coef and T. 

**lambda1**: is the rate of arrival of the taxis (I have chosen this to be exponentially distributed due to its memoryless property)

**lambda2**: is the rate of arrival of the customers

**aban1**: is the rate of abandonment of the taxi (this is the time when a taxi has finished working and exit the simulation)

**aban2**: is the rate of arrival of the customers (this is considerd to be the customer's patience time when they are waiting to be match with a taxi)

**time_coef**: is the simulation time that a taxi would take to travel to a customer

**T**: is the termination time of the simulation.

The above input paremeters can be changed to produce different outcomes. The goal of the project was to determined how different matching algorithms affect the performance of the system (i.e: the performance measures). 
