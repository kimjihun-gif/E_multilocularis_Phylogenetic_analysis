# Supplementary_Pipeline_Blast

This repository contains the full analysis pipeline used for phylogenetic investigation of *Echinococcus multilocularis* based on the mitochondrial **cox1** gene.

It accompanies the manuscript:  
**"cox1-Based Phylogenetic Analysis Reveals Sichuan-Origin Lineage of Echinococcus multilocularis in a Korean AE Case"**

---

## 📌 Purpose

To automate the retrieval, filtering, and alignment of *E. multilocularis cox1* sequences for maximum likelihood phylogenetic analysis.

---

## 🧪 Features

- Retrieves GenBank sequences using NCBI BLAST API (via Biopython)  
- Extracts annotated **cox1** CDS regions (≥1000 bp)  
- Performs multiple sequence alignment with **Clustal Omega**  
- Outputs an alignment file (`aligned.fasta`) compatible with **IQ-TREE** phylogenetic software  

---

## 🛠 Requirements

This script is intended to run in **Google Colab** or a **Linux-based Python 3** environment.

Install dependencies:

```bash
pip install biopython
sudo apt-get install -y clustalo
