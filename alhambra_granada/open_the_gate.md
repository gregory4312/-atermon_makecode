# Open the Gate
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


## Step 1

You need to open the Gate. Have your agent move and reach the lever. Use ``||agent: agent turn||`` and ``||agent: agent move||`` 

### ~ Hint 
You can use a ``||loops: repeat||`` loop to make things easier!

```  blocks
    for (let index = 0; index < 2; index++) {
        agent.move(FORWARD, 5)
        agent.turn(LEFT_TURN)
        agent.move(UP,2)
    }
         
})
```

