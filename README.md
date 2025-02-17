# Bioinformatic tools for genome assembly and comparative genomics


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14231070.svg)](https://doi.org/10.5281/zenodo.14231070)



## Summary

This e-learning tutorial will guide you through the long-read sequencing genome assembly. The availability of new technologies to obtain accurate long DNA sequencing reads enabled the construction of high-quality genome assemblies for complex organisms and streamlined the production of chromosome-level assemblies for most microorganisms. This course aims to provide basic knowledge on the current genome assembly process, including practical training on one tool available for assembling genomes from long reads (NGSEP). The course also includes practical training on common tools for the evaluation of genome assemblies to obtain statistics such as N50, gene completeness, and QV scores. Finally, we will cover some basic tools to align genomes and perform comparative genomics to provide further context on downstream analysis of genome assemblies.

## Learning Objectives

- Understand basic concepts of genomics and technologies for DNA sequencing and genome assembly.

- Practice with bioinformatic tools for genome assembly, evaluation and comparative genomics.

- Visualize and compare genomes.


## Target Audience

The course is aimed at students, researchers, or professionals. Previous genomics and bioinformatics knowledge is desirable but not required. 

## Previous knowledge

The exercises included in this course are intended for an audience with desirable experience in genomics and bioinformatics. However, this tutorial was adapted to Google Collaboratory and we included an introduction to understanding the basics of this platform, making it friendly with any operative system and avoiding computational resources requirements, you will only need a Google account and internet connection. 

## Technical requirements 
To complete this tutorial you will need a computer with internet connection.

## Introduction

Piangua (*A. tuberculosa*) is a commercially valuable bivalve species being economically important for communities along the Colombian Pacific coast. Understanding microbial interactions, including Vibrio, is vital to ensuring the sustainable use of this resource. Vibrio species are known pathogens capable of causing diseases in humans and marine organisms. Since piangua is harvested for consumption, the presence of pathogenic Vibrio isolates poses a potential health risk to humans, especially when consumed raw or undercooked.

In this tutorial, we will assemble a strain of *Vibrio alginolyticus* originally isolated in the Colombian Pacific (Restrepo-Benavides, et al., 2024). We will understand basic concepts of genomics and technologies for DNA sequencing and genome assembly, practice with bioinformatic tools for genome assembly, evaluation and comparative genomics and visualize and compare our assembly to a reference genome.

## Program

### Module 1: [Introduction to Google Colaboratory](Pt1_IntroToCollab.ipynb)

Before going to Python Notebooks, we would like to suggest you create a Google Drive folder and upload the Python notebook to this folder, this would help you in further steps to be organized. 
Open Google Drive: Just type Google search “Google Drive” and click on the Sign-in result: 

To get started, go to https://colab.research.google.com/.

On the Colab homepage, select "File" and then "Open notebook".

There is a tab for "GitHub"; select that tab and paste the following URL into the search bar under "Enter a GitHub URL or search by organization or user":

`https://github.com/cabana-online/`


After a brief search, you will see the notebook:

`Pt1_IntroToCollab.ipynb`

Select it and you will see the notebook open.

To run the cells, you will need to sign in with your Google account (feel free to create an account). Using Colab is free. 

**Note:** there are limitations in the free version, but they will not be reached in this course.

### Module 2: [NGS and Genome Assembly ](Pt2_NGS&GenomeAssembly.ipynb)

This notebook contains a brief context of the origin of the data and theoretical information so our hands on makes more sense to all the audience.

Go to https://colab.research.google.com/.

Select the repository

`https://github.com/cabana-online/ `

After a brief search, you will see the notebook:

`Pt2_NGS&GenomeAssembly.ipynb`

Select it and you will see the notebook open.

### Module 3: [Hands-on tutorial ](Pt3_Hands_On.ipynb)

We created a Google Collab file that performs genome assembly, quality evaluation, gene annotation, alignment and genome comparison with the reference genome. Remember to set up the connection with Drive to the folder that you’re using. 

Data with reads and the reference genome can be found here data. If you make this a subfolder of your main folder, there is no need of additional set up 

Go to https://colab.research.google.com/.

Select the repository

`https://github.com/cabana-online/Introduction_tutorial`

After a brief search, you will see the notebook:

`Pt3_Hands_On.ipynb`

Select it and you will see the notebook open.

### Module 4: [Results interpretation](04.Module_4_QC.ipynb)

Evaluate all the output files created, it might be needed to check manuals: 
- Quast: https://quast.sourceforge.net/docs/manual.html
- Busco: https://busco.ezlab.org/busco_userguide.html
- gff3 format: https://www.ensembl.org/info/website/upload/gff3.html

As output files of **NGSEP**, you will find:  

- The presence/absence matrix for each of the orthogroups found.
- The frequency of each orthogroup and its classification between core_genome and accessory_genome.
- The ortho groups with the list of genes for each one
- The files for visualization with SynVisio
+ The alignment of the genomes in html format

Now let’s visualize our assembly. SynVisio is a web-based synteny viewer where you can view aligned genomes (the genome you aligned and the reference genome).

1. Open the link https://synvisio.github.io/#/

2. In the tab “Upload own data to Dashboard” load your output files galn_SynvisioCollinearity.txt y galn_SynvisioAnnot.txt. 

3. Click on upload.

4. Go back to the “Synteny Dashboard” Tab.

5. Select source and target chromosomes to make contrasts. 

6. Explore your data visualization.

**D-GENIES**
D-Genies is a web-based tool for aligning genomes based on sequence. Go to the web portal https://dgenies.toulouse.inra.fr/, in the “Run” tab, load the two genomes you used in the previous step. Explore the visualizations of your data.


## Authors & Affiliations: 

Johanna Stepanian, MSc, Universidad de los Andes
Laura Gonzalez, PhD, Universidad de los Andes
Luisa Sacristan, MSc, Universidad de los Andes
Jorge Duitama, PhD, Universidad de los Andes