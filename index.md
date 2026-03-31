# Bio / topics

I am a **research associate in [BONSAI](https://www.cristal.univ-lille.fr/bonsai/) team (Lille, France)**. My work focuses on **methods and data structures** in **sequence bioinformatics**, with applications to **RNA** in particular.

_Je suis chargée de recherche au CNRS dans l'équipe [BONSAI](https://www.cristal.univ-lille.fr/bonsai/) (Lille, France). Je travaille sur des méthodes et structures de données dédiées à la bioinformatique des séquences, avec souvent des applications à l'ARN._

_Intéressé.e par une formation à la bioinformatique pour les données de séquençage ? Le CNRS propose une formation à Lille (labos/entreprises) : [lien](https://cnrsformation.cnrs.fr/index.php?c=stage&stage=23283_)._

After an engineer degree in Bioinformatics from INSA de Lyon and a MsC in Ecology and Evolution from Université Claude Bernard Lyon 1, I worked for two years as an engineer in [ERABLE](https://team.inria.fr/erable/en/) team (LBBE, Lyon) with [Vincent Lacroix](https://lbbe.univ-lyon1.fr/-Lacroix-Vincent-.html?lang=fr). I obtained a PhD funding in [GenScale](https://team.inria.fr/genscale/) team (Rennes, France), where I was supervised by [Pierre Peterlongo](http://people.rennes.inria.fr/Pierre.Peterlongo/). I defended my PhD in 2018 and joined [BONSAI](http://www.lifl.fr/bonsai/) in the CRIStAL lab  afterwards as a postdoc. Lately I was recruited by the CNRS to work as a researcher in the same lab ([CV](cv.md)). 

My postdoc took part in [Transipedia ANR](https://anr.fr/Project-ANR-18-CE45-0020), with [Rayan Chikhi](http://rayan.chikhi.name/) and [Mikaël Salson](https://mikael-salson.univ-lille.fr/). Transipedia aims at being a transcriptome-encyclopedia, e.g., facilitating indexing, query and exploitation of the numerous publicly available RNA-seq data. I am mostly working on new data structures to index large collections of NGS datasets. 
Before and during my PhD I worked on methods for transcriptomics, in particular for _de novo_ variants discovery and RNA long read analysis.

# Job offers

- no job offer at the moment
  

## News

- Launch of the thematic year **“L’ADN dans tous ses états”** (2026–2028), dedicated to DNA and computer science  
  https://ddal.inria.fr/adn_etat/

- Recent team developments:
  - Rémi Morvan joined as a postdoctoral researcher (2026, ANR Find-RNA / D-DAL collaboration)  
  - Klara Sladeckova joined as a PhD student (2025, co-supervised with Helsinki/WILL Chair)  
  - Lore Depuydt joined as a postdoctoral researcher (2025, WILL Chair)
  - new MsC interns in 2026: Simon Lecocq and Younes Aghamiri

- With Simon Puglisi’s group (University of Helsinki) we were granted an **WILL international chair (BOSSA)**  
	- recent preprint of the collaboration: [https://www.biorxiv.org/content/10.64898/2026.03.15.711907v1](https://www.biorxiv.org/content/10.64898/2026.03.15.711907v1)

- Recent research:
  - very fast fasta parser with SIMD optimization by Igor Martayan: [https://www.biorxiv.org/content/10.64898/2026.03.19.712912v1.abstract](https://www.biorxiv.org/content/10.64898/2026.03.19.712912v1.abstract)
  - hierarchical and multi-k index with application to chromosomal mapping: [https://www.biorxiv.org/content/10.64898/2026.03.15.711907.abstract](https://www.biorxiv.org/content/10.64898/2026.03.15.711907.abstract) led by Jarno Alanko
  - Paper accepted at **RECOMB 2026** on minimizer density models  [https://www.biorxiv.org/content/10.1101/2025.11.21.689688v2.abstract](https://www.biorxiv.org/content/10.1101/2025.11.21.689688v2.abstract)
  - [REINDEER2](https://www.biorxiv.org/content/10.1101/2025.06.16.659990v1) presented at **SPIRE 2025**  
  - Updated preprint on **Vizitig** (interactive exploration of sequence graphs):  
    [https://www.biorxiv.org/content/10.1101/2025.04.19.649656v2](https://www.biorxiv.org/content/10.1101/2025.04.19.649656v2 ) by Bastien Degardins

- Conferences:
  - Bonsai will organize **DSB 2027** in Lille
  - We invite you to attend **Genome Informatics 2026** in Hinxton
  - Meet me at **SPIRE 2025**  
  - Co-chair of **Genome Informatics (2025–2026)** and **RECOMB-Seq (2025)**, see you in Seoul.

- Recent publications:


---

## Career

- 2025: Habilitation à diriger des recherches
- Since 2021: **CNRS researcher (CRCN)** at CRIStAL (Université de Lille), working within the BONSAI team on sequence data structures and bioinformatics  
- 2018–2020: Postdoctoral researcher in BONSAI, working on indexing methods for large RNA-seq datasets (Transipedia project)  
- 2019: Visiting researcher at EMBL-EBI (Cambridge), collaborating on large-scale sequence indexing  
- 2018: PhD in Computer Science, University of Rennes (GenScale team), supervised by Pierre Peterlongo  
- 2013–2016: Engineer in bioinformatics and MSc in Ecology and Evolution (INSA Lyon, Université Lyon 1)  
- 2025: **Habilitation à diriger des recherches (HDR)**, Université de Lille  

---

# Research themes

My research lies at the intersection of **algorithms, data structures, and sequence bioinformatics**, with a particular focus on large-scale sequencing data and RNA-related applications. It combines methodological developments, software design, and applications to real datasets, often in interdisciplinary and international collaborations.

## Data structures for large-scale sequencing data

A central part of my work focuses on the design of **compact and scalable data structures** for indexing and querying large collections of sequencing datasets, in particular through **k-mer representations**.

This work is developed within projects such as **Find-RNA (ANR JCJC, PI)** and **Full-RNA**, and builds on earlier work in **Transipedia**. It has led to several tools, including [REINDEER](https://github.com/kamimrcht/REINDEER), [REINDEER2](https://github.com/Yohan-HernandezCourbevoie/REINDEER2), [CBL](https://github.com/imartayan/CBL), and [PAC](https://github.com/Malfoy/PAC), which enable scalable exploration of thousands of sequencing datasets.


## Graph-based models, pan-transcriptomics and pangenomics

Another major direction of my research concerns **graph-based representations of sequences**, in particular **de Bruijn graphs**, which are central to pangenomics and reference-free approaches.

This work has been supported by projects such as **ALPACA ITN**, and is connected to national and international initiatives structuring the field. In particular, I contribute to **MIGGS** (Methods for Interfacing with Graphs of Genomic Sequences), a community focused on graph-based genomic data, and to networks such as **GET-a-Pan** and **RECENT**, which foster interactions between bioinformatics and theoretical computer science.

It involves collaborations with groups in Cambridge, Helsinki, and Stockholm, and includes algorithmic contributions to dynamic and updatable graphs (e.g. [Cdbgtricks](https://github.com/khodor14/Cdbgtricks)) as well as ongoing work on visualization and interaction, including **Vizitig**:  
https://www.biorxiv.org/content/10.1101/2025.04.19.649656v2

## RNA and transcriptomics applications

My work is strongly motivated by applications to **RNA sequencing and transcriptomics**, both in methodological developments and in collaboration with domain scientists.

I have worked on problems such as _de novo_ transcript discovery, long-read RNA analysis, and large-scale exploration of RNA-seq datasets, including cancer-related data. These applications are central to projects such as **Full-RNA** and **ESCALATE**, and involve close interactions with biological and medical partners.

This work includes the development of tools such as [REINDEER](https://github.com/kamimrcht/REINDEER) and [REINDEER2](https://github.com/Yohan-HernandezCourbevoie/REINDEER2), as well as collaborative studies on large transcriptomic datasets.

## Algorithms for sequence analysis

Beyond specific data structures, I am interested in the design of **efficient algorithms for sequence analysis**, including sketching techniques, hashing-based methods, and sampling strategies.

This work connects to projects such as **INSSANE (ANR)** on RNA structure analysis, and includes contributions on minimizers, sketching, and sequence indexing.

---

## Team and supervision

- **PhD students**
  - Klara Sladeckova (since 2025, co-direction with University of Helsinki): data structures and lower bounds for k-mer membership  
  - Bastien Degardins (since 2024, co-direction with Charles Paperman): integration of de Bruijn graphs in databases and visualization (best presentation award, JOBIM mini symposium 2025)  
  - Igor Martayan (since 2023): locality-preserving representations of k-mer sets  
  - Fiona Hak (since 2024, co-supervision with Daniel Gautheret and Mélina Gallopin): RNA analysis methods for cancer (best poster award, JOBIM 2025)  

- **Postdoctoral researchers and engineers**
  - Lore Depuydt (since 2025, WILL Chair): compressed sequence indexes and locality properties  
  - Rémi Morvan (since 2026, ANR Find-RNA / with Inria D-DAL team): query abstractions and graph-based structures  
  - Florian Ingels (2022–2025, ANR Full-RNA): combinatorics and sequence sampling  
  - Lucas Robidou (2025–2026, engineer / with I2BC): development of REINDEER2 and associated tools  

- **Former PhD students**
  - Khodor Hannoush (PhD 2024 with Pierre Peterlongo in GenScale team, Rennes): dynamic pangenome graphs, now at Illumina  
  - Thomas Baudeau (PhD 2025): long-read mapping for structural variants, currently postdoctoral researcher  

- **Supervision activity**
  - Around ten Master’s students supervised since 2019, several continuing as PhD students  
  - Participation in PhD committees and mentoring within the laboratory  

## Collaborations and networks

My research is developed within a structured network of collaborations at local, national, and international levels, often at the interface between **algorithms, bioinformatics, and genomics**. These collaborations are largely organized through joint projects, and support both methodological developments and applications.

- **Local collaborations (Lille)**  
  I work closely with colleagues in Lille, in particular:
  - **Charles Paperman** (D-DAL, Inria), on database approaches and querying of graph-structured data  
  - **Antoine Limasset** (BONSAI), on sequence indexing, k-mer data structures
  - **Mikaël Salson** (BONSAI), on RNA-seq analysis and large-scale k-mer methods  

- **National collaborations (ANR projects and consortia)**  

  - **Transipedia (ANR)**  
    A consortium dedicated to indexing and exploring large collections of RNA-seq datasets, in collaboration with teams in Montpellier, Toulouse, and Paris. This project led to several tools and publications, and to long-term collaborations with both algorithmic and biomedical groups.

  - **INSSANE (ANR, site coordinator)**  
    A project on computational methods for RNA structure analysis, involving collaborations with LIX, Université Paris Cité, and other partners. This project connects algorithmic questions with RNA biology and structural analysis.

  - **Full-RNA (ANR)**  
    A project focused on indexing large-scale RNA datasets, involving collaborations with several French bioinformatics groups and supporting developments such as REINDEER2.

  - **Find-RNA (ANR JCJC, PI)**  
    My current project, which includes collaborations with local and national partners, in particular on graph querying and formal methods (e.g. with the D-DAL team), and application to transcriptomics.

  In addition, I contribute to national initiatives such as:
  - **MIGGS**, focused on graph-based genomic data and pangenome representations, and **[Get-a-Pan](https://maiage.inrae.fr/node/3390)** 

- **International collaborations**  
  I collaborate with several groups abroad on topics related to sequence indexing, pangenomics, and RNA analysis:

  - **Simon Puglisi, Jarno Alanko** (University of Helsinki), in the context of the **WILL international chair (BOSSA)**, on compressed data structures and large-scale sequence indexing  
  - **Zamin Iqbal** (EMBL-EBI / Cambridge), on genome assembly  
  - **Rob Patro** (University of Maryland), on sequence indexing and transcriptomics methods  
  - **Floris Barthel** (Houston), on genomic feature mapping at large scale  


---

## Teaching and training

I contribute to teaching and training at different levels, from university courses to international schools and professional training.

- **University teaching**
  - Responsible for a course on data structures in the Master in Bioinformatics (Université de Lille), which I developed  
  - Teaching contributions to the AI and Health diploma  

- **International schools or training**
  - Evomics workshop (since 2020): course on genome assembly combining lectures and practical sessions for an international audience  
  - TBA: [EMBO pangenomics course 2026](https://easigen.eu/events/embocourse_pangenomics)
  - Indexing Pangenomics, Pangenomic Course, EMBL-EBI 2025
    
- **Doctoral training**
  - JC2BIM: summer school of GDR BIMMM, courses on sequence data structures, MinHash methods, and RNA analysis  

- **Professional training**
  - Bilille platform and CNRS Formation Entreprises: RNA-seq analysis and genome assembly for academic and industrial audiences
 

---

## Outreach and visibility

- **Press and scientific visibility**
  - A recent collaborative article on leukemia transcriptomics, [*A strong internal promoter drives massive expression of YEATS-domain devoid MLLT3 transcripts in HSC and most lethal AML*](https://spj.science.org/doi/10.1002/cac2.12650), was featured on the **cover of *Cancer Communications* (March 2025)**.  
  - **Vizitig** was featured in the Nature Methods technology article [*It’s a colorful pangenome world*](https://www.nature.com/articles/s41592-026-03021-0) (2026).  
  - Popular science articles in *Le Monde* (*Binaire* blog): [*Rencontre à la frontière entre l’informatique et la biologie*](https://www.lemonde.fr/blog/binaire/2020/02/07/rencontre-a-la-frontiere-entre-linformatique-et-la-biologie/) and [*SARS-CoV-2 et Covid-19 : jouons sur les mots*](https://www.lemonde.fr/blog/binaire/2020/05/06/sars-cov-2-et-covid-19-on-va-jouer-sur-les-mots/).
  -  Profile in **CNRS Sciences informatiques**: [*Camille Marchet, bioinformaticienne des séquences*](https://www.ins2i.cnrs.fr/fr/cnrsinfo/camille-marchet-bioinformaticienne-des-sequences)

- **Public outreach**
  - Public lecture: [*Explorer des millions de nucléotides d’ADN et d’ARN avec les graphes et les bases de données*](https://sciences-technologies-mail.univ-lille.fr/bar-des-sciences/index.html), *Bar des sciences*, Lille (2026).  
  - Participation in outreach initiatives aimed at high-school students, including the [RJMI / *Filles & Maths* program](https://www.inria.fr/fr/mathematiques-informatique-lyceennes-rjmi-2025)   

- **Art and science**
  - Participation in [Emilien Dubuc’s artistic residency](https://culture.univ-lille.fr/agenda/residence-airlab-2024-2025/artistes-2024-2025/emilien-dubuc/) (2025), exploring memory, information, and their alterations in DNA.  

