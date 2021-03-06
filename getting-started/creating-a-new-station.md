# Creating a New Station

<span class="app-name"></span> provides several different types of stations that you can add to your project. Some station types require that you have access to your own data logging hardware such as the eTracker and Cell-Net station types. <span class="app-name"></span> also offers a variety of station types that collect data from third-party data sources and do not require any additional hardware to setup. Note that because external station types are maintained by third parties, we cannot guarantee the frequency or quality of the data transmitted from these external data sources. Here is a list of <span class="app-name"></span> station types:

### Internal Data Source Station Types

Stevens Connect provides a variety of station types to support Stevens telemetry devices. Below is a list of the supported station types: 

-   Stevens Cell-Net + Stevens DLight
-   Stevens eTracker
-   Stevens AVO
-   Stevens Cell-Net
-   Stevens Cell-Net + MetOne AutoMet + MetOne Weather
-   Stevens Cell-Net + MetOne AutoMet + MetOne E-Sampler
-   Stevens Cell-Net + MetOne

### External Data Source Station Types

<ul>
  <li>
    <a href="http://www.goes.noaa.gov/" target="_blank">GOES</a>: 
    The Geostationary Operational Environmental Satellite system (GOES) is operated by the United States' National Oceanic and Atmospheric Administration's National Environmental Satellite, Data, and Information Service division.
  </li>
  <li>
    <a href="https://water.weather.gov/ahps/" target="_blank">Advanced Hydrologic Prediction Service (AHPS)</a>:
    <span class="app-name"></span> pulls metiorlogic weather data directrly from the AHPS weather API. The AHPS data can be used to determine the magnitude and uncertainty of the occurrence of floods or droughts, from hours to days and months in advance. 
  </li>
  <li>
    <a href="https://waterdata.usgs.gov/nwis" target="_blank">US Geological Survey (USGS)</a>:
    <span class="app-name"></span> pulls in data from the USGS National Water Information System API which provides access to water-resources data collected at approximately 1.9 million sites in all 50 States, the District of Columbia, Puerto Rico, the Virgin Islands, Guam, American Samoa and the Commonwealth of the Northern Mariana Islands.
  </li>
  <li>
    <a href="http://mesowest.utah.edu/" target="_blank">Mesonet</a>
    The Mesonet station type provides weather data from the MesoWest weather station network. The MesoWest database offers access to weather data from several thousand weather stations across the United States. 
  </li>
  <li>
    <a href="https://www.wcc.nrcs.usda.gov/snow/" target="_blank">SNOTEL</a>
    The SNOTEL station type provides data from the Snow Survey and Water Supply Forecasting Program, and the NRCS National Soil Climate Analysis Network (SCAN). SNOTEL is part of the National Water and Climate Center (NCRS) provided by the United Stated Department of Agriculture.
  </li>
  <li>
    <a href="https://www.wcc.nrcs.usda.gov/scan/" target="_blank">SCAN</a>
    The SCAN station type provides data from the National Water and Climate Center's (NRCS) Soil Climate Analysis Network (SCAN) service.
  </li>
</ul>

After determining what type of station you would like to create, follow the steps below to get started.

### Creating a New Station

1.  Navigate to the Project Navigator page. Click the '+ Station' button in the top right corner of the map.
    ![Project Navigator](/img/project-navigator800x800.png "Click the '+ Station' button")
2.  Select the type of station you would like to create.
    ![Add Station Wizard Step 1](/img/add-station-wizard-step-1.png "Select a station type")
3.  Setup your station's basic configurations:
    ![Add Station Wizard Step 2](/img/add-station-wizard-step-2.png "Enter station configuration details")
    -   For internal station types, enter the basic station configurations
        -   **Station Name**: Give your station a unique name to identify it by.
        -   **Station Unique Identifier (SUI)**: The Station Unique Identifier is a unique string of numbers and letters that identifies each device or external station. You can find the SUI on the side of your telemetry device's case. 
        -   **Reporting Interval**: This setting controls how often the station reports it's data to the cloud.
        -   **Station Location**: The name of the city or region of your station's physical location. Note that GPS location information can be configured from the station's management page after the initial setup.
        -   **Station Visibility:** This settings controls whether your station is visibly to public users not associated with your organization.
    -   For external station types follow the provided instructions for searching for the external station that you would like to log data from.
4.  Select your timezone by clicking the green dot that is closest to your station's physical location or click 'Skip for now'.
    ![Add Station Wizard Step 3](/img/add-station-wizard-step-3.png "Click on a timezone or click 'Skip for now'")
5.  Review your new station's configurations.
    ![Add Station Wizard Step 4](/img/add-station-wizard-step-4.png "Review your station's configuration details")
    -   For external station types sensors will be auto generated for you. For internal station types no further configuration is necessary.
6.  Click 'Submit' and you will be taken to your new stations 'Station Management' page.
    ![New Station Management Page](/img/add-station-wizard-complete.png "Welcome to your new Station's Managment page!")