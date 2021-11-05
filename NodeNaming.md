# OPC UA Node Naming Convention
There are 5 metadata keys associated with each service instances of the "SignalStatus" and "SignalUpdate" services.
The metadata keys are "NodeId", "Device", "DeviceType", "Location" and "http-method".
Hence, all nodes follow the naming structure as  \<DeviceID>\_\<DeviceType>\_\<Location>.

The names of the nodes is presented in the figure below.

![alt text](https://github.com/aparajita07/Client-OPC-UA-Adaptor/blob/main/OPCUAClient.PNG)
  
## Note
Here, the naming convention for OPC UA nodes is informal and self-derived.
In real manufacturing industries, to maintain a common technical language between stakeholders, systems can be built using an international standards such as ISO 81346, which will be implemented in the next version of this Adaptor.
