# Job Offer: Internship - bacterial pangenomics & visualization
(posted on 09/25/24)

(english below)

# Amélioration des analyses pangénomique par la fusion d'outils graphiques

## Contexte : 

Avec l'approche pangénomique, la génomique comparative microbienne se base sur une approche ensembliste pour mettre en évidence les éléments stables et variables entre les génomes d'une unité taxonomique particulière. PPanGGOLiN ([https://github.com/labgem/PPanGGOLiN](https://github.com/labgem/PPanGGOLiN)) est un outil bioinformatique conçu pour l'analyse et l'exploration du pangenome dans les génomes microbiens. Le pangenome englobe l'ensemble des gènes trouvés dans un groupe d'organismes apparentés que ce soit les gènes de base partagés par tous les membres et les gènes accessoires présents seulement chez certains. Cet outil est de plus en plus largement adopté par les chercheurs en génomique microbienne cherchant à caractériser la diversité génénomique au sein des espèces microbiennes. PPanGGOLiN aide en particulier à tracer la conservation de la synténie des gènes dans les génomes, et à examiner les implications fonctionnelles des variations dans la partie accessoire. Pour ce faire, PPanGGOLiN visualise le pangenome sous forme de graphe, où les nœuds représentent des familles de gènes et les arêtes décrivent le contexte génomique de ces gènes à travers différents génomes.

## Proposition de sujet de stage

Notre projet vise à étendre les capacités de PPanGGOLiN en développant un nouvel outil qui ajoute une nouvelle couche de résolution à l'analyse. Tandis que PPanGGOLiN fournit une perspective globale du pangenome au niveau des gènes, nous visons à introduire un graphe local qui relie chaque famille de gènes à un graphe plus détaillé, représentant les variantes au sein de la famille. Cela inclurait également une représentation similaire des régions intergéniques. Pour atteindre cet objectif, nous proposons d'utiliser le modèle de graphe de de Bruijn de Vizitig ([https://gitlab.inria.fr/pydisk/examples/vizitig](https://gitlab.inria.fr/pydisk/examples/vizitig)) — un outil qui traite les graphes de de Bruijn d'individus uniques ou multiples dans des bases de données avec des annotations. Vizitig permet la manipulation et la visualisation des graphes, y compris la sélection de sous-graphes basés sur des requêtes relationnelles, la coloration de graphes et l'exportation. Le projet impliquera des développements spécifiques pour intégrer les capacités de Vizitig avec PPanGGOLiN, en se concentrant sur le chargement et la mise en évidence d'une famille de gènes donnée. Un défi crucial sera de permettre l'exploration de ces données génomiques à différentes échelles, allant de la vue panchromosomique (Fig 2., Gautreau et al., 2020) jusqu'au niveau du nucléotide. L'objectif idéal irait jusqu'à l'étape d'aligner les lectures issues des technologies de séquençage longue lecture sur le graphe pour identifier les différents variants d'un métagénome (gènes et nucléotide).

## Environnement de travail

Le stage se déroulera à MaIAGE INRAE, Jouy-en-Josas, et sera supervisé par Guillaume Gautreau (MaIAGE, INRAE Jouy-en-Josas) et Camille Marchet (CRIStAL, CNRS & Univ Lille). La/la stagiaire interagira avec différents chercheurs et ingénieurs des unités MaIAGE et CRIStAL, ainsi qu'au LABGeM du Genoscope.

## Résultats attendus

Tout au long du stage, l'étudiant acquerra ou renforcera les compétences suivantes :

- Réaliser une recherche bibliographique
 - Développement frontend pour un outil de visualisation et programmation en Python
 - Expérience avec les tests, le développement, le déploiement, et les bonnes pratiques en développement logiciel
 - Compréhension et manipulation des données de séquences dans la pangenomique microbienne

## Profil recherché

Nous recherchons des candidats avec une formation en informatique ou bioinformatique, avec une première expérience ou des connaissances de base en programmation (JavaScript, SQL, Python). Un intérêt pour la génomique microbienne et la datavisualisation utilisant des méthodes graphiques sera apprécié.

============

# Internship Subject: Enhancing Pangenomic Analysis with Integrated Graph Tools

## Overview

With the pangenomic approach, microbial comparative genomics is scaling up by adopting a ensemblist approach to highlight stable and variable elements between the genomes of a particular taxonomic unit.

PPanGGOLiN ([https://github.com/labgem/PPanGGOLiN](https://github.com/labgem/PPanGGOLiN)), is a cutting-edge bioinformatics tool designed for the analysis and exploration of the pangenome in microbial genomes. The pangenome encompasses the complete set of genes found in a group of related organisms, including core genes shared by all members and accessory genes present in only some.

This tool has been widely adopted by researchers in microbiology and genomics who aim to understand genetic diversity within microbial species. PPanGGOLiN aids in identifying shared and unique genes, tracing the conservation of the gene synteny in genomes, and examining the functional implications of variations in the accessory part.

To do so, PPanGGOLiN visualizes the pangenome as a graph, where nodes represent gene families and edges depict the genomic context of these genes across different genomes.

## Project Proposal

Our project seeks to expand PPanGGOLiN's capabilities by developing a novel tool that adds a new layer of resolution to the analysis. While PPanGGOLiN provides a global perspective of the pangenome at gene level, we aim to introduce a local graph that links each gene family to a more detailed graph, representing the variants within the family. This would also include a similar representation of intergenic regions.

To reach this goal we propose using the de Bruijn graph model from Vizitig [https://gitlab.inria.fr/pydisk/examples/vizitig](https://gitlab.inria.fr/pydisk/examples/vizitig), a tool that digests de Bruijn graphs from single or multiple individuals in databases along with annotations. Vizitig enables graph manipulation and visualization, including subgraph selection based on relational queries, graph coloring, and export.

The project involves specific developments integrating Vizitig's capabilities with PPanGGOLiN, with a focus on loading and highlighting a given gene family. A critical challenge will be enabling exploration of this genomic data at various scale ranging from the panchromosomic view (Fig 2., Gautreau et al., 2020)  to the signal base level. Ultimately, we aim to map reads from long-read sequencing technologies onto the graph to identify variants and genes.

## Work Environment

The internship will take place at MaIAGE INRAE, Jouy-en-Josas, and will be supervised by Guillaume Gautreau (MaIAGE, INRAE Jouy-en-Josas) and Camille Marchet (CRIStAL, CNRS & Univ Lille).

## Learning Outcomes

Throughout the internship, the student will acquire or strengthen the following skills:

- Conducting bibliographic research
 - Frontend development for a visualization tool and Python programming
 - Experience with testing, development, deployment, and best practices in software development
 - Understanding and handling sequence data in microbial pangenomics

## Desired Profile

We are looking for candidates with a background in computer science or bioinformatics, with initial experience or a foundational knowledge in programming (JavaScript, SQL, Python). An interest in microbial genomics and data visualization using graphical methods is highly valued
