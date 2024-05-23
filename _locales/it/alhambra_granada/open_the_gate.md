# Apri il cancello
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


## Passo 1

Devi aprire il cancello. Chiedi al tuo agente di muoversi e raggiungere la leva. Usa ``||agent: agent turn||'' e ''``||agent: agent move||''

### ~ Suggerimento 
È possibile utilizzare un ciclo ``||loops: repeat||``  per rendere le cose più facili!


```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

