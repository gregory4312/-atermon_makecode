### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Activate the Radio Tower

## Step 1

Let's gather some more materials. In order to make our lives easier, you can have the agent perform an activity on repeat. Study the walk pattern and then have the agent gather all the materials in one go. Don't forget to place them in the ``||Loops:on start||`` block.

#### ~ tutorialhint  
Use a ``||loops: repeat||`` loop


``` ghost
    count = 0
    for (let index = 0; index < 4; index++) {
        agent.move(FORWARD, 1)
        agent.turn(RIGHT_TURN)
    }
```

```template
   //     
```
