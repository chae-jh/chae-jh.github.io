---
title:          "WAD: a wavelet-based linear programming method using L1-minimal reconstruction loss for accessible chromatin data deconvolution"
date:           2025-12-01
selected:       true
pub:            "Preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  We present WAD (Wavelet-based Accessible chromatin Deconvolution), a principled framework for robust estimation of cell type composition of bulk accessible chromatin data such as from the ATAC-seq assay. To determine informative reference cell profiles from single-cell accessible chromatin studies, WAD leverages wavelet-based denoising to suppress stochastic noise while preserving local chromatin continuity. Cell type proportion inference is reformulated as an L1-minimal linear programming problem, enabling scalable and interpretable solutions. Across 700 in silico pseudo-bulk mixtures generated from single-cell data, WAD achieved a consistently lower mean absolute error (MAE) and higher concordance (r > 0.85) than existing machine learning-based methods. These results demonstrate that wavelet-based feature extraction provides a biologically grounded and computationally efficient approach to chromatin signal deconvolution.
cover:          /assets/images/covers/WAD.png
authors:
  - Jeongho Chae
  - Benjamin McMichael
  - Terrence S. Furey
links:
  Code: https://github.com/chae-jh/WAD
  Paper: https://www.biorxiv.org/content/10.1101/2025.11.26.690776v1.full
---
