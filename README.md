# poc-gprc

`Golang example`

```sh
$ protoc -I helloworld/ helloworld/helloworld.proto --go_out=plugins=grpc:helloworld
```

```sh
$ go run server/server.go
```

```sh
$ go run client/client.go
$ Greeting: Hello world
```