---
layout: default
---
[back](../../sc2ai){: .btn.btn-default}

# StarCraft 2 API

[SC2 API Github link](https://github.com/Blizzard/s2client-api){: target="_blank"}

This Github repository is SC2 API. SC2 API is a protobuf based on protocols using websockets as the connection layer. Therefore, SC2 API is accessed through the web sockets. SC2 API communicates with SC2 game through the web socket URL. The whole communications between SC2 API and SC2 gmae are done by "request" and "response". 

![SC2 API and SC2 Game](./sc2apiAccess.png)

Each request is usually paired with each response.

## Protocols