### Ve370 Final Big RC

#### Chapter 13

​	Main difference between interrupt and exception: Cause (external/internal)

​	Concept of parallelism and asynchronous.

![image-20210728165028095](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165028095.png)

![image-20210728165045491](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165045491.png)

![image-20210728165107173](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165107173.png)

![image-20210728165418364](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165418364.png)

![image-20210728165500789](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165500789.png)

Multiple exceptions/interrupts at the same time: Priority.

High prioritized interrupts can interrupt low prioritized interrupt.



#### Chapter 14

![image-20210728165733689](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165733689.png)

Flynn Bottleneck: CPI = 1

![image-20210728165900280](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728165900280.png)

"Hazards" caused by parallelism:

1. Data dependency (load use, type 1, type 2...)
2. Scramble for resource usage (memory, Reg file...)
3. Branch & Jump (maintain the overall instruction order), use out-of-order  to maintain the order

Benefits:

​	Performance

Threats:

​	Power consumption



#### Chapter 15-18

​	What is Cache: Another memory

​	Why need cache: Performance![image-20210728170521049](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728170521049.png)

![image-20210728170557732](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728170557732.png)

Terminologys:

1. Block: unit of copying
2. Word address/Byte address 
3. Word offset/Byte offset (Word address & Byte offset = Byte address)
4. Hit/Miss ratio
5. Hit time/Miss penalty

![image-20210728171002235](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728171002235.png)

Tag + Cache index = block address

![image-20210728171449878](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728171449878.png)

![image-20210728171239992](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728171239992.png)

How to write for memory consistency:

1. Write through: when a write is needed, just write to memory. Pros: Easy to implement, less problems; Cons: worse performance
2. Write back: write to memory when the block is replaced. Use a dirty bit to indicate if replacement needs to write to memory. Pros: better performance; Cons: Complexity



Associativity:

![image-20210728172107418](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172107418.png)

![image-20210728172120442](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172120442.png)

![image-20210728172149257](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172149257.png)

![image-20210728172228881](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172228881.png)

![image-20210728172548337](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172548337.png)

3 Cs Model of Misses

![image-20210728172532266](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172532266.png)

![image-20210728172646205](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172646205.png)

Hamming Code:

[说人话，人话！！ 汉明码（海明码、hamming code）通俗易懂的解释，说人话！！！！_Yonggie的博客-CSDN博客_汉明码](https://blog.csdn.net/Yonggie/article/details/83186280)

![image-20210728172857394](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728172857394.png)



#### Chapter 19

![image-20210728173050164](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173050164.png)

![image-20210728173212244](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173212244.png)

![image-20210728173258425](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173258425.png)

![image-20210728173333223](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173333223.png)

![image-20210728173441255](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173441255.png)

![image-20210728173516875](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173516875.png)

![image-20210728173527846](C:\Users\yangg\AppData\Roaming\Typora\typora-user-images\image-20210728173527846.png)



#### Concepts in Chapter 20-23

1. Storage Types
2. RAM,DIMM, ROM, Flash
3. Volatility
4. Accessibility
5. Mutability
6. Addressability
7. I/O
8. OS
9. Bus
10. MMIO (memory mapped I/O)
11. Polling
12. Interrupt
13. DMA
14. Amdahl's Law
15. Flynn's Classification
16. Thread & SMT
17. GPU v.s CPU

