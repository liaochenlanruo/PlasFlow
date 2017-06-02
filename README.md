# PlasFlow 1.0
A set of scripts used for prediction of plasmid sequences in metagenomic contigs

Requirements:
- Python 3.5
- Python packages:
  - Scikit-learn 0.18.1 
  - Numpy
  - Pandas
  - TensorFlow
  - rpy2
- R 3.25 
- R packages:
  - Biostrings


PlasFlow can be easily installed as an Anaconda package from my Anaconda channel using:

conda install plasflow -c smaegol

To exclude the possibility of dependencies conflicts its encouraged to create spearate conda environment for Plasflow
using command: 

conda create --name plasflow python=3.5


PlasFlow accepts fasta files as input. Possible options are:

--input - specifies input  fasta file with assembly contigs to classify [required]

--output - should be tsv file with the tabular output of classification [required]

--threshold - manually specified threshold for probability filtering (default = 0.7)

