# $x$-index
Accurately evaluating scholarly influence is essential for fair academic assessment. However, traditional bibliometric indicators (e.g., $np$, $tc$, and the $h$-index) often favor hyperprolific authors over those with deeper, long-term impact. 

We propose the $x$-index, a novel citation-based metric that conceptualizes citation as a process of knowledge diffusion. By weighting citations according to the collaborative proximity between citing and cited authors, the x-index captures both the depth and breadth of influence within evolving academic networks. 

Empirical analyses show that the x-index significantly improves the rankings of Turing Award recipients while reducing those of hyperprolific authors, better aligning rankings with recognized academic merit.

# Dataset
This project utilizes the **[DBLP-Citation-network V18 dataset](https://www.aminer.cn/open/article?id=655db2202ab17a072284bc0c)** from the Aminer Citation Network Dataset, a large-scale, disambiguated citation network covering the computer science literature. The full dataset contains over 6.7 million papers and 73.7 million citation links spanning up to July 2025.

# Code Structure
*(Source code is currently being refactored and will be fully uploaded upon publication.)*
- `src/`: Core Python scripts for data processing, distance computation, and statistical significance testing.
- `data/`: Directory for the raw dataset and intermediate caching files.
- `results/`: Output directories for generated statistical analyses (e.g., Wilcoxon signed-rank tests) and plot data.
  
