
<h1>Lecture 1, 2 and 3</h1>
Q: What is Moores Law?
A:

Q: What metrics are of interest to computer architects?
A: 

Q: What type of bench marking is there ?
A:

Q: What is the formula for saying "A is **n** time faster than B"
A: 

Q: What is the formula for saying "A is **m%** faster than B"
A:

Q: What are 3 ways we can introduce parallelism to improve performance 
A: 

Q: What are the two types of locality that come under the **principle of locality**?
A: 

Q: What do we do to exploit the 2 types of localities that come under the **principle of locality**?
A:

Q: What is the **RISC** principle?
A:

Q: What is Amdahls Law, derive it?
A:

Q: What is the CPU performance equation?
A: 


<h1>Lecture 4</h1>

Q: What is the purpose of hardware description languages (HDLs)?
A: 

Q: What is a module in Verilog?
A:

Q: What is the code to create a 32-bit adder in verilog with a **carry-out**?
A:

Q: What are the 3 levels that verilog can describe a system at?
A:

Q: In what manner could Verilog be considered a "programming langauge" ?
A:

Q: What happens during synthesis in Vivado, what is produced?
A: 

Q: What are "constraints" in synthesis?
A:

Q: What is the "implementation" phase in Vivado?
A:

Q: We have 4 logic values in Verilog. We know what 0 and 1 is, what is **x** and **z**?
A: 

Q: How are values stored and transmitted in Verilog?
A:

Q: What is a **wire** in verilog, and give an example of it being used in an **AND** module.
A:

Q: Do we need to explicitly declare something as a Wire if it is an **Output**?
A:

Q: What is **continuous assignment** in Verilog and where would you use it?
A:

Q: What does the always @*  do in Vivado?
A:

Q:  What is blocking and non-blocking assignments, and when do you use which one?
A:

Q: What is the difference between synchronous and combinational logic?
A:

Q: Define a 32 bit vector called A in Verilog
A:

Q: With literals in verilog, how would you define each of the following: **Binary Literals**, **Hex Literals** and **Decimal Literals**?
A:

Q: How can you concatenate 2 vectors in Verilog?
A:

Q: Write the code to replicate a vector called *data2* 5 times and assign it to *data 3*
A:

Q: How would you 1kb of memory using a multidimensional array in Verilog?
A:

<h1>Lecture 5</h1>
Q: Suppose we are assigning a result to a reg that is too small, what would be truncated?
A: 

Q: What is synthesis-simulation mismatch?
A:

Q: How do we make something **signed** in Verilog?
A:

