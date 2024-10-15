# albatross-mitogenomes
Variant calling from population samples of Antipodean and Gibson's albatross (_Diomedea antipodensis antipodensis_ & _D. a. gibsoni_) aligned to a reference genome (see albatross-refgenomes for assembly and alignment),  and multiple sequence alignment.

Variant calling uses the Genome Analysis ToolKit (GATK) joint genotyping approach. 
Reads are filtered with BCFtools. 
Consensus FASTA sequences for all individuals in the populations are created using GATK's FastaAlternateReferenceMaker.
All sequences are aligned using MAFFT multiple sequence alignment. 
