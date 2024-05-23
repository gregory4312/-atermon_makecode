# Het mozaïek repareren
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


## Stap 1

Aisha heeft je gevraagd om het mozaïek te repareren waarmee deze vloer is versierd. Gebruik een ``|loops: repeat|`` en ``|agent: agent place||`` om het te repareren.

### Hint 
Kijk naar het patroon en herhaal het dan 4 keer!


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

