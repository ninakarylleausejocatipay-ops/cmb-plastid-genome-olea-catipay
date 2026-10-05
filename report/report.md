# Characterization of the *Olea europaea* Plastid Genome

**Student Name:** Niña Karylle A. Catipay  
**Course & Section:** Cell & Molecular Biology  
**Assigned Genus:** *Olea*  
**Selected Species:** *Olea europaea* (Olive)  


## 1. Summary Table
| Parameter | Value |
| :--- | :--- |
| **Organism** | *Olea europaea* |
| **Family** | Oleaceae |
| **NCBI Accession** | `NC_013707.2` |
| **Genome Size** | 155,888 bp |
| **GC Content** | 37.8% |
| **Topology** | Circular |
| **LSC Size** | 85,528 bp |
| **SSC Size** | 17,856 bp |
| **IR Size (IRa / IRb)** | 26,252 bp (each) |
| **Total Annotated Genes** | 130 |
| **Protein-Coding Genes (CDS)** | 85 |
| **tRNA Genes** | 37 |
| **rRNA Genes** | 8 |


## 2. Answers to Lab Questions

### Question 1: Organism Information
* **Scientific Name:** *Olea europaea*
* **Family:** Oleaceae
* **NCBI Accession/Version:** `NC_013707.2`
* **Database Source:** NCBI RefSeq
* **Complete Plastid Genome Size:** 155,888 bp

### Question 2: Evidence of Complete Plastid Genome
The sequence represents a complete, circular plastid genome because it displays the complete, conserved quadripartite architecture (LSC, SSC, and two Inverted Repeats) with a total length of 155,888 bp. It encodes a full functional set of photosynthetic and ribosomal genes rather than a partial barcode fragment (like *rbcL* or *matK* alone) or nuclear mitochondrial/plastid DNA insertions.

### Question 3: Genome Organization
Yes, *Olea europaea* contains the typical quadripartite structure:
* **Large Single-Copy (LSC):** 85,528 bp
* **Small Single-Copy (SSC):** 17,856 bp
* **Inverted Repeats (IRa & IRb):** 26,252 bp each

### Question 4: Gene Content & Inverted Repeat Duplication
* **Total Genes:** 130
* **Protein-Coding Genes:** 85
* **tRNA Genes:** 37
* **rRNA Genes:** 8
* **Pseudogenes:** None reported in this RefSeq record.
* **IR Duplication:** Genes within the Inverted Repeat regions (e.g., ribosomal RNA genes *rrn16*, *rrn23*, *rrn4.5*, *rrn5*, and CDS like *ndhB*) exist in two identical copies because the entire IR segment is duplicated symmetrically across the circular genome.

### Question 5: Functional Classification of Selected Protein-Coding Genes
1. **`psaA`** (Photosystem I): Encodes Photosystem I P700 chlorophyll a apoprotein A1 involved in light-driven primary electron transport.
2. **`psbA`** (Photosystem II): Encodes the D1 reaction center protein of Photosystem II.
3. **`atpA`** (ATP Synthase): Encodes the alpha subunit of the CF1 ATP synthase complex.
4. **`petA`** (Cytochrome b6f): Encodes Cytochrome f involved in electron transfer between PSII and PSI.
5. **`rbcL`** (Carbon Fixation): Encodes the large subunit of RuBisCO responsible for primary CO₂ fixation.
6. **`rpoA`** (RNA Polymerase): Encodes the alpha subunit of plastid-encoded RNA polymerase (PEP).
7. **`rps12`** (Ribosomal Protein): Encodes 30S ribosomal protein S12 required for translation.
8. **`clpP`** (Protease): Encodes the ATP-dependent Clp protease proteolytic subunit for protein degradation.

### Question 6: RNA & Intron Features
* **rRNA Genes:** Four core ribosomal RNA loci (*rrn16*, *rrn23*, *rrn4.5*, *rrn5*), all duplicated within the IR regions.
* **tRNA Genes:** Transfer RNAs including *trnH-GUG*, *trnK-UUU*, and *trnL-UAA*.
* **Intron-Containing Genes:** Features group II introns in coding genes such as *clpP*, *atpF*, and *ndhA*.

### Question 7: Rearrangements or Notable Structural Features
The *Olea europaea* plastome shows high structural conservation typical of core angiosperms without significant structural inversions, gene losses, or rearrangements.

### Question 8: GC Content & Notable Sequence Observations
* **GC Content:** 37.8% (with a higher concentration of GC bases in the rRNA/tRNA genes within the IR regions).
* **Observations:**
  1. The complete genome is represented as a single contiguous circular sequence record in Galaxy (Scaffold len_max = 155,888 bp).
  2. The *trnK-UUU* tRNA gene harbors a large intron containing the open reading frame for the *matK* (maturase K) gene.


## 3. Plastid vs. Mitochondrial Genome Comparison Table

| Feature | Plastid Genome | Mitochondrial Genome |
| :--- | :--- | :--- |
| **Cellular Location** | Chloroplast / Plastid stroma | Mitochondrial matrix |
| **Main Biological Functions** | Photosynthesis, fatty acid and amino acid biosynthesis | Cellular respiration (ATP synthesis via oxidative phosphorylation) |
| **Typical Genome Organization** | Single circular chromosome with conserved quadripartite structure (LSC-IRa-SSC-IRb) | Highly variable; multi-chromosomal, linear, circular, and branched networks |
| **Relative Genome Size** | Uniform and compact (~120–170 kb in green plants) | Highly variable and large in plants (~200 kb to >11 Mb) due to non-coding expansion |
| **Gene Content** | Highly conserved (~110–130 genes) | Relatively few coding genes (~30–60 genes) despite large overall genome size |
| **Copy Number** | Very high (thousands of copies per plant cell) | Moderate to high (hundreds of copies per plant cell) |
| **Inheritance** | Predominantly maternal in most angiosperms | Predominantly maternal in most angiosperms |
| **Recombination / Structural Change** | Low structural rearrangement rate; highly conserved gene order | High rate of active homologous recombination causing structural chimeras |
| **Mutation / Substitution Pattern** | Moderate nucleotide substitution rate | Very low point mutation rate in plant mitochondria, but high structural rearrangement rate |
| **Common Research Applications** | Plant phylogenetics, DNA barcoding, plastid transformation / biotechnology | Evolutionary dynamics, cytoplasmic male sterility (CMS) studies in crops |


## 4. Research Value, Advantages, & Limitations

### Advantages over Nuclear Genome:
1. **High Copy Number:** High abundance per cell simplifies PCR amplification and sequencing from degraded tissue.
2. **Uniparental Inheritance:** Lacks meiotic recombination, allowing clear maternal lineage tracing.
3. **Conserved Structure:** Facilitates straightforward universal primer design and cross-species alignment.
4. **Haploid Nature:** Avoids heterozygosity complications encountered during nuclear assembly.

### Limitations:
1. Reflects only single-parent evolutionary history (cannot detect hybrid speciation or nuclear gene flow).
2. Slower nucleotide evolution rate limits resolution at extremely fine population/subspecies scales.

### Practical Research Applications:
* **Plastid Data Preferred:** Resolving deep evolutionary relationships and plant family phylogenetics (e.g., establishing relationships among angiosperm clades using whole plastomes).
* **Nuclear Genomic Data Preferred:** Studying recent speciation, hybridization, gene flow, or traits governed by polygenic nuclear loci (e.g., mapping drought-tolerance QTLs in crop breeding).
