ML applicataion on CRISPR data
===============================

# Data source

GUIDEseq_allgRNAs_identified.csv: Output cleavage frequency and corresponding chromosomal position identified by GUIDE-seq technique with 10 different gRNAs.
                                  This table is the output table from [guideseq](https://github.com/aryeelab/guideseq) package
                                  developed by [jounglab](http://www.jounglab.org/guideseq).

CIRCLEseq_allgRNAs_identified_matched.txt: Output cleavage frequency and correspoinding chromoslmal position identifed by CIRCLE-seq technique with 10 different gRNAs.
                                           This table is the output table from [circleseq](https://github.com/tsailabSJ/circleseq) package
                                           developed by [jounglab](http://www.jounglab.org/).

gRNAs.casoff.scores.csv: Output potential off-target sites with less than 7 mismatches against gRNA sequence
                         from input file `gRNAs.casoff.input` using published program [cas-offinder](https://github.com/snugel/cas-offinder).
                         The listed 10 gRNAs in `gRNAs.casoff.input` was the 10 gRNAs examined in the GUIDE-seq and CIRCLE-seq papers.



# Preprocessing
# Analyses
# Discussion

Features
--------

* TODO
