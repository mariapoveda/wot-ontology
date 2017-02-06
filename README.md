# vicinity-ontology-wot summary
Repository for collaborative edition of the VICINITY ontology module for the Web Of Things domain. This ontology is being developed within the context of the [VICINITY H2020 project] (http://vicinity2020.eu/).

To include issues for this domain (that is, things you need this ontology to represent or improve): https://github.com/mariapoveda/vicinity-ontology-wot/issues

The ontology latest release is published: (draft) http://iot.linkeddata.es/def/wot/

Relevant links:

- [WoT interest group current practices] (http://w3c.github.io/wot/current-practices/wot-practices.html)
- [WoT demos] (https://www.w3.org/WoT/demos/td2ttl/)

# How We Work
This document provides a brief overview of the process for developing the [WOT ontology](http://iot.linkeddata.es/def/wot/). It contains a minimal amount of technical detail sufficient to explain our approach to collaborative ontology development.

## Structure of the GitHub repository

The sytem selected to store the ontology is GitHub. Each module in VICINITY ontology will be stored in a repository. We will also have an aggregator repository which integrates all the modules and submodules of VICINITY Ontology (not available yet). Each repository will include:

An evaluation folder where the evaluation reports of the ontology are stored.

A documentation folder where the documentation reports of the ontology are stored, including the requirements and the description of the ontology.

## GitHub Flow

For developing an ontology using GitHub the developers can follow the [GitHub good practices guides](https://guides.github.com/). Basically, the central repository holds a main branch called master where the source code reflects the production-ready state.To work on something new, the ontology developers have to create a descriptively named branch off the master, so that the rest of the developers can see what is being worked on. Once the branch is created, the developers add changes to the ontology and commit them. Each commit has to be associated with a commit message, which is a description explaining why a particular change was made, so that the developers can roll back changes if a bug is found. After adding commits, the ontology developers have to open a pull request to discuss the modifications done to the ontology. If everyone agree, the pull request is accepted and the changes are merged to the master branch.

## Development process

Once the ontology is implemented (for this step you can use an ontology editor like [Protégé](http://protege.stanford.edu/)), it has to be evaluated and documented before its publication.

### Ontology Evaluation
The ontology has to be evaluated according to syntactic, model and semantic errors. The ontology developers have to guarantee that the ontology meets all the requirements identified.

### Ontology Documentation

The ontology development team in collaboration with the domain experts has to generate the ontology documentation. This documentation has to include an HTML description of the ontology which describes the classes, properties and data properties of the ontology, and the license URI and title being used.

### Ontology Publication

Releases are published in the official site by the project webmaster, so the ontology and its documentation will be accessible to all the users. The site will publish additionally for each ontology the repositiory where is stored, its issue tracker and the requirements associated to each ontology.

### Ontology Maintenance
If the ontology developers or domain experts want to update or add new requirements to the ontology they have to create a new issue in the GitHub issue tracker. This issue will let the developers to start a discussion and accept or regret the modifications. GitHub also provide a good practices guide for [creating issues](https://guides.github.com/features/issues/). 
