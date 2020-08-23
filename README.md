# Netty HTTP Gateway



Test server with: 


Client -------> GatewayServer(localhost:9090)   -----> NettyHTTPServer(localhost:6060) 
                        


Client 
```shell script
curl http://localhost:9090/foo
```
