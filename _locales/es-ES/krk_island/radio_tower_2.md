### @flyoutOnly true
### @hideIteration true
### @explicitHints true

``` ghost
    count = 0
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```
# Activar la Torre de Radio

## Paso 1

Reunamos más materiales. Para facilitarnos la vida, puedes hacer que el agente realice una actividad de forma repetida. Estudia el patrón de paseo y luego haz que el agente recoja todos los materiales de una sola vez. No olvides colocarlos en el bloque ||Loops:al inicio||.

#### ~ Pista 
Utilizar un bucle ||loops: repetir||


```  blocks
    
    agent.move(FORWARD, 6)
    agent.turn(RIGHT_TURN)
         
})
```

```template
   //     
```
