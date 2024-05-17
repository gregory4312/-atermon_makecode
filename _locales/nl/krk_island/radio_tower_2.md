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
# Activeer de radiotoren

## Stap 1

Laten we wat meer materiaal verzamelen. Om ons het leven gemakkelijker te maken, kun je de agent een activiteit op herhaling laten uitvoeren. Bestudeer het looppatroon en laat de agent dan alle materialen in één keer verzamelen. Vergeet niet om ze in het blok ||Loops:on start|| te plaatsen.

#### ~ Tip  
Gebruik een ||loops: repeat| lus


```  blocks
    
    agent.move(FORWARD, 6)
    agent.turn(RIGHT_TURN)
         
})
```

```template
   //     
```
