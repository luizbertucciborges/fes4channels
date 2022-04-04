# Fes4channels

Fes4channels is an open access project, developed at the Edmond and Lily Safra International Institute of Neuroscience. The software presented in this repository is intended for the closed-loop control of functional electrostimulation hardware, with inertial sensor feedback, the description of the use of the software and hardware are described below.


## Hardware Description

### Modules and Connections 

To develop electrostimulation hardware, it is necessary a module to increase voltage (Boost), a module to manipulate the signal (H-bridge) and a module for data processing.

![MontagemHardware](https://user-images.githubusercontent.com/75434453/161472988-60682ab0-1fb1-44a5-afe8-ff088ba89f04.png)


The image shows the connection between the bridgeH modules (left), processing unit (center) and boost converter (right).


### Architecture

The architecture of the functional electrical stimulation device is presented below.

![ArquiteturaHardware](https://user-images.githubusercontent.com/75434453/161472466-8ea788fa-37f4-443b-818d-da9c0ece81d8.png)


### Firmware

To embed the firmware on the ESP-32 (as used in this project), the following features are required (all open projects):
-VScode
-Plattformio
-Python
-Mosquitto Broker

## Inertial Sensor

JAMA was an inertial sensor open access project based on the IMU GY-80 + ESP-32. It is an option for the feedback sensor for closed loop control. All project information can be found at https://github.com/tuliofalmeida/pyjama.

## Developers

◾ André Dantas - https://github.com/lordcobisco

◾ Luiz Bertucci- https://github.com/luizbertucciborges



