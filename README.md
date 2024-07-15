OpenEMS - the Open Source Energy Management System - is a modular platform for energy management applications. It was developed around the requirements of monitoring, controlling, and integrating energy storage together with renewable energy sources and complementary devices and services like electric vehicle charging stations, heat-pumps, electrolysers, time-of-use electricity tariffs and more.

If you plan to use OpenEMS for your own projects, please consider joining the [OpenEMS Association e.V.](https://openems.io/association), a network of universities, hardware manufacturers, software companies as well as commercial and private owners, and get in touch in the [OpenEMS Community forum](https://community.openems.io). 

### OpenEMS in »Local Energy Management«

![alt text](./doc/modules/ROOT/assets/images/local-energy-management.png "Local Energy Management")

### OpenEMS in »Areal Energy Management«

![alt text](./doc/modules/ROOT/assets/images/areal-energy-management.png "Areal Energy Management")

## OpenEMS IoT stack

The OpenEMS 'Internet of Things' stack contains three main components:

 * **OpenEMS Edge** runs on site, communicates with devices and services, collects data and executes control algorithms
 * **OpenEMS UI** is the real-time user interface for web browsers and smartphones
 * **OpenEMS Backend** runs on a (cloud) server, connects the decentralized Edge systems and provides aggregation, monitoring and control via internet

## Features

The OpenEMS software architecture was designed to leverage some features that are required by a modern and flexible Energy Management System:

 * Fast, PLC-like control of devices
 * Easily extendable due to the use of modern programming languages and modular architecture
 * Reusable, device independent control algorithms due to clear device abstraction
 * Wide range of supported devices and protocols

## OpenEMS UI Screenshots

![alt text](./doc/modules/ROOT/assets/images/ui-live.png "OpenEMS UI Live View")
![alt text](./doc/modules/ROOT/assets/images/ui-history.png "OpenEMS UI History View")

## System architecture

OpenEMS is generally used in combination with external hardware and software components
(the exception is a simulated development environment - see [Getting Started](https://openems.github.io/openems.io/openems/latest/gettingstarted.html)). As a brief overview, this is how OpenEMS is used in production setups:
![alt text](./doc/modules/ROOT/assets/images/system-architecture.png "OpenEMS System Architecture")

## Getting Started

* Open up a [Live-Demo on Gitpod](https://gitpod.io/#https://github.com/OpenEMS/openems)
* Follow the [Getting Started](https://openems.github.io/openems.io/openems/latest/gettingstarted.html) guide to setup OpenEMS on your own computer

## Documentation

* [Latest version of documentation](https://openems.github.io/openems.io/openems/latest/introduction.html)
* [Javadoc](https://openems.github.io/openems.io/javadoc/)
