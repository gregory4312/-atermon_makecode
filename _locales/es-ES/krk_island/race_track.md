# Preparar el circuito
### @flyoutOnly true
### @hideIteration true


``` ghost
     for (let index = 0; index < 2; index++) {}
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```

```template
   //     
```

## Paso 1
Vamos a configurar las antenas para contar la puntuación de la carrera. Haz que tu agente visite los puntos marcados usando ||agente: agente avanzar|| así como ||agente: agente girar||. Estudia primero el patrón de paseo y luego ejecuta tu código en el bloque ||Loops: al empezar||.

### ~ Pista
Hay varias formas de resolverlo. También puedes hacer uso de los bloques ||loops: repetir||. Intenta encontrar el camino más corto

```  blocks
agent.turn(LEFT_TURN)
for (let index = 0; index < 2; index++) {
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
}
agent.move(FORWARD, 6)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 10)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 4)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 6)


```

