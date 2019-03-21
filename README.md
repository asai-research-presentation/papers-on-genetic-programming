Personal memo about GP. Mind you, Im not a professional in the field!

Also, not about another GP (Gaussian Process).

# venues

Conference ranking http://www.conferenceranks.com/#data
A: CEC http://cec2019.org/ 
A: GECCO https://gecco-2019.sigevo.org/index.html/HomePage 
A: FOGA / Foundations of Genetic Algorithms	(Workshop and also a journal?) https://hpi.de/foga2019/
B: EvoCOP / European Conference on Evolutionary Computation in Combinatorial Optimization http://www.evostar.org/2019/cfp_evocop.php -- collocated with EvoApplication, EuroGP, EvoMUSART
B: EvoApplications http://www.evostar.org/2019/cfp_evoapps.php
B: EuroGP / European Conference on Genetic Programming http://www.evostar.org/2019/cfp_eurogp.php
C: EP / Annual Conference on Evolutionary Programming 

# Papers and recent work

+ Koza, John R., and John R. Koza. Genetic programming: on the programming of computers by means of natural selection. Vol. 1. MIT press, 1992.
  + https://sceweb.uhcl.edu/boetticher/ML_DataMining/john97genetic.pdf
  + Assumes a closure
    + a set of functions
    + every output of a function can be fed into another function
  + Bloat seems the major problem (??)
    + 

+ Stack based GP
  + http://geneticprogramming.com/about-gp/stack-based-gp/

+ Strongly Typed GP
  + Montana, David J. "Strongly typed genetic programming." Evolutionary computation 3.2 (1995): 199-230.
  + http://davidmontana.net/papers/stgp.pdf

+ Grammatical evolution
  + https://en.wikipedia.org/wiki/Grammatical_evolution
  + http://www.grammatical-evolution.org/
  + Separates the genotype and phenotype
  + Instead of a set of functions, it has a BNF grammar
  + Each expansion rule in the grammar has an index
  + A genotype is a sequence of expansion rule indices to apply (in order)
  + A phenotype is the resulting tree of applying the rules
  + Since the genotype is a string, it can be evolved in a standard GA process / toolsuite
  + However, loses some locality constraint in the tree-based representation

+ Cartecian GP
  + https://en.wikipedia.org/wiki/Cartesian_genetic_programming
  + Use a graph (assumed to be a cartecian grid) instead of a tree
  + originated from an FPGA
  + survey paper https://dl.acm.org/citation.cfm?id=3275518



  
