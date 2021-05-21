# MuKEA-TCP

MuKEA-TCP is a mutant kill-based local search augmented evolutionary algorithm test case prioritization technique. MuKEA-TCP uses the parameter information given below.

Parameter Type | Parameter Value
------ | ------
Generations   | 100  
Alpha (Population size)   | 100  
Mu (number of parents)   | 25  
Lambda (number of children)   | 25  
Crossover Rate   | 0.75  
Mutation Rate   | 0.30  
Crossover Operator   | Bucket  
Mutation Operator   | Insert  
Mutation Rate Type   | Adaptive  
Number of Threads   | 12  


There are also three more techniques implemented in the code that uses: 
* Total-based approach (TMKPT)
* Additiona-based approach (AMKPT)
* Evalutionary Algorithm without local search

To run MuKEA-TCP, run the `Main.java` class. You can set the mutation report file in the `Main.java` class file. There are currently 5 mutation report files generated by [Pitest](https://github.com/hcoles/pitest).
