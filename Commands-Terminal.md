
---
```
Configure basic settings for each router.
Open configuration window
a. Console into the router and enable privileged EXEC mode.
Router> enable
Router# configure terminal
b. Configure host names as shown in the topology.
R1(config)# hostname R1
c. Configure interface IP addresses as shown in the IP Addressing Table.
R1(config)# interface g0/0/0
R1(config-if)# ip address 10.1.1.1 255.255.255.0
R1(config-if)# no shutdown
R1(config)# interface g0/0/1
R1(config-if)# ip address 192.168.1.1 255.255.255.0
R1(config-if)# no shutdown
```
```
show ip route
```

## Save the running-config to the startup-config.
```R1# copy running-config startup-config
```
`R1#show running-config` - pokazuje ustawienia urządzenia 


If you cannot ping but the device interfaces are up and IP addresses are correct, use the **show run**, **show ip ospf neighbor**, and **show ip route** commands to help identify routing protocol-related problems.


**copy running-config startup-config**


