# Sacīkšu trases iestatīšana
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

## 1 darbība
Uzstādīsim antenas, lai skaitītu sacensību rezultātus. Ļaujiet savam aģentam apmeklēt atzīmētās vietas, izmantojot ||aģents: aģents virzās uz priekšu || kā arī ||aģents: agents pagriežas||. Vispirms izpētiet staigāšanas modeli un pēc tam palaidiet savu kodu blokā|| cikls: starts||.

### ~ Padoms 
Ir vairāki veidi, kā to atrisināt. Varat izmantot arī || cikls: atkārtošanās|| blokus. Mēģiniet atrast īsāko ceļu


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

