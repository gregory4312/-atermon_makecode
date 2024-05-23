# Attivare la fontana
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


## Passo 1

Guida il tuo agente ad accendere la fontana e sconfiggere ``|agent: Dragon||``

### ~ tutorialhint 
Raggiungi la leva con il tuo agente. Dovrai usare 3 ``||loops: repeat||`` in totale e 3 ``||agent: agent turn||``

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
