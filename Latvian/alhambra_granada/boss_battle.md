# Activate the fountain
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


## Step 1

Norādiet savam aģentam, kā ieslēgt strūklaku un sakaut ``|agentu: aģentu, kas darbojas kā pūķis|||``

#### ~ pamācības padoms
Sasniedziet sviru ar savu aģentu. Jums būs jāizmanto kopā 3 ``|| cikls: atkārtot||`` un 3 ``| aģenta: aģenta pagrieziens||``


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
