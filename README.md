dam-akka-streams
================

A sample playground on distributed DAM system leveraging all of the current goodies such as:
- [Akka](http://akka.io/)
- [Akka Streams](http://doc.akka.io/docs/akka/snapshot/scala/stream/index.html)
- [Alpakka](https://github.com/akka/alpakka)
- [Scala](http://scala-lang.org/)
- [SBT](http://www.scala-sbt.org/)

### Playground architecture
TBD!

### Setting up development infrastructure
```
docker-compose -f docker/dev.yml up
```

### Running all components
```
```

### Ingesting an asset
```
curl -X POST http://localhost:8080/dam/asset -d "{'name':'helloAsset', 'contentUrl':'https://farm8.staticflickr.com/7336/11770504415_a3304be7d7_o_d.jpg'}" -H "Content-Type: application/json"
```
