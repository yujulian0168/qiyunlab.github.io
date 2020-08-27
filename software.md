---
title: Software
wol:
  - title: Web of Life (WoL)
    url: https://biocore.github.io/wol/
    image_path: assets/images/software/wol.png
    excerpt: >
        WoL is a highly collaborative project aiming at building a reference phylogeny which accurately defines the evolutionary relationships among all microbes. In Phase I of the project, we built a phylogeny of 10,575 genomes using 381 marker genes, making this the single largest dataset upon which de novo phylogenetic trees have been built, yet the bioinformatic approaches we adopted or invented are significantly more robust than previous works. We made the resource publicly available to benefit the research community. It means to serve as a reference for researchers to explore the evolution and diversity of microbes, and to improve the study of microbial communities. <br/><br/>
        [Zhu et al., _Nat Commun_, 2019](https://www.nature.com/articles/s41467-019-13443-4)
woltka:
  - title: Woltka
    url: https://github.com/qiyunzhu/woltka
    excerpt: >
        Woltka is a bioinformatics package for shotgun metagenomic data analysis. It highlights: 1) fine-grain community ecology featuring individual reference genomes; 2) tree-based, rank-free classification to maximize resolution and flexibility; 3) combined taxonomic & functional analysis through one alignment to ensure consistency and accuracy. It takes full advantage of, but not limited by, the [WoL](https://biocore.github.io/wol/) reference phylogeny. It comes with an interface for the [QIIME 2](https://qiime2.org/) package, and has been integrated into the [Qiita](https://qiita.ucsd.edu/) web server.
others:
  - title: HGTector
    url: https://github.com/DittmarLab/HGTector
    excerpt: Genome-wide detection of horizontal gene transfer based on BLAST hit distribution statistics.
  - title: Horizomer
    url: https://github.com/biocore/horizomer
    excerpt: Integrated workflow and benchmark system for various horizontal gene transfer prediction tools.
  - title: BinaRena
    url: https://qiyunzhu.github.io/binarena/demo.html
    excerpt: Interactive graphical interface for manual observation and binning of metagenomic contigs.
contrib:
  - title: QIIME 2
    url: https://qiime2.org/
    image_path: assets/images/software/qiime2.png
    excerpt: >
        QIIME 2 is an integrated software package for microbiome data analysis. It provides a complete and flexible solution from raw sequencing data to publication-grade tables and figures. It highlights transparent and reproducible science. It has been the most widely-used bioinformatics tool in the field of microbiomics. <br/><br/>
        [Estaki et al., _Curr Protoc Bioinformatics_, 2020](https://currentprotocols.onlinelibrary.wiley.com/doi/full/10.1002/cpbi.100) <br/>
        [Bolyen et al., _Nat Biotechnol_. 2019.](https://www.nature.com/articles/s41587-019-0209-9)
  - title: Qiita
    url: https://qiita.ucsd.edu/
    image_path: assets/images/software/qiita.png
    excerpt: >
        Qiita is a web server for managing microbiome studies, datasets and analyses. It implements a wide range of state-of-the-art programs and databases for the analysis of amplicon, metagenomic and metabolomic data. It enables meta-analysis of an extremely large volume of datasets across many studies. <br />
        [Gonzalez et al., _Nat Methods_, 2018](https://www.nature.com/articles/s41592-018-0141-9)
  - title: scikit-bio
    url: http://scikit-bio.org/
    image_path: assets/images/software/skbio.png
    excerpt: >
        scikit-bio is an open-source Python package for bioinformatics researchers and developers. It provides algorithms and data structures for sequence alignments, phylogenetic trees, distance matrices, ordinations and diversity metrics. It powers QIIME 2, Qiita and multiple other bioinformatics tools.
  - title: SHOGUN
    url: https://github.com/knights-lab/SHOGUN
    excerpt: >
        SHOGUN is a pipeline for analyzing shallow shotgun metagenomic sequencig data, which is more afforable than deep sequencing whereas advantageous over amplicon sequencing. <br />
        [Hillmann et al., _Bioinformatics_, 2020](https://academic.oup.com/bioinformatics/article-abstract/36/13/4088/5828930)
  - title: PhyloPhlAn
    url: https://huttenhower.sph.harvard.edu/phylophlan
    excerpt: PhyloPhlAn 3.0 is a fully-automated pipeline for phylogenomic reconstruction and insertion of microbial genomes and metagenomes. <br />[Asnicar et al., _Nat Commun_, 2020](https://www.nature.com/articles/s41467-020-16366-7)
  - title: Empress
    url: https://github.com/biocore/empress
    excerpt: Empress is a phylogenetic tree viewer that is extremely scalable (can display 1m+ taxa simultaneously) and is interactive with the QIIME 2 ecosystem to facilitate microbial community studies.
---

Check out our software projects at <i class='fab fa-github fa-lg'></i> [GitHub](https://github.com/qiyunlab/).

## Projects we lead

{% include feature_row id="wol" type="left" %}
{% include feature_row id="woltka" type="center" %}
{% include feature_row id="others" %}

## Projects we contribute to

{% include feature_row id="contrib" %}
