# changelog

## 0.6.0(2024-03-27)
-   translated from [dynatalk-js 0.6.0](https://github.com/wwj718/dynatalk-js/blob/main/docs/0.6.0.md)
    -   Supervisor: deliver broadcast messages
    -   Agent: add `ping` action; support `broadcast`; add `broadcastHelp`. 
    -   PyDemoAgent: add `help` action. 
-   Add console script: `dynatalk-monitor`

## 0.5.0(2024-03-26)

-   translated from [dynatalk-js 0.5.0](https://github.com/wwj718/dynatalk-js/blob/main/docs/0.5.0.md)
    -   agent public api
        -   client
            -   request
            -   sendTo
        -   server
            -   responseWith
            -   raiseWith

## 0.1.0(2024-03-18)

- Minimum dynatalk
    -   The agent will interpret the message it understands and optionally respond (or error message)
    -   Implemented MQTTSpace, Supervisor, Agent, and a simple example: LivelyDemoAgent (it only understands `echo`)
