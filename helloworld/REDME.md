# Hello World tutorial

## Dependecies

1. RabbitMq (installed via brew)
2. AMPQ Client
3. SLF4J API
4. SLF4J Simple


## How to build

Execute, in order to export env variable CP (for Class Path):
```
source setup.sh
```

Then execute command:
```
bin/build.sh
```

## How to run

In order to observe the behaviour of message queues, use 2 terminals to run:
```
bin/run_recv.sh
```
and
```
bin/run_send.sh
```
