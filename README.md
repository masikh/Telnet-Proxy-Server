# What if you have a device which allows only 1/one concurrent connection? 
You should have some sort of proxy server. That's exactly what this software does. I allows 1024 clients to connect to a telnet proxy server which simplex the connection to one end device.

use case: Connect to a cisco router with more then one client at the same time. Each client gets its own telnet session output

How to use?

Change in the top of the file device_host and device_port to the telnet address and port of the device you'd like to connect to. The proxy will listen to 0.0.0.0 on port 2048
