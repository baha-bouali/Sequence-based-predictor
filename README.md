# Sequence-based-predictor
The objective of this competition is to construct a model that can predict the thermodynamic folding stability of a protein (DDG) in response to a single amino acid mutation. The challenge involves developing a Deep Learning algorithm that is trained on the amino acid sequences of wild-type (WT) proteins and mutant proteins with a single amino acid variation. The ultimate goal of this work is to provide insight into mutation-related diseases and to demonstrate the crucial role played by loss of stability in the loss of protein function. By participating in this competition, you will have the opportunity to contribute to scientific advancements in the field of protein stability, which have significant implications for the diagnosis and treatment of various diseases.

Proteins are large, complex molecules that play many critical roles in the body. They do most of the work in cells and are required for the structure, function, and regulation of the body’s tissues and organs. The overall stability of a protein is influenced by its residues and their interactions. Any change to the wild-type sequence, even a single mutation, has the potential to drastically affect stability because proteins are marginally stable. The effects of non-synonymous variants on the protein stability are quantified in terms of the Gibbs free energy of unfolding (dG). The stability change from a mutated (mutant) protein to its wild-type (wildtype) form is defined as the difference between the folded and unfolded states (dGfolding) and the change in dGfolding when a point mutation is present.

## Evaluaion 
The evaluation metric for this competition is Root Mean Squared Error.

For every row in the dataset, submission files should contain 2 columns: ID and deg.

Your submission file should look like this (numbers to show format only):

ID    deg
0     0.12
1     1.36

