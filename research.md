---
title: Research
wol:
  - url: https://www.nature.com/articles/s41467-019-13443-4
    image_path: assets/images/research/wol.png
    title: Reference phylogeny of 10,575 bacterial and archaeal genomes
  - image_path:
td:
  - url: https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0579-0
    image_path: assets/images/research/td.png
    title: Metagenome assembly of a traveler's diarrhea microbiome
  - image_path:
amazon:
  - url: https://www.nature.com/articles/s41564-019-0593-4
    image_path: assets/images/research/amazon.png
    title: Microbial and chemical diversity by urbanization level
  - image_path:
---

## Our Mission

The rapid growth of microbiome data yields great opportunities to achieve higher accuracy, greater predictive power and novel insights into biology; at the same time, it poses great challenges in computation and statistics imposed by many dimensions of data and metadata. Advancing microbiome science demands fundamental innovations in both methods and applications, and can only be achieved by integrating wisdom from multiple disciplines. At the [Qiyun Lab](https://qiyunlab.github.io/), we are exploring a wide range of questions that span both the computational (community ecology to metagenome assembly) and the biological (the origin of life to the transmission of pathogenicity). We strive to push the frontier of microbiomics by combining the development of bioinformatics tools and the investigation of meta-omics datasets. We are dedicated to collaborative, reproducible and open-source science.


## Phylogeny-Guided Shotgun Metagenomics

Microbiome research has long benefitted from [phylogeny](https://en.wikipedia.org/wiki/Phylogenetic_tree) which makes sense of high-dimensional data by using a hierarchical representation of their relationships. Algorithms like UniFrac and Faith's PD along with databases like Greengenes and Silva have been widely adopted to describe phylogenetic relationships in modern high-throughput 16S rRNA gene amplicon studies. However, in the rapid-growing field of shotgun metagenomics, the utilization of phylogeny is still rare and primitive. Most studies are limited to the analysis of lower-dimensional genus- or species-level taxonomic units by using non-hierarchical methods, or rely on the taxonomy tree, which is inherently less accurate and more error-prone than explicit phylogeny.

{% include gallery id="wol" class="center" caption="Reference phylogeny of microbial genomes. [_Nat Commun_, 2019](https://www.nature.com/articles/s41467-019-13443-4)" %}

We initiated the "Web of Life" ([WoL](https://biocore.github.io/wol/)) project to change the game by providing a whole genome-based reference phylogeny for all microbes. Our highly collaborative team developed or exploited cutting-edge computational approaches to harness the complexity of microbial genome and gene evolution. During phase I of the project ([_Nat Commun_, 2019](https://www.nature.com/articles/s41467-019-13443-4)), we built a phylogeny of 10,575 genomes using 381 marker genes, making this the single largest dataset upon which _de novo_ phylogenetic trees have been built. In the ongoing phase II, we are significantly expanding the phylogeny by incorporating phylogenomic placement and marker gene optimization and grouping.

The reference phylogeny itself is merely the beginning of a paradigm shift, and is to be followed by innovations in multiple aspects. We are in active development of [Woltka](https://github.com/qiyunzhu/woltka), a bioinformatics package integrating multiple novel ideas, algorithms and protocols which enhance the analytics of shotgun metagenomic datasets by using the reference phylogeny. It operates on individual genomes -- rather than taxonomic units -- as the basic elements. [Woltka](https://github.com/qiyunzhu/woltka) uses a tree-based, rank-free classification system to maximize accuracy and flexibility. It combines taxonomic & functional analysis through one alignment against the reference genome database to ensure consistency and accuracy. In addition to these features, we are actively exploring methodology for database refinement, false positive identification, network-structured classification, and many other novel and important directions.


## Diversity, Vertical and Horizontal Evolution of Microbes

The natural history of living organisms is among the most fundamental and long-standing questions in science. Culture-independent methods, especially metagenomics, have enabled many exciting discoveries of novel microbial groups in recent years. This has  led to repeated re-writings of the tree of life, and yielding markers and products of medical, environmental and technological importance.

{% include gallery id="td" caption="Bacterial and viral genomes recovered from a traveler's diarrhea metagenome. [_Microbiome_, 2018](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0579-0)." %}

We study the diversity and evolution of microbes by combining metagenomics, phylogenetics and comparative genomics. Specifically, from metagenomic data generated using 2nd and 3rd generation sequencing techniques, we extract the uncultivated "dark matter" genomes using a series of bioinformatics approaches: assembly, binning, scaffolding and more. The metagenome-assembled genomes ([MAGs](https://www.nature.com/articles/nbt.3893)) are then analyzed to characterize their evolutionary status, genetic structures and functional potentials (e.g., [_Microbiome_, 2018](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-018-0579-0)). This process is never easy despite the advances in algorithms. We are developing a visualization-assisted [program](https://qiyunzhu.github.io/binarena/demo.html) for comparison and curation of MAG schemes, as well as exploring other important topics in MAG discovery.

The study of whole genome evolution, a.k.a. phylogenomics, often yields novel insights compared with conventional methods which are limited to one or a few genes. For example, our [WoL](https://biocore.github.io/wol/) tree revealed that the two domains Bacteria and Archaea are remarkably closer in evolution than previously estimated using a handful of “core” genes ([_Nat Commun_, 2019](https://www.nature.com/articles/s41467-019-13443-4)). Not since Carl Woese work in the 1970s has a discovery fundamentally changed our understanding of the “tree of life." Further investigation showed that the Candidate Phyla Radiation (CPR), a highly diversified clade of mainly uncultivated microorganisms, are distinct from the remaining bacteria in phylogeny and in gene profiles. This inspires us to extend research in this and other mysterious clades of life.

The evolutionary "tree" of microbes is often confounded by the discrepancies among individual genes trees due to the prevalence of horizontal gene transfer events ([HGTs](https://en.wikipedia.org/wiki/Horizontal_gene_transfer)). HGTs play vital roles in the adaptation of pathogens to host environments and the dispersal of virulence and antibiotic resistance. We develop computational methods for HGT identification, including [HGTector](https://github.com/DittmarLab/HGTector), an algorithm that has been shown effective in multiple studies, as well as more comprehensive methods incorporating similarity, composition, context, phylogeny and other characteristics indicative of HGTs. Our goal is identify the true “web of life”: a network structure incorporating both vertical and horizontal evolutions.


## Microbiome Interacting with Hosts and Environments

Microbial communities interact with their environments -- either host-associated (human gut, oral, skin, etc.) or free-living (soil, carbonate, deep sea, etc.). Such interactions are hiding under the complexity of biological big data. Analysis of biological big data is increasingly needed yet extremely challenging for scientists. Capturing correlations among multiple omics datasets with hundreds to thousands of dimensions, and dozens to hundreds of metadata fields coded in diverse formats is a monumental task that only recently scientists have begun to understand how to approach.

{% include gallery id="amazon" class="center" caption="Microbial and chemical diversity across an urbanization gradient in Amazon. [_Nat Microbiol_, 2020](https://www.nature.com/articles/s41564-019-0593-4)." %}

We are experts in data science for meta-omics. We collaborate with scientists from multiple disciplines to answer specific questions about how microbiomes interact with hosts and environments. Using the latest and most advanced computational approaches -- multiple of which are developed by us or with our contributions -- we cluster samples based on community diversity, characterize community changes along time series or feature gradients, explore correlations between microbes or  chemicals, identify differentially abundant species across test groups, and build machine learning models to identify biomarkers that best predict the status of subjects.

For example, in a study of the microbiome and metabolome of the built environment and body sites across an urbanization gradient in the Amazon rainforest, we found correlations between bacterial and fungal diversity and urbanization, especially the use of chemical products along with altered lifestyle ([_Nat Microbiol_, 2020](https://www.nature.com/articles/s41564-019-0593-4)). In a systematic and deliberate survey of public datasets, we characterized microbial communities present in various cancer tissues and built highly predictive machine models which have diagnostic potentials ([_Nature_, 2020](https://www.nature.com/articles/s41586-020-2095-1)). Through a combined investigation of six omics data types, we found microbial determinants of ulcerative colitis severity which guided subsequent successful experimental validation (in submission).

We are committed to building a competitive and comprehensive microbiome data science platform for the ASU community, which will bring together researchers from various fields to explore the many exciting opporunities about microbiomes and beyond.
