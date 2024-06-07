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
# Aktivirajte Radio toranj

## Korak 1

Prikupimo još materijala. Kako biste nam olakšali život, agentu možete omogućiti ponavljanje aktivnosti. Proučite obrazac hoda i onda neka agent prikupi sve materijale odjednom. Ne zaboravite ih smjestiti u ||Loops:on start|| blok.

#### ~ Savjet 
Koristite petlju ``||loops: repeat||`` petlju



```  blocks
    
    agent.move(FORWARD, 6)
    agent.turn(RIGHT_TURN)
         
})
```

```template
   //     
```
