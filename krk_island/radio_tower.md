# Activate the Radio Tower
### @hideIteration false 
### @flyoutOnly 1


``` ghost
    
         agent.move(FORWARD, 1)
         agent.turn(LEFT_TURN)
     
```
```template
   //     
```


## Step 1

We need to fix the Radio Tower. Use your agent to collect the resources on the map. Use multiple ``||agent: agent move forward||`` as well as ``||agent: agent turn||`` blocks and place them in the ``||Loops:on start||`` block. When you're finished, click **RUN**. Careful, do it in a single run or else it won't work.

### ~ Hint 
You can change the number of steps your Agent will move by changing the number inside the ``||agent: agent move||`` block. You also can use an ``||agent: agent turn||`` block to turn the Agent to the left or right.

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


