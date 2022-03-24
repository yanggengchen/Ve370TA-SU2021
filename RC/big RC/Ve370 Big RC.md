### Ve370 Big RC



#### Chapter 1

##### Concepts:

1. Moore's Law

2. Hardware : physical structure

3. Software : set of instructions

   a. Application software

   b. System software

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616120638430.png" alt="image-20210616120638430" style="zoom: 67%;" />

 4. Levels of Program Code:

    a. High-level (C++, Python)

    b. Assembly language (mips, risc-v)

    c. hardware representation (machine code, single stage, pipeline)

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616120939581.png" alt="image-20210616120939581" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121031872.png" alt="image-20210616121031872" style="zoom: 67%;" />

	5. Instruction set architecture (ISA)
	6. Integrated Circuit Cost

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121158520.png" alt="image-20210616121158520" style="zoom: 67%;" />

7. Performance

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121242119.png" alt="image-20210616121242119" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121300382.png" alt="image-20210616121300382" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121314879.png" alt="image-20210616121314879" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121329415.png" alt="image-20210616121329415" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121345708.png" alt="image-20210616121345708" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121405446.png" alt="image-20210616121405446" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121419723.png" alt="image-20210616121419723" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121444752.png" alt="image-20210616121444752" style="zoom: 67%;" />

7. Power

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121511166.png" alt="image-20210616121511166" style="zoom: 80%;" />



**Suggestions**: Have a quick look over the slides and the textbook.





#### Chapter 2

##### Principles:

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121635849.png" alt="image-20210616121635849" style="zoom: 67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121652310.png" alt="image-20210616121652310" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121717125.png" alt="image-20210616121717125" style="zoom: 67%;" />

##### RF and Memory

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121756852.png" alt="image-20210616121756852" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121834157.png" alt="image-20210616121834157" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121852423.png" alt="image-20210616121852423" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616121914607.png" alt="image-20210616121914607" style="zoom:67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616122230554.png" alt="image-20210616122230554" style="zoom:150%;" />

Instructions:

![image-20210616122426081](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616122426081.png)



##### Note: RISC-V use xor to implement not

**Suggestions**: Look at the reference card, make sure you know at least **what the instructions do**, and which registers they use and where they store the processed information. Do some exercises on the textbook if you have time



#### Chapter 3

Instructions are stored in machine code along with data, but in different sections.

Each instruction is stored as a word (32-bit), has address

PC (instruction pointer, special register) += 4 → Go to the next instruction

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616123008296.png" alt="image-20210616123008296" style="zoom: 80%;" />

Function calling:

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616123104254.png" alt="image-20210616123104254" style="zoom:67%;" />



**Note**: Leaf and non-Leaf functions have different procedures

##### Others:

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616123230366.png" alt="image-20210616123230366" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616123301914.png" alt="image-20210616123301914" style="zoom: 80%;" />



**Suggestions**: Review Project 1. Beginning of RC in week 4 gives an example of calculateAverage. Function calling is strictly formative, memorizing the procedure is of critical importance.

​	Also note that in P1, you are using RV32, but for P2, P3 and exams, you are using RV64, beware the difference 



#### Chapter 4

![image-20210616123810755](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616123810755.png)

**Assembler, Linker and Loader**

 See example in slides



**Suggestions**: This chapter is basic and **very very very important**. You need to use in in your single stage & pipeline. Be sure you know how to convert instruction into corresponding machine code. And also be sure to know the boundaries, limits of instructions. For example, in I type, imm only has 12 bits.



#### Chapter 5

1. 2's complement arithmetic (Ve270)
2. Multiplication and Division (Project 1), review the process chart on the slides

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616124611478.png" alt="image-20210616124611478" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616124550712.png" alt="image-20210616124550712" style="zoom: 80%;" />

3. Corresponding RISC-V Extension set
4. Sign dealing in mul and div



#### Chapter 6

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616125027781.png" alt="image-20210616125027781" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616125054323.png" alt="image-20210616125054323" style="zoom: 80%;" />

Other aspects:

1. Range
2. Precision
3. Overflow
4. Special Representations

5. Arithmetic for float numbers
6. FP Extentions in RISC-V



**Suggestions**: Along with Chapter 5,  check the textbook & slides and do a few exercises



**Chapter 7**

​	See Ve270 or Slides



**Chapter 8**

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616125857351.png" alt="image-20210616125857351" style="zoom:150%;" />



Performance issues:

​	Critical path: load instruction

​	All instructions have same execution time

​	Clock frequency determined by critical path

​	Violates "making common case fast"



**Suggestions**: Critically important, over 50% chance of having a question on this topic. Exercise on this helps a lot. Especially focus on the control signals.



#### Chapter 9-10

Reason for having pipeline structure: **Performance**

Core for pipeline: Separate single-stage into multiple segments (so the whole processor will not be occupied by one instruction), like assembly line

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616130849984.png" alt="image-20210616130849984" style="zoom:150%;" />

5 stages: IF, ID, EX, MEM, WB. Bars between each two stages, named IF/ID, ID/EX, used for storing signals from previous stage

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616130916844.png" alt="image-20210616130916844" style="zoom:67%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616131301400.png" alt="image-20210616131301400" style="zoom:150%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616131053666.png" alt="image-20210616131053666" style="zoom: 80%;" />



Others:

​	Conceptual terminology

​	Pipeline diagram

​	**Time calculation**



**Suggestions**: Normally you should expect at least one question on this. **DO HAVE SOME PRACTICE YOURSELF**



#### Chapter 11

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616131620747.png" alt="image-20210616131620747" style="zoom: 67%;" />

![image-20210616131804357](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616131804357.png)



Two kinds of data hazard, classified according to usage: EX hazard and MEM hazard

##### EX hazard

##### Method 1: Stalling

​	Just delay the subsequent commands (nop)

​	Cons: use time

##### Method 2: Forwarding

​	Core: Earliest time possible

​	The latest usage time is (pre)EX stage

​	The earliest time possible is (aft)EX stage

​	If earliest time possible < latest time needed, then forwarding can be implemented

​	**How to implement**: Add a path from result of ALU (or other possible stages) to input of ALU, and use MUX and control signals to determine whether forwarding or not

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616132401779.png" alt="image-20210616132401779" style="zoom: 80%;" />

​	**How to determine forwarding**:

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616132416763.png" alt="image-20210616132416763" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616132633244.png" alt="image-20210616132633244" style="zoom: 80%;" />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616132937485.png" alt="image-20210616132937485" style="zoom: 80%;" />

​	Note: Now, the hazard dealt with is data hazard (dependency)



##### MEM hazard (Load Use Hazard)

​	The ultimate choice is to **stall**

​	Another method to save time is code scheduling

​	<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616133517703.png" alt="image-20210616133517703" style="zoom: 80%;" />

​	



#### Chapter 12

​	Method 1: Stall

​	Method 2: Branch Prediction (Static and Dynamic)

​		Penalty for wrong prediction

​	Also move branch into earlier stages will help. But beware not to influence critical path (or critical stage), you might also need forwarding for this, too

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616134240106.png" alt="image-20210616134240106"  />

<img src="C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616134456497.png" alt="image-20210616134456497"  />

![image-20210616134510147](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616134510147.png)

​	![image-20210616134211943](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210616134211943.png)



### Good Luck to your Mid-Term Exam!