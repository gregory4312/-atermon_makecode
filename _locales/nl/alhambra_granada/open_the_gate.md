# Open de poort
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


## Stap 1

Je moet de poort openen. Laat je agent bewegen en de hendel bereiken. Gebruik ``|agent: agent draaien||`` en ``|agent: agent bewegen||``.

### ~ Hint 
Je kunt een ``|loops: repeat|`` lus gebruiken om het makkelijker te maken!

```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

