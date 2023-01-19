# SCMCCA
Similarity Corrected Multiple Canonical Correlation Analysis (SCMCCA) is a novel computational method for integrative analysis of the scRNA-seq data. SCMCCA considers 
both maximizing the variance of each dataset, and maximizing the canonical correlation between different datasets. It also includes the k-nearest-neighbor matching 
across different datasets. SCMCCA can be formulated as an optimization problem defined on stiefel manifold and we propose an accelerated Riemannian trust-region 
algorithm to solve it.

Downstream integrative analyses , such as joint clustering, are available based on the canonical results of SCMCCA.

# Installation
Extract the ZIP file (or clone the git repository). Then add the SCMCCA-main/ folder to your path in MATLAB.

You can also use the "Set Path" dialog in MATLAB, or run the addpath function from your command window or startup script.
