# 3-colorability
Python code to determine 3-colorability of a given graph and, if 3-colorable, output graph coloring.


Convert all vertex labels to letters: current version supports only up to 26 vertices.
Input into function all edges denoted by the vertices they connect,
i.e. in graph below, input [(a,b),(c,b),(e,f),(f,a),(d,e),(d,c)].

Code terminates when successful coloring is reached or after 2^(number of vertices) unsuccessful coloring attempts. This threshhold can be changed by editing line __ of code.

Future versions: relabel vertices automatically (no user conversion required), determine likelihood of successful coloring unreached after 2^(number of vertices) attempts
