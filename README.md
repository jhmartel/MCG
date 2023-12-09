# Mapping Class Groups, Closing the Steinberg Symbol, and Spines.

[Updated 2023-12-09] 

This repository contains our projects on the Mapping Class Group of closed hyperbolic surfaces. This morning we have uploaded our draft article on constructing an equivariant spine for Teichmueller space of minimal dimension. We have finally assembled all our ideas into a coherent retraction, and we think it's quite interesting. Next step is to actually submit somewhere for publication. 





The article MCG.pdf includes some of our research into the mapping class group of closed hyperbolic surfaces. We are looking to apply the reduction to singularity method from our PhD thesis to constructing equivariant spines for the Teichmueller space hyperbolic surfaces. To apply our reduction method requires we solve a computational subprogram we call "Closing the Steinberg Symbol" (CS). Solutions of Closing Steinberg (CS) are finite subsets I of MCG. 

Using the python program curver of Mark C. Bell, we have successfully found some formal solutions to (CS) for the genus two case. These are included in the ClosingSteinbergGenusTwo.ipynb notebook.

Having formal solutions to (CS) requires we further establish the necessary geometric properties of the solution I in order to replace Teich with a chain sum F. The chain sum F gives us a good set of global coordinates from which we can construct an optimal transportation program, and thereby homotopy reduce Teich onto the singularity Z of the optimal transport plan.

