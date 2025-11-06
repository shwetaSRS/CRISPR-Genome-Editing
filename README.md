# CRISPR-Based Genome Editing

This repository provides a simple overview of CRISPR-Cas9 genome editing.

## What is Genome Editing?
Genome editing allows precise modification of DNA in living organisms. CRISPR-Cas9 is a popular tool for this purpose.

## How CRISPR Works
1. Guide RNA (gRNA) binds to a specific DNA sequence.
2. Cas9 protein cuts the DNA at the target site.
3. DNA repair occurs:
   - NHEJ (Non-Homologous End Joining): random mutations
   - HDR (Homology Directed Repair): precise changes using a template

## CRISPR Genome Editing Workflow (ASCII Diagram)

DNA: 5' - ATCGTACGATCG - 3'  
gRNA:        ||||||||||  
Cas9 cut:     ^  

DNA Repair Options:

1. NHEJ
   -------------------------
   DNA breaks rejoined randomly
   Can introduce insertions/deletions
   Outcome: Gene disruption
   -------------------------

2. HDR
   -------------------------
   DNA repaired using a template
   Can introduce precise changes
   Outcome: Gene correction or insertion
   -------------------------

## Example gRNAs
See [`examples.csv`](examples.csv) for sample gRNAs targeting genes.

## References
See [`references.md`](references.md) for papers and resources.
