# MSc Thesis Examples

This repository demonstrates several examples from my Masters thesis in Mathematics 
and Statistics at the University of Melbourne. My supervisor for this project 
was Dr Daniel Murfet. 

Part of this thesis involves particular series expansions of polynomials in 
a completion of the polynomial ring. These series expansions can be computed 
using polynomial division via an an algorithm referred to as Algorithm 3.3.7
in the thesis. Under some conditions this algorithm will always terminate, 
which shows that the series expansions are finite and passing to the completion 
is not necessary. The relevant section of the thesis is Section 3, particularly 
3.3 and 3.4. Lemma 3.3.6 precisely states the series expansions we are computing 
in Algorithm 3.3.7. 

In this repository we implement Algorithm 3.3.7 and use it to demonstrate 
Example 3.4.4 and Example 3.4.5 from the thesis, and an example involving the 
Dn-type singularity which is mentioned in passing. 

Algorithm 3.3.7 is implemented in Python 3 using [Sage](https://www.sagemath.org). 
The file `examples.py` must be run with the version of Python which comes 
with Sage. Having installed Sage, run `examples.py` using the command 
`sage --python examples.py`.

