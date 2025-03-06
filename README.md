# Parklands ASRI
Data and .kml generator

## Created with Grok 3

### Prompt
I have a csv file from a model rocket flight (attached) with elapsed time in milli seconds, altitude in meters and acceleration in x,y,z measured in g. If I give a start lat/lon, can you write a program that converts that into actual waypoint, so I can view it in google earth?I think I want to run the program as Python in Google colab.
Use any  method for integrating acceleration.
Flat earth is fine for this.
Start position: -34.602642, 20.302401 (In South Africa). Pls study the csv file and use the right headers. Please list the !pip imports I have to do in a script

### Prompt Update
Pls modify the code like this:
- Make it a KML file with altitude parameters, so I can do a "Fly along a route" in Google Earth
- Reduce the number of waypoints down to around 10% of the input


