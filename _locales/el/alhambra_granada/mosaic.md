# Επισκευάστε το ΜωσαΪκό
### @hideIteration false 
### @flyoutOnly 1


```` ghost
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
        agent.place(DOWN)
    }
```
```template
   //     
```


## Βήμα 1

Η Aisha σας ζήτησε να επισκευάσετε το ψηφιδωτό που κοσμούσε αυτό το πάτωμα. Χρησιμοποιήστε ``|||loops: repeat|||`` και ``|agent: agent place|||`` για να το φτιάξετε.

### ~ Hint 
Κοιτάξτε το μοτίβο και στη συνέχεια επαναλάβετε το 4 φορές!

```  blocks
    for (let index = 0; index < 4; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
    agent.move(FORWARD, 2)
    agent.place(DOWN)
    agent.move(FORWARD, 1)
    agent.turn(RIGHT_TURN)
}
         
})
```

