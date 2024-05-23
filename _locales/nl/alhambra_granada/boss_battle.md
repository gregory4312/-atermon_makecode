# Activeer de fontein
### @flyoutOnly true
### @hideIteration true
### @explicitHints true


```` ghost
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```
```template
   //     
```


## Stap 1

Leid je agent om de fontein aan te zetten en versla de ``agent: Draak``

~ tutorialhint 
Bereik de hendel met je agent. Je moet in totaal 3 ``|loops: repeat|`` en 3 ``|agent: agent turn|`` gebruiken.


```  blocks
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 2)
    agent.turn(RIGHT_TURN)
}
agent.turn(LEFT_TURN)
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 2)
    agent.turn(LEFT_TURN)
}
agent.turn(LEFT_TURN)
agent.turn(LEFT_TURN)
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 2)
    agent.turn(RIGHT_TURN)
}
         

```
```package
github:gregory4312/-atermon_makecode-ts
```
