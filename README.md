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
