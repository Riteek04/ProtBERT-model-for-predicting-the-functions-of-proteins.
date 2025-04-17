# 🧬 Deep Learning on Protein Sequences using ProtBERT

## 📌 Project Overview

This project leverages **ProtBERT**, a deep learning model inspired by BERT, to understand and analyze **protein sequences** using techniques from **Natural Language Processing (NLP)**. ProtBERT treats protein sequences like text — where amino acids act like words — enabling powerful predictions and classifications in biological data.

## 👨‍🔬 Team Members

- Anshuman Rath – 22BAC10002  
- Pratham Verma – 22BAC10005  
- Riteek Panigrahi – 22BAC10012  
- M K Kiriti – 22BAC10016  
- Priyanshu Kumar Singh – 22BEC10006  
- Aman Singh – 22BEC10010  

## 🔍 Why ProtBERT?

ProtBERT applies NLP-based transformer models to protein sequences, allowing us to:

- 🔬 **Classify proteins** based on function  
- 🧲 **Identify binding sites** for drug interaction  
- 🧬 **Predict subcellular localization** (e.g., nucleus, mitochondria, cytoplasm)  
- 📈 Improve protein function analysis using deep learning

## 🧱 Protein Sequences & Amino Acids

- Proteins are composed of 20 amino acids, each with a unique side chain.
- Example sequence: `MKTAYIAKQRQISF`
- Each letter represents a specific amino acid.
- Understanding these sequences allows for insights into **function**, **structure**, and **disease targeting**.

## 🤖 How ProtBERT Works

ProtBERT is based on the **BERT architecture**:
- **Word Embeddings** → Represent amino acids as vectors  
- **Positional Encoding** → Maintains sequence order  
- **Self-Attention Layers** → Learns relationships between amino acids  
- **Masked Language Modeling** → Trains by hiding random amino acids and predicting them

## 📚 Dataset Information

- Source: **[UniProt](https://www.uniprot.org/)** – a widely used protein sequence database
- Format: **FASTA**
  - Header line (starts with `>`) contains metadata
  - Following lines represent the amino acid sequence

### 🔍 FASTA Example
```text
>sp|A0A087X1C5|CP2D7_HUMAN Putative cytochrome P450 2D7 OS=Homo sapiens OX=9606 GN=CYP2D7 PE=5 SV=1  
MGLEALVPLAMIVAIFLLLVDLMHRHQRWAARYPPGPLPLPGLGNLLHVDFQNTPYCFDQ…
```

- `sp` → Swiss-Prot (manually curated)  
- `A0A087X1C5` → Accession number  
- `CP2D7_HUMAN` → Protein name  
- `OS=Homo sapiens` → Organism source  
- `GN=CYP2D7` → Gene name  
- `PE=5` → Protein existence level  
- `SV=1` → Sequence version  

## 🚀 Future Scope

| Technique | Description |
|----------|-------------|
| Enhanced Predictive Accuracy | Training on larger datasets |
| Integration with Omics | Combine protein data with genomics, transcriptomics, etc. |
| Multi-Modal Training | Use structural + sequence data |
| Improved Interpretability | Add visualization tools for predictions |

## 🙌 Thank You!

This project showcases how **transformer-based models** can revolutionize **bioinformatics**, opening new doors in drug discovery, genomics, and molecular biology.
