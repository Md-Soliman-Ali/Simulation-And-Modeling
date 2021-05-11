Experiment Name: AIRPORT TERMINAL CHECK-IN MODEL 

Introduction: It is often the case that the time a passenger spends at the origin airport is longer than the flight duration due to the inefficient check-in process. According to this, airline service plays a significant role for customers or passengers in choosing an airline. Checking in does mean reporting to the desk and getting the boarding pass and registering or to weight bags and luggage. As at any moment, the passenger may be checking in for several different flights. The objects that flow through the system are the passengers, and in Arena, these objects are known as entities. By Arena, we construct this airport terminal check-in model.

Airport Terminal Check-In Procedure Using Arena: To build this Airport Terminal Check-In simulation model and carry out this simulation runs with Arena, a user performs the following steps: 

Create: The passengers will come in it. We will set the Create name as Passenger Arrival then set the entity type as Passenger. In the time between arrival value set as 1.3 and Units set as minutes. Then we will leave the rest of the set-up as it is in the system. 

Resource: We will fix the Resource name as Agents then set the Capacity as 6. 

Process: In the Process, the passengers will have arrived in the module for check-in. We will fix the Process name as Checkin Process and action set as Seize Delay Release. Then we will change the resource name and some value. Then we will leave the rest of the set-up as it is in the system. 

Dispose: Dispose of the Passenger after Check-In. We will set the Dispose name as forwarding to the Gate. 

Conclusion and Discussion: Arena is a very versatile integrated simulation development tool. Constructing this Airport Terminal Check-In simulation model involves identifying one or more flow objects known as entities that flow through the system and then building a flowchart of the model using Arena’s flowchart modules. The model is then enhanced by editing some of the data modules. Arena provides a simple method to setup the simulation parameters and the model input parameters. After completing all procedure, we will run the model then we will get a report. 