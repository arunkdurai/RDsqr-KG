# RD<sup>2</sup>-KG: Multiscale Biomedical Knowledge Graph for Explainable Drug Repurposing in Rare Diseases
## Overview
The lack of potential treatment candidates is a critical issue in managing rare diseases. A knowledge-based approach, incorporating relations and concepts from multiple types of biological databases, can allow for the discovery of new uses for existing drug candidates inexpensively and expeditiously. We have assembled RD<sup>2</sup>-KG, a knowledge graph incorporating various negative and positive biological interactions collected from over 10 publicly available standard biomedical databases. The entities and relations in RD<sup>2</sup>-KG are aligned to ensure data traceability and support AI studies. Only high-quality interactions are represented in RD2-KG making it highly reliable and permitting precise predictions. RD<sup>2</sup>-KG has 105,241 nodes and 4,472,526 edges.
## Features
* Large-scale Integration: 105,241 nodes and 4,472,526 edges representing positive and negative biological interactions.
* High Quality Data: Only high-confidence interactions are included for accuracy and reliability.
* Traceability: All entities and relations are aligned for reproducibility and transparency.
* AI-Ready: Suitable for graph neural networks and link prediction tasks.
* Drug Repurposing Validated: Link prediction on Parkinson’s Disease and Muscular Dystrophy using CompGCN, supported with literature validation of mechanism hypotheses.

## Usage
* Prepare the knowledge graph data using the provided scripts and guidelines.
* Perform link prediction experiments using CompGCN or other graph learning models.
* Run analyses to generate and validate drug-disease hypotheses.

## Folders
* KG_datasets/   -         preprocessed and mapped datasets used for building the knowledge graph
* Knowledge_Graph/    -    scripts to constructing the graph and a zip file with the knowledge graph
* Mapping/            -    mapping notebooks for subject-object relationships
* Preprocessing/       -   preprocessing scripts

Create two additional folders within RD<sup>2</sup>-KG
* Datasets/ – This folder should contain all the raw datasets required for the project.
Download the datasets and place them in their respective subfolders before running any scripts.

* Preprocessed_datasets/ – This folder stores all intermediate and processed files generated from the preprocessing scripts.
Running the preprocessing pipeline will automatically generate and save outputs here.

## Data Sources
RD<sup>2</sup>-KG integrates biological interactions from top public databases (see publication for full list), ensuring comprehensive representation of the biomedical landscape.

## Citation
If you use RD<sup>2</sup>-KG, please cite the following publication:
* Annadurai, A. Arun Kumar, Bhandary, S., Hegde, S. G., & Chatterjee, J. (2025). Assembling a multiscale biomedical knowledge graph for explainable drug repurposing in rare diseases. Network Modeling Analysis in Health Informatics and Bioinformatics, 14, 37. [https://link.springer.com/article/10.1007/s13721-025-00532-2](https://doi.org/10.1007/s13721-025-00532-2)

## Authors
A Arun Kumar, 
Samarth Bhandary,
Swathi Gopal Hegde,
Dr. Jhinuk Chatterjee
