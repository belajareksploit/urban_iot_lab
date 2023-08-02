# urban_iot_lab
An attempt to build a light weight urban iot lab using raspberry pis and free open source solutions

Building a testbed is an important part of anyone who is interested in learning how the technology of Internet of Things work. Building a testbed are usually done by picking opensource servers and application and installing it on the testbed manually. This task could be time consuming and to some people with little experience can even be frustating. There are opensource frameworks that is already widely available to automate the installing process such as IoT Stack, but it has a more general approach and it is geared more towards hobbyist and general enthusiasts. This means that for a testbed, it does not provide some key functions that is important for conducting research and experimentation such as the capability to revert to its original state, the capability to provision end points with new updated firmware and the capability to collect data and provide an analytical platform to conduct data science related experiments. 


This project is made with the goal of providing a simple and economical way to implement an IoT testbed using serveral raspberry pis, a network switch or a wifi accesspoint and several IoT development boards (such as ESP3, ESP8266, etc.). 

## Ansible collection built specific for raspberry pi's using raspbian/armbian

This ansible collection is made to build an IoT Testbed using Raspberry Pis running Raspbian Linux

The roles that will be built:
- Testbed Configurator
- Docker installer
- Mosquitto installer
- Nanomq installer 
- Influxdb installer
- Grafana installer

Special Experimentation Roles:
- Experiment configurator
- Data collector
- Endpoint Firmware OTA automation