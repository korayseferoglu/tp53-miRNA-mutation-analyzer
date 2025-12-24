# TP53 3′-UTR Mutation & miRNA Interaction Analysis Tool
A specialized bioinformatics utility for detecting somatic mutations in the TP53 3′-UTR and quantifying their impact on miRNA binding sites using the novel **miRES Algorithm**.

### Scientific Context
Somatic mutations in the regulatory 3′-UTR region of the TP53 gene can disrupt miRNA-mediated gene silencing, potentially leading to tumor progression in Anaplastic Thyroid Cancer (ATC). This tool automates the alignment and interaction scoring.

### The miRES Algorithm
The tool implements a proprietary scoring system (miRNA Risk Effect Score) based on:
- **Binding Strength (B):** Normalized $\Delta G$ binding energy.
- **Functional Impact (F):** Literature-backed regulatory effect.
- **Pathogenicity Link (P):** Association with Thyroid Cancer phenotypes.
- **Conservation Score (C):** Evolutionary importance via **PhyloP** genomic scores.

### Technical Implementation
- Designed the biological algorithms and scoring logic independently, leveraging AI-augmented coding techniques to accelerate software development and prototype deployment.
- **Architecture:** Client-side JavaScript (Zero-server architecture for maximum data privacy).
- **Alignment:** Real-time nucleotide-by-nucleotide comparison against the TP53 reference sequence (1188 nt).
- **Database:** Integrated library of ~100 validated miRNA seed regions.
