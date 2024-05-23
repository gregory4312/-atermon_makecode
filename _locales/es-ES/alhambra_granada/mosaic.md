# Repara el mosaico
### @hideIteration false 
### @flyoutOnly 1


```` ghost
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
        agent.place(DOWN)
    }
```
```template
   //     
```


## Paso 1

Aisha te ha pedido que repares el Mosaico que decoraba este suelo. Usa ``||loops: repeat||`` y ``|agent: agent place||`` para arreglarlo.

### ~ Sugerencia 
Mira el patrón y repítelo 4 veces.

```  blocks
    for (let index = 0; index < 4; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 2)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.turn(RIGHT_TURN)
}
         
})
```

