# De renbaan instellen
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

## Stap 1
Laten we de antennes opstellen om de score voor de race te tellen. Laat je agent de gemarkeerde plekken bezoeken met behulp van ||agent: agent move forward| en ||agent: agent turn||. Bestudeer eerst het looppatroon en voer dan je code uit op het blok Loops:on start.

### ~ Tip 
HintEr zijn meerdere manieren om dit op te lossen. Je kunt ook gebruik maken van ||loops: repeat|| blokken. Probeer het kortste pad te vinden
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

