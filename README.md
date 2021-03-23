# JSON-to-ISO8583

JSON endpoint to ISO8583 Server.

## Deployment Scenario
```
                      /-------------------\
/-----------\         |                   |       /------------------------\      /-------------------\
| HTTP-json | ----->  | json-to-iso8583   |  ---> | JPOS as ISO8583 Client | ---> | ISO8583 Server    |
\-----------/         |   springboot      |       \------------------------/      \-------------------/
                      \-------------------/

```

https://github.com/leonartambunan/iso8583-server-simulator-beanshell suits as ISO8583 Server

## How to build
```mvn clean package```

## How to run
```java -Xms126m -Xmx512m -jar target/json-iso-1.0.0.jar```



## Commercial collaboration

Feel free to send your inquiries about commercial collaboration (such as systems integration, Android/iOS applications development and other payment solutions) to leonar.tambunan@gmail.com.
