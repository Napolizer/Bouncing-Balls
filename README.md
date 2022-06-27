# Concurrent programming

### Overview
Project contains multitier architecture application using MVVM pattern. Balls are moving independently using asynchronous programming. Data integration is provided via critical sections implemented using locks and mutexes.

### Multitier architecture
Each layer provides abstract API to communicate with higher layers. Implementation of properties and methods is always internal within layer.

