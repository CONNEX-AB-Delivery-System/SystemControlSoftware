# Package Delivery System / System Control Software project

## Why

## About this project

This project is part of `CONNEX-AB-Delivery-System`. This repository stores a project `System Control Software` -
software to handle deliveries and manage communication with all trucks.


## Getting Started


# Command interface

This section describes commands that trucks will receive and commands that trucks can send to SCS.

## SCS commands:

"ORDER-PACKAGES" - starts movement of Forklift Truck.

"ORDER-CONTAINER" - starts movement of Container Sorting and Loading truck.

"STOP" - halt all movement of truck. (generally used in emergency).

## FT commands:

"PACKAGES-LOADED" - indicates that all packages has been loaded in container

"PACKAGE-LOADED:RED" - indicates that RED colored package has been loaded in container
"PACKAGE-LOADED:GREEN" - indicates that RED colored package has been loaded in container

"ERROR" - error

## CSLT commands:

"CONTAINER-LOADED" - indicates that container is loaded on truck

"ERROR" - error

## DT commands:

"LOADING-PLACE" - indicates that Delivery truck has arrived in loading place

"CONTAINER-DELIVERED" - indicates that container has been delivered to location

"ERROR" - error
