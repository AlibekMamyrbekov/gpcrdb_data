Sequence signature tool
=======================

A sequence signature is a set of residue positions with amino acids or properties thereof that are distinctly
conserved in one of two sets of proteins; and is generated to identify determinants of a biological function
differing between these two sets.

The GPCRdb sequence signature tool (available under Receptors – Sequences –
Similarity) receives a selection of two sets of GPCRs. These are aligned separately to calculate their individual
percent conservation of amino acids or properties thereof within each column of the alignment which is indexed with a
generic residue number. For each such residue position, the tool then identifies most distinctly conserved amino acid
or property in either dataset and assigns a score representing the difference in percent conservation. For example, a
conservation of 87 and 27 percent in the two receptor sets gives a score of 60. Finally, the sequence signature is
derived by applying a score cut-off (default is 40) to extract the most distinct residue positions. This sequence
signature can be downloaded as an Excel spreadsheet for further analysis, for example design of mutagenesis
experiments based on signature scores and amino acids/properties. Furthermore, the sequence signature can be matched
against the protein sequences of other receptors to predict which of those share the reflected function (as
defined by the two original sets of proteins). This provides a sum of signature position scores that is normalised by
dividing by the maximum theoretical score (if the GPCR and signature matches in all positions). All receptors are
listed in decreasing score order and can be downloaded as an Excel spreadsheet for example to select GPCRs
for validating functional characterization.
