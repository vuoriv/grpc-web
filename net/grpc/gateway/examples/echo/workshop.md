## Basic commands

Start service
```
docker-compose up node-server envoy commonjs-client
```

Start and rebuild service
```
docker-compose stop && docker-compose up node-server envoy commonjs-client
```

Remove
```
docker-compose rm --all
```

## Workshop Step 1

Tutustutaan palveluun ja testataan pohjatilanteen toimivuus

### Repon kloonous
```
git clone https://github.com/vuoriv/grpc-web.git
git checkout workshop
```

### Käynnistys
```
docker-compose up node-server envoy commonjs-client
```

### Testaa

http://localhost:8081/echotest.html

### Kuvaus

https://grpc.io/docs/tutorials/basic/web.html

Tiedostot

  - https://github.com/vuoriv/grpc-web/tree/workshop
  - https://github.com/vuoriv/grpc-web/tree/workshop/net/grpc/gateway/examples/echo
  - https://github.com/vuoriv/grpc-web/tree/workshop/net/grpc/gateway/examples/echo/commonjs-example


## Workshop Step 2

Reverse echo ja kellonaika 