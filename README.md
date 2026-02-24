# Bioinformatics Fundamentals Portfolio 🧬

This repository serves as a growing collection of fundamental bioinformatics algorithms and simulations, implemented in Python.

## 📂 Projects

### 1. Central Dogma Simulation (DNA -> Protein)
* **File:** `01_central_dogma_simulation.ipynb`
* **Description:** A simulation of the biological information flow. Converts DNA sequences to mRNA and then translates them into protein chains using the standard genetic code.
* **Key Concepts:** Transcription, Translation, Codon Mapping.

### 2. SARS-CoV-2 Genome Analysis 🦠
* **File:** `02_covid_genome_analysis.ipynb`
* **Description:** Analysis of the SARS-CoV-2 Spike Protein gene using the **Sliding Window Algorithm**.
* **Visualization:** Plots GC content fluctuations to identify genetically stable vs. unstable regions (potential mutation zones).
* **Tech Stack:** `Biopython`, `Matplotlib`, `NumPy`.

### 3. NGS Data Quality Control (FASTQ Analysis) 🧬
* **File:** `03_ngs_data_quality_control.ipynb`
* **Description:** A Quality Control (QC) pipeline for Next-Generation Sequencing (NGS) data.
    * **Simulation:** Generates synthetic FASTQ reads mimicking Illumina sequencing errors (quality drop-off at read ends).
    * **Analysis:** Calculates **Phred Quality Scores** per base position to assess sequencing reliability.
* **Visualization:** Generates boxplots to identify low-quality reads that require trimming (similar to FastQC reports).
* **Tech Stack:** `Biopython`, `Seaborn`, `Pandas`.

### 4. Clinical Variant Analysis (VCF Parsing & SNV/Indel) 🧬🏥
* **File:** `04_clinical_vcf_analysis.ipynb`
* **Description:** A clinical bioinformatics pipeline designed to parse and analyze Variant Call Format (VCF) data.
    * **Variant Detection:** Extracts and classifies mutations into **SNVs** (Single Nucleotide Variants) and **INDELs** (Insertions/Deletions).
    * **Quality Filtering (QC):** Filters out low-quality (`LowQual`) reads to eliminate false positives and ensure data integrity.
    * **Clinical Interpretation:** Cross-references variants to identify clinically significant mutations (e.g., Pathogenic BRCA1).
* **Tech Stack:** `Pandas`, `Matplotlib`, `Seaborn`.

### 5. Probability of Mutation in DNA Sequencing (Statistical Modeling) 📊🧬
* **File:** `05_Probability_of_Mutation_in_DNA_Sequencing.ipynb`
* **Description:** An intersection of statistics and genetics. This project models the randomness of biological systems using the **Binomial Distribution** to calculate mutation probabilities across large DNA sequences.
    * **Case Study:** Simulates a 10,000 base-pair sequence to calculate the exact probability of observing a specific number of background mutations using the Probability Mass Function (PMF).
    * **Disease Risk Estimation:** Utilizes the Cumulative Distribution Function (CDF) for **Anomaly Detection**, identifying when a high mutation count is statistically significant (p-value evaluation) and potentially indicative of pathogenic factors or external mutagens.
    
* **Tech Stack:** `SciPy`, `NumPy`, `Matplotlib`.
---

## 🛠️ Tools & Libraries
* **Python:** 3.13.9
* **Biopython:** For biological sequence manipulation.
* **SciPy & NumPy:** For statistical modeling and numerical operations.
* **Matplotlib & Seaborn:** For data visualization.
* **VSCode Notebook:** For interactive analysis.

## 👨‍💻 Author
**Emre Engin** | Developer & Aspiring Bioinformatician
*Goal: Bridging Biology and Computer Science.*
