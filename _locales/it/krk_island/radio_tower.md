# Attiva la torre radio
### @hideIteration true 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Passo 1

Dobbiamo sistemare la Torre Radio. Usa il tuo agente per raccogliere le risorse sulla mappa. Usa più volte i blocchi||agent: agent move forward|| così come ||agent: agent turn|| e posizionali nel blocco ||Loops:on start||. Al termine, fare clic su ESEGUI. Attenzione, fallo in una sola volta altrimenti non funzionerà.

### ~ Suggerimento 
Puoi modificare il numero di passi che il tuo agente farà cambiando il numero all'interno del blocco ||agent: agent move||. È anche possibile utilizzare un blocco ||agent: agent turn||  per girare l'agente a sinistra o a destra.

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


