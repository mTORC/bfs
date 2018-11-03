## This bfs program is an implementation on how to solve the following problem:

Suppose there are two types of professional wrestlers: “Babyfaces” (“good guys”) and “Heels” (“bad guys”). Between any pair of professional wrestlers, there may or may not be a rivalry. Suppose we have n wrestlers and we have a list of r pairs of rivalries.

Provide an efficient algorithm that determines whether it is possible to designate some of the wrestlers as Babyfaces and the remainder as Heels such that each rivalry is between a Babyface and a Heel. If it is possible to perform such a designation, your algorithm should produce it.

Instructions on how to execute:
- To run wrestler.py, make sure that all the necessary test .txt files are in the same directory.
- To run in the terminal, type in "python3 wrestler.py"
- It will ask you to enter the text file you want to input, so you can enter in:
- "wrestler1.txt" without quotations and the program will run automatically and produce results to the screen

#### Sample Input file:  
5  
Ace  
Duke  
Jax  
Biggs  
Stone  
6  
Ace Duke  
Ace Biggs  
Jax Duke  
Stone Biggs  
Stone Duke  
Biggs Jax  

#### Sample Output:  
Yes  
Babyfaces: Ace Jax Stone  
Heels: Biggs Duke  
