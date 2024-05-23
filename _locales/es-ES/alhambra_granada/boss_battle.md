# Activar la fuente
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


## Paso 1

Guía a tu agente para encender la fuente y derrotar al ``|agente: Dragón||``

### ~ tutorialhint 
Alcanza la palanca con tu agente. Tendrás que usar 3 ``||loops: repetir||`` en total y 3 ``||agente: agente girar|||``


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
