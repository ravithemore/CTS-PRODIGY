# CTS-PRODIGY

## Project Idea
Road accidents are dreaded incidents which are known to take about 146 thousand lives in a year in India itself. Out of these, it is usually seen that about 32% all such accidents are attributable to motorcycles only and out of which 23% lose their lives. It is easy to blame the 98.6% of bikers who died didn’t wear a helmet but what about the 1.4% who did their part of trying to protect themselves from an injury? Reports suggest that these cases are primarily due to the delay in taking such casualty to a hospital. This can be avoided if the process of reporting an accident became automated. Thus, we propose this solution, where the sensor itself initiates a communication to report the accident using the person’s phone.

The Vechile sensor has inbuilt pressure sensors which are cheap yet effective and productive. These contain two flexible metal plates with a velostat in between the layers. As the pressure changes, the resistance drops across the plates and the Raspberry Pi reads it through an analog to digital converter. So when the rider crashes, the spike in the sensor initiates a code which updates the online database triggering the application on a rider’s phone to send an alert to nearby hospitals. Thus the location is precise. The solution proposed in this paper does not affect the status quo by trying to modify the motorcycle itself, etc.

## Technologies and Tools used:

- Raspberry Pi Zero W
- Pressure Sensors (Velostat)
- MCP3008 IC
- Google Firebase (Cloud Messaging, Realtime Database, Authentication, Storage)
- Android Studio
- Java, Node.js, Python3

## Block Diagram

![](https://github.com/ravithemore/CTS-PRODIGY/blob/main/1-244.png)
