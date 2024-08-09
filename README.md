# 2G_Platform

The aim of this project is to set up a platform to manage Data related to Dengue virus genomic surveillance in Senegal.
It should be accessible through access and all entry data have to be accessible in real time.

The platform should host on database with differents columns including ;

1.
SampleID, Region of Collection, Age, Sex, Sequencing Method, FastaSeq (Containing the fenomic sequence)

.2
According to Selected SampleID the user should be also able to Download their corresponding Fasta sequences in a Single fasta file.
The fasta file should contain ; \
'>' SampleID 1 \
Sequence 1 \
'>' SampleID 2 \
Sequence 2 \
.......... \
.......... \
'>' Sample ID n \
Sequence n 


**Used Tools**
The backbone of the tool will be **duckdb** software
