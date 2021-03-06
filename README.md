# I-LBR: 
A Query-Specific Ligand-Binding Residue Identification based on protein sequence and support vector machine

## Pre-requisite:
    - Python, Java, Perl
    - SANN software (https://github.com/newtonjoo/sann)
    - NCBI nr90 database (ftp://ftp.ncbi.nlm.nih.gov/blast/db/FASTA/)

## Installation:

*Download I-LBR.tar.gz 
~~~
  $ tar xvzf I-LBR.tar.gz
  $ cd I-LBR
  $ java -jar I-LBR.jar "2w1aC" "EIDTLREEIDRLDAEILALVKRRAEVSKAIGKARMASGGTRLVHSREMKVIERYSELGPDGKDLAILLLRLGRGRLGH" null 0.3 ./tempfolder ./savefolder 4
~~~

*Edit the SANN_RUNNER_PATH and BLASTPGP_DB_PATH variable in the file “Config.properties”

## Update History:

- First release 2020-05-01

## References

[1] Jun Hu, Liang Rao, Xueqiang Fan, and Guijun Zhang. Identification of Ligand Binding Residues Using Protein Sequence Profile Alignment and Query-Specific SVM Model. Analytical Biochemistry. sumitted
