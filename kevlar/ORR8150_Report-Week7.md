Omar Rosad Ramirez
801-12-8150
CCOM-
Prof. H. Ortiz-Zuazaga

Lab Report : week Feb.25-Mar.1


**SUMMARY**

Hi, this is my first lab report. I haven't been in the lab for a few years so I'm going to take the time 
to brush up on the lingo, digest the article and just write whatever I'll find useful for my research.

This semester I'll be researching a framework that handles _de novo_ variant discovery without the need of
a reference genome.

As this is my last semester, I'll be focusing more on enhancing the code instead of trying to solve the 
problem at large. 



**DEFINITIONS**

**de novo mutation**: n alteration in a gene that is present for the first time in one family member as a result of a mutation in a germ cell (egg or sperm) of one of the parents or in the fertilized egg itself ;

**indels**: insertion and/or deletions of nucleotides into genomic DNA and include events less than 1kb in length ;**[1]**

**megabase**: a length of nucleic acid containing one million nucleotides ;

**elucidation**: clarification ;

**etiology**: cause, set of causes, or manner of causation of a disease or condition ;


**MISC COPY/PASTE**

The genetic heritability of many disorders is estimated to be relatively high ;

One hypthesis is that _de novo_ mutations (especially indels and structural variants) are a large source of causative variation--and consequently missing heritability-- in developmental dissorders ;


Many of the challenges withde novovariant prediction can be mitigated by an approach that compares sequencecontent between related individuals directly, rather than indirectly via a reference genome. Such an approach does notrequire any read alignments, nor is it sensitive to off-target shared/inherited variation. What a mapping-free approachdoesrequire is a signature of variation that is not defined in terms of alignment artifacts. In this mapping-free context,we define variants in terms of sequence content and abundance via analysis ofk-mers (sequences of a fixed lengthk).A similar idea was recently utilized for accurate discovery of somatic variants in cancer tumors18and indel discoveryin whole-exome sequencing data
