# Event Driven Simulation
This project was an implementation of a server simulation at a fast food restaurant.

- Developed common linked data structure template class for simulation: a sorted doubly-linked list and a simple queue
- Arrival time interval between customers is drawn from a uniform distribution, and the time for the server to wait for the customer is drawn from a normal distribution
- An event object(arrival, end service, etc) is inserted into a list sorted based on the time that event is scheduled to occur
- A first-in-first-out queue of customers represents the line of customers waiting in the restaurant
- The simulation run from time 0 to a specified time and keep track of some basic statistics

## Run
```
make clean
make
./proj5.exe
```
Then a interacitve command line will prompt to let you set parameter and run the simulation.
