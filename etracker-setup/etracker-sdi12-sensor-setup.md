# SDI-12 Sensor Setup

SDI-12 stands for serial data interface at 1200 baud. It is a standard to interface battery powered data recorders with micro-processor based sensors designed for environmental data acquisition (EDA). eTrackers can support up to 62 SDI-12 sensors while an AVO can support 10 SDI-12 sensors. More information about SDI-12 sensors can be found in our [SDI-12 Quick Start Guide](../getting-started/sdi12-quick-start.md). To add a SDI-12 sensor to your station navigate to the Station Management page and select 'SDI-12 Sensors' from the side menu. On the SDI-12 summary page click the '+ Sensor' button to get started. Follow the steps below to add your new SDI-12 sensor.

### SDI-12 Sensor Setup Steps

1.  Give your new sensor a unique name and select the channel that you want to connect your sensor to.
2.  You can now add parameters to your new sensor. You can select a sensor template from the dropdown list to auto-generate parameters (auto generated parameters can be edited or added to later) or select 'Custom' to create your own custom parameter configurations.
3.  Select 'Custom' to add your own sensor parameters. To begin, select the M Command that you would like to add parameters to and click the '+ New M Parameter' button.
4.  Name the parameter, select an input unit and set the parameters 'Incoming Order' which defaults to the first available. When you're satisfied with your parameter configuration, click 'Add M Parameter'.
5.  Repeat step 4 to add additional parameters to your sensor. When you're finished click the 'Create Sensor and x Parameters' button.
6.  You should now see your new SDI-12 sensor in the side menu list as well as the Sensor Summary page list. Click on the sensor from either list to make further configurations.