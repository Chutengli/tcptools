# tcptools

## Using Ping

### For www.amazon.com
- round-trip min/avg/max/stddev = 25.431/38.943/83.269/15.325 ms
- 0.0% packet loss
- The IP address won't change  if the times between each ping are short. It will change if the times between each ping are longer

### For www.google.com
- round-trip min/avg/max/stddev = 22.578/31.741/39.703/6.236 ms
- 0.0% packet loss
- The IP address won't change  if the times between each ping are short. It will change if the times between each ping are longer

### For www.microsoft.com
- round-trip min/avg/max/stddev = 21.855/48.217/157.777/33.733 ms
- 0.0% packet loss
- The IP address won't change  if the times between each ping are short. It will change if the times between each ping are longer

## Using tracert

### For www.amazon.com
- target ip: 65.8.70.230
- 22 hops
- Yes, based on `hop 5 po-2-rur902.seattle.wa.seattle.comcast.net (69.139.161.158)`. My provider is comcast
- Identify the "class" of IP address for each major step in the trip

### For www.google.com
- Target IP: 142.250.69.196
- 11 hops
- Yes, based on `hop 5 po-2-rur902.seattle.wa.seattle.comcast.net (69.139.161.158)`. My provider is comcast
- address for each major step in the trip

### For www.microsoft.com
- Target IP: 96.216.153.5
- 9 hops
- Yes, based on `hop 5 po-2-rur902.seattle.wa.seattle.comcast.net (69.139.161.158)`. My provider is comcast
- Identify the "class" of IP address for each major step in the trip