Q: What happens if we do ($x$ == 1'bx) in Verilog, will it evaluate to true, and if not what other operator could we use?
A:

Q: Why are positional arguments dangerous and what should we do instead, and give an example of this
A:

Q: What is combinational logic, and how does it differ from sequential logic?
A:

Q: Write out the truth table for a 2-input AND and OR gates, and draw them.
A:

Q: Write out the truth table for a 1-input NOT gate, and draw them.
A:

Q: Draw the timing diagram for AND, NOT and OR gates.
A:

Q: Draw a rough sketch of an AND-OR-INVERT gate.
A:

Q: Draw an exclusive OR gate, and an exclusive NOR gate.
A:

Q: What is the truth table for a XNOR gate?
A:

Q: Given inputs x, y, a and b, define a function (x, y, a, b) such that f delivers x when a = b and y when a != b.
A:


<h1>Lecture 6</h1>

Q: What is a minterm, and what do we do between minterms?
A:

Q: What is a maxterm, and what do we do between maxterms?
A:

Q: What is the minimum Sum-Of-Products (SOP)?
A:

Q: How can we show that the maxterm $M_i$ is inverse of minterm $m_i$?
A:

Q:  What are the 2 main approaches we can use for logic simplication?
A:

Q: Simplify this function deductively:
![[Pasted image 20241125175105.png]]
A:

Q: What is the structure of a **always** block, and what is each of the 2 parts responsible for, and what are they called?
A:

Q: What is the difference between a **combinational** and a **sequential** process?
A:

Q: How do we define a always block triggered on the positive edge of the clock?
A:

Q: What are symbols for blocking and non-blocking assignments?
A:

Q: How exactly does non-blocking assignments work, when are RHS calculated and when are they assigned?
A:

Q: What is the structure of an if statement in verilog?
A:

Q: What is the structure of a ternary operator in verilog?
A:

Q: Why should you always have a default case in case statements in Verilog?
A:

Q: How do you do 'dont care' cases, what type of case block do we need to use?
A:
<h1>Lecture 7</h1>
Q: Write the Verilog to implement a 7-segment display, you are given this:
![[Pasted image 20241126134153.png]]
A:

Q: Implement the clocked 12 bit counter shown in the lecture
A:

Q: What is the key property of a kaurnagh map?
A:

Q: What does a sqaure in a kaurnagh map represent?
A:

Q: What is an implicant?
A:

Q: What is a prime implicant, and what is an essential prime implicant?
A:

<h1>Lecture 8</h1>
Q: What is an instruction set architecture (ISA)?
A:

Q: What are the four major types of operations in an ISA?
A:

Q: What are some important ISA design considerations?
A:

Q: What is the difference between CISC and RISC architectures?
A:

Q: What are the different instruction classes that an ISA should support?
A:

Q: Make a table for the 6 C comparison operators with a corresponding RISCV instruction for **Comparison** and for **Branch** (we can use the comparison with branch).
A:

Q: What is integer promotion?
A:

Q: What are the 2 main reg-based operands options for what can be specified ?
A:

Q: What are is the name for the type of instructions that operate on a constant operand (a literal value)?
A:

Q: What is a relative branch target? 
A: 

Q: What is an absolute branch target?
A:

Q: Is the offset in control flow signed or unsigned?
A: 

Q: What size are addresses typically ?
A:

Q: Why do we have a signed and unsigned option when loading half words and bytes from memory (hint: word is biggest)?
A: 

Q: What is the most common memory addressing mode?
A:

Q: In what direction does the stack grow?
A:

<h1>Lecture 9 + 10</h1>
Q: What is the size of the fixed-length instructions in RISCV?
A:

Q: What bits of RISCV instructions make up the opcode and what is it's use?
A:

Q: What is an R-Type instruction, provide some examples
A:

Q: What is an I-Type instruction, provide some examples?
A:

Q: What is an S/B-Type instruction, provide some examples?
A:

Q: Why do we have the MSB of the IMM at the end of the instruction encoding?
A:

Q: What are U/J-type instructions, provide some examples?
A:

Q: What are the lower 2-bits of the opcode used for (the least significant 2 bits) ?
A:

Q: What are the main 3 main guidelines for ISA Design?
A:

Q: What are the 5-stages in the RISCV pipeline, and give a brief sentence explaining what happens at each stage
A:

Q: What is meant by a **speculative** results processor, use the WRB stage in your explination
A:

Q: How does SLTU or SLT work (think about an arithmetic operation we can use to do this), and explain separately for each one?
A:

Q: How do we compute subtract using an addition operator?
A:

Q: How is branch target calculated?
A:

Q: What happens cycle-by-cycle when executing branch instructions (1-2 lines for each cycle)
A:

Q: How does a pipeline flush get implemented, what property do we rely on the results from the other stages to allow for this to be possible?
A:

Q: Where do we store the link value in our 5-stage processor?
A:

Q: What is the purpose of "align load data" after we retrieve 32 bits from memory?
A:

Q: What is a not-aligned access
A:

Q: Why don't we directly store into memory in the MEM stage (for store instructions), and how is this issue dealt with?
A:

Q: Why can the STQ never overflow, give an informal explination?
A:

Q: What happens if we have a load instruction in EXE stage and a store instruction in MEM or Store Queue and it is for the same address?
A:

<h1>Lecture 11</h1>

Q: What is a pipeline hazard generally speaking?
A: 

Q: What are the **three** types of pipeline hazards, provide a sentence for each and an example for each.
A:

Q: What is bad about stalling?
A:

Q: What is a RAW hazard, give a basic 3 lines of RISCV code that demonstrate this hazard
A:

Q: How do we solve RAW hazards, go into both possible solutions and why one is more desirable?
A:

Q: What is the CPI bounded below and above by (excluding divides operations).
A:

Q: What speculative results do you choose when you are doing data-forwarding, what is the level of prioritisation?
A:

Q: What situations can we **not** avoid stalling, and what could we do with the code in some situations at compile time?
A:

Q: What is one way we can avoid the structural hazard with a 2 byte multiply?
A:

Q: What is known the "contribution to CPI", how would one do it for a specific instruction type?
A:

Q:  How do we calculate the speedup from pipelining, show the formula
A:

Q: Assuming the clock period for pipelined and unpipelined processors remains at 1, what factor would it be reduced by?
A:

Q: What is the issue with a really deep pipeline on the CPI, think about branch instructions
A:

Q: What are 3 techniques we can use to reduce branch penalties?
A:

Q: What is BTFN?
A:

Q: Draw the tree to show how we obtain 1.04 using this info
![[Pasted image 20241203175626.png]]
A:

<h1>Lecture 12</h1>
Q: What does a latch and flipflop actually do?
A:

Q: How does an SR latch work, draw the circuit diagram for a NOR (active high) one, and draw the function table
A:

Q: Do the same as above but for NAND (Active Low)
A:

Q: How does an SR Latch with an enable work, can you draw the function table, and write it as a kanaurgh map, and derive the minimum SOP?
A:

Q: How does a D-Latch work?
A:

Q: Explain how an edge-triggered D-type flip-flop works
A:

Q: What is the setup time?
A:

Q: What is the hold time?
A: 

Q: Explain how an edge-triggered D-type flip-flop works with a reset
A:

Q: What is a reset recovery?
A:

Q: Write the verilog code for a D-Flip-Flop and a Edge-Triggered-Flip-Flop 
A:

<h1>Lecture 13</h1>
Q: Given this state transition table and graph, what parts are states, and what parts of the arc show x and y?
![[Pasted image 20241204114052.png]]
A:

Q: Why is it good to separate synchronous and sequential logic?
A:

Q: What are the 2 types of FSMs, what is the difference between them?
A:

Q: Give the verilog code to implement a 4-bit register
A:

Q: Give the verilog code to implement a 4-bit linear shift register
A:

Q: With ASM charts, what type of diagrams are these![[Pasted image 20241204120853.png]]
![[Pasted image 20241204120825.png]]
![[Pasted image 20241204120924.png]]
A:

Q: What is a Moore type output signal?
A:

Q: In lecture 13 Slide 14, describe what is happening in ASM charts (b) and (c)
A:

Q: Use the spec on lecture 13 slide 16 to draw your own ASM chart, and then derive verilog code from it 
A:

Q: Use the spec on lecture 13 slide 19 to draw your own ASM chart, and then derive verilog code from it 
A:

<h1>Lecture 14</h1>
Q: What is RTL design ?
A:

Q: What is a clock-period constraint?
A:

Q: Explain what $t_{cp}, t_{u}, t_{su}, t_{hld}, t_{cq}$ mean here 
![[Pasted image 20241204125446.png]]
A:

Q: What is the equation for the setup slack and the hold slack
A:

Q: Why does both setup and hold slack have to be greater than or equal to 0?
A: 

Q: Explain the blue and purple path in this:![[Pasted image 20241204144557.png]]
A:

Q: Derive $t_{su\_slack}$ with the above diagram
A:

Q: What is one way of fixing setup slack violations?
A:

Q: What is a metastable state?
A:

Q: How can metastability affect an RTL system?
A:

Q: How can we mitigate metastability?  
A:

Q: What is a clock domain?
A: 

Q: What is the Mean Time Between Faliures?
A:

Q: Can a reset cause metastability?
A:

<h1>Lecture 15 + 16</h1>
Q: Whats the difference between static and dynamic branch predicition?
A:

Q: Which branch is more likely to be taken when you view this statically?
![[Pasted image 20241204163220.png]]
A:

Q: What is the BTFN strategy?
A:

Q: When may a static branch predictor be more accurate than dynamic prediction
A:

Q: How does a 1-bit dynamic predictor work, with a simple while loop how many mispredictions would there be?
A:

Q: How does a bi-modal predictor work, how does state updates work, maybe show a basic state diagram?
A:  

Q: What history does 1 and 2 bit branch predictors exploit?
A:

Q: What is the difference between local and global correlation?
A:

Q: What is a pattern history table (PHT) ?
A:

Q: What is an issue with aliasing?
A:

Q: Whats the issue with having a 2d table of PHTs (one for each PC)?
A:

Q: Why is having a larger PHT better?
A:

Q: How does the PHT for a local predictor work?
A:

Q: How does the PHT work for a global predictor?
A:

Q: What is a combined predictor?
A:

Q: What is the difference between GShare and GSelect predictors?
A:

Q: How would deal with unconditional branches?
A:

Q: Give a comparison of bimodal branch predictors and a 2-level branch predictor
A:

Q: How does tournament predictors combat biased branches from polluting PHT?
A:
<h1>Lecture 17</h1>
Q: How is this a **RAW** dependency?
![[Pasted image 20241205104240.png]]
A:

Q: How is this a **WAR** dependency?
![[Pasted image 20241205104316.png]]
A:

Q: How is this a **WAW** dependency?
![[Pasted image 20241205104338.png]]
A:

Q: Give a brief description of the 4 steps in **Scoreboarding**
A:

Q: What are the 3 conditions for controlling instruction progression?
A:

Q: What is some drawbacks of the scoreboarding algorithm?
A: 

<h1>Lecture 18</h1>
Q: How are reservation stations used for register renaming?
A:

Q: What are the high-level 3 steps for **Tomasulos** algorithm?
A:

Q: Why is re-ordering across load and store buffers NOT ALLOWED?
A:

Q:  How is Tomasulo's algorithm better than the scoreboarding scheme?
A:

Q: What is a limitation regarding branches that exists with both **Tomasulos** and **Scoreboarding**?
A:

Q: How would we enforce in-order state updates?
A:

Q: How does the ROB help with speculation and mis-speculation rollback? 
A:

Q: How could we support register renaming without reservation stations?
A:
<h1>Lecture 19</h1>
Q: What is the term for a 2 binary digit adder?
A:

Q: What is the term for a 3 binary digit adder?
A:

Q: Derive the circuit diagram for half adder
A: 

Q: Derive the circuit diagram for a full adder
A:

Q: What is the logical delay and complexity of a n-bit ripple carry adder
A: 

Q: What is the logic behind creating a carry lookahead adder?
A:

Q: What is the point of parrallell pr efix addition?
A:

Q: How do we obtain the 2s compliment value of a binary value?          
A:

Q: How an we do integer subtraction but as *addition*?
A:

Q: 
A:

<h1>Lecture 20</h1>
<h1>Lecture 21</h1>
<h1>Lecture 22</h1>
Q: What is the principle of temporal locality?
A:

Q: What is the principle of spatial locality?
A:

Q: What is the main purpose of a memory hierarchy, what impression are we trying to create?
A:

Q: What is a *hit ratio*?
A:

Q: Define what a *block, and a block size is*
A:

Q: Define *block placement*
A:

Q: Define *block identification*
A:

Q: Define *block replacement*
A:

Q: Define what *write strategy* is 
A:

Q: Define *inclusivity*
A:

Q: Explain what a fully associative and directly mapped cache, outline any drawbacks with both
A:

Q: Explain how a set associative cache works
A:

Q: What does a 2-way set associative cache actually mean?
A:

Q: How can we use tags to identify cache blocks?
A:

Q: What is the purpose of the *valid bit*?
A:

Q: How does LRU work, and what type of locality does this exploit?
A:

Q: How does NRU work, is it better than random or not?
A:

Q: When is it maybe okay to use a random algorithm for cache block replacement?
A:

Q: How is an LRU policy implemented for a 2-way set associative cache, give a high level sentence
A:

Q: How could we do it for higher m-way associative caches, what data structure do we need, and how could LRU be "approximated"?
A:

Q: How does pseudo-LRU work?
A: 

Q: How does the *write through* cache write strategy work, and what are some drawbacks and advantages?
A:

Q: How does *write back* cache write strategy work, and what are some advantages and disadvantageous?
A:

Q: What is the cache-coherency problem?
A:

Q: What happens if the block is not found in the cache? 
A:

Q: Do lower-level caches keep a copy of the block that's brought into a higher-level cache?
A:

Q: What are the pros and cons of inclusive and exclusive caches?
A:
<h1>Lecture 23</h1>
Q: What types of instructions does caching affect the CPI of, and why?
A:

Q: What is *miss penalty*?
A:

Q: What 3 basic parameters could we decrease to improve memory hierarchy performance?
A:

Q: What contributes to the miss penalty, and how could we try reduce this? 
A:

Q: Come up with an equation that gives the number of cycles for reading a block
A:

Q: Come up with an equation that gives the number of cycles to write to a block
A:

Q: What are the 3 different types of cache misses that can occur? 
A:

Q: What are some techniques to reduce *compulsory* miss rate, describe any advantages and drawbacks
A: 

Q: How is pre-fetching done in software, and how is it done in hardware?
A:

Q: In what scenarios is *linear prefetching predictions* good?
A:

Q: What is tiling?
A:

Q:
A:
<h1>Lecture 24</h1>
<h1>Lecture 25</h1>
<h1>Lecture 26</h1>
