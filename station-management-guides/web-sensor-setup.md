# Web Sensor Setup

A Web Sensor is a [virtual sensor](virtual-sensor-setup.md) which pulls data from external data sources in the vicinity of your weather station. Web Sensors can retrieve data from various sources on the Internet and add it to your stations data set. <span class="app-name"></span> currently provides two types of web sensors which include NOAA Daily Precipitation Total and Current Weather Conditions. You can use the web sensors to add an additional layer of data to your station. This data can be used in conjunction with your physical sensor's data to create charts and identify trends.


### Current Weather Conditions

The Current Weather Conditions web sensor receives it's data readings from the [Dark Sky API](https://darksky.net/dev/docs). Dark Sky 

### NOAA Daily Precipitation Total

The NOAA Daily Precipitation web sensor receives it's data from the National Weather Service's [Weather Prediction Center](http://www.wpc.ncep.noaa.gov/qpf/obsmaps/obsprecip.php).


This feature is under active development. Expect to see many more Web Sensor data source options in the future. To add a web sensor to your station follow the steps below.

### Virtual Sensor Setup Steps

1. Navigate to the Station Management page of the station you would like to create a web sensor for.
2. Select 'Web Sensors' from the side menu. Click the '+ Web Sensor' button in the top right corner of the Web Sensor Summary page.
3. Select what type of Web Sensor you would like to add to your station. At the time of writing, two types of web sensors are available:
	- **NOAA Daily Precipitation Total**: Daily precipitation total for a latitude/longitude position (North America only)
	- **Current Weather Conditions**: Hourly weather conditions for a latitude/longitude position. Weather data is provided by the Dark Sky Weather API.
4. Select the type of web sensor you would like to add to your station.
5. <span class="app-name"></span> automatically fills in the configuration options but you can make changes to any of the configurations. The sensor location defaults to your station's location but can be updated by either dragging the pin on the map or filling out the latitude and longitude values on the form.
6. Once you're satisfied with the web sensor configuration, click the 'Create' button. You should now see your new web sensor displayed in the web sensor summary table.

After adding a new web sensor, it will begin collecting data at regular intervals. You can use the data from a web sensor in the same way that you would a physical sensor. For instance, you can trend data on charts, adding parameters from your physical sensors and the web sensor to the same chart.