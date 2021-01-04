# Link-Budget-and-Path-Profiling
Eulogio "Amang" Rodriguez Institute of Science and Technology, College of Engineering, final project requirements for Microwave Design.

We highly suggest to run the code on Spyder, Python version 3.7.
In order for the code to function properly, the lists of libraries must fully installed correctly:
## Library Dependencies
1. IPython
2. numpy
3. math
4. tkinter
5. json
6. webbrowser
7. urllib
8. webbrowser
9. matplotlib
10. haversine

Aside from these 10 library dependencies, the user must PROVIDE a Google Cloud Platform's Elevation API.
Learn more on how to get @: https://developers.google.com/maps/documentation/elevation/start

![Interface](https://github.com/papa1560868/Link-Budget-and-Path-Profiling/blob/main/image/Interface.PNG)

## How to use the python script:
### Path Profiling
**API KEY** - This is where the user needed to place the generated API Elevation from GCP.
**TX Latitude** - Transmitters Latitude, must be in Decimal Degrees (DD) and *not* in Degrees Minutes and Seconds (DMS).
**TX Longitude** - Transmitters Longitude, must be in Decimal Degrees (DD) and *not* in Degrees Minutes and Seconds (DMS).
**RX Latitude** - Receivers Latitude, must be in Decimal Degrees (DD) and *not* in Degrees Minutes and Seconds (DMS).
**RX Longitude** - Receivers Longitude, must be in Decimal Degrees (DD) and *not* in Degrees Minutes and Seconds (DMS).
**No. of datapoints** - This sets how many samples the system is going to get, rule of thumb the higher the sample rate the better the resolution is.
**Frequency (GHz)** - Operational frequency of the transmitting and receiving signal.
#### Link Budget
**TX Output (dBm)** - 
**TX Waveg
