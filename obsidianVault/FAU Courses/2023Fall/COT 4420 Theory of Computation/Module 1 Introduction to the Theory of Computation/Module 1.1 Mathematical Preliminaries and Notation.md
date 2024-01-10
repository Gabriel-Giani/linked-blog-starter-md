- Sets
- Functions and relations
- Graphs
- Proofs

**_Set_** is a collection of elements, without any structure other than membership.

	S = {0, 1, 2} //Set of integers 0, 1, 2

	Set S, x element in S notation: x ∈ S
	Set S, x element in S notion: x ∉ S

	S = {i: i > 0, i is even}
	//S is the set of all i such that i is great than 0 and i is even

  **Union ∪** 
	  S1 ∪     S2= {x:  x ∈ S1 or x ∈ S2}

**Intersection ∩**
	S1 ∩  S2 = {x:  x ∈ S1 and x ∈ S2}

**Difference -**
	S1 -    S2 = {x:   x ∈ S1 and x ∉ S2}

**U universal set**

**S compliment** is $\bar S$ = {x: x ∈ U and x ∉ S}  

**∅ empty set/null set**

S ∪ ∅ = S - ∅ = S

$\bar{\bar{S}}$ = S

## Demorgans Law:

$\overline {S1 \cup S2}$  = $\overline {S1}$ ∩ $\overline {S2}$
![[Screenshot 2023-08-27 at 6.55.04 PM.png|200]]


$\overline {S1 \cap S2}$ = $\overline {S1}$ ∩ $\overline {S2}$
![[Screenshot 2023-08-27 at 7.02.07 PM.png|200]]

Subset: **$S1 \subseteq S$**
Proper Subset: **$S1 \subset S$**     *//S contains an element not in S1*
Disjoint: $S1 \cap S = ∅$ 
$| S |$ - number of elements in S
**Powerset:** The set of all subsets of S is denoted by $2^s$ 
Powerset example:
$S = {\brace{a,b,c}}$ 
$2^s = {\brace{{∅},{\brace{a}},{\brace{b}},{\brace{c}},{\brace{a,b}},{\brace{a,c}},{\brace{b,c}},{\brace{a,b,c}}}}$ 
$|2^s| = 2^{|s|}$

**Cartesian (Cross Product) -** set operation that builds a set consisting of ordered pairs of elements from 2 existing sets.

Sets: A and B

$\text{A x B} = {(x,y)\text{ | } x ∈ A \text{ and } y ∈ B}$ 

Example: $A = {\brace{1,2,3}}, B = {\brace{1,2}}$ 
 
