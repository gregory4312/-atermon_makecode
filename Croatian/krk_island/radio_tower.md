# Aktivirajte Radio toranj
### @hideIteration true 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Korak 1

Moramo popraviti Radio toranj. Koristite svog agenta za prikupljanje resursa na karti. Koristite višestruki ||agent: agent pomakni naprijed|| kao i ||agent: agent turn|| blokove i smjestite ih u ||Loops:on start|| blok. Kada završite, kliknite POKRENI. Pažljivo, učinite to u jednoj vožnji ili inače neće uspjeti.

### ~ Savjet 
Možete promijeniti broj koraka koje će vaš agent pomaknuti promjenom broja unutar ||agent: agent move|| blok. Također možete koristiti ||agent: agent turn|| blok za okretanje Agenta ulijevo ili udesno.

```  blocks
         agent.move(FORWARD, 2)
         agent.turn(LEFT_TURN)
          agent.move(FORWARD, 1)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 3)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 5)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 3)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 2)
         agent.turn(RIGHT_TURN)
          agent.move(FORWARD, 1)
         agent.turn(RIGHT_TURN)
         
})
```


