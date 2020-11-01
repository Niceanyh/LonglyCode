# Decision,Computation and Language  

> overview:  
>> - Automata theory  
>> - 
>> - 
>> - 


* [Week1](#1)
* [Week2](#2)
* [Week3](#3)
* [Week4](#4)



<h2 id="1">Week1</h2>

### Lecture 1  Theory of computation  
#### The law of computation :
&#8195;• Automata Theory studies the law of computation which tell us what is possible and impossible for computers;  
&#8195;• Machine learning algorithms; Applying machine learning algorithms to practical problems;

#### Formal language and Automata Theory :
&#8195;• Automata describe the operation of a device/process; used in lexical analyze to recognize expression in programming language.  
&#8195;• 

#### Different kind of machine:
&#8195;• finite machine  
&#8195;• pushdown machine 
&#8195;• Turing machine 
&#8195;• resource-bounded Turing machine  

### Lecture 2  Language
#### Alphabet and strings
&#8195;• An alphabet is a finite set of symbols.  
[![0zmvhd.md.png](https://s1.ax1x.com/2020/10/19/0zmvhd.md.png)](https://imgchr.com/i/0zmvhd)  
&#8195;• String  

[![String](https://s1.ax1x.com/2020/10/19/0zeJZF.md.png)](https://imgchr.com/i/0zeJZF)  

### Lecture 3  Decision  
#### DFS 




<h2 id="2">Week2</h2>  

### Lecture 4  DFA
#### A deterministic finite automaton
&#8195;a DFA (Q, S, d, q0, F) is the set of all strings over S that  
&#8195;Starting from q0 and following the transitions as the string is read left to right, will reach some accepting state   

### Lecture 5  NFA
#### A nondeterministic finite automaton 
&#8195; a 5-tuple (Q, Σ, δ, q0, F) where  
&#8195;–  Q is a finite set of states  
&#8195;–  Σ is an alphabet  
&#8195;–  δ: Q × Σ → subsets of Q is a transition function –  q0 ∈ Q is the initial state  
&#8195;–  F ⊆ Q is a set of accepting states (or final states)  

#### feature
&#8195;An NFA can reach several different states after reading a given word  
&#8195;Differences from DFA: transition function δ can go into several states  

### Lecture 6  ε-NFA
#### An ε-nondeterministic finite automaton (ε-NFA)
&#8195; a 5-tuple (Q, Σ, δ, q0, F) where  
&#8195;–  Q is a finite set of states  
&#8195;–  Σ is an alphabet  
&#8195;–  δ:Q×(Σ∪{ε})→subsetsof Q is a transition function  
&#8195;–  q0 ∈ Q is the initial state   
&#8195;–  F ⊆ Q is a set of accepting states (or final states)  

#### feature
&#8195;Differences from NFA: It allows ε-transitions  

<h2 id="3">Week3</h2> 
### Lecture 7 ε-NFA to NFA to DFA conversion

### Lecture 8 Regular Expression(regex)

### Lecture 9

