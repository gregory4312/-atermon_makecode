# Ανοίξτε την πύλη
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


## Βήμα 1

Πρέπει να ανοίξετε την πύλη. Βάλτε τον πράκτορά σας να κινηθεί και να φτάσει στο μοχλό. Χρησιμοποιήστε τα ``|| πράκτορας: πράκτορα γύρνα ||`` και `|| πράκτορας: πράκτορα μετακινήσου ||``

### ~Υπόδειξη 
Μπορείτε να χρησιμοποιήσετε έναν βρόχο ``||Βρόχοι: επανάληψη||`` για να διευκολύνετε τα πράγματα!


```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

