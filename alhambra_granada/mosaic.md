# Repair the Mosaic
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


## Step 1

Aisha asked you to repair the Mosaic which used to decorate this floor. Use a ``||loops: repeat||`` and ``|agent: agent place||`` to fix it.

### ~ Hint 
Look at the pattern and then repeat it 4 times!

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

