# XMLgenerator_v1
XMLgenerator_V1 is a Python script designed to generate structured XML files for BEAST v1.10.4. The tool provides flexibility for creating custom XML programmatically.

Run the script:
<code>python XMLgenerator_v1.py [-o OUTPUT] [-t TEMPLATE] [-f FASTA] [-g GFF] [-p PRIORS] [-m MCMC] [-l LOG]</code>

Optional arguments:

<code>
-h, --help                             [show this help message and exit.]
-o OUTPUT, --output OUTPUT             [The output XML file.]
-t TEMPLATE, --template TEMPLATE       [The XML template file.]
-f FASTA, --fasta FASTA                [The aligned fasta file.]
-g GFF, --gff GFF                      [The gff annotation file.]
-p PRIORS, --priors PRIORS             [The priors table in csv format.]
-m MCMC, --mcmc MCMC                   [The MCMC chain length.]
-l LOG, --log LOG                      [Write the log file.]
</code>
