# Prepara la pista da corsa
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

## Passo 1
Impostiamo le antenne per contare il punteggio per la gara. Chiedi al tuo agente di visitare i punti contrassegnati utilizzando ||agent: agent move forward||  così come ||agent: agent turn||. Studia prima il modello di camminata e poi esegui il codice sul blocco||Loops:on start||.

### ~ Suggerimento 
Esistono diversi modi per risolvere questo problema. È inoltre possibile utilizzare i bocchi ||loops: repeat||. Prova a trovare il percorso più breve

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

