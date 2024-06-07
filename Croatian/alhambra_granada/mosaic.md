# Popravite mozaik
### @hideIteration false 
### @flyoutOnly 1


```` ghost
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
        agent.place(DOWN)
    }
```
```template
   //     
```


## Korak 1

Aisha te je zamolila da popraviš mozaik koji je nekada ukrašavao ovaj pod. Upotrijebite ``||petlje: ponavljanje||`` i ``|agent: mjesto agenta||`` da to popravite.

### ~ Savjet 
Pogledajte uzorak i ponovite ga 4 puta!

```  blocks
    for (let index = 0; index < 4; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 2)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.turn(RIGHT_TURN)
}
         
})
```

