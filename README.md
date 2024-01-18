## A Unified Catalog of Freshwater Microbial Genomes (iframe.github.io)

<picture>
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://github.com/llemos/iframe/blob/main/iframeLogo.png" width="800" height="800">
</picture>

<br>
<br>
<br>
- Integrated FReshwAter Microbial GenoME Catalog (iFRAME) is a new repository of freshwater microbial genomes compiled from the biomining of public genomic repositories. iFRAME catalog is composed of 2,855 species-level genome bins (SGBs), comprising isolates and uncultivated metagenome-assembled genomes (MAGs) from different parts of the Earth. The iFRAME repository will be a useful resource to explore new biotechnological enzymes and functional processes of cultivated and uncultivated species in future studies.

<br>
<br>


### Resources


+ A genomic repository wiht 2,855 species-level genome bins (SGBs) available to scientific community explore the taxonomical and funcional potential of cultivated and uncultivated microrganisms.

<br>
<br>


### How to use?

+ iFrame is composed by 2,855 species-level genome bins (SGBs) using available public datasets from NCBI (Sayers et al. 2021), IMG (Markowitz et al., 2014), Genomes from Earth’s Microbiomes (GEM) catalog (Nayfash et al. 2020) and several metagenome-assembled genome-based studies (Buck et al., 2021; Santos-Júnior et al. 2021). The iFRAME catalog is available in the Figshare repository (https://figshare.com/s/e5cf16b321b1b5cdd6dc | 10.6084/m9.figshare.23296373) and was built using several bioinformatics tools to remove low-quality and redundant microbial genomes.

### Main files available in Figshare:

+ Supplementary Table 1. Access: (https://figshare.com/s/e5cf16b321b1b5cdd6dc)
+ Genomes files (fasta file). Access:  (https://figshare.com/s/e5cf16b321b1b5cdd6dc)
+ Phylogenetic tree of species-level genome bins (SGBs): (https://figshare.com/s/e58150d3fcbc00c86db4)
+ Alignment of Reference: (https://figshare.com/account/projects/169103/articles/25020005)


### How to update iFrame repository with new genomes?

+  To extend the iFrame repository, there is a phylogenetic tree file on the github platform with all representative genomes, where third-user could add new genomes.

```bat
conda install -c bioconda epa-ng
epa-ng --ref-msa Aligned_SCGs_iFrame.faa --tree SGBs_iFrame.tree --query User_alignment.faa --model GTR+G+F
```
+









