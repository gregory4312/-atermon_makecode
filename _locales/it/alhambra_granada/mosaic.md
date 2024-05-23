# Ripara il mosaico
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


## Passo 1

Aisha vi ha chiesto di riparare il mosaico che decorava questo pavimento. Usate ``|loops: repeat||`` e ``|agent: agent place||`` per ripararlo.

### ~ Suggerimento 
Guardate lo schema e poi ripetetelo 4 volte!

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

