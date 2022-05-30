# REcon-Workshop-Public
Challenges for Symbolic Execution Workshop @ REcon

## Storyline 
The challenges are meant to be solved in linear order and each reveal a new story piece around a mysterious distress signal.  

## Challenges
While the challenges are deliberately coded simple and could be solved via other means, the learning objective is to use symbolic execution.  
For the workshop we'll be using the [angr framework](https://github.com/angr/angr).  

## Goal
The challenges have been design with enough simplicity to not test your reverse engineering skills, but your symbolic execution ones.  
Each challenge follows roughly the following structure:
```python

def main():
  var flag = getSomeInput()
  if (CHECK_FLAG_WITH_CONSTRAINTS(flag)):
    print("Good Job")
```

You will overcome three main obstacles:
- Providing input into the symbolic execution framework via various means
- Dealing with constraints
- Optimizing for speed

### Demo solutions are available for all challenges upon request
