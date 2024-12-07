
<h1>Lecture 1</h1>
Q: What is **Concrete Syntax** and how does it differ to **Abstract Syntax**?
A: 

Q: What is an AST?
A: 

Q: What is the general strategy for structural induction?
A: 

<h1>Lecture 2</h1>
Q: What is evaluation ?
A: 

Q: What is totality property ?
A: 

Q: What is uniqueness ?
A: 
<h1>Lecture 3</h1>
Q: What is the difference between static and dynamic typing ?
A:

<h1>Lecture 4</h1>
Q: Formally define what variable scope is in a program
A:

Q: Explain what variable binding is, and what it is meant for a variable to be bound ?
A: 

Q: Explain what a free variable is and give 2 examples:
A:

Q: What is the technical term for consistent renaming:
A:

Q: What is alpha conversion
A:

Q: Give an example of alpha conversion
A:

Q: What is the call-by-value evaluation strategy?
A:
<h1>Lecture 5</h1>
Q: How do we typecheck this
![[Pasted image 20241126171910.png]]
A:

Q: What is the environment (delta) ?
A:

Q: What is the difference between static and dynamic scope?
A:

Q: What would the result be for each scope?
![[Pasted image 20241126173656.png]]
A:

Q: What is an issue in terms of type checking with dynamic scope, refer to example in the last question
A:

Q: Given the typing rule for recursive named functions, explain it
A:

Q: Given the evaluation rule for recursive anonymous functions, explain it
A:

**MAYBE LOOK INTO DOING EVALUATION AND TYPECHECKING USING RECURSIVE FUNCTIONS**

<h1>Lecture 6</h1>

Q: Give an example of a pair data structure
A:

Q: What is the Unit type in Scala?
A:

Q: What is a variant type, give an example of it
A:

Q: Why do we have *option* types?
A:

Q: Do the result types of a variant have to be the same or not?
A:
<h1>Lecture 7</h1>
Q: How can we construct something similar to a pair (i.e has fst and snd) with a record type?
A:

Q: How does named variants work, give a basic example?
A:

Q: What is wrong with this, refer to the order scala matches in?
![[Pasted image 20241130153558.png]]
A:

Q: How can we abbreviate types in Scala, give an example for <x:int, y:str>?
A:

Q: What is a "type definition", and are they allowed to be recursive or not?
A:

Q: What is subtyping, explain the Liskov Substitution Principle?
A:

Q: What is an example of width subtyping, show it for a record type
A:

Q: What is depth subtyping, show an example for record type
A:

Q: How does subtyping for named variants and record types differ?
A:

Q: Explain the sub-typing rules for functions, in the simple case? 
A:

Q: What is meant by reflectivity in subtyping?
A:

Q: What is covariant subtyping?
A:

Q: What is contravariant subtyping?
A:

Q: What is a *any* type in scala?
A:

Q: What is an *empty* type in scala?
A:

Q: What is structural subtyping?
A:

Q: What is nominal subtyping?
A:
<h1>Lecture 8</h1>
Q: What is polymorphism in Scala?
A:

Q: What is a "type parameter" in Scala?
A:

Q: What is parametric polymorphism?
A:

Q: Can you solve this using the FTV rules. Suppose the pair has type: τ=A×B , then finish this off:
FTV(A×B)= ....
A:

Q: What is a type constructor?
A:

Q: What is subtype polymorphism?
A:

Q: What is ad hoc polymorphism?
A: 

Q: What is type inference?
A:

Q: What is the general idea behind the *Hindley-Milner* type inference approach?
A:

Q: What is the strengths and weaknesses of ML-Style inference?
A:

Q: What is the strength and weaknesses of type-inference in Scala?
A:
<h1>Lecture 9</h1>
Q: How could we prevent a distance function from allowing Point 3d from being used in Scala?
A:

Q: What is the difference between nominal and structural subtyping?
A:

Q: What is a program in the sense of this course?
A:

Q: What is a decliration?
A:

Q: What are the different types of program entry points, give the 4 presented in this course and provide a brief sentence.
A:

Q: What is a namespace, how is this handled in java?
A:

Q: What is an abstract data type (ADT)?
A:

Q: Define a Priority Queue ADT in scala, with Type, empty and then def insert and remove
A:

Q: What is a Scala "trait"?
A:

Q: What does the keyword "extends" enable us to do in Scala, what happens, what relationship does it imply?
A:

Q: Can modules satisfy more than one interface?
A:

Q: What is representation independence, give a basic example for a stack ?
A:


<h1>Lecture 10</h1>
Q: What is encapusaltion, what would motivate this?
A:

Q: What is self-reference
A:

Q: What is inheritance
A:

Q: What does the **object** keyword do in Scala
A:

Q: What is a singleton object?
A:

Q: What is meant by open recur
A:

Q: What is a private field in scala?
A:

Q: What is the difference between a class and an interface?
A:

Q: Give a basic example of dynamic dispatch?
A:

Q: What is said about inheritance of parent classes and implementing of interfaces?
A:

Q: How are constructors called in Scala?
A:

