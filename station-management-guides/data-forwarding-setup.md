# Data Forwarding Setup

Data forwarding allows you to forward all of your station's data to an external location using one of several transfer protocol options. <span class="app-name"></span> currently offers forwarding with the following transfer protocols:

<ul>
  <li><strong>FTP:</strong> <a href="https://en.wikipedia.org/wiki/File_Transfer_Protocol" target="_blank">File Transfer Protocol</a></li>
  <li><strong>SFTP:</strong> <a href="https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol" target="_blank">Secure File Transfer Protocol</a></li>
  <li><strong>HTTP:</strong> <a href="https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol" target="_blank">Hypertext Transfer Protocol</a></li>
  <li><strong>HTTPS:</strong> <a href="https://en.wikipedia.org/wiki/HTTPS" target="_blank">Hypertext Transfer Protocol for secure communication</a></li>
  <li><strong>Socket:</strong> <a href="https://github.com/StevensWater/stevens-connect-socket-data" target="_blank"><span class="app-name"></span> Socket.io Data Server</a></li>
  <li><strong>Secure Socket:</strong> HTTPS <a href="https://github.com/StevensWater/stevens-connect-socket-data" target="_blank"><span class="app-name"></span> Socket.io Data Server</a></li>
</ul>

### Prerequisites

Before setting up data forwarding, ensure that your server and database are configured to receive incoming data through one of the transfer protocols listed above. Once your server is setup you can follow the steps below to setup data forwarding.

### Data Forwarding Setup Steps

1.  Navigate to the Station Management page for the station who's data you would like to forward.
2.  Press the 'Data Management' option in the Station Management side menu and then press 'Data Forwarding' from the expanded menu.
3.  Select the forwarding protocol type that you have configured your remote server to receive.
4.  Give your forward a unique name and description.
5.  Select which format you would like receive your data in. The following options are available:
    -   **Stevens format**:  [JSON syntax](https://en.wikipedia.org/wiki/JSON)
    -   **Raw data**: Selecting this option will forward your data in the same format in which it is received. The format will vary depending on which type of station you are forwarding from.
6.  Configure the host name, port and path based on your server's configuration.
7.  Configure any protocol specific settings such as username and password.
8.  Once you've filled in all of the form fields, press the 'Submit' button to create your new forward.
9.  You should now see that a new tab has been added for your new forward.

You can click the tab for your forward to view it's configuration settings and/or update the configurations at any time. Note that once you've created a forward for one station, you can copy this forward to other stations within your project.

### Copying Data Forwarding Configuration to Additional Stations Steps

1.  Navigate to the Station Management page that contains the original forward that you would like to copy.
2.  Press the 'Data Management' option in the Station Management side menu and then press 'Data Forwarding' from the expanded menu.
3.  Select the forward that you would like to copy.
4.  Press the 'Edit' button on the forward display card.
5.  Now that you're in edit mode press the 'Copy Forward' button at the top of the card.
6.  Select the station that you would like to copy the forward to from the dropdown list.
7.  Enter the password that you gave to this forward when it was originally created.
8.  Press the 'Submit' button.
9.  Navigate to the Station Management page for the station that you copied the forward to and verify that the new forward has been created.
