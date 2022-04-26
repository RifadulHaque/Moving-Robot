# MovingRobotFolder

Program which can make a robot draw and move on an xy plane

Project done by:
Paul Westenberg,
Rifadul Haque,
Erfan Reza


Project Description 

Imagine a robot that walks around a room under the control of a Java program. The robot holds 
a pen in one of two positions, up or down. While the pen is down, the robot traces out shapes as 
it moves; while the pen is up, the robot moves about freely without writing anything. The room 
will be represented by an N by N array called floor that is initialized to zeros. Initially the robot is 
at position [0, 0] of the floor, its pen is up, and is facing north (as shown in the below figure).
The robot moves around the floor (i.e. the array) as it receives commands from the user. The 
set of robot commands your program must process are as follows: 

Command Meaning 
  [U|u] Pen up 
  [D|d] Pen down 
  [R|r] Turn right 
  [L|l] Turn left 
  [M s|m s] Move forward s spaces (s is a non-negative integer) 
  [P|p] Print the N by N array and display the indices

N-1 0 0 0 0 0 0 0 0 0
… 0 0 0 0 0 0 0 0 0
… 0 0 0 0 0 0 0 0 0
5 0 0 0 0 0 0 0 0 0
4 0 0 0 0 0 0 0 0 0
3 0 0 0 0 0 0 0 0 0
2 0 0 0 0 0 0 0 0 0
1 0 0 0 0 0 0 0 0 0
0 ▲ 0 0 0 0 0 0 0 0
0 1 2 3 4 5 … … N-1

  [C|c] Print current position of the pen and whether it is up or down and its 
        facing direction
  [Q|q] Stop the program
  [I n|i n] Initialize the system: The values of the array floor are zeros and the robot 
        is back to [0, 0], pen up and facing north. n size of the array, an integer 
         greater than zero 
         
 Tasks and Deliverables:
 
 Task 1: Development and Verification  (Deadline: Week 5 – Friday 11:59pm)
    a) A working application
    b) The souce code and the Unit test code is included
    c) Test cases execution results (fail or pass).
    
 Task 2: Code Analysis and Software Release (Deadline: Week 7 – Friday 11:59pm)
    a) Function coverage: how many of defined functions have been called;
    b) Statement coverage: the number of statements that have been successfully executed in 
        the program;
    c) Path coverage: how many paths of the control structures in the program (if statements or 
        loops) have been executed;
    d) Condition coverage: how many Boolean expressions have been validated inside your 
        program;
    e) Line coverage: how many lines of the program have been executed.
    
 Task 3: Black-box and White-box Testing (Deadline: Week 11 – Friday 11:59pm)
     a) statement coverage (show percentage covered > 50%)
     b) decision coverage (show percentage covered > 50%)
     c) condition coverage (show percentage covered > 50%)
     d) multiple condition coverage (show percentage covered > 50%)
     E) Select one function and apply data flow testing
     
 Task 4: Regression Testing (Deadline: Week 13 – Friday 11:59pm
     a) Add in one new function development to the current application. 
        [H|h] Replay all the commands entered by the user as a history 
     b) Carry out regression test according to the newly added function
 