Q: In scala, how many parent classes can we inherit using the extends key word?
A:

Q: In scala, how many interfaces could a class implement?
A:

Q: What is the subtyping relationship between an object Obj that extends a trait Tr?
A:

Q: What is the subtyping relationship between a class Cl that extends another class Super?
A:

Q: How is subtyping an inheritance distinct features?
A:

Q: What is the difference between private and protected in Scala?
A:

Q: How does the *static* keyword work?
A:

Q: What is a companion object in Scala, what motivates them?
A: 

Q: C++ allows for multiple inheritance, what are 2 associated problems with this ?
A:

Q: What is an abstract class, and the purpose of it?
A:

Q: How can you override something in Scala?
A:

<h1>Lecture 11</h1>
Q: What is the motivation behind having inner classes?
A:

Q: How can we have inner objects in Scala?
A:

Q: How would we nest a class within an object in Scala?
A:

Q: What is a local class?
A:

Q: What is a paramterized type (generics)?
A:

Q: What are the 3 ways that you can define paramterised types in scala?
A:

Q: How would we indicate if a type parameter is covariant?
A:

Q: How would we indicate if a type parameter is contravariant?
A:

Q: How would we indicate if a type parameter is covariant?
A:

Q: What is a type bound, how would someone do this in Scala (both ways round)?
A:

Q: What is the difference between a Scala trait and a Java interface?
A:

Q: How does Mixins work in Scala?
A:

Q: Why is the *apply* method special in Scala?
A:

Q: What is an iterator in Java?
A:

Q: Are for each loops in Java and Scala syntactic sugar?
A:

Q: Why can't we do "foreach" on an Int in Scala
A:

Q: How can we write the same code using map in Scala
![[Pasted image 20241204192348.png]]
A:

<h1>Lecture 12</h1>
Q: What is the advantages of immutability and mutability?
A:

Q: How can you define a mutable variable in Scala?
A:

Q: Explain the 3 symbols important for the $L_{while}$ rules, and state what each one is
A:

Q: What are some other control flow constructs?
A:

Q: What does $L_{while}$ lack?
A:

<h1>Lecture 13</h1>
Q: What are the limitations of Big-Step semantics?
A:

Q: What is small-step semantics?
A:

Q: Suppose we have the function fact -> if x == 0 then 1 else 2 $*$ fact(x - 1), and we then call fact 2, use small step semantics to evaluate it.
A: 

Q: Give a brief explanation of how we can do induction over derivation trees, what type of induction is this?
A:

Q: Define what is meant by type soundness, and in particular, value soundness.  
A:

Q: Explain the *progress* lemma
A:

Q: Explain the *preservation* lemma
A:

Q: How would you prove progress for this 
![[Pasted image 20241206112808.png]]
A:

Q: How would you prove preservation for this 
![[Pasted image 20241206112940.png]]
A:

Q:
A:

<h1>Lecture 14</h1>
Q: What is a reference in terms of $L_{ref}$ ?
A:

Q: How can we use references in Scala, and what methods are relevant?
A:

Q: What is the difference between a *procedure* and a *function*, and why may someone want to use a procedure?
A:

Q: What are the 2 possible evaluations, (do one left to right, and then one right to left)
![[Screenshot 2024-12-06 at 12.02.22.png]]
A:

Q: What is the consequence of contravariant sub-typing with references?
A:

Q: What is the consequence of covariant sub-typing with references?
A:

Q: What are some issues with resource programming?
A:

Q: What are some design choices that have been employed to help solve some of the issues listed above?
A:

Q: What are some ways we can enable the safe deallocation of resources?
A:

<h1>Lecture 15</h1>
Q: Why are administration rules important in evaluation?
A:

Q: What is *call-by-value (eager)* evaluation?
A:

Q: Show how this would be eagerly evaluated?
![[Pasted image 20241206174854.png]]
A:

Q: What is *call-by-name* evaluation?
A:

Q: How do we evaluate this using *call-by-name*?
![[Pasted image 20241206175354.png]]
A:

Q: What is the Scala built-in support for telling the compiler that a function argument is *call-by-name*?
A:

Q: Where could *call-by-name* be useful?
A:

Q: What are some differences between *call-by-need* and *call-by-value*?
A:

Q: What is *call-by-need (lazy evaluation)* ?
A:

Q: How can you use *call-by-need* in Scala?
A:

Q:  How do we keep a track of values of expressions that have already been evaluated?
A:

Q: What is the strengths and drawbacks of lazy evaluation? 
A:

Q What is the difference between *call-by-need* and *call-by-name*?
A:

Q: What are some examples of *lazy* datastructures?
A:
<h1>Lecture 16</h1>
Q: What is an exception?
A:

Q: What is a *finally* clause?
A:

Q: What is the difference between checked and unchecked exceptions?
A:

Q:  What is the purpose of the intermediate *e raises v* rule?
A:

Q: What is a tail function call?
A:

Q: How come this function isn't tail recursive?
![[Pasted image 20241206173251.png]]
A:

Q: Why can tail recursion be more performant, what annotation in Scala can we use to help?
A:
