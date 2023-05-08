# ARP Spoofing using mininet

A pure-Python ARP Cache Poisoning (a.k.a. "ARP Spoofing") tool that leverages
a low-level assembly of Ethernet II frames and ARP packets.

## Files
### `SDNSpoof.py`
ARP Spoofing with SDN OVS switch (star topology)
### `TradSpoof.py`
ARP Spoofing in a traditional network (star network)
### `webserver.sh`
Execute `netcat` based webserver
### `test`
Create the webpage