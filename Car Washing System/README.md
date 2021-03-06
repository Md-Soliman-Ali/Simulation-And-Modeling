# Experiment name: SIMULATING A SIMPLE MODEL OF A CAR-WASH SYSTEM

Introduction: Vehicles arrive at a carwash shop to get a simple wash and clean up. The Carwash system consists of a single wash machine, which provides the actual service to the vehicles. Arriving vehicles join a line to wait for service. The vehicle at the head of the line is the one that is next to be serviced by the carwash machine. After the vehicle wash is completed, the vehicle leaves the system. The vehicles are considered the system's customers, as they are the entities requesting service by the server (the washing machine). The objects that flow through the system are the vehicles, and in Arena, these objects are known as entities. By Arena we construction this car-wash system.

Car-Wash Procedure Using Arena: To build this Car-Wash simulation model and carry out this simulation runs with Arena, and a user performs the following steps: 

Create: The cars will come in it. We will set the Create name as Enter then set the entity type as Car. In the time between arrival value set as 3 and Units set as minutes. Then we will leave the rest of the set-up as it is in the system. 

Process: In the Process, the cars will be cleaned by the machine. We will set the Process name as Car Washing and the action set as Seize Delay Release. Then we will leave the rest of the set-up as it is in the system. 

Dispose: Dispose of the Car after washing. We will set the Dispose name as Completed.

Conclusion and Discussion: Arena is a very versatile integrated simulation development tool. Constructing this Car-Wash simulation model involves identifying one or more flow objects known as entities that flow through the system and then building a flowchart of the model using Arena’s flowchart modules. The model is then enhanced by editing some of the data modules. Arena provides a simple method to setup the simulation parameters and the model input parameters. After completing all procedures, we will run the model then we will get a report.
