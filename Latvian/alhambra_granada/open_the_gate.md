# Atveriet vārtus
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


## 1 solis

Jums ir jāatver Vārti. Palūdz savam aģentam pārvietoties un aizsniegt sviru. Izmantojiet ``|||`` un ``||`` aģents: aģenta kustība||

### ~ Padoms
Lai atvieglotu darbu, varat izmantot ``|| cikls: atkārtot|``!


```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

