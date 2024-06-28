# Bio / topics

I am a **research associate in [BONSAI](https://www.cristal.univ-lille.fr/bonsai/) team (Lille, France)**. My work focuses on **methods and data structures** in **sequence bioinformatics**, with applications to **RNA** in particular.

_Je suis chargée de recherche au CNRS dans l'équipe [BONSAI](https://www.cristal.univ-lille.fr/bonsai/) (Lille, France). Je travaille sur des méthodes et structures de données dédiées à la bioinformatique des séquences, avec souvent des applications à l'ARN._

_Intéressé.e par une formation à la bioinformatique pour les données de séquençage ? Le CNRS propose une formation à Lille (labos/entreprises) : [lien](https://cnrsformation.cnrs.fr/index.php?c=stage&stage=23283_)._

After an engineer degree in Bioinformatics from INSA de Lyon and a MsC in Ecology and Evolution from Université Claude Bernard Lyon 1, I worked for two years as an engineer in [ERABLE](https://team.inria.fr/erable/en/) team (LBBE, Lyon) with [Vincent Lacroix](https://lbbe.univ-lyon1.fr/-Lacroix-Vincent-.html?lang=fr). I obtained a PhD funding in [GenScale](https://team.inria.fr/genscale/) team (Rennes, France), where I was supervised by [Pierre Peterlongo](http://people.rennes.inria.fr/Pierre.Peterlongo/). I defended my PhD in 2018 and joined [BONSAI](http://www.lifl.fr/bonsai/) in the CRIStAL lab  afterwards as a postdoc. Lately I was recruited by the CNRS to work as a researcher in the same lab ([short cv](cv.md)). 

My postdoc took part in [Transipedia ANR](https://anr.fr/Project-ANR-18-CE45-0020), with [Rayan Chikhi](http://rayan.chikhi.name/) and [Mikaël Salson](https://mikael-salson.univ-lille.fr/). Transipedia aims at being a transcriptome-encyclopedia, e.g., facilitating indexing, query and exploitation of the numerous publicly available RNA-seq data. I am mostly working on new data structures to index large collections of NGS datasets. 
Before and during my PhD I worked on methods for transcriptomics, in particular for _de novo_ variants discovery and RNA long read analysis.

# Job offers
- Postdoc position, see [the job offers page](jobs.md)

# News
- Send an abstract to MIGGS (Methods for Interfacing with Graphs of Genomic Sequences)([submissions](https://easychair.org/conferences/?conf=miggs1.) [website](https://miggs.mathnum.inrae.fr/)) and meet other scientists interested in pangenomics and visualization in Lille on September 23. Zamin Iqbal and Alexandra Calteau are our confirmed invited speakers.
- Preprint by Florian Ingels, Igor Martayan and myself: [Constrained enumeration of k-mers from a collection of references with metadata](https://www.biorxiv.org/content/10.1101/2024.05.26.595967v1)
- Preprint by Khodor Hannoush, Pierre Peterlongo and myself: [Cdbgtricks: strategies to update a compacted de Bruijn graph](https://www.biorxiv.org/content/10.1101/2024.05.24.595676v1)
- Accepted to ISMB: by Igor Martayan, Bastien Cazaux, Antoine Limasset and myself: [Conway-Bromage-Lyndon (CBL): an exact, dynamic representation of k-mer sets](https://www.biorxiv.org/content/10.1101/2024.01.29.577700v1.abstract). It describes a dynamic k-mer set equipped with set operations and its implementation.
- New preprint on application cases using REINDEER: [Exploring a large cancer cell line RNA-sequencing dataset with k-mers](https://www.biorxiv.org/content/10.1101/2024.02.27.581927v1.abstract)


# Blog posts / short articles
* [Data-structures for sets of _k_-mer sets: what’s new since 2020](sets_kmer_sets.html)
* [Minimal Perfect Hash Functions in the k-mer world](mphf.md)
* [Sketching for bioinformatics](sketch.md): featuring Niqki (Clément Agret et al.'s [recent preprint](https://www.biorxiv.org/content/10.1101/2021.11.04.467355v1))
* [Strobemers](strobemers.md), a new kind of spaced seeds from [K Sahlin's preprint](https://www.biorxiv.org/content/10.1101/2021.01.28.428549v1)
* [Othello hashing in bioinformatics](othello.md)
* [Sneak peek at the -tigs!](tigs.md) a (very) high-level presentation of the population of -tigs sequences we encounter lately in k-mers related-papers (unitigs, simplitigs, monotigs, omnitigs, macrotigs) but that also includes UST and super-k-mers
* [A short popularization article about coronavirus assembly](https://www.lemonde.fr/blog/binaire/2020/05/06/sars-cov-2-et-covid-19-on-va-jouer-sur-les-mots/) with long reads (in French)
* [A short popularization article about my PhD work](https://www.lemonde.fr/blog/binaire/2020/02/07/rencontre-a-la-frontiere-entre-linformatique-et-la-biologie/) (in French)

# Research projects

## Present
- 2024-.. **Find-RNA** ANR JCJC project, _Data-structures for collections of sets of (meta-)transcriptomics data_ (coordinator)
- 2021-.. **INSSANE** ANR project, _Novel methods for studying RNA structures_ (partner)
- 2022-.. **Full RNA** ANR project,_Indexing large scale 2nd and 3rd generation RNA datasets_ (member)
- 2020-.. **ALPACA** ITN, _Methods for pangenomics_ (informal member)

## Past
- 2018-22 **Transipédia** ANR project, _Indexing large scale RNA-seq datasets_ (member)
- 2017 CNRS MASTODONS project, _Correction of 3rd generation sequencing data_ (member)
- 2013-16 **Colib’read** ANR project, _De novo methods for the variant calling in short read sequencing_ (member)

# Journal Publications
- [Conway-Bromage-Lyndon (CBL): an exact, dynamic representation of k-mer sets](https://www.biorxiv.org/content/10.1101/2024.01.29.577700v2.abstract), I Martayan, B Cazaux, A Limasset & C Marchet, _Bioinformatics_ 2024 (in press)
-  KaMRaT: a C++ toolkit for $k$-mer count matrix dimension reduction, H Xue, M Gallopin, C Marchet, H N Nguyen, Y Wang, A Lainé, C Bessiere, D Gautheret; _Bioinformatics_ 2024
- [A survey of mapping algorithms in the long-reads era](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02972-3), K Sahlin, T Baudeau, B Cazaux, C Marchet; _Genome Biology_, 2023
- [Scalable sequence database search using Partitioned Aggregated Bloom Comb-Trees](https://academic.oup.com/bioinformatics/article/39/Supplement_1/i252/7210475), C Marchet & A Limasset; _Bioinformatics_ 2023
- [BLight: Efficient exact associative structure for k-mers](https://academic.oup.com/bioinformatics/advance-article-abstract/doi/10.1093/bioinformatics/btab217/6209734), C Marchet, M Kerbiriou, A Limasset; _Bioinformatics_, 2021
- [Scalable long read self-correction and assembly polishing with multiple sequence alignment](https://www.nature.com/articles/s41598-020-80757-5), P Morisse, C Marchet, A Limasset, T Lecroq, A Lefebvre; _Scientific Reports_, 2021
- [Data structures based on k-mers for querying large collections of sequencing data sets](https://genome.cshlp.org/content/early/2020/12/16/gr.260604.119.abstract), C Marchet, C Boucher, S. J. Puglisi, P Medvedev, M Salson, R Chikhi; _Genome Research_ 2020
- [REINDEER: efficient indexing of k-mer presence and abundance in sequencing datasets](https://academic.oup.com/bioinformatics/article/36/Supplement_1/i177/5870500?guestAccessKey=55740e31-df79-4471-a5c0-7af969f98cbe), C Marchet, Z Iqbal, D Gautheret, M Salson, R Chikhi; _Bioinformatics_, 2020 
- [ELECTOR: Evaluator for long reads correction methods](https://academic.oup.com/nargab/article/2/1/lqz015/5625503?guestAccessKey=3c7f948f-457f-4585-b6b3-5fbed1fa40db), C Marchet, P Morisse, L Lecompte, A Limasset, A Lefebvre, T Lecroq, P Peterlongo; _Nucleic acid research Genomics and Bioinformatics_, 2019
- [Comparative assessment of long-read error-correction software applied to RNA-sequencing data](https://academic.oup.com/bib/advance-article-abstract/doi/10.1093/bib/bbz058/5512144), L Ishi Soares de Lima, C Marchet, S Caboche, C Da Silva, B Istace, J-M Aury, H Touzet, R Chikhi; _Briefings in Bioinformatics_, 2019
- [Clustering _de Novo_ by Gene of Long Reads from Transcriptomics Data](https://academic.oup.com/nar/article/47/1/e2/5107577), C Marchet, L Lecompte, C Da Silva, C Cruaud, J-M Aury, J Nicolas, P Peterlongo; _Nucleic Acids Research_, 2018
- [A _de novo approach_ to disentangle partner identity and function in holobiont systems](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0481-9) A Meng, C Marchet, E Corre, P Peterlongo, A Alberti, C Da Silva, P Wincker, E Pelletier, I Probert, J Decelle, S Le Crom, F Not, L Bittner; _Microbiome_, 2018
- [A resource-frugal probabilistic dictionary and applications in bioinformatics](https://www.sciencedirect.com/science/article/pii/S0166218X18301288), C Marchet, L Lecompte, A Limasset, L Bittner, P Peterlongo; _Discrete Applied Mathematics_, 2018
- [Complementarity of assembly-first and mapping-first approaches for alternative splicing annotation and differential analysis from RNAseq data](https://www.nature.com/articles/s41598-018-21770-7) C Benoit-Pilven, C Marchet, E Chautard, L Lima, M-P Lambert, G Sacomoto, A Rey, C Bourgeois, D Auboeuf, V Lacroix; _Scientific Reports_, 2018
- [Playing hide and seek with repeats in local and global de novo transcriptome assembly of short RNA-seq reads](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5322684/) L Lima, B Sinaimeri, G Sacomoto, H Lopez-Maestre, C Marchet, V Miele, M-F Sagot and V Lacroix; _Algorithms for Molecular Biology_, 2017
- [SNP calling from RNA-seq data without a reference genome: identification, quantification, differential analysis and impact on the protein sequence](https://www.ncbi.nlm.nih.gov/pubmed/27458203) H Lopez Maestre, L Brinza, C Marchet, J Kielbassa, S Bastien, M Boutigny, D Monnin, A El Filali, CM Carareto, C Vieira, F Picard, N Kremer, F Vavre, M-F Sagot, V Lacroix; _Nucleic Acids Research_, 2016
- [Colibread on galaxy: a tools suite dedicated to biological information extraction from raw NGS reads](https://gigascience.biomedcentral.com/articles/10.1186/s13742-015-0105-2) E Rivals, A Andrieux, A Z El Aabidine, B Cazaux, C Marchet, C Lemaitre, C Monjeaud, G Sacomoto, L Salmela, O Collin, P Peterlongo, R Uricaru, S Alves-Carvalho, V Lacroix, V Miele, Y LeBras; _GigaScience_, 2016

# Research papers accepted to peer-reviewed conferences
- [Cdbgtricks: strategies to update a compacted de Bruijn graph](https://www.biorxiv.org/content/10.1101/2024.05.24.595676v1), K Hannoush, C Marchet and P Peterlongo, _PSC_ 2024
- [Conway-Bromage-Lyndon (CBL): an exact, dynamic representation of k-mer sets](https://www.biorxiv.org/content/10.1101/2024.01.29.577700v2.abstract), I Martayan, B Cazaux, A Limasset & C Marchet, _ISMB_ 2024
- [Fractional Hitting Sets for Efficient and Lightweight Genomic Data Sketching](https://www.biorxiv.org/content/10.1101/2023.06.21.545875v1), T Rouzé, I Martayan, C Marchet & A Limasset, _WABI_ 2023
- [Scalable sequence database search using Partitioned Aggregated Bloom Comb-Trees](https://www.biorxiv.org/content/10.1101/2022.02.11.480089v2), C Marchet & A Limasset; _ISMB_ 2023
- [REINDEER: efficient indexing of k-mer presence and abundance in sequencing datasets](https://www.biorxiv.org/content/10.1101/2020.03.29.014159v1), C Marchet, Z Iqbal, D Gautheret, M Salson, R Chikhi; _ISMB_ 2020
- [Indexing De Bruijn graphs with minimizers](https://www.biorxiv.org/content/10.1101/546309v2), C Marchet, A Kerbiriou, A Limasset; _RECOMB-SEQ_ 2019
- [CONSENT: Scalable self-correction of long reads with multiple sequence alignment
](https://www.biorxiv.org/content/10.1101/546630v3), P Morisse, C Marchet, A Limasset, A Lefebvre, T Lecroq; _RECOMB-SEQ_ 2019
- [A resource-frugal probabilistic dictionary and applications in (meta)genomics](https://hal.inria.fr/hal-01386744/document), C Marchet, A Limasset, L Bittner, P Peterlongo; _PSC_ 2016
- [Navigating in a Sea of Repeats in RNA-seq without Drowning](https://link.springer.com/chapter/10.1007/978-3-662-44753-6_7), G Sacomoto, B Sinaimeri, C Marchet, V Miele, MF Sagot, V Lacroix; _WABI_ 2014


# Preprints
- [Constrained enumeration of k-mers from a collection of references with metadata](https://www.biorxiv.org/content/10.1101/2024.05.26.595967v1), F Ingels, I Martayan, M Salson and C Marchet 
- [Exploring a large cancer cell line RNA-sequencing dataset with k-mers](https://www.biorxiv.org/content/10.1101/2024.02.27.581927v1.abstract), C Bessière, H Xue, B Guibert, A Boureux, F Rufflé, J Viot, R Chikhi, M Salson, C Marchet, T Commes and D Gautheret
  
# Communications

## Invited talks
- 2024: Incoming keynote TBA, Genome Informatics, Cambridge (UK)
- 2024: Incoming keynote TBA, Iggsy, Ascona (Switzerland)
- 2024: Reference-free pangenomics and other large indexes, EAGS International Environmental and Agronomical Genomics symposium, Toulouse (France)
- 2024: _Reference-free transcriptomics and other large indexes_, Statistical Methods for Post Genomic Data workshop, Paris (France)
- 2023: Hashing-based data-structures for querying large k-mer (collections of) sets, [CiE](https://www.viam.science.tsu.ge/cie2023/), Batumi (Georgia)
- 2023 Hashing-based data-structures for querying large k-mer (collections of) sets, [Sequences in London](https://sites.google.com/view/sequencesworkshop/home), UK
- 2022 [_Scalable sequence database search using Partitioned Aggregated Bloom Comb-Trees_](https://coursesandconferences.wellcomeconnectingscience.org/wp-content/uploads/2021/11/Genome-Informatics-programme-5-Aug-22.pdf), Genome Informatics, Cambridge (UK)
- 2022 [How to improve student/advisor relationships](https://algo2022.eu/wabi/), WABI, ALPACA 2nd Annual Workshop, Potsdam (Germany)
- 2022 Data-structures for querying large _k_-mer (collections of) sets, JOBIM mini-symposium, Rennes (France)
- 2022 [Data-structures for querying large _k_-mer (collections of) sets](https://muse.edu.umontpellier.fr/2022/02/08/online-seminar-data-structures-for-querying-large-k-mer-collections-of-sets/), KIM Data and Life Sciences seminars, Montpellier (France, online) **[[slides](https://github.com/kamimrcht/webpage/blob/master/slides/s_minaire_montpellier_2022%20(1).pdf)]** **[[recording (in French)](https://muse.edu.umontpellier.fr/2022/02/08/online-seminar-data-structures-for-querying-large-k-mer-collections-of-sets/)]**
- 2022 [Data structures for large _k_-mer sets](https://miat.inrae.fr/site/S%C3%A9minaires#28.2F01.2F2022.C2.A0:_Structures_de_donn.C3.A9es_pour_les_grands_ensembles_de_k-mers_Camille_Marchet_.28CNRS.2C_Universit.C3.A9_de_Lille.29_.5Bdistanciel.5D), MIAT seminars, Toulouse (France, online) **[[slides](https://github.com/kamimrcht/webpage/blob/master/slides/s_minaire_toulouse_2022%20(8).pdf)]**
- 2020 [From reads to transcripts: de novo methods for the analysis of transcriptome second and third generation sequencing](https://congres.societe-informatique-de-france.fr/programme/), SIF congress, INSA de Lyon (France)
- 2020 Scalable data structures for sequencing data, Symposium GDR Madics, Lyon (France) (covid-19 : canceled)
- 2019 New methodologies for the analysis of transcriptome sequences, MAB team seminar, LIRMM Montpellier (France)
- 2018 CARNAC-LR and C2C: de novo clustering and detection of alternative isoforms in Third Generation Sequencing transcriptomes, [Genotoul Biostats/Bioinfo day](https://bioinfo-biostat.sciencesconf.org/), INRA Toulouse (France)
- 2018 From reads to transcripts: _de novo_ methods to analyze transcriptome 2d and 3d generations sequencing data, Roscoff Biological Station seminar (France)
- 2018 A _de novo_ approach to disentangle partner identity and function in holobiont systems, Advances techniques to study and exploit the sponge and coral microbiomes Workshop, ULB Brussels (Belgium)
- 2018 A highly scalable data structure for read similarity computation and its application to marine holobionts, EEB group meeting, ULB Brussels (Belgium)
- 2018 CARNAC-LR: clustering genes expressed variants from long read RNA sequencing, team TIBS seminar, LITIS Rouen (France)
- 2017 _De novo_ Clustering of Gene Expressed Variants in Transcriptomic Long Reads Data Sets at workshop RNA-Seq and Nanopore sequencing, Genoscope Evry (France)
- 2017 Rconnector: a resource-frugal probabilistic dictionary and applications in (meta)genomics and transcriptomics, LBBE NGS group seminar, Lyon (France)

## Workshops/conferences/seminars
- 2020 [REINDEER: efficient indexing of _k_-mer presence and abundance in sequencing datasets](http://biata2020.spbu.ru/), BIATA, St Petersburg (Russia, virtual conference)
- 2020 [REINDEER: efficient indexing of _k_-mer presence and abundance in sequencing datasets](https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php#HitSeq:%20High-throughput%20Sequencing), ISMB, Montreal (Canada, virtual conference)
- 2020 [REINDEER: efficient indexing of _k_-mer presence and abundance in sequencing datasets](https://jobim2020.sciencesconf.org/program), JOBIM, Montpellier (France, virtual conference)
- 2020 [REINDEER: efficient indexing of _k_-mer presence and abundance in sequencing datasets](https://dsb-meeting.github.io/DSB2020/program_DSB2020.pdf), DSB, Rennes (France)
- 2019 [Indexing De Bruijn graphs with minimizers](https://recombseq.recomb2019.org/schedule/#Sat), RECOMB-seq, Washington DC (US)
- 2019 [Indexing De Bruijn graphs with minimizers](http://biata2019.spbu.ru/program/), BiATA, St Petersburg (Russia)
- 2019 [Survey of _k_-mer set of sets data structures for querying large collections of sequencing datasets](https://dsb2019.gitlab.io/), DSB, Dortmund (Germany)
- 2019 [Survey of _k_-mer set of sets data structures for querying large collections of sequencing datasets]( https://www.helsinki.fi/en/researchgroups/bioinformatics/bioinformatics-day-2019), Helsinki Bioinformatics Day (Finland)
- 2019 Read correction for non-uniform coverages, [RCAM](http://maiage.jouy.inra.fr/?q=fr/rcam2019) Institut Pasteur Paris (France)
- 2019  Survey of _k_-mer set of sets data structures for querying large collections of sequencing datasets, at [SeqBim](http://seqbim.cnrs.fr/seqbim-2019/), Marne La Vallée (France)
- 2018 [BCOOL-Trans: accurate and variant-preserving correction for RNA-seq](http://bioinfo.univ-rouen.fr/seqbio2018/programme.php), Seqbio, Rouen (France)
- 2018 [ELECTOR: EvaLuator of Error CorrectionTools for lOng Reads](http://bioinfo.univ-rouen.fr/seqbio2018/programme.php), Seqbio, Rouen (France)
- 2018 [CARNAC-LR : Clustering coefficient-based Acquisition of RNA Communities in Long Reads](https://jobim2018.sciencesconf.org/data/pages/Program_A4_JOBIM2018.pdf), JOBIM, Marseille (France)
- 2017 _De novo_ Clustering of Gene Expression in Transcriptomic Long Reads Data Sets, Seqbio, Lille (France)
- 2017 A highly scalable data structure for read similarity computation and its application to marine holobionts, RCAM, Paris (France)
- 2017 A scaling transcriptomic approach to study holobiont data sets, 4e colloque Génomique Environnementale, Marseille (France)
- 2016 Rconnector: a resource-frugal probabilistic dictionary and applications in (meta)genomics and transcriptomics, SeqBio, Nantes (France)
- 2015 kissDE : a replicate-wise and annotation-free R package for testing the association between differential variants and experimental conditions in high throughput sequencing data, SeqBio 2015, Orsay (France)
- 2015 kissDE : a package to test for differences in reads counts derived from variants in RNA sequencing data, Quatriemes rencontres R 2015, Lyon (France)

## Other talks
- 2022 [A little tour of assembly methods](https://raw.githubusercontent.com/kamimrcht/webpage/master/files/Cesky_Assembly_Course_2022-1.pdf) with Antoine Limasset, for Evomics school on genomics in Cesky Krumlov
- 2021 [An introduction to data-structures for _k_-mer sets indexing](https://github.com/kamimrcht/webpage/raw/master/files/presentation_ens_marchet.pdf) for ENS Rennes students

# Involvement in scientific events

**Program committee and venue organization**
- 2024 OC @MIGGS (FRANCE)
- 2023 PC, OC @SeqBIM (France)
- 2021 OC @SPIRE (virtual)
- 2020 PC @SPIRE (virtual)
- 2020 PC @RECOMB-Seq (virtual)
- 2019 PC @SeqBIM (France)
- 2018 Volunteer @RECOMB-seq and RECOMB, Paris
- 2016 OC "Biological insights from raw high-throughput sequencing data" - Colib'read ANR workshop, Paris

**Tutoring for scientists**
- 2020,2022,2023 [Evomics, workshop on Genomics](http://evomics.org/2020-workshop-on-genomics-cesky-krumlov-czech-republic/), Cesky Krumlov, Czech Republic
- 2019,2022,2023 Tutor at [Bilille training courses](https://wikis.univ-lille.fr/bilille/formation) (RNA-seq analysis), Lille.
- 2022, 2024 Teacher for [JC2BIM's summer school](https://www.gdr-bim.cnrs.fr/actions-du-gdr/ecole-jc2bim/)
- 2015 Tutor at CNRS course: "Bioinformatique pour les NGS", Montpellier
- 2014 Tutor at BGE & EMBnet tutorials: "RNA-seq analysis", Lyon
- 2014 Tutor at PRABI training courses, "Analyse de données RNA-seq sous l'environnement Galaxy", Lyon

# Supervision
PhD students

- 2023-.. Igor Martayan (with Jean-Stéphane Varré), subject: locality-preserving k-mer data structures
- 2022-.. Thomas Baudeau (PhD student, with Mikaël Salson), subject: Mapping of structural long reads
- 2021-.. Khodor Hannoush (PhD student, with Pierre Peterlongo), subject: Dynamic pangenome graphs

Interns from past years

Thomas Baudeau, Louis-Maël Gueguen, Agathénaïs Adiguna, Benjamin Churcheward, Lolita Lecompte, Camille Sessegolo

# Teaching

<table>
  <tr>
    <th>Year</th><th>Level</th><th>Topic</th>
  </tr>
     <tr>
    <td>2023/2024</td><td>M1 bioinformatique Université de Lille</td><td> responsable de l'UE structures de données</td>
  </tr>
   <tr>
    <td>2021/2022</td><td>M1 bioinformatique Université de Lille</td><td> responsable de l'UE structures de données</td>
  </tr>
   <tr>
    <td>2019/2020</td><td>L2 informatique Université de Lille</td><td>TP/TP Algorithmique et structures de données</td>
  </tr>
  <tr>
    <td>2018/2019</td><td>L2 informatique Université de Lille</td><td>TP/TP Algorithmique et structures de données</td>
  </tr>
  <tr>
    <td>2016/2017</td><td>4ème et 5ème année école d'ingenieur (M1/M2) INSA Rennes</td><td>Modélisation et ingénierie pour le vivant</td>
  </tr>
  <tr>
    <td>2016/2017</td><td>2ème année cycle prépa INSA Rennes</td><td>TP/TP Bases de Données</td>
  </tr>
  <tr>
    <td>2016/2017</td><td>M1 ENS Rennes</td><td>Biostatistiques, programmation avec R</td>
  </tr>
    <tr>
    <td>2015/2016</td><td>M1 ENS Rennes</td><td>Biostatistiques, programmation avec R</td>
  </tr>
   <tr>
    <td>2014/2015</td><td>L1 Université Lyon 1</td><td>TD Mathématiques pour les Sciences de la Vie</td>
  </tr>
</table>

# Press review

- [Camille Marchet, bioinformaticienne des séquences
](https://www.ins2i.cnrs.fr/fr/cnrsinfo/camille-marchet-bioinformaticienne-des-sequences)

