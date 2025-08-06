# RNA-seq Analysis and Python Script

This repository contains two main components:

- `genomic_feature.txt`: A Python script to extract specific genomic sequences from FASTA files using GTF annotations. Usage instructions are included within the script.
- `RNA_seq_Analysis_of_Skin_Cancer.pdf`: A transcriptomic analysis report prepared in Overleaf as part of academic training.

## Test Files Included

To facilitate testing of the Python script, two small example input files are also provided:

- `mini_genome.fasta`: A simplified FASTA file with mock genomic data.
- `mini_annotations.gtf`: A corresponding GTF annotation file.

These files allow you to validate the script's functionality in a controlled environment.

## How to Use

1. Rename `genomic_feature.txt` to `genomic_feature.py`.
2. Ensure you have Python 3 installed.
3. Open a terminal and navigate to the repository directory.
4. Run the script using the example files:

   ```bash
   python genomic_feature.py --fasta mini_genome.fasta --gtf mini_annotations.gtf --features gene --output output.fasta
5. Check the output in output.fasta for the extracted sequences.

---

**Author:** María José Zaruma Delgado  
**Contact:** mzaruma.d@gmail.com

