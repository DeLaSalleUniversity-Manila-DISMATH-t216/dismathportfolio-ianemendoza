# dismathportfolio-ianemendoza
dismathportfolio-ianemendoza created by Classroom for GitHub

<b>Week 1</b><br>
Proposition - a statement that has a truth value it may be true or false<br>
Logic Operator - it's like the logic operations in LOGICIR but the difference is the symbol of the operator.<br>
Negation - it is also known as the "bar" in LOGICIR. In dismath the symbol for negation is ¬ . It act as an inverter in logic gates.<br>
Conjuction - it act as an and gate with a symbol of ^<br>
Disjunction - On the other hand, this is like the or gate with a symbol of v.<br>
Exclusive Or - also known as the "if and only if" operator with a symbol of ⊕ <br>
Conditional - p→q  will only be true if p and q are both true or if q is false.<br>
Biconditional - p ↔ q will only be true if both statements have the same truth value<br>

<b>Week 2</b><br>
Statement: p → q<br>
	Inverse - ¬p → ¬q <br>
	Converse - q→p <br>
	Contrapositive - ¬q → ¬p <br>
We applied the logic operators to different propositions. I felt like I was inside a Philosophy class because we used to study<br>
these kinds of statements. The only difference is that we were given different logical operators that we need to memorize to know what's the<br>
statement's validity and truth value. Mathematics was being connected to English.<br> 

Ex. I love the letter B and I have a friend named Karl, then I hate Karl.<br>
Simple statement but it is valid based on the different logical operators that were discussed but the truth value is false. Validity of the statement will be measures with truth table and logical operators while the truth value will be based on reality.<br>

A few more identities were discussed that we need to fully understand and keep in mind because we need it to prove logic equations.<br>
There are several tools you can use in proving:<br>
-Truth Table<br>
-Logical Equivalence<br>
-Quantifiers<br>
-Rule of Inference<br>

FALLACY - incorrect reasoning<br>

INFERENCE:<br>
MODUS PONENS<br>
  p<br>
  p → q<br>
---------<br>
  q<br>
  
MODUS TOLLEN<br>
  ¬q<br>
  p → q<br>
---------<br>
  ¬p<br>

HYPOTHETICAL SYLLOGISM<br>
  p → q<br>
  q → <br>
---------<br>
  p → r<br>
  
DISJUNCTIVE SYLLOGISM<br>
  p v q<br>
  ¬ p<br>
--------<br>
  q<br>
  
ADDITION<br>
  p<br>
------<br>
p v q<br>
		

<b>Week 3</b><br>
Propositional Logic - logic that deals with propositions<br>
Predicate Logic - logic that deals with predicates and quantifiers<br>
Why study proving?<br>
	- It may seem weird but it is a big help in programming<br>
	- It helps finding errors or bug in a system easier<br>
Methods of Proving:<br>
SAMPLE STATEMENT : p → q <br>
	1. Direct Proof -<br>
		A. Assume that p is true<br>
		B. Show that q is true with the help of A.<br>
	2. Contraposition<br>
		A. We assume that ¬q  is true<br>
		B. Show that ¬p  is not negating A.<br>
	3. Vacuous Proof<br>
		A. Show that p is false, since in a conditional statement if p is false, then the statement is true.<br>
	
<b>Week 4<br></b>
Methods of Proving:<br>
	1. Contradiction<br><br>
		A. Assume  that the premise is false which will lead to a contradiction.<br>
	2. Equivalence<br>
		A. To prove a biconditional statement to be true, we should prove that even you inter change p and q as the premise, the statement will still be both true.<br>
  3. Mathematical Induction <br>
    A. Substitution or the basis step<br>
    B. Direct Proof or the inductive step <br>
Mathematical Induction is usually used for proving summation and recursive functions.<br>
<b> Week 5</b><br>
Start of Lecture for the 2nd quiz <br>
RECURSIVE ALGORITHMS<br>
- reducing with smaller input <br>
Ex. <br>
	Recursive algorithm for a^n where a is a non-zero number and real, while n is not equal to a negative number <br>
		power(a,n)<br>
		{<br>
			if (n==0)<br>
				return 1;<br>
			else<br>
				return power(n-1)(a);<br>
		}<br>
Program Verification<br>
- partial corectness <br>
- show that the program always terminates<br>

HOARSE TRIPLE<br>
p{s}q<br>
p = initial assertion<br>
s = program <br>
q = final assertion <br>

