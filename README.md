### Code for the following publication: "*Population density influences genetic connectivity in the Canary Islands endemics Viola cheiranthifolia and Viola guaxarensis*"

This GitHub repository provides a step-by-step guide to the analyses presented in the publication "*Population density influences genetic connectivity in the Canary Islands endemics Viola cheiranthifolia and Viola guaxarensis*". This study is part of the GENCLIMA project, which aims to evaluate functional connectivity among high-mountain and laurel forest species in the Canary Islands, with a focus on preserving genetic diversity and mitigating the impacts of climate change. Here, we specifically investigate the genetic connectivity of *Viola cheiranthifolia* and *Viola guaxarensis*.

The project's specific objectives are to (1) identify correlations between genetic diversity and environmental variables, (2) assess the functional connectivity, (3) determine which landscape variables influence gene flow in each species, and (4) evaluate changes in connectivity under projected climate change scenarios.

<img src="framework-connectivity-analysis.jpg" alt="framework" width="1000">


### 00-Sampling
The sampling scheme used here is individual-based, which enhances our ability to detect complex interactions of environmental variables on gene flow patterns and allows for a more precise identification of landscape factors independently influencing gene flow. 


### 01-Genetic diversity
This script evaluates the relationship between genetic diversity and environmental variables for Teide Violets. It processes spatial and genetic data and performs functions such as extracting environmental variables from raster layers and calculating population-level genetic distance means. Linear models are applied to test the relationship of each variable with genetic diversity. Collinearity between variables is assessed, and results are visualized.

### 02-Gravity models
This section provides a comprehensive script for building and evaluating gravity models to study gene flow between individuals. The code integrates spatial and genetic data, extracts relevant environmental variables, assesses collinearity, and constructs gravity models to assess functional connectivity and identify key landscape factors influencing genetic connectivity. Additionally, it includes tools for evaluating how well models fit the data and for comparing their performance.


### 03-Climate modelling
This script evaluates how climate change alters connectivity and gene flow by comparing gravity models fitted for current and future scenarios. It integrates climate data, gene flow values, site coordinates, and topographic variables to derive environmental statistics for both nodes and edges. Connectivity under present conditions is then contrasted with connectivity under future climate projections, allowing us to quantify changes and identify implications for conservation planning.


### Citation
If you use the code, data-processing workflow, or materials provided in this repository, please cite the associated publication:

Sarmiento Cabello S, Murphy M, Sosa PA, Fernández de Castro AG, Martín Esquivel JL, Rodríguez-Rodríguez P. Population density influences genetic connectivity in the Canary Islands endemics Viola cheiranthifolia and Viola guaxarensis. Ann Bot. 2025 Dec 9. doi: 10.1093/aob/mcaf317. PMID: 41362993.






