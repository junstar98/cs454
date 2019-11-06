# cs454

FLUCCS

- SUT: System Under Test
- SBFL: Spectrum Based Fault Localisation
- Variable definitions for ep, np, nf, ef ==> executed/ non-executed method , corresponding pass/fail
- Program Element: statement, predicate, function / method etc. 



Problem: 
The best SBFL formula has to be adaptively learnt rather than declared


Solution: 
* Same set of features can be effective for both defect prediction and fault localisation
* GP as learning mechanism
* Utilize source code metrics

Features:
From Source Code
  1. Set of SBFL scores using different SBFL formulae
  2. Set of code and change metrics

"Method Level Localisation" --> can have same spectrum tuple

Depency network in the unit of methods -- Call Graph Propagated (CGP)








