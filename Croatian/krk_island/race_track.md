# Postavite trkaću stazu
### @flyoutOnly true
### @hideIteration true


``` ghost
     for (let index = 0; index < 2; index++) {}
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```

```template
   //     
```

## Korak 1
Postavimo antene da brojimo bodove za utrku. Neka vaš agent posjeti označena mjesta koristeći ||agent: agent pomakni naprijed|| kao i ||agent: agent turn||. Prvo proučite uzorak hodanja, a zatim pokrenite svoj kod na||Loops:on start|| blok.

### ~ Hint 
Postoji više načina da se to riješi. Također možete koristiti ||petlje: ponovi|| blokovi. Pokušajte pronaći najkraći put

```  blocks
agent.turn(LEFT_TURN)
for (let index = 0; index < 2; index++) {
agent.move(FORWARD, 4)
agent.turn(RIGHT_TURN)
}
agent.move(FORWARD, 6)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 10)
agent.turn(RIGHT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 4)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 6)


```

