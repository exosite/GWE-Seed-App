# GWE-Seed-App
An example solution displaying all the telemetric data from GateWay Engine as well as showing a Custom GateWay Application, "gmq-sine-demo".
# Getting Started
1. Create a Murano account and login to your account.
2. Chose to create a new prodiuct from scratch as a starting point. Feel free to make up a name
3. Add a device called "GateWay", use your gateway's MAC address as the Identity. Example format "00:08:00:4A:02:25"
4. Add a device called "Test Data", use 12345 as the identity
5. Add the "test" resource to your "Test Data" device as a float
6. Add the "usage_report", "engine_report", "device_info", "update_interval", "engine_fetch", and "fetch_status" resources to your "GateWay" Device
2. Install GWE on your GateWay following the documentation https://gateway-engine.exosite.io/gateway-engine/README.html
3. Add a "Test Data" Device to your Murano Solution. You can use anyting you would like for the device identity, such as 12345.
4. Install the gmq-sine-demo onto the GateWay using the documentation https://github.com/exosite/gmq-sine-demo
	-Use the device identity as the Serial when prompted. (12345)
5. 
