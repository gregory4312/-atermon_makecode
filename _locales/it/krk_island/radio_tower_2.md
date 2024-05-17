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
# Attiva la torre radio

## Passo 1

Raccogliamo un po' più di materiale. Per semplificarci la vita, puoi chiedere all'agente di eseguire un'attività a ripetizione. Studia lo schema di camminata e poi chiedi all'agente di raccogliere tutti i materiali in una volta sola. Non dimenticare di posizionarli nel blocco ||Loops:on start||

#### ~ Suggerimento  
Usa un ciclo ||loops: repeat||


```  blocks
    
    agent.move(FORWARD, 6)
    agent.turn(RIGHT_TURN)
         
})
```

```template
   //     
```
