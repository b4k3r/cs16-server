# Counter Strike 1.6 server on Docker

It contains ESL configs.

## Example
```
docker run -d -p 27015:27015 -p 27015:27015/udp --name cs16-server -v /cs/cs16_server.cfg:/home/steam/cs16/cstrike/server.cfg b4k3r/cs16-server
```