ZENO'S PARADOX<br>
-infinite series<br>
	a. Geometric Series<br>
	b. Power series<br>

INTRODUCTION TO SET THEORY<br>
1. Set - with distinct objects<br>
2. Cardinality - number of distinct objects inside the set<br>

<b> MIT APP INVENTOR TUTORIAL</b><br>

<b> Week 6 = NO CLASSES </b><br>

<b> Week 7 </b><br>
Algorithm - finite set of precise instructions for performing a computation or for solving a problem <br>
Ex. Finding the maximum value <br>

max = ai;<br>
	for i = 2:n<br>
		if (max<ai)<br>
			max = ai<br>

The code is called <b> PSEUDOCODE</b><br>

Precondition - statements that describe valid input<br>
Postconditiona - condtions that the output must satisfy<br>
Definiteness - steps of algorithm must be defined<br>
Correctness - algorithm should produce the correct output all the time<br>
Finiteness - should produce desired output after several number of steps<br>
Generality - procedures should be applicable to all<br>

2 Types of Algorithm<br>
1. Linear Search Algorithm<br><br>
2. Binary Search Algorithm<br>

<b> Week 8</b><br>
Sorting Algorithm - putting a number of elements in an increasnig order<br>
	a. Bubble Sort - the largest number goes up the pyramid like a bubble<br>
	b. Insertion Sort - comparison with the first number as the basis<br>
Greddy Algorithm - in a coin problem, greedy algorithm chooses the least amount of cois to add up to a value<br>
	c={25,10,5}<br>
	x= total amount<br>
	n=minimal number of coins<br>
	for i=1:4<br>
		while (x>=ci)<br>
			x=x-ci<br>
			
<b> Week 9 </b><br>
Growth function - often described using Big-O notation<br>
Big-O <br>
- function bigger than the original function<br>
- always upper hand<br>
Big Theta <br>
-upper and lower bound<br>
Algorithm Time Complexity<br>
-count the number of comparison, then measure the big theta<br>
1. Finding the maximum: Big theta = (n)<br>
			Number of comparison = 2n-1<br>
2. Bubble Sort: Number of comparison=n(n-1)/2<br>
3. Linear Search: Number of comparison = 2n+2<br>
<br>
Division and Modulus Operator<br>
-cryptology<br>
<br>
<br>
<b>Week 10</b><br>
Graph Theory<br>
Graph - discrete structures consisting of vertices and edges that connect these vertices<br>
G = (V,E)<br>
G=graph<br>
V=vertices
E=edges<br>
Degree = number of paths connected to 1 node. A loop is counted as degree 2.<br>
Handshake Theorem<br>
2e = Summation(degree)<br>
# of edges = summation(degree)/2<br>
Euler Circuit<br>
- even degrees for all nodes<br>
- closed path<br>
Euler Path<br>
-exactly 2 nodes have odd degrees<br>
-distinct edges:OPEN<br>
Hamilton Circuit<br>
-when all nodes are passed by and you can go back to the node where you started<br>
- if there is a pendant, there is no hamilton circuit<br>
Hamilton Path<br>
-pass by all nodes but can't go back to the node where it started<br>
Matrices of Graphs <br>
Isomophosm of Graphs<br>
- it is when a certain graph can be manipulated to form another graph without disconnecting anything<br>
Planar Graphs <br>
-graphs that can be drawn in the plane without any edges having to cross.<br>
<br>
Euler's Formula<br>
r=e-v-2<br>
Kuratowski's Theorem<br>
-graph that contains a subgraph homeomorphic; no longer planar<br>
K3,3 - non planar<br>
K4,3 - non planar<br>
K5 - non planar<br>
<br>
<br>
<b> Week 11</b><br>
Homeographic Graphs <br>
Elementary Subdivision - obtained by removing an edge<br>
Ex.<br>
remove edge {u,v} then replace it with {u,w}{w,v}<br>
Graph Coloring <br>
-minumum number of colors that you can place in a graph with out any adjacent colors<br>
Tree<br>
-graphs with no simple circuit<br>
Leaf - does not have any children<br>
Forest - consists of several trees<br>
Rooted Tree - starts with the root <br>
Internal Vertice - vertices with children<br>
M-ary Tree - same number of children all throughout <br>
<br>
<br>
Grammar - generate words of a language<br>
Formal language - generated by grammar<br>
Compiler - program that reads a program <br>
Automata Theory - laws of computation<br>
Lexical Analysis - code is read from left ro right<br>
			
