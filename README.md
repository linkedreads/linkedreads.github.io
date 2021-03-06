# Linked-Reads Community Challenge Overview

### Organizers:
- [Melissa Gymrek](https://gymreklab.github.io/), UCSD
- [Aaron Quinlan](http://quinlanlab.org/), University of Utah
- [Valerie Schneider](https://www.linkedin.com/in/valerie-schneider-45aa82b4/), NCBI
- [Michael Schatz](http://schatz-lab.org), Johns Hopkins University

Linked-reads, also called read-clouds, are a powerful new datatype that blends many of the advantages of low-cost highly-accurate short-read sequencing with the advantages of long-reads. Several high profile applications have been published using this new datatype, including [GrocSV](https://www.nature.com/articles/nmeth.4366) for highly accurate structural variation detection, [SuperNova](https://genome.cshlp.org/content/27/5/757) for phased de novo genome assembly, or [HapCut2](https://genome.cshlp.org/content/27/5/801.full) for highly accurate phasing, each showing substantial improvements over regular short-read sequencing. However, as impressive as these applications are, we feel more could be done from the academic community to further optimize methods for this type of data. To try to promote these developments, we are starting the Linked-reads Community Challenge (LRCC), a DREAM-like challenge to promote methods development. Under the LRCC, we will release a few linked-reads datasets to the community, so that different groups can contribute analysis results for evaluation. The final results will be presented in a capstone publication, although method developers are free to use the data for their own papers without restriction. 

For the first community challenge, we are focusing on germline genome analysis, and the analysis will examine accuracy in SNP, indel, and SV calling, along with phasing and personalized phased genome construction. Our evaluation will include a few different approaches, including concordance to deep coverage PCR-free libraries, trios and larger pedigrees to look at Mendelian concordance, targeted resequencing over variants of interest, and potentially concordance to long read sequencing (PacBio and/or ONT). We are planning to release the data in two phases, first a few well known samples (NA12878, GIAB, etc) to establish the analysis protocols with ample training data, and then a set of novel genomes, ideally one or more multigenerational pedigrees with a disease focus. We are aiming to release the phase one dataset by the end of this year and then the phase two genomes early next. The winners will be announced in 2020, with a variety of prizes awared.

### Evaluate accuracy across a range of categories
- Detection of SNPs, Indels, & SVs
- Phased variants & Personalized genome construction
- Separate benchmarking for simple and complex regions
- Reproducible software & workflows

### Evaluation Approaches
- Concordance with deep coverage PCR-free short read libraries
- Large-scale targeted resequencing of selected variants to high coverage
- Trios and larger pedigrees to assess phasing, Mendelian concordance
- Orthogonal sequencing including PacBio and/or Oxford Nanopore

### Data Coordination
- Evaluation guidelines posted through [contest website](http://linkedreads.github.io)
- Sequencing data will be hosted at [Basespace](https://basespace.illumina.com)
- Contest leaderboard in development

### Contest Timeline

#### Phase 1: Known samples
  - Phase 1 will be released later this year
  - Phase 1 winners announced late 2019

#### Phase 2: Novel samples
  - Phase 2 to be released in early 2019
  - Phase 2 winners announced in early 2020

#### Publication Plans
  - Capstone paper to be submitted for publication in 2020
  - Researchers are free to use the data for their own papers at any time
  
### More Information
- Follow this page on [github](https://github.com/linkedreads/linkedreads.github.io)
- Follow us on [twitter](https://twitter.com/linkedreads)
- Email us at linkedreads @ gmail.com







