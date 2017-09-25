# pubsub

Publish/Subscribe seever which broadcast messages to all other connected clients

## Building

```
git clone https://github.com/sokil/pubsub
cd pubsub
go build
```

## Useage

Start server:

```
./pubsub --port=12345 --host=localhost
```

Add few connections to server:

```
nc localhost 12345
```

Messages written on one instanse will be published to all other instances