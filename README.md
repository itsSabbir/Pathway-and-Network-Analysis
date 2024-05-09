# Data Set Pathway and Network Analysis

Welcome to the repository for Assignment 3 in the Bioinformatics course (BCB420). This project extends from previous assignments by integrating gene network mapping and interactions using sophisticated bioinformatics tools and methods.

## Project Objective

The main goal of this project is to utilize the ranked gene data from Assignment 2 to perform non-thresholded pathway analysis, visualize these interactions with Cytoscape, and explore the network dynamics. This involves detailed gene set enrichment analysis (GSEA) and network visualization to uncover relationships between genes and the diseases they may influence.

## Timeline

- **Estimated Time**: 8 hours
- **Time Used**: 20 hours
- **Start Date**: 2022/04/13
- **Completion Date**: 2022/04/20

## Repository Structure

This repository includes all necessary data, scripts, and outputs for conducting and understanding the pathway and network analysis performed in this assignment.

### Key Features

- Non-thresholded gene set enrichment analysis using ranked gene data
- Visualization of gene set enrichment in Cytoscape
- Detailed interpretation of pathway and network analysis results
- Comparative analysis with previous thresholded methods from Assignment 2

## Non-Thresholded Gene Set Enrichment Analysis

### Approach

The gene set enrichment analysis was conducted using the ranked list of genes from Assignment 2. This approach helps to understand the broader biological implications of gene expressions and their interactions without arbitrary cutoffs, providing a holistic view of the gene networks.

### Methodology

- **Gene Ranking**: Genes were ranked based on their differential expression, incorporating metrics such as log fold change and t-values.
- **Enrichment Analysis Tool**: GSEA was utilized to perform the enrichment analysis, identifying significant pathways and interactions among the ranked genes.

## Visualization with Cytoscape

### Network Creation

Gene interaction networks were visualized using Cytoscape, leveraging the data from GSEA to create comprehensive network maps that illustrate the intricate relationships and pathways among the genes.

### Network Details

- **Enrichment Map Creation**: Nodes and edges in the map represent genes and their interactions, respectively.
- **Annotation and Theming**: Networks were annotated based on gene function and pathway involvement, highlighting key themes and novel pathways that may be relevant to the study.

## Interpretation and Detailed View of Results

### Analysis and Conclusions

- **Supporting Evidence**: The analysis sought to correlate the observed gene interactions with known biological pathways and mechanisms, supporting or contradicting existing hypotheses or findings from referenced studies.
- **Novel Findings**: Special attention was given to 'dark matter' genes, which are significantly expressed but not annotated in any known pathway, presenting potential new areas for research.

## Repository Contents

- **R Notebook (.Rmd and .html formats)**: Contains the complete analysis code, explanations, and results.
- **Data/**: Includes all datasets used in the analyses.
- **Figures/**: Contains all figures and network diagrams generated, stored in a way that ensures they are referenced correctly in the notebook.
- **docs/**: Additional documentation and references.

## Usage Instructions

1. **Clone this Repository**: Download all files to your local machine.
2. **Explore the R Notebook**: Run the R Notebook to replicate the analysis and explore the methodologies used.
3. **View the Results**: Detailed results are documented within the notebook and can also be viewed in the HTML output.

## Submission Details

- **R Markdown File Naming**: The R Markdown file is named `A3_<yourname>.Rmd` and is located in the root directory.
- **HTML Output**: After knitting the R Notebook to HTML, the file is submitted through the university's learning management system and linked in the repository README for easy access.

## Further Reading and Resources

- **Pathway Enrichment Analysis**: Reimand et al., 2019 discuss methodologies for pathway enrichment analysis and visualization using tools like g:Profiler and Cytoscape. [PubMed Link](https://www.ncbi.nlm.nih.gov/pubmed/30610321)

## References

This project incorporates insights and methodologies from a broad range of sources to ensure a robust analysis framework. All tools and datasets used are thoroughly referenced in the project documentation.