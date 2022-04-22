# Passenger-Controlled Seat Heater

## Objective

  The Seat Heater control system is basically used to control the temperature of a car seat. When a passanger or a driver of the car seats on a car, the button sensor gets activated (which acts as one switch here). After that, the user can turn on the heater(which acts as another switch). The temperature sensor keeps monitoring and recording the temperature and sends the analog value to the microcontroller ATmega328. The microcontroller takes the analog input of the temperature sensor and gives output a temperature value through UART( through serial communication).

## Description

The aim of this project is to turn on the Heater and sense the temperature in the environment of the passenger when he is seated on the seat and the Heater switch is turned on.


# Implementation

The passenger's seating status and the Heater switch is shown using 2 switches.To indicate the success of this condition and to show Heater is ON, LED glows.
The sensing of the temperature is depicted with the help of a potentiometer.
The analaog value from pot is converted to digital depending on the given limits with respect to voltage in terms of temperature.
The output from this ADC in terms of PWM is shown in the oscilloscope.
The data in terms of temperature is transmitted with the help of USART and shown in the Serial Monitor.
