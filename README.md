# BioinformaticsNotes
Bioinformatics algorithms help analyze biological data such as DNA, RNA, and protein sequences. They support tasks like sequence alignment, gene prediction, protein structure prediction, and evolutionary analysis.
1. Sequence Alignment Algorithms

Needleman–Wunsch → Global alignment (aligns full sequences).

Smith–Waterman → Local alignment (finds best matching subsequences).

Both use dynamic programming with match/mismatch/gap scores.

2. BLAST (Basic Local Alignment Search Tool)

Fast, heuristic tool for sequence comparison.

Finds regions of similarity in large databases.

Outputs: scores, E-values, % identity → used for annotation.

3. Hidden Markov Models (HMMs)

Statistical models with “hidden” states.

Used for gene prediction, protein family detection, and RNA structure.

Models transitions between coding / non-coding regions.

4. Phylogenetic Tree Algorithms

Infer evolutionary relationships from sequence data.

Distance-based: UPGMA, Neighbor-Joining

Character-based: Maximum Likelihood, Bayesian

Used to study species evolution.

5. Genome Assembly Algorithms

Reconstruct genomes from short sequencing reads.

De novo assembly (no reference) vs. reference-based assembly.

Challenges: repetitive regions, accuracy.

6. Gene Prediction Algorithms

Identify coding regions (genes) in DNA.

Ab initio: use statistical sequence features.

Homology-based: compare with known genes.

7. Multiple Sequence Alignment (MSA)

Align 3+ sequences to find conserved regions.

Tools: ClustalW, MUSCLE

Important for evolution studies and protein family analysis.

8. Clustering Algorithms

Group similar biological data (e.g., gene expression).

K-means: divides data into K clusters.

Hierarchical clustering: builds a tree of clusters.

9. Motif Finding Algorithms

Find recurring patterns in DNA/RNA/protein sequences.

Use position weight matrices (PWMs) and probabilistic models.

Identify regulatory elements and functional motifs.

10. RNA Secondary Structure Prediction

Predict RNA folding based on base-pairing and energy rules.

Often uses dynamic programming.

Helps understand RNA function.

11. Protein Structure Prediction

Predict 3D protein structure from sequence.

Methods: Homology modeling, threading, ab initio.

Key for drug design and understanding function.

12. GWAS Algorithms

Analyze genetic variants in populations to link SNPs → traits/diseases.

Use statistical tests to find significant associations.

13. NGS Data Analysis Algorithms

Handle large-scale DNA/RNA sequencing datasets.

Includes: alignment, variant calling, expression quantification.

Essential for genomics & transcriptomics.

14. Machine Learning in Bioinformatics

Used for prediction, classification, and pattern recognition.

Supervised (SVMs, random forests)

Unsupervised (clustering, dimensionality reduction)

15. Network Analysis Algorithms

Study interactions among genes, proteins, metabolites.

Use graph theory to identify key nodes/pathways.

Helps understand cell pathways and diseases.
