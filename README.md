# Bioinformatic tools for genome assembly and comparative genomics



[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14969215.svg)](https://doi.org/10.5281/zenodo.14969215)



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

***Note: It is mandatory to complete the survey at the end of the tutorial, as your feedback is essential for improving our courses and ensuring a better learning experience for future participants. We appreciate your time and input!***

## Program

### Module 1: [Introduction to Google Colaboratory](Pt1_IntroToCollab.ipynb)

Before going to Python Notebooks, we would like to suggest you create a Google Drive folder and upload the Python notebook to this folder, this would help you in further steps to be organized. 
Open Google Drive: Just type Google search “Google Drive” and click on the Sign-in result: 

To get started, go to https://colab.research.google.com/.

On the Colab homepage, select "File" and then "Open notebook".

There is a tab for "GitHub"; select that tab and paste the following URL into the search bar under "Enter a GitHub URL or search by organization or user":

`https://github.com/cabana-online/Tutorial_Long_Reads_Genome_Assembly`


After a brief search, you will see the notebook:

`Pt1_IntroToCollab.ipynb`

Select it and you will see the notebook open.

To run the cells, you will need to sign in with your Google account (feel free to create an account). Using Colab is free. 

**Note:** there are limitations in the free version, but they will not be reached in this course.

### Module 2: [NGS and Genome Assembly ](Pt2_NGS&GenomeAssembly.ipynb)

This notebook contains a brief context of the origin of the data and theoretical information so our hands on makes more sense to all the audience.

Go to https://colab.research.google.com/.

Select the repository

`https://github.com/cabana-online/Tutorial_Long_Reads_Genome_Assembly `

After a brief search, you will see the notebook:

`Pt2_NGS&GenomeAssembly.ipynb`

Select it and you will see the notebook open.

### Module 3: [Hands-on tutorial ](Pt3_Hands_On.ipynb)

We created a Google Collab file that performs genome assembly, quality evaluation, gene annotation, alignment and genome comparison with the reference genome. Remember to set up the connection with Drive to the folder that you’re using. 

Data with reads and the reference genome can be found [here](https://zenodo.org/records/14969215).

This module also contains a **Results interpretation** section and you will evaluate all the output files created.

Go to https://colab.research.google.com/.

Select the repository

`https://github.com/cabana-online/Tutorial_Long_Reads_Genome_Assembly`

After a brief search, you will see the notebook:

`Pt3_Hands_On.ipynb`

Select it and you will see the notebook open.


## Authors & Affiliations: 

- Johanna Stepanian, MSc, Universidad de los Andes

- Laura Gonzalez, PhD, Universidad de los Andes

- Luisa Sacristan, MSc, Universidad de los Andes

- Jorge Duitama, PhD, Universidad de los Andes