# Mapping Cleaned Reads Worksheet

<!--- Write name below --->
## Name:

<!--- For this worksheet, answer the following questions --->

## Q1: What does it mean to map/align reads to a reference?
Answer:

It means to take sequencing data in short chunks called reads and determining where they fit along / originate from compared to a reference genome.

## Q2: What read mapper does the mapping_cleaned_reads.sh script use?
Answer:

minimap

## Q3: Both Illumina and Nanopore reads are used for this assignment. What are the major differences between the methodology used for these sequencing platforms?
Answer:

Illumina = fluorescent nucleotides are added to a DNA template / produces short reads

Nanopore = sequences are run through small pores and each nucleotide disrupts an electric current in a unique way / produces long reads

## Q4: What differences do you notice between the Illumina and Nanopre raw_data fastq file sizes? Which are larger?
Answer: 

Nanopore files are larger by quite a large margin (Nanopore's biggest = 88577293 bytes / Illumina's biggest = 17959855 bytes)

## Q5: What differences do you notice between the Illumina and Nanopore cleaned_reads fastq file sizes? Which are larger?
Answer:

Nanopore files are larger (Nanopore's biggest = 43743611 bytes / Illumina's biggest =  20719557 bytes)

## Q6: What explains the difference in your responses of Q4 and Q5? (HINT: Take a glimpse at the raw data .fastq files themselves)
Answer:

As mentioned in Q3, Nanopore sequencing produces much larger reads, with Nanopore sequences being around 1400 bases long & Illumina sequences being about 255 bases long.

## Q7: What is the average read depth for the Illumina data across all samples for the genomic regions that were mapped to?
Answer:

73494.4965

## Q8: What is the average read depth for the Illumina data across all samples for all genomic regions?
Answer:

5124.14242

## Q9: What is the average read depth for the Nanopore data across all samples for the genomic regions that were mapped to?
Answer:

490.896

## Q10: What is the average read depth for the Nanopore data across all samples for all genomic regions?
Answer:

125.0149138


