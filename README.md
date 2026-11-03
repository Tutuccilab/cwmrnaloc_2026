# cwmrnaloc_2026

Cell wall mRNA localisation analysis, 2026

Analysis by Edward Wallace Edward.Wallace@ed.ac.uk, and colleagues.

Supporting the preprint:

**Multi-colour smFISH with automated cell-cycle quantification reveals distinct localization of co-regulated cell wall mRNAs in Saccharomyces cerevisiae yeast**.
Marah Jnied, Sander C. van Otterdijk, Kelly van Rossum, Florence Berbain, Carlotta Meyer, Philipp Savakis, Evelina Tutucci, Edward Wallace.

We will update this repository with the preprint doi when we submit it to bioRxiv.

The analysis in this repository is interdependent with the pipelines, buddy and napari-buddy, [doi: 10.5281/zenodo.23771337](https://doi.org/10.5281/zenodo.23771337).



# Contents

## data

- budSegmentationData20260311.csv - cell statistics and smFISH counts underlying the analysis
- README_budSegmentationData20260311.txt - README file describing the data in that .csv file

## Rmd

- BudSegmentationAnalysis.Rmd - all the analysis code in R markdown format
- BudSegmentationAnalysis.html - the output of running BudSegmentationAnalysis.Rmd including all figures.

## figure

Selected figures output by BudSegmentationAnalysis.Rmd, in .pdf format, to be put in the preprint

## output

Processed data output by BudSegmentationAnalysis.Rmd for alternative analysis. The folder contains lists of cells randomly selected by cell cycle phase, to use in validation analysis and as "representative cells" for paper figures.
