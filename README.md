# Detect Tails from Cigar


## Detection of polyadenylation and uridylation in RNA-seq data

Polyadenylation plays a crucial role in transcript maturation, and it is widespread in eukaryotic mRNA. We prepared the script that helps to detect polyadenylation in the available RNA-seq sequencing data sets. The tool combined Python script with commonly used genomic tools samtools, bamtools). 

Input:
   * data after alihnment in sam format,
   * references in bed format.
 
Output:
   * data frame (table) in csv format containing read IDs, gene IDs, information about 3' tails. 
