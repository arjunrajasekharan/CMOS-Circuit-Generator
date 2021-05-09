# BoolExptoSIM
This repository contains a python script which converts a Boolean Expression to a .sim file.

## Running
```
python3 be2sim.py
```

NOTE: It is necessary to use paranthesis wherever possible. <br>e.g. !A.B.C should be writtern as (((!(A)).B).C). The input variables can be any alphabet. The final output is 'out'.The following gates can be used: 
1. '+' (OR)
2. '.' (AND)
3. '!' (NOT)

