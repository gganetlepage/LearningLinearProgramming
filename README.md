# Learning about Linear Programming
-----------------------------------
Based on "Linear Programming: Foundations and Extensions" 2nd Edition by J. Vanderbei.
Personal objectives :
	- Consolidate my basics
	- Learn advanced technics 
	- Implement my own solver of the simplex algo, which will then be called using JuMP

	
## computational todos:

1. Intro

2. The Simplex method
	- [ ] checking a LP model is in a canonical form
	- [ ] pivot operation : i.e. leaving variable selection
	- [ ] pivot selection : entering variable has the highest coef in the objective function
	- [ ] initialization, i.e. Phase I, when right-hand side's elements are nonpositive
	- [ ] checking unfeasibility (with Phase I)
	- [ ] detecting an objective function's unboundness

3. Degeneracy
	- [ ] detecting degeneracy (maybe a simple count within a `while` loop?)
	- [ ] Pivot method 2: lexicographic method (not sure it's practical)
	- [ ] Pivot method 3: Bland's rule
	
4. Efficiency of the simplex method
	- [ ] Compare computational results with the by-hand results
	
5. Duality theory
	- [ ] Using a canonical primal LP form, get the dual
	- [ ] Check results using the strong duality property




## Remarks:
	- LP using matrix form only appears first in chapter 6
	- How to handle a sparse matrix computationally ?
	- 


