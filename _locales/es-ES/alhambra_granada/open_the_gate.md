# Abrir las puertas
### @hideIteration false 
### @flyoutOnly 1


```` ghost
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```
```template
   //     
```


## Paso 1

Tienes que abrir la Puerta. Haz que tu agente se mueva y alcance la palanca. Usa ``||agente: agente girar||`` y ``||agente: agente mover||``

### ~ Sugerencia 
Puedes utilizar un bucle ``||loops: repetir||`` para facilitar las cosas.


```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

