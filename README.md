# CS4262_ChatServer

## Project Setup

Make sure you have gradle on your machine. Original project initializing version is Gradle 7.3.3 with JVM 17.0.3

### Run Project

``` 
./gradlew run --args="s1 D:\projects\semester_8\distributed_systems\CS4262_ChatServer\sample_config"
```

### Run client application

check the IPv4 Address by using `ipconfig` command.

```
java -jar .\client.jar -h <IPv4 Address> -p 6000 -i lucifer
```

### Connect to chat server

check the IPv4 Address by using `ipconfig` command.

```
java -jar .\client.jar -h 143.198.68.88 -p 6000 -i <username>
```

### Build a jar
```
gradle fatJar
```