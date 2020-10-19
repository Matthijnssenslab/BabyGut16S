# BabyGut16S
Code used for the analysis of 16S data from infant gut samples, published by Beller *et al*. (insert ref).
## Data
Data files include: 
- metadata file (metadata information per sample)
- abundance file (read counts per ASV, per taxon, after preprocessing as described in the paper)
- taxonomy file (per ASV, the taxonomic information)

And a seperate folder containing the results from projecting the infant samples to adult samples from the FGFP dataset.
## Code
The code is written in R, in a Markdown file that can be converted to pdf (or html) using knitr.
Don't forget to change the working directory (*Workdir* variable) at line 22.
## Output
All figures are saved in an automatically created output directory.
An example of how it normally looks is shown.
