# Activeer de radiotoren
### @hideIteration true 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Stap 1

We moeten de radiotoren repareren. Gebruik je agent om de grondstoffen op de kaart te verzamelen. Gebruik meerdere ||agent: agent ga vooruit| en ||agent: agent draai| blokken en plaats ze in het ||Loops:on start| blok. Als je klaar bent, klik je op RUN. Voorzichtig, doe het in één keer, anders werkt het niet.

### ~ Tip 
Je kunt het aantal stappen dat je Agent zal bewegen veranderen door het getal in het ||agent: agent move|| blok te veranderen. Je kunt ook een ||agent: agent turn|| blok gebruiken om de Agent naar links of rechts te draaien.

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


