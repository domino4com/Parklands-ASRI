# Parklands ASRI
Data and .kml generator

## Created with Grok 3

### Prompt
I have a .csv file from a model rocket flight (attached) with elapsed time in milli seconds, altitude in meters and acceleration in x,y,z measured in g. If I give a start lat/lon, can you write a program that converts that into actual waypoints, so I can view it in google earth? I think I want to run the program as Python in Google colab.
Use any method for integrating acceleration.
Flat earth is fine for this.
Start position: -34.602642, 20.302401 (In South Africa). Pls study the csv file and use the right headers. Please list the !pip imports I have to do in a script.

### Prompt Update
Pls modify the code like this:
- Make it a KML file with altitude parameters, so I can do a "Fly along a route" in Google Earth
- Reduce the number of waypoints down to around 10% of the input

## Usage:
- Best way is to use an AI engine (ChatGPT, DeepSeek, Grok, Gemini, etc) and give it a similar prompt as above. Or just click on the code file in this repository and click on the "Open in Colab" button
- Copy and Paste the generated code into [Google Colab](https://colab.google), run it and download the generated .kml file.
- Download and install [Google Earth Pro](https://www.google.com/earth/about/versions/#download-pro).
- Double-click on the .kml file so it opens in Google Earth.
- Expand the .kml file in Temporary Places and select the line below the .kml file - See A in the image
- Now click on the Play button to fly the path - See B in the image
