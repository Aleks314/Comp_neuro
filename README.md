The purpose of this code is to intake human brain structural connectivity matrices, and convert them to mathematically similar
yet biologically unnatural connectivity matrices. The new array, new_SC then stores these matrices for further use. This iteration
completed on: 04/12/2025, uses SCmatrices88healthy.mat available from Škoch A, Rehák Bučková B, Mareš J, Tintěra J, Sanda P, 
Jajcay L, Horáček J, Španiel F, Hlinka J. Human brain structural connectivity matrices-ready for modelling. Sci Data. 2022 Aug 9;
9(1):486. doi: 10.1038/s41597-022-01596-9. PMID: 35945231; PMCID: PMC9363436. Each matrix M is mapped to Q^TMQ, where Q is an 
orthogonal matrix. This transformation ensures the preservation of eigenvalues and their multiplicity, the rank, trace and
determinant of each matrix M, only mapping the eigenvectors of M, say v, from v to Q^Tv, on the condition that Q is square.
