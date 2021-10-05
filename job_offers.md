**M2 internship: mapping methods for new long read probing data**

**Context:**
RNA molecules harbor structures, identifiable through domains such as hairpin loops or bulges. 
**Identifying and resolving such RNA structures** is a key to our understanding of structure and complexes mediated functions, 
and therefore important advances in molecular biology. 
For instance, recent studies have characterized the structure of RNA viruses (such as SARS-CoV2). 
Different bioinformatics communities shed complementary lights on RNA structure analysis analysis of sequencing data. 
First, the field studying *RNA structure prediction*, based on *probing data* [1], 
uses data produced with reagents that specifically interact with structured (unpaired) positions in the RNA. 
Second, the field working on **high throughput sequencing**, produces efficient algorithms scaling to genome-scale read datasets. 
This project ambitions to develop tighter communication between these two communities.

**Approach:**
Starting from a very recent probing protocol based on **Oxford Nanopore long reads** [2], we have direct access to reactive nucleotides. 
The yielded reads require to be mapped on a genomic reference in order to be processed. 
Then, the successfully mapped reads are used to compute a statistical analysis of counts, then derive quantitative signals; 
and to construct structural models. However, Nanopore’s base-calling has to handle a versatile and complex signal, 
which leads to **reads that are difficult to align to a reference**. 
For mapping noisy, long reads, seed-and-extend algorithms have been complemented by techniques based on ordering minimizers sketches [3]. 
We are interested in the possible **current shortcomings of these methods**: they have been primarily designed to focus on large overlaps for assembly purposes, they require long sequences for high efficiency, and they are not tuned to target high sensitivity.

**Goals:**
This internship project aims at **exploring the mapping methods for new long read probing data**, providing a thorough analysis of their pros and cons, 
and possibly initiating a new method tailored for structure data.

**Perspectives:**
This internship will give the student a quite unique opportunity to work at the **interface between sequence data analysis and structure characterization**, 
on a novel topic. The student will gain expertise with long reads, latest mapping algorithms and their connection to RNA structure. 
The consortium in which this project takes part has secured funding and will potentially **fund a PhD** after the internship is completed.

**Team, location and facilities:**
The internship is based in **Lille, France for a six-months duration**, starting from the **beginning of 2022**. It is compensated. 
The candidate will work in the Bonsai team http://www.lifl.fr/bonsai/, an expert team in the design of efficient methods and data structures 
for processing high-throughput, including long read, sequencing data.
This project is part of a **consortium involving four teams**: BONSAI ; AMIBio team in LIX, (Ecole Polytechnique, France) – 
RNA structure specialists ; and CiTCoM and LCBPT teams ( Université de Paris, France) for the biochemistry and cellular biology expertise. 
The candidate will benefit from contacts with the consortium, and in particular the internship is meant to be led in close interaction with AMIBio.

**Candidate:**
We are looking for a master student with a bioinformatics/CS major (though we keep an open eye on applications with different profiles). 
A CS/programming background is strongly encouraged, as well as previous experience with RNA-seq or probing data.


**Contact:**
Camille Marchet camille.marchet@univ-lille.fr

**References:**

[1]  N. A Siegfried, S Busan, G. M Rice, J. A Nelson, and K. M Weeks. RNA motif discovery by shape and mutationalprofiling (shape-map).Nature methods, 11(9):959–965, 2014

[2] J. G. A Aw, S. W Lim, J. X Wang, F. R. P Lambert, W. T Tan, Y Shen, Y Zhang, P Kaewsapsak, C Li, S. B Ng, L. AVardy, M. H Tan, N Nagarajan, and Y Wan. Determination of isoform-specific RNA structure with nanopore long reads.Nature biotechnology, 39:336–346, 2021

[3] H Li. Minimap2: pairwise alignment for nucleotide sequences.Bioinformatics, 34(18):3094–3100, 2018
