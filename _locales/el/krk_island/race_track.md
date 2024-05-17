# Ρύθμιση της πίστας αγώνων
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

## Βήμα 1
Ας στήσουμε τις κεραίες για να μετρήσουμε το σκορ του αγώνα. Βάλτε τον πράκτορά σας να επισκεφτεί τα σημεία που έχουν σημειωθεί χρησιμοποιώντας || πράκτορας: πράκτορα κινήσου μπροστά || καθώς και || πράκτορας: πράκτορα γύρνα ||. Μελετήστε πρώτα το μοτίβο περιπάτου και στη συνέχεια εκτελέστε τον κώδικά σας στο μπλοκ||Βρόχοι:στην αρχή||.

### ~ Υπόδειξη 
Υπάρχουν πολλαπλοί τρόποι για να λύσετε αυτό το πρόβλημα. Μπορείτε επίσης να χρησιμοποιήσετε τα μπλοκ ||Βρόχοι: επανάληψη||. Προσπαθήστε να βρείτε τη συντομότερη διαδρομή
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

