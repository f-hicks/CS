
Different operating systems are very different at a low level, so applications that can run on one OS will not work on others.
- Different ways of putting things on screen
- different ways of making sound
- different ways of taking input from the keyboard

How can Python work on all these platforms? 
- the PVM (python virtual machine)

![[Pasted image 20251002150739.png]]

Software allowing python code to run on any platform

A (simplified) process for executing python code
1. bytecode generation: compiling python code into bytecode
2. interpreter loop: fetch bytecode instructions, decodes them, executes them sequentially


- applicable to CPython (the reference implementation)
- not necessarily applicable to other versions


## ways to run python code

- python script
- python commandline
- jupyter notebooks

## REPL 
1. Read: Take user inputs 
2. Eval: Executes the inputs 
3. Print: Shows the result to the user 
4. Loop: Go back to 1.


## Jupyter
- web based application
- for creating and sharing computational documents (jupyter notebooks)
- document-centric
- support many programming languages (through "kernels")

![[Pasted image 20251002152331.png]]

