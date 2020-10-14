# ngrok_multiple_tunnel
ngrok config for starting multiple tunnel in ( free version )

find ```ngrok.yml``` configuration in windows file

then add the following:

```
tunnels:
    tcp_demo:
        proto: http
        addr: 80
    tcp_demo:
        proto: http
        addr: 8080
```
make sure it has 4 spaces for value not tab to make it works
