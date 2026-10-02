# DHT11 Temperature and Humidity Monitoring

## Project Overview

This project uses an ESP32 and DHT11 sensor to measure temperature and relative humidity. Sensor readings are displayed in the Serial Monitor every two seconds.

## Components

* ESP32 DevKit V1
* DHT11 Sensor
* Jumper Wires

## Technologies

* Arduino C++
* Wokwi Simulator
* DHTesp Library

## Circuit Connections

* DHT11 VCC → ESP32 3.3V
* DHT11 DATA → ESP32 GPIO 15
* DHT11 GND → ESP32 GND

## Working Principle

The DHT11 sensor measures the surrounding temperature and relative humidity. The ESP32 reads the sensor data and prints the readings to the Serial Monitor every two seconds.

## Expected Result

Temperature in degrees Celsius and relative humidity in percentage are displayed and refreshed every two seconds.

## Wokwi Simulation

Paste your Wokwi project link here.

## GitHub Repository

Source code and circuit configuration are available in this repository.
