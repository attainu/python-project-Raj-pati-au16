# Parking lot
Designed a parkinglot using python with list data structure .

## Dependies
This code is only compatible with python 3

## Description
This repository gives an overview of how we can design a basic parking lot in Python. It creates parking lot with given number of slots. The cars follow Greedy approach while being parked in the slots.

## **_managingparkinglot.py_** file defines the following functions -
**create_parking_lot n**- Given n number of slots, create a parking lot

**park car_regno car_color** - Parks a vehicle with given registration number and color in the nearest empty slot possible. If there are no more empty slots available, it shows a message "Sorry, parking lot is full".

**status**- Prints the slot number, registration number and color of the parked vehicles.

**leave x** - Removes vehicle from slot number x. There are few query functions to retrieve slot number from registration number of car, get registration numbers of cars with particular color etc.
#
1.**entities** file contains all sub modules required for managingparkinglot.

2.**Main.py** file for execution the program , here i import 2 module _"FileInput"_ for read and run all the commands from the 'abc.txt' file and _"Interactive"_ for manual input.

3.**managingparkinglot.py**, Here i have imported all the modules from entities.