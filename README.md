# Long-read-preeclamptic
# Multi-Omics Data Preprocessing Pipeline for Preeclamptic Placentas

This repository contains the multi-omics data preprocessing and analysis pipelines for the study: **"Long-read transcriptome sequencing reveals isoform signatures in preeclamptic placentas"**. 

This project integrates Oxford Nanopore Technologies (ONT) long-read sequencing, Illumina short-read RNA-Seq, ATAC-seq, and Whole-Genome Bisulfite Sequencing (WGBS) to generate an isoform-resolved transcriptome of the human placenta.

## 📋 Data Availability
* **Raw Sequencing Data (In-house):** Deposited in the Genome Sequence Archive (GSA) at the BIG Data Center under accession number **HRA014329**.
* **Public RNA-Seq Data:** Integrated datasets from GEO under accession numbers **GSE154377** and **GSE163023**.

## 🛠 Prerequisites & Software
The following tools were used in this pipeline. Please ensure they are installed in your environment:
* **ONT RNA-Seq:** `chopper` (v0.9.0), `minimap2` (v2.28), `cDNA_cupcake` (v8.7.3), `SQANTI3` 
* **Short-read RNA-Seq:** `Trim-galore` (v0.6.10), `HISAT2` (v2.2.1), `Salmon` (v1.10.1), `featureCounts` (v2.0.6) 
* **ATAC-Seq:** `Trim-galore` (v0.6.10), `Bowtie2` (v2.5.4), `sambamba` (v1.0.1), `deepTools` (v3.5.5), `wiggletools` (v1.2.11), `bedtools` (v2.31.1)
* **WGBS:** `Trim-galore`, `Bismark` (v0.24.2), `DMRfinder` (v0.3) 

---
