# Halting-problem
Possible solution to the Halting problem. 
The halting problem asks whether it is possible to construct an algorithm (or computer program) that can automatically determine whether a computer program will stop at a particular input or continue to run forever. Turing showed in 1936 that no such algorithm can be constructed for every computer program and every possible input.

Turing's proof is based on the idea of ​​self-reference, and is carried out using a logical contradiction. The proof begins with Turing assuming, for the sake of contradiction, that there exists an algorithm HH that can solve the halting problem for every program and every input. HH was supposed to receive a program PP and an input II as input and predict whether or not the program would stop on input II.

Turing then constructed a special program DD that behaves in such a way that it changes its behavior depending on the output of HH. The program DD receives a program PP as input, and if HH says it will stop at that input, then DD will run forever, and if HH says it will not stop, then DD will stop.
