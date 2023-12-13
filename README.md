### @explicitHints true

# Omarillo Logo - Lesson #3

## Omarillo Logo - Lesson #3 @unplugged
**Making the Omarillo Turn.**

In questa lezione farai ruotare l'**Omarillo**.
![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson3/raw/main/assets/turn_screenshot.png)

## Step 1
** Follow Along**

Ancora una volta, tutti i nostri programmi iniziano con un blocco ⇢``on start``⇠ .Quindi devi aggiungere **Omarillo** usando  ⇢``show omarillo``⇠ block.
```blocks
omarillo.showOmarillo()
```

## Step 2
** Follow Along**

Nell'ultima lezione hai imparato a muovere l'**Omarillo** avanti o indietro.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 50)
```

## Step 3
** Follow Along**

Per ruotare l'**Omarillo** usiamo ⇢turn omarillo right 90 °⇠ block dentro ⇢on start⇠ block dopo il move block.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Right, 90)
```

## Step 4
** Follow Along**

Al momento sembra che non sia successo nulla. Questo perché l'**Omarillo** si è girato, ma devi spostarlo per vedere che si è girato. Aggiungi un altro blocco ⇢turn omarillo right 90 °⇠ block.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Right, 90)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 5
** Try it Out**

Notare il *right* nel blocco. La direzione può essere cambiata per girare l'**Omarillo** a destra o a sinistra. Prova a girare l'**Omarillo** a sinistra.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Left, 90)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 5
** Try it Out**

Ora prova a spostare **Omarillo** a distanze diverse, in direzioni diverse e ora anche a girarlo.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 25)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Right, 90)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 50)
omarillo.turnOmarilloDirectionByDegrees(OmarilloTurnDirection.Left, 90)
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Step 6
**Success!**

You can now make the **Omarillo** turn right and left.

## Step 7
**Your Turn**

Get your **Omarillo** to:
- move
- turn
- move again
- then say, "I can change direction!"

## Step 8
**Done**

You have successfully completed your third lesson in Omarillo Logo.

```ghost
omarillo.say("Hello, World!")
```
