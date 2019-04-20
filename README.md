# LegoSCADA [WaterTanks Testbed]

Traditional control systems are being upgraded with novel 
computing, communication and interconnection capabilities. 
This opens new threats that must be handled both in terms 
of [security](http://en.wikipedia.org/wiki/Information_security) 
and [safety](http://en.wikipedia.org/wiki/Safety). The recently 
coined cyber-physical 
defense term has come to address such a challenge. In this 
context, we are currently preparing some 
[SCADA](http://en.wikipedia.org/wiki/SCADA) testbeds using 
[Lego Mindstorms EV3](http://en.wikipedia.org/wiki/Lego_Mindstorms_EV3) 
bricks and [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi) 
boards. The testbeds aim at validating the security of existing SCADA 
protocols, such as the [Modbus](http://en.wikipedia.org/wiki/Modbus), 
[DNP3](http://en.wikipedia.org/wiki/DNP3), and 
[IEC 104](https://en.wikipedia.org/wiki/IEC_60870-5#IEC_60870-5-104) protocols. 

This project contains the following two subprojects:

# IEC-608670-5-104-Grovepi SCADA testbed

Java server/client SCADA IEC/104 demonstrator using:

- 2 (or 1) Raspberry Pi+Grovepi connected with one ultrasound GrovePi distance sensor each
- 1 Raspberry Pi linked through an electronic circuit with 3 pumps
- 1 computer (as a controller) 

# Matlab/Simulink co-simulation of the SCADA testbed

- Eight Simulink co-simulations increasing the protection in terms of controllability and observability.

# Further information

Visit the [companion website of the project](http://www-public.imtbs-tsp.eu/~garcia_a/web/prototypes/legoscada/TSPScada.html).
