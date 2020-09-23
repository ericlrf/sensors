![](images/sensor.png)

## Introduction to Sensors

### Time series modeling exercise

[Example models and data](30mhz)

Create a model based on one of four available example models, or create a new model from scratch. 

Use at least two sensors to predict the output of one other sensor.

### Micropython Lunar Lander filter exercise

[Micropython filtering](micropython)

One of the main differences of coding for an MCU is that they offer very few resources. It is generally not possible to use large Python libraries such Numpy or Scipy.

The Lunar Lander assignment requires you to implement a filter while working around these limits.

### MQTT streaming data analysis exercise

[MQTT exercise](mqtt)

Run the minimal MQTT chat example, and chat with your follow students. Work together with your team: let one of your team publish data and another(s) receive data, respectively generated by and analyzed with https://github.com/jmaces/statstream

### Scailable edge computing exercise

[Scailable 101](https://github.com/scailable/sclbl-tutorials/blob/master/sclbl-101-getting-started/README.md)

Fit a Python Sklearn SVR model on the time series data from the first exercise, convert it to WebAssembly, and make it available as a rest endpoint using the the Scailable edge computing platform. Follow [Scailable 101](https://github.com/scailable/sclbl-tutorials/blob/master/sclbl-101-getting-started/README.md) to get started.

### TTGO HiGrow

[TTGO HiGrow with MQTT Cayenne integration](higrow)

An example of a plant sensor to MQTT based dashboard solution. Use your HiGrow Device to measure one of your own plants for a week, and analyse the resulting data with a time series model.



