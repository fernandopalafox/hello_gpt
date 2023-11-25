# hello_GPT.py 

This repo includes code from following Andrej Karpathy's [intro to generatively pre-trained transformers (GPTs)](https://www.youtube.com/watch?v=kCc8FmEb1nY). `bigram.py` is a script to define, train, and a run decoder-only transformer. Training data are Shakespeare's writing and the output is a 500-token prediction given a new-line character.

I wrote about what I learned on my website [here](https://palafox.info/research/). 

Here as a sample output.

```
> python bigram.py
using device cuda
step 0: train loss 4.2846, val loss 4.2823
step 500: train loss 1.8571, val loss 1.9660
step 1000: train loss 1.4969, val loss 1.6838
step 1500: train loss 1.3556, val loss 1.5768
step 2000: train loss 1.2733, val loss 1.5226
step 2500: train loss 1.2040, val loss 1.4977
step 3000: train loss 1.1510, val loss 1.4955
step 3500: train loss 1.0976, val loss 1.4858
step 4000: train loss 1.0429, val loss 1.5014
step 4500: train loss 0.9942, val loss 1.5322

Oppon the time of our mistress! Bolingbroke
To the seal'd shepherd of honour-flutted
Return to me,ignity o'er throat up on ours.

GREY:
Go, good Margaret, thou artius on, do not forth.

STANLEY:
Sir, at thou dost not stand in this world,
In hopest ourselves and smiles, for wholen
Then I be grave died, though with salt long Henry,
The a quarrel of Juliet shall war knock.

RICHAMOP:
Art thou, palace.

KING RICHARD II:
At Henry, farewell! Prince Edward.

DUKE VINCENTIO:
Come, come hither, my lord.
```

# hello_x series
This repo is part of a series where I familiarize myself with a new package, library, or technique.