# Salabo moziaku 
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


## 1. solis

Aiša lūdza jūs salabot mozaīku, kas rotāja šo grīdu. Lai to salabotu, izmantojiet ``||`` un ``|agent: agent place||``.

### ~ Padoms 
Aplūko rakstu un atkārto to 4 reizes!

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

