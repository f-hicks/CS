## MOS transistor
![[Pasted image 20251003151357.png]]
A voltage on the gate turns on the drain-source circuit

## Combinatory circuits

Interconnected gates whose output is at any time a function only of the input at that time.
The output is followed (almost) immediately by the output

consists of n inputs and m outputs.
Can be defined in 3 ways
1. Truth Table
	- for each of the $2^n$ possible combinations of input signals, the binary value of each of the m output signals is listed
2. Graphical symbols
	- The interconnected layout of gates
3. Boolean equations
	- Each output signal is expressed as a Boolean function of it's inputs.

## Boolean equations (in Logic Notation) 
- To write logic easily + and l are used for OR/AND 
C = A + B means A OR B 
C = A l B means A AND B 

NOT is useful too! 
A = NOT B is written as: 
A = $\overline B$ 
Sometimes typed as /B, ⌝ B.

## How does logic relate to electronics?
0 means 0 volts or "low"

1 usually means power supply voltage. 
i.e. 3.3V, which is "high"

## Logic gates

### NOT
![[Pasted image 20251003152921.png]]

| A   | Y   |
| --- | --- |
| 1   | 0   |
| 0   | 1   |
### AND

| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 0   |
| 0   | 1   | 0   |
| 1   | 1   | 1   |
![[Pasted image 20251003153308.png]]

### OR

| A   | B   | Y   |
| --- | --- | --- |
| 1   | 0   | 1   |
| 1   | 1   | 1   |
| 0   | 0   | 0   |
| 0   | 1   | 1   |
![[Pasted image 20251003153422.png]]


Both AND & OR can be combined with a NOT gate, effectively inverting the output.

![[Pasted image 20251003153511.png]]![[Pasted image 20251003153517.png]]

