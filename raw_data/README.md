Raw Data
---------

This file should contain records of all raw data relevant to this project.\s\s
# Discription of raw data
The tar ball contains files:
  - CIRCLE-seq: `CIRCLEseq_allgRNAs_identified_matched.txt` Cleavage events observed by CIRCLE-seq technique in vitro.
  - GUIDE-seq: `GUIDEseq_allgRNAs_identified.csv` Cleavage events observed by GUIDE-seq technique in cell line HEK293T and U2OS.
  - cas-offinder: `gRNAs.casoff.socres.csv` Lists of sequence with no more than 6 mismatches given gRNA were retrieved using cas-offinder in GRCh37. 10 gRNAs used as input of cas-offinder examined in both CIRCLE-seq and GUIDE-seq.

** Note: the TRUE NEGATIVE INSTANCE has to be done by getting the UNIQUE list of `gRNAs.casoff.socres.csv` compared with CIRCLE-seq/GUIDE-seq results; in another word, one should excludes the off-target sites observed by CIRCLE-seq/GUIDE-seq to acquire the TRUE NEGATIVE INSTANCE.\s\s


This includes meta-data like:
  - Source (person, website, experiment)
  - Any relevant version info
  - Date
  - Any hand-processing required
  
---------------------------
