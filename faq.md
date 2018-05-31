# FAQ

### What is an 'external station type'?

<span class="app-name"></span> offers a variety of station types that collect data from third-party data sources and do not require any additional hardware to setup. We refer to these as 'external station types'.  Note that because external station types are maintained by third parties, we cannot guarantee the frequency or quality of the data transmitted from these external data sources. External station types currently offered include [GOES](http://www.goes.noaa.gov/), [Advanced Hydrologic Prediction Service (AHPS)](https://water.weather.gov/ahps/), [US Geological Survey (USGS)](https://waterdata.usgs.gov/nwis), [Mesonet](http://mesowest.utah.edu/), [SNOTEL](https://www.wcc.nrcs.usda.gov/snow/) and [SCAN](https://www.wcc.nrcs.usda.gov/scan/).

### What is station health?

A station's health is calculated by averaging each sensor's transmission history over the last 24 hours. If all sensors are reporting successfully then your station's health will be 100%.

### What is a Station Unique Identifier (SUI)?

The Station Unique Identifier (SUI) is an identification code which can be found on your Stevens data logging device. For external station types (e.g. USGS, AHPS, GOES) the SUI is used to identify the station code for the external weather station.

### How do I update my alarm notification preferences

- **Update the notification settings for your account** <br>
Navigate to your User Settings page by clicking the user menu in the top right corner of the page and selecting 'User Settings'. On the User Settings page you can update your alarm notification preferences by toggling 'Send alarms via email', 'Send alarms via SMS' or you can toggle both to receive notifications through both mediums. Be sure to click the 'Submit' button in order to save your changes. 

- **Update the notifcation settings for an alarm** <br>
If you want to stop or begin receiving notifications for a particular alarm, you can update this by navigating to your Project Dashboard and selecting 'Alarms' from the side menu. Click the alarm that you want to update the notification settings for and update the toggle next to your name.

### Can I save or export the data produced from an Algebraic Function?

Algebraic functions can be used on their own to create tables and charts with the [Trends](project-dashboard-guides/building-charts-and-data-tables-in-trends.md) feature. These charts and tables can be exported in multiple file formats including CSV, PNG, JPEG, PDF and SVG.  Algebraic Functions can also be used in conjunction with a [Virtual Sensor](station-management-guides/virtual-sensor-setup.md) to allow the calculated data to be stored and tracked.

### What is a virtual sensor and what can I use them for?

Virtual Sensors are designed to be used in conjunction with a predefined algebraic function or flow table. The purpose of a virtual sensor is to allow you to save the data from a physical sensor with a data transformation applied to it. A virtual sensor consists of virtual parameters and each parameter can be tied to a different algebraic function or flow table. Learn more about [Virtual Sensors](station-management-guides/virtual-sensor-setup.md).

### What's a Web Sensor?

A Web Sensor is a virtual sensor which pulls data from external data sources in the vicinity of your weather station. <span class="app-name"></span> currently provides two types of web sensors: NOAA Daily Precipitation Total and Current Weather Conditions. You can use the web sensors to add an additional layer of data to your station. This data can be used in conjunction with your physical sensor's data to create charts and identify trends.