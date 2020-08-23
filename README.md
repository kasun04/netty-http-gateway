# Netty HTTP Gateway



## Scenario 

Client -------> GatewayServer(localhost:9090)   -----> NettyHTTPServer(localhost:6060) 
                        


## Usage

- Start NettyHTTPServer
- Start GatewayServer 
- Invoke GatewayServer from client:   
    ```shell script
    curl http://localhost:9090/foo
    ```
