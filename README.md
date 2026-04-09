# HBB-Phylogenetic-and-Protien-Analysis-
In-silico Analysis and Phylogenetic Study of Human Hemoglobin Subunit Beta (HBB)

1. Introduction

Hemoglobin is a crucial oxygen-transport protein present in red blood cells. It consists of multiple subunits, including the beta-globin chain encoded by the HBB gene. This protein plays a fundamental role in oxygen binding and transport throughout the body. Mutations in the HBB gene are associated with genetic disorders such as sickle cell anemia and β-thalassemia.

This study aims to perform an in-silico analysis of the human HBB gene and its protein product, followed by a comparative phylogenetic analysis across multiple species to understand evolutionary relationships and functional conservation.

---

2. Objectives

- Retrieve and validate the HBB mRNA sequence
- Translate mRNA into protein sequence
- Analyze physicochemical properties of the protein
- Perform multiple sequence alignment (MSA)
- Construct and interpret a phylogenetic tree
- Understand evolutionary conservation of the HBB gene

---

3. Methodology

3.1 Sequence Retrieval

The mRNA sequence of human HBB was retrieved from the NCBI database (Accession: NM_000518.5) in FASTA format.

3.2 Sequence Validation (BLAST)

The sequence was validated using BLAST to confirm its identity. The results showed:

- 100% identity
- 100% query coverage
- E-value = 0.0

These results confirmed that the sequence corresponds to human HBB mRNA.

---

3.3 Translation of mRNA

The mRNA sequence was translated into a protein sequence using the ExPASy Translate tool by identifying the correct open reading frame (ORF).

The resulting protein consisted of 147 amino acids.

---

3.4 Protein Analysis (ProtParam)

The translated HBB protein sequence was analyzed to determine its physicochemical properties:

Parameter| Value
Number of amino acids| 147
Molecular weight| 15,998.41 Da
Theoretical pI| 6.74
Instability Index| 6.16 (Stable)
Aliphatic Index| 93.47
GRAVY| 0.014

---

3.5 Comparative Sequence Collection

HBB mRNA sequences from five species were collected:

- Homo sapiens (Human)
- Bos taurus (Cow)
- Rattus norvegicus (Rat)
- Peromyscus maniculatus (Deer mouse)
- Heterocephalus glaber (Naked mole rat)

All sequences were selected based on completeness and coding region availability.

---

3.6 Multiple Sequence Alignment

Multiple sequence alignment was performed using Clustal Omega. The alignment allowed identification of conserved and variable regions across species.

---

3.7 Phylogenetic Analysis

A phylogenetic tree was constructed based on aligned sequences to study evolutionary relationships among the selected species.

---

4. Results

4.1 BLAST Analysis

The BLAST results confirmed that the retrieved sequence is human HBB mRNA with perfect alignment and statistical significance.

---

4.2 Protein Characterization

The HBB protein was found to be:

- Stable (low instability index)
- Slightly acidic (pI < 7)
- Structurally stable (high aliphatic index)
- Balanced in hydrophobicity (GRAVY ≈ 0)

---

4.3 Multiple Sequence Alignment

The alignment revealed:

- Highly conserved regions across all species
- Minor variations indicating evolutionary divergence
- Conserved motifs essential for protein function

---

4.4 Phylogenetic Tree Interpretation

The phylogenetic analysis revealed:

- Rodent species (Rattus norvegicus and Peromyscus maniculatus) clustered together, indicating close evolutionary relationship
- Homo sapiens and Bos taurus formed a separate cluster, showing conserved mammalian lineage
- Heterocephalus glaber appeared more divergent, suggesting species-specific adaptations

Branch lengths indicated genetic distances, where shorter branches represented higher similarity.

---

5. Discussion

The high conservation of the HBB gene across different species highlights its essential biological role in oxygen transport. The clustering of species in the phylogenetic tree aligns with known evolutionary relationships, particularly among rodents and mammals.

The physicochemical properties of the HBB protein indicate high stability and suitability for functioning in the aqueous environment of blood. The slight acidity and balanced hydrophobicity support its role in efficient oxygen binding and transport.

The divergence observed in the naked mole rat sequence may be associated with its unique physiological adaptations, such as tolerance to low-oxygen environments.

---

6. Conclusion

This study successfully performed an in-silico analysis of the human HBB gene and its protein product. The sequence was validated using BLAST, translated accurately, and analyzed for physicochemical properties. Comparative analysis across species demonstrated strong evolutionary conservation, reinforcing the functional importance of the HBB gene.

The phylogenetic analysis provided insights into evolutionary relationships and highlighted both conserved and divergent patterns among species.

---

7. Tools and Resources Used

- NCBI (Sequence Retrieval)
- BLAST (Sequence Alignment)
- ExPASy Translate Tool (Protein Translation)
- ProtParam (Protein Analysis)
- Clustal Omega (Multiple Sequence Alignment and Phylogenetic Tree)

---

8. Future Scope

- Mutation analysis of HBB (e.g., sickle cell mutation)
- Structural modeling of protein variants
- Inclusion of non-mammalian species for broader evolutionary analysis
- Functional impact analysis of amino acid substitutions

---
