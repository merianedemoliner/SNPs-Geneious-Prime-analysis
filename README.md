# SNPs-Geneious-Prime-analysis
Multi-sequence mutations analyzer from individual annotation tables generated by calling SNPs analysis in Geneious Prime software.

##### First step:
Create the **mutation** column with the annotation of the amino acid exchange.  
E.g.: reference sequence amino acid + amino acid position + amino acid of sample sequence.

![image](https://github.com/merianedemoliner/SNPs-Geneious-Prime-analysis/assets/70864956/2f2a5992-1b0d-4fe7-a358-0fc3a14e4d40)

##### Second step:
Filter all changes that appear in the reads at a **frequency** equal to or less than 80% and where the protein effect is equal to *substitution*. Create a table a new considering the columns: gene, Amino Acid Change, CDS Position, Variant Frequency, Variant Frequency 1, Variant Frequency 2, and AA Position. Unnamed columns can be ignored.


![image](https://github.com/merianedemoliner/SNPs-Geneious-Prime-analysis/assets/70864956/0fb86032-ea40-4939-a06e-78dd998369ac)

##### Step3:
Generate a table with the mutations of all samples, considering one mutation per line. Note that each column is a sample.

![image](https://github.com/merianedemoliner/SNPs-Geneious-Prime-analysis/assets/70864956/0c5aa653-0bf6-42ba-918e-24b344661a3f)

