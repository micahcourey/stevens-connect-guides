# Virtual Sensor Setup

Virtual Sensors are designed to be used in conjunction with a predefined algebraic function or flow table. The purpose of a virtual sensor is to allow you to save the data from a physical sensor with a data transformation applied to it. 

### Virtual Parameters

A virtual sensor consists of any number virtual parameters and each parameter can be tied to a different algebraic function or flow table. There are some key differences between a flow table virtual parameter and a algebraic function virtual parameter.

### Algebraic Function Virtual Parameters

When you create an algebraic function you tie a physical parameter to each of the variables in your formula. These physical parameters are known as the 'source parameters'.  When data comes in from your source parameters, your virtual sensor will receive this data, run it through the algebraic function and then output the modified value as a virtual parameter reading. For example, lets say you want to create a virtual sensor that logs dew point values. You will first create an algebraic function that calculates dew point by linking a physical sensors humidity and temperature parameter values (the source parameters) to the variables of the dew point formula. You can now create a virtual sensor, add a virtual parameter called Dew Point and link it to the Dew Point algebraic function. Now your dew point readings will be logged and stored just like a real sensor's parameter readings.

### Flow Table Virtual Parameters

Flow table virtual parameters are setup slightly different from algebraic functions. Unlike algebraic functions, flow tables do not have a source parameter. Instead, a source parameter is linked directly to the virtual parameter. The source parameter is selected during the virtual parameter setup process. When data comes in from your source parameter, your virtual sensor will receive this data, run it through the flow table and then output the modified value as a virtual parameter reading. 

### Virtual Sensor Setup Steps

1.  Navigate to the Station Management page of the station you would like to create a virtual sensor in.
2.  Select 'Data Transformations' from the side menu and create a Flow Table or Algebraic Function.
3.  Once you've created at least one Algebraic Function or Flow Table, select Virtual Sensors from the side menu and click the '+ Virtual Sensor' button.
4.  Give your Virtual Sensor a unique name and click the 'Create' button.
5.  Once you create your Virtual Sensor you will be taken to the sensors configuration page. Click the '+ Parameter' button on the Virtual Sensor's configuration page.
6.  Select either 'Flow Table' or 'Algebraic Function' depending on which of these you created in step 2.
7.  Now select the Algebraic Function/Flow Table that you created in step 2 from the list.
8.  Give your new virtual parameter a name and set a scale and/or offset if applicable. Note that in most cases scale and offset options should be left at their default values (scale: 1, offset: 0). When you're ready, click 'Submit'.
9.  Success! You should now see your new virtual parameter on the Sensor Configuration page. Once new readings are reported for the physical sensor parameter that you have tied to the Algebraic Function the new data will be saved to your virtual sensor with the data transformation applied.