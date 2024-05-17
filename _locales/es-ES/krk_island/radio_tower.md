# Activar la Torre de Radio
### @hideIteration true 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Paso 1

Tenemos que arreglar la Torre de Radio. Usa tu agente para recoger los recursos del mapa. Utiliza varios bloques ||agente: agente avanzar|| así como ||agente: agente girar|| y colócalos en el bloque ||Loops:al empezar||. Cuando hayas terminado, haz clic en EJECUTAR. Cuidado, hazlo de una sola vez o no funcionará.

### ~ Pista 
Puede cambiar el número de pasos que se moverá su Agente cambiando el número dentro del bloque "agente: agente mover". También puede utilizar un bloque "agente: agente girar" para girar el agente a la izquierda o a la derecha.
```  blocks
         agent.move(FORWARD, 2)
         agent.turn(LEFT_TURN)
          agent.move(FORWARD, 1)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 3)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 5)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 3)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 2)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 1)
         agent.turn(RIGHT_TURN)
         
})
```


