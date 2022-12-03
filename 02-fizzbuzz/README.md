# FizzBuzz
#### Respond to the following:

1. Fill out the following truth table:

| P  | Q  | P && Q | P \|\| Q |
|:--:|:--:|:------:|:--------:|
| T  | T  |    T   |    T     |
| T  | F  |    F   |    T     |
| F  | T  |    F   |    T     |
| F  | F  |    F   |    F     |


2. Prove a version of DeMorgan's Law:

| P  | Q  | P \|\| Q | ! (P \|\| Q) | !P | !Q | !P && !Q |
|:--:|:--:|:--------:|:------------:|:--:|:--:|:--------:|
| T  | T  |    T     |       F      |  F |  F |     F    |
| T  | F  |    T     |       F      |  F |  T |     F    |
| F  | T  |    T     |       F      |  T |  F |     F    |
| F  | F  |    F     |       T      |  T |  T |     T    |

3. What does DeMorgan's state and how did you prove it for the case above?
  * Stuff that were originally different become the same under proper conditions（achieve a replacement effect）. For example: P || Q is not the same as P && Q, but !(P || Q) is the same as !P && !Q, since they have the same result on the same variables. 
