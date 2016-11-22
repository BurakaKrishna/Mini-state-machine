# Mini-state-machine
My design of mini state machine in python

Problem:
     You are a bomb diffuser in the field.The instructions are for u to cut only specific wires with certain rules which are
     
     If you cut a white cable you can't cut white or black cable.
     If you cut a red cable you have to cut a green one
     If you cut a black cable it is not allowed to cut a white, green or orange one
     If you cut a orange cable you should cut a red or black one
     If you cut a green one you have to cut a orange or white one
     If you cut a purple cable you can't cut a purple, green, orange or white cable
     
     If you have anything wrong in the wrong order, the bomb will explode.
There can be multiple wires with the same colour and these instructions are for one wire at a time. Once you cut a wire you can forget about the previous ones.


Input 1

white
red
green
white
Input 2

white
orange
green
white
Output description

Whether or not the bomb exploded
Output 1

"Bomb defused"
Output 2

"Boom"
