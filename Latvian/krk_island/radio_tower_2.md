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
# Radio torņa aktivizēšana

## 1 darbība

Apkoposim vēl dažus materiālus. Lai atvieglotu mūsu dzīvi, varat likt aģentam atkārtot kādu darbību. Izpētiet pastaigas modeli un pēc tam palūdziet aģentam savākt visus materiālus vienā piegājienā. Neaizmirstiet tos ievietot blokā || cikls: starts|||.

#### ~ Padoms  
Izmantot || cikls: atkārtot||cikls


```  blocks
    
    agent.move(FORWARD, 6)
    agent.turn(RIGHT_TURN)
         
})
```

```template
   //     
```
