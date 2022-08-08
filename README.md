# minefield-Aug-2022
A program written in Java syntax that simulates a very primitive version the game Minefield or Minesweeper, it doesn't sweep any mines though. You can just move around them and it tells you how many mines there are around

# notes 
It is part of the "Introduction to Programming" course that I've attended in C and System Programmers Association (https://github.com/CSD-1993). Back then I couldn't pay a lot of attention due to some personal stuff. I am now reviewing the course and aware of what's needed to be done to learn programming. That's why it is here. Rather than using Java tools, the goal here is to come up with an algorithm that does the required task. The instructor had a better solution for this of course but I made this one on my own.

The only change I made is to use '&&' operator so that the program would 'seem' less complicated. Some things are repetitive and could have been done in a better way: For example I could have used '++' in lots of places. But I'm planning to do all these changes after I finish reviewing my Java 101 course. As I learn more, hopefully it will get better.

# what does it do? / what does it not do? 
- It is a 10x10 area. 
- At the beginning, 25 mines are placed randomly in the area. They are represented as -1. 
- Player enters a row and a column number from the keyboard and makes a move. If there is a mine (-1) in the area, the game ends.
- If there is no mine, it tells you how many mines there are in the neighbouring cells. The purpose is to find out all mine-free cells. (There 25 mines and 75 mine-free cells.) 
- Theoretically, a cell could be surrounded with up to 8 mines. That's why each value of the matrix must be 9 at the beginning.  
- Total number of mines should be assigned to the exact same cell in a new matrix. 
- You should be able to see all previous moves. 
- If the player steps on a mine or completes 75 moves successfully, the game ends. 

- X It can be done in a single matrix but I don't know how to do that.
- X If there are 0 mines around, it doesn't automatically clean the surrounding area. It just says 0.



