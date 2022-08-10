# CNN_classifier
## Background (why?): 
  A major issue with sequencing microbial samples is that it is hard to analyze  microbiome communities due to their composition; each of them are typically comprised of several source environments. This has given rise to many different types of microbial source tracking methods. Currently all methods of source tracking rely on some variations of abundance tables to train their classifiers. These processes can be time intensive and inconvenient.  Here we are attempting to create a new method, which does not rely on abundance tables and works directly from the fastq sequences

## Objective: 
  To create a novel tool that uses  deep learning to predict microbial composition metagenomic samples using only the raw fastq files. Once composition of samples are classified we will open up our "black box" to evaluate which kmers are being used to drive the decision for the classifications. This way we can gain insight into any evolutionary relationships that might have otherwise been unknown.
