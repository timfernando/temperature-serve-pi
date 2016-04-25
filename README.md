
## Temperature serve pi

This repository contains a Python Flask project to read temperature readings from a DS18B20 one wire digital thermometer hooked up to a Raspberry Pi and making the reading available in Celcius and Fahrenheit via a lightweight API.

A beginner's tutorial to wiring up and running the software: 

Quick software setup:
* In your virtual environment `pip install -r requirements.txt`
* `gunicorn temperature:app`
