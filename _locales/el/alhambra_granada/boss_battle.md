# Ενεργοποιήστε το συντριβάνι
### @flyoutOnly true
### @hideIteration true
### @explicitHints true


```` ghost
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```
```template
   //     
```


## Βήμα 1

Καθοδηγήστε τον πράκτορά σας για να ενεργοποιήσετε το σιντριβάνι και να νικήσετε ``|τον πράκτορα: Δράκος||``


### ~ Υπόδειξη
Φτάστε στο μοχλό με τον πράκτορά σας. Θα χρειαστεί να χρησιμοποιήσετε συνολικά 3 ``||βρόχοι: επανάληψη||`` και 3 ``||πράκτορα: πράκτορα γύρνα||``


```  blocks
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 2)
    agent.turn(RIGHT_TURN)
}
agent.turn(LEFT_TURN)
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 2)
    agent.turn(LEFT_TURN)
}
agent.turn(LEFT_TURN)
agent.turn(LEFT_TURN)
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 2)
    agent.turn(RIGHT_TURN)
}
         

```
```package
github:gregory4312/-atermon_makecode-ts
```
