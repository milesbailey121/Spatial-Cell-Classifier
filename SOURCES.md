# STHELAR (bioRxiv 10.1101/2025.07.11.664123) – data sources

Processed dataset (BioStudies S-BIAD2146): https://ftp.ebi.ac.uk/biostudies/fire/S-BIAD/146/S-BIAD2146/Files/STHELAR/
Code: https://github.com/MICS-Lab/STHELAR

Already downloaded here:
- `STHELAR_manifest.json`, `STHELAR.tsv` – full file listing of the deposit
- `summary_all_labels_per_slide/*.parquet` – per-cell phenotype labels keyed by Xenium `cell_id`
  (use `cells_final_label` / `cells_final_label_group`; no coordinates)

## Raw 10x Xenium pages (Table 1). Needed per page: H&E OME-TIFF, H&E alignment CSV, Xenium output bundle (for cells.parquet)

| Slide(s) used | Ref | 10x page |
|---|---|---|
| bone_s0, bone_marrow_s0, bone_marrow_s1 | 18 | https://www.10xgenomics.com/datasets/human-bone-and-bone-marrow-data-with-custom-add-on-panel-1-standard |
| brain_s0 | 19 | https://www.10xgenomics.com/datasets/ffpe-human-brain-cancer-data-with-human-immuno-oncology-profiling-panel-and-custom-add-on-1-standard |
| breast_s0 | 20 | https://www.10xgenomics.com/datasets/xenium-ffpe-human-breast-with-custom-add-on-panel-1-standard |
| breast_s1 | 21 | https://www.10xgenomics.com/datasets/ffpe-human-breast-using-the-entire-sample-area-1-standard |
| breast_s3 | 22 | https://www.10xgenomics.com/datasets/ffpe-human-breast-with-custom-add-on-panel-1-standard |
| breast_s6 | 24 | https://www.10xgenomics.com/datasets/xenium-prime-ffpe-human-breast-cancer |
| cervix_s0 | 25 | https://www.10xgenomics.com/datasets/xenium-prime-ffpe-human-cervical-cancer |
| colon_s1 | 26 | https://www.10xgenomics.com/datasets/human-colon-preview-data-xenium-human-colon-gene-expression-panel-1-standard |
| colon_s2 | 27 | https://www.10xgenomics.com/datasets/ffpe-human-colorectal-cancer-data-with-human-immuno-oncology-profiling-panel-and-custom-add-on-1-standard |
| heart_s0 | 28 | https://www.10xgenomics.com/datasets/human-heart-data-xenium-human-multi-tissue-and-cancer-panel-1-standard |
| kidney_s0, kidney_s1 | 29 | https://www.10xgenomics.com/datasets/human-kidney-preview-data-xenium-human-multi-tissue-and-cancer-panel-1-standard |
| liver_s0, liver_s1 | 30 | https://www.10xgenomics.com/datasets/human-liver-data-xenium-human-multi-tissue-and-cancer-panel-1-standard |
| lung_s1 | 32 | https://www.10xgenomics.com/datasets/ffpe-human-lung-cancer-data-with-human-immuno-oncology-profiling-panel-and-custom-add-on-1-standard |
| lung_s3 | 33 | https://www.10xgenomics.com/datasets/xenium-human-lung-cancer-post-xenium-technote |
| lymph_node_s0 | 34 | https://www.10xgenomics.com/datasets/preview-data-xenium-prime-gene-expression |
| ovary_s0 | 35 | https://www.10xgenomics.com/datasets/ffpe-human-ovarian-cancer-data-with-human-immuno-oncology-profiling-panel-and-custom-add-on-1-standard |
| ovary_s1 | 36 | https://www.10xgenomics.com/datasets/xenium-prime-ffpe-human-ovarian-cancer |
| pancreatic_s0 | 37 | https://www.10xgenomics.com/datasets/pancreatic-cancer-with-xenium-human-multi-tissue-and-cancer-panel-1-standard |
| pancreatic_s1 | 38 | https://www.10xgenomics.com/datasets/ffpe-human-ductal-adenocarcinoma-data-with-human-immuno-oncology-profiling-panel-1-standard |
| pancreatic_s2 | 39 | https://www.10xgenomics.com/datasets/ffpe-human-pancreas-with-xenium-multimodal-cell-segmentation-1-standard |
| prostate_s0 | 40 | https://www.10xgenomics.com/datasets/xenium-prime-ffpe-human-prostate |
| skin_s1 | 41 | https://www.10xgenomics.com/datasets/human-skin-data-xenium-human-multi-tissue-and-cancer-panel-1-standard |
| skin_s2 | 42 | https://www.10xgenomics.com/datasets/human-skin-preview-data-xenium-human-skin-gene-expression-panel-add-on-1-standard |
| skin_s3 | 43 | https://www.10xgenomics.com/datasets/human-skin-preview-data-xenium-human-skin-gene-expression-panel-1-standard |
| skin_s4 | 44 | https://www.10xgenomics.com/datasets/xenium-prime-ffpe-human-skin |
| tonsil_s0, tonsil_s1 | 45 | https://www.10xgenomics.com/datasets/human-tonsil-data-xenium-human-multi-tissue-and-cancer-panel-1-standard |

Not needed: ref 23 (breast_s4/s5 duplicate s0/s3), ref 31 (lung_s0 excluded for bad alignment).
