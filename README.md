# Urban Digital Twins over the Cloud-to-Thing Continuum
This repository contains source files for the development of an Urban Digital Twin (UDT) in the city of Málaga (Spain). We also propose its distribution over the Cloud-to-Thing Continuum (C2T Continuum). _(All this work is currently in progress)_.

### Metamodel
Our proposed model for the Urban Digital Twin of a Public Transport System is shown in the following image.

![Metamodel](https://github.com/atenearesearchgroup/public-transport-system-dt/blob/main/assets/Model.png?raw=true "System Metamodel")

### Object Model
According to the predictions we have done for a specific bus line in Málaga, we obtain a timetable which collects the time that a bus takes in going from one stop to other. Having these times, we can simulate the movement of a bus along this line. If we establish the tick time to 60 seconds (1 minute), we can see how the system change its state. Some examples of snapshots are shown below:

##### When t = 0
![Object model when clock=0](https://github.com/atenearesearchgroup/public-transport-system-dt/blob/main/assets/clock0.png?raw=true "Object model when clock=0")

##### When t = 120
![Object model when clock=120](https://github.com/atenearesearchgroup/public-transport-system-dt/blob/main/assets/clock120.png?raw=true "Object model when clock=120")

##### When t = 360
![Object model when clock=360](https://github.com/atenearesearchgroup/public-transport-system-dt/blob/main/assets/clock360.png?raw=true "Object model when clock=360")
