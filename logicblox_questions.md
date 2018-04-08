## Questions for LogicBlox lecture

The LogicBlox paper and company spans the intersection of databases, programming languages, ML, and algorithms/theory.  There are three sets of questions to ponder while reading the paper.   Pick one of the following sets of questions to answer:

### 1. DB and PL

Notice that the PL community tends to hold the virtual machine constant (e.g. Java VM, the CLR, the x86 instruction set) and vary the imperative or functional surface language.  ON the other hand, the DB community holds the language constant (SQL) and varies the underlying run-time (e.g. runtimes for OLTP, OLAP, Graphs, Documents, etc).


- What are the boundaries between programming languages (PL) and databases?  Is the separation fundamental or is it an accident of history?
- The NoSQL movement went back and added SQL.  Why?
- PL’s and their runtimes have added support for automatic memory management and garbage collection and are starting to add support for thread safe programming (e.g. Rust).  What prevents language designers and compiler writers to add support for out-of-core computations, automatic parallelization, concurrency, incremental view maintenance, etc?


<!--- Why does the PL community ignore the relational/logic programming paradigm, ceding to the DB community (and perhaps the classic AI community)?  Can the DB community take advantage of the PL community's work on compilers, garbage collectors, type systems, functional data structures, etc?-->

### 2. DB and ML/AI

- How many databases and programming languages are needed to build an "AI"  powered application today?  (e.g., fraud detection, supply chain optimization, or whatever you deem an AI powered app)
- What are the similarities between DB’s and ML frameworks like TensorFlow and Pytorch?
  * How are relations, tensors, metrics, and arrays related?  
  * What are the differences and similarities between linear algebra and relational algebra?
- How are statistical models related to database models/queries?

### 3.DB and Algorithms/Theory

Broadly speaking, the performance of a program can be improved in two ways:  

1. improving constant factors (e.g. reduce interpretation overhead, memory hierarchy optimizations (latency hiding), parallelization)
2. improving asymptotics (e.g. sorting in O(n log n) vs in O(n^2))

Q1 and 2:

* Why are the traditional relational algebra operators unary/binary?  What are the implications of doing this on constant factors? On asymptotics?  Think about how you would reason about and execute a 10-way join operator vs a chain of 9 binary join operators.
* What are the implications of binary operators on the way DB’s generate and optimize query plans.

Seminal work from the early 1970’s by researchers like Codd working on relational database and Kowalski on Prolog showed that it is possible to build systems that can compute the correct answers to declarative programs written in subsets of first order logic.  Their work established that it can be done but didn’t make any guarantees about the computing resources needed to do it.  The lack asymptotic complexity guarantees on the evaluation of such programs limited the utility of declarative of programming systems to important but niche subsystems like databases.  Most systems today are still built primarily with imperative programming languages.  

Q3: 

* Can we build databases systems that make asymptotic complexity guarantees on query evaluation?  For what fragments of first order logic can such guarantees be made?  (start with the most trivial example, e.g., select 1, and move more complex)