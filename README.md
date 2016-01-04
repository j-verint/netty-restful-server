# netty-restful-server

A light and high performance restful server build on netty. If you are preparing for leaning java or netty, it's a nice gift for you.

### Preview

project demo can be visited home:

1. get user info api
[http://netty.restful.api.mengkang.net/user/1](http://netty.restful.api.mengkang.net/user/1)

2. get user album info
[http://netty.restful.api.mengkang.net/user/1/album/10?build=103](http://netty.restful.api.mengkang.net/user/1/album/10?build=103)


### Version 1.0.0

In this version,there is no database, so you can run it directly.

At first, java 8 should be supported in your server.

There's two way to run it.

1. Run `net.mengkang.netty.Server` in Intellij IDEA, Then you can visit 

[http://localhost:8080/user/1](http://localhost:8080/user/1) 

[http://localhost:8080/user/1/album/10?build=103](http://localhost:8080/user/1/album/10?build=103)

in your browser for testing.

2. Anther way is using java command line. 

Download the 
[netty-restful-server-1.0.1.zip](https://github.com/zhoumengkang/netty-light-api-server/releases/download/1.0.1/netty-light-api-server-1.0.1.zip) 
and unzip it , then run it like this:
```sh
java -Dfile.encoding=UTF-8 -jar netty-restful-server-1.0-SNAPSHOT.jar
```
