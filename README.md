grpc Examples
==============================================

In order to run the examples simply execute one of the gradle tasks `pollServiceServer`, `pollServiceServer`,  `routeGuideServer`, `routeGuideClient`, `helloWorldServer`, or `helloWorldClient`.

For example, say you want to play around with the poll service examples. First you want to start
the server and then have the client connect to it and let the good times roll.

Assuming you are in the grpc-java root folder you would first start the route guide server
by running

```
$ ./gradlew :grpc-examples:pollServiceServer
```

and in a different terminal window then run the route guide client by typing

```
$ ./gradlew :grpc-examples:pollServiceClient
```

That's it!

