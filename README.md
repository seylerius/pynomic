=PyNomic=
How do you build a game where changing the rules is the only constant? Well, you implement the rules as python methods and go from there. 

==What is PyNomic==
PyNomic is a python server for playing Nomic games on the web. It allows the creation of arbitrary rules as python methods, which validate a turn action. Turn actions are also simple python, and draw from the available action set, defined by the rules.

==What is a Nomic==
A Nomic is a game wherein the point of the game is to change the rules. It starts with an initial set of rules, and one or more win conditions defined within those rules, which also govern how rules are changed. 
