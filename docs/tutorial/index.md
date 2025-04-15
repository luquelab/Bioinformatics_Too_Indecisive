# Tutorial

The easiest way to use this pipeline is to run it in a Google Colab notebook. You can do so by using the "Open in Colab" button in the readme.md file.

### Load the sequences and install dependencies

```
!pip install biopython
from Bio import SeqIO
sequences = list(SeqIO.parse("sequences.fna", "fasta"))
```
This code installs BioPython, imports the SeqIO module, and loads all sequences from a FASTA file (sequences.fna) into a list of SeqRecord objects. Each SeqRecord contains sequence data and metadata like ID and description.

### Calculate sequence length and GC content

Sequence length and GC content are calculated and plotted.

![Image 1](image1.png)
![Image 2](image2.png)
![Image 3](image3.png)
