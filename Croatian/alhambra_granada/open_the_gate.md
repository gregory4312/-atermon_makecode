# Otvori Vrata
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


## Korak 1

Morate otvoriti Vrata. Neka se vaš agent pomakne i dosegne polugu. Koristite ``||agent: agent turn||`` i ``||agent: agent move||``

### ~ Savjet 
Možete upotrijebiti petlju ``||: ponovi||`` kako biste olakšali stvari!


```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

