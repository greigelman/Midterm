a.) Use g++ -g prog1.cc

b.) ./prog1 (executes program)
    % gdb prog1 (starts debugger)

c.) (gdb) break prog1.cc:10

d.) (gdb) run

e.) The difference between next and step is that if there is a function call then step will go into them while next will stay in the same function. If you have run the command next on code that leads into a function
then it would not enter like if the function were a student who just finished a class and didn't want to continue on to the next class. But step will continue if the class is a function call or taking the next class
