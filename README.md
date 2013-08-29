# CiscoApp-1.0 

Monitor CiscoASA, PIX devices 


 ![Cisco ASA Searches and Workspaces](http://www.google.com) 


## Installation

It is recommended to use Logscape Syslog Server to monitor your Cisco Devices. If your data is deleted if the device, the logs will remain in Logscape. 

1. To monitor CiscoASA devices create a datasource that points to your log data or point your Cisco devices to Logscape's Syslog Server

	tcp MANAGER:1468
	udp MANAGER:1514

2. Import the CiscoSyslog.config file


3.  Update the Dir and File fields of the cisco-asa datatype to reflect the location of your data. 

	![](docs/images/datatype.png) 

	If you are using Logscapes Syslog server update the host to match that of your Cisco ASA Device	




![](docs/images/apphome.png)


