## Izveidot number guessing spēli ar Python programmēšanas valodu

### Saturs 

#### 1. Aprakstīt spēli 
#### 2. Spēles loģika 

Dators nejauši ģenerē vienu skaitli no 1 līdz 10. Tālāk, piedāvā spēlētājam uzminēt to skaitli. 
Spēles loģika ir labi aprakstīta šajā kodā 
```py
import random

repeat = True

while repeat:
    number = random.randint(1, 100)
    guess = 100
    tries = 0

#### 3. Un t.t.
