# ebs
(Extended) Berry-Sethi algorithms for the recognition and parsing of a string generated by a regular expression.
Both the "bs" and "bsp" tools are written in JavaScript and need an HTML browser to run. The browsers Firefox and Chrome are supported (not Explorer).
File "bs.html" is the standard Berry-Sethi algorithm for constructing the recognizer DFA of a regular expression.
File "bsp.html" is the extended Berry-Sethi algorithm for constructing the parser DFA of a regular expression, capable to recognize a string and also to build its syntax tree(s): one tree if the string is not ambiguous, and two or more trees if the string is ambiguous.
The "bsp" tool can optionally use the Greedy and POSIX disambiguation criteria to select one tree only, if required. Both tools draw an interactive graphical representation of the recognizer or parser DFA they construct.
The "bs" and "bsp" tools are user-friendly and self-documented: run them in a browser and have a look at the instructions in their interface page; all commands and data can be input into dialog boxes.
