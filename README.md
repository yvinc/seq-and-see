# Data Sources

## Hypothalamic Preoptic Region Single-Cell Dataset
![](https://img.shields.io/badge/license-CC0%201.0-green.svg?style=flat)

The dataset provides molecular, spatial, and functional single-cell profiling of the hypothalamic preoptic region using MERFISH. It was retrieved from the study: "Molecular, spatial and functional single-cell profiling of the hypothalamic preoptic region" by Moffitt et al. (2018) published in *Science* ([DOI: 10.1126/science.aau5324](https://doi.org/10.1126/science.aau5324)). The raw data can be downloaded directly from [Dryad](https://doi.org/10.5061/dryad.8t8s248).

## Dataset Description

The dataset, `Moffitt_and_Bambah-Mukku_et_al_merfish_all_cells.csv`, contains properties of cells measured with MERFISH, including:

-   **Cell ID**: Unique identifier for each cell.

-   **Animal ID**: Unique identifier for the animal.

-   **Animal sex**: Gender of the animal.

-   **Behavior**: Behavioral treatment ('Naïve' for no treatment).

-   **Bregma**: Approximate slice location in bregma coordinates.

-   **Centroid X/Y**: Cell centroid coordinates in µm.

-   **Cell class**: Major cell class (e.g., 'Ambiguous' for putative doublets).

-   **Neuron cluster_ID**: Neuronal cluster assignment (empty for non-neurons).

-   **Gene expression**: Expression values for 135 genes (combinatorial smFISH, counts per cell volume scaled by 1000) and 21 genes (sequential FISH, fluorescence units per µm³). 'NaN' for Fos indicates unmeasured genes. Five blank control barcodes are included.

## Usage

The dataset is provided under [CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)


## Citation

Moffitt, J.R., Bambah-Mukku, D., Eichhorn, S.W., Vaughn, E., Shekhar, K., Perez, J.D., Rubinstein, N.D., Hao, J., Regev, A., Dulac, C., Zhuang, X. (2018). Data from: Molecular, spatial and functional single-cell profiling of the hypothalamic preoptic region. Dryad. <https://doi.org/10.5061/dryad.8t8s248>