# Ενεργοποιήστε τον Πύργο Ραδιοφώνου
### @hideIteration true 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Βήμα 1

Πρέπει να φτιάξουμε τον πύργο ραδιοφώνου. Χρησιμοποιήστε τον πράκτορά σας για να συλλέξετε τις πρώτες ύλες στο χάρτη. Χρησιμοποιήστε πολλαπλά μπλοκ ||πράκτορας: πράκτορα κινήσου μπροστά|| καθώς και ||πράκτορας: πράκτορα γύρνα|| και τοποθετήστε τα στο μπλοκ ||Βρόχοι:στην αρχή||. Όταν τελειώσετε, κάντε κλικ στο κουμπί ΤΡΕΞΕ. Προσοχή, κάντε το σε μία μόνο εκτέλεση, αλλιώς δεν θα λειτουργήσει.

### ~ Υπόδειξη 
Μπορείτε να αλλάξετε τον αριθμό των βημάτων που θα μετακινηθεί ο πράκτοράς σας αλλάζοντας τον αριθμό μέσα στο μπλοκ ||πράκτορας: πράκτορα μετακινήσου||. Μπορείτε επίσης να χρησιμοποιήσετε το μπλοκ ||πράκτορας: πράκτορα γύρνα||| για να στρέψετε τον πράκτορα προς τα αριστερά ή προς τα δεξιά.

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


