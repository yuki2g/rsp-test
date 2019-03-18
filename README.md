## Test code for Scratch Remote Sensors Protocol for Scratch 1.4

To broadcast the typed in message to Scratch.

 - Scratch cat can receive it with "When I receive 'message'".
 - Just click OK without message to terminate the script.


## How it works
When remote sensors are enabled, Scratch listens for connections on TCP port 42001. Once a connection is established, messages are sent in both directions over the socket connection according to the protocol as below.

```
<size: 4 bytes><msg: size bytes>
```



### Remote Sensors Protocol Documents

## Official Blog
https://en.scratch-wiki.info/wiki/Remote_Sensor_Connections
http://wiki.scratch.mit.edu/wiki/Remote_Sensors_Protocol

## blog.champierre.com (Junya Ishihara)

https://blog.champierre.com/1047
https://blog.champierre.com/1048
https://blog.champierre.com/1049
https://blog.champierre.com/1050
https://blog.champierre.com/1051

## Scratch Remote Sensor Protocol on UDP (YOKOBOND)
https://lab.yengawa.com/2015/12/11/scratch-remote-sensor-protocol-on-udp/

