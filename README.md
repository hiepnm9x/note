# Error
## Docker

### Ports are not available


Error response from daemon: Ports are not available: exposing port TCP 0.0.0.0:5432 -> 0.0.0.0:0: listen tcp 0.0.0.0:5432: bind: An 
attempt was made to access a socket in a way forbidden by its access permissions.

```
net stop winnat
docker-compose up ...
net start winnat
```