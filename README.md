# AlignmentAutomation
This project documents the automation process of vacuum alignment of a global-discrete charged BSM scalar field theory. 

The process currently includes A4 and Δ(27) symmetries. Each section of the code attempts to reproduce the results obtained analytically in each corresponding papers that introduces the inclusion of family-charged familon scalar fields called flavons. 

The current progress includes the automation of 10.1016/j.nuclphysb.2005.05.005, 10.1007/JHEP09(2018)047, 10.1007/JHEP03(2018)007. The project is associated with the DECO algorithm that calculates the number of contractions of an effective Wilsonian term of dimension n using the Hilbert Series. 

_Alignment.nb_ (published) – this file includes reproduction of the alignment of scalar fields charged under either A4 or Δ(27).
The programme includes definitions of the Δ(27) generators and contraction rules between triplet fields under the fundamental representation and functions that produce singlets of arbitrary choice of representation. 
The renormalizable terms are based on the Universal Texture Zero programme by Varzielas, Ross and Talbert and the programme reproduces the alignment condition in the appendix. The final part of the script includes an attempt to add a non-renormalizable 6th-dimensional term. 

_classification.nb_ (published) – this file contains the addition of 6 dimensional non-renormalizable term built from a single triplet field that transforms under the fundamental representation of Δ(27). The categorisation of the diverse ways of construction a 6 dimensional term is flashed out and all terms are enumerated through, except where assumption are delcared. The result finds 3 possible contractions at dimension 6, one from each of the 2+2+2, 3+3, 2+4 constructions via the potential perturbation method around the renormalizable alignment direction. The justification for the perturbation stems in the ΛUV^-2 suppression from the renormalizability. 

_**NNclassifier**_ (in construction) – The future code aims to classify non-renormalizable terms to 1. vacuum-invariant 2. vacuum-scaling 3. vacuum-breaking using convoluted neural network. The introduction of additional term perturbs the potential landscape but preserves the manifold structure of the vacuum. The diffeomorphism could 1. preserve the initial alignment, 2. scale the manifold, or 3. collapse the vacuum manifold to a point. The goal is to categorise without going through the perturbation analysis. This step is particulrly useful for future mixing of non-renormalizable terms. The current project in construction scans the potential landscape as the input and carry out dimensional reduction in the attempt to understand the polynomial-parameter space formed by the non-renormalized terms. 
