## Meta-analysis on human gut microbiota in Colorectal Cancer 

### Introduction



### Directory

*  **Assay**: All the scripts for data analysis
*  **Result**: The results by scripts
*  **Study**: The materials about the project

```bash
# tree -L 3 /disk/user/zouhua/project/MetaAnalysis_CRC
/disk/user/zouhua/project/MetaAnalysis_CRC
├── Assay
│   ├── 00.RawData
│   │   ├── DownloadData_v0.Rmd
│   │   ├── DownloadData_v0.nb.html
│   │   ├── DownloadData_v1.Rmd
│   │   ├── DownloadData_v1.nb.html
│   │   ├── preprocess.Rmd
│   │   └── preprocess.nb.html
│   ├── 01.Phenotype
│   │   ├── Distribution.Rmd
│   │   ├── Distribution.nb.html
│   │   ├── Phenotype.Rmd
│   │   └── Phenotype.nb.html
│   ├── 02.GlobalView
│   │   ├── GlobelView.Rmd
│   │   ├── GlobelView.nb.html
│   │   ├── MDS.Rmd
│   │   ├── MDS.nb.html
│   │   ├── PERMANOVA.Rmd
│   │   └── PERMANOVA.nb.html
│   ├── 03.Diversity
│   │   ├── diveristy.Rmd
│   │   └── diveristy.nb.html
│   ├── 04.Composition
│   │   ├── barplot.Rmd
│   │   ├── barplot.nb.html
│   │   ├── sankey.Rmd
│   │   └── sankey.nb.html
│   ├── 05.Comparison
│   │   ├── Difference.Rmd
│   │   ├── Difference.nb.html
│   │   ├── STAMP.Rmd
│   │   └── STAMP.nb.html
│   ├── 06.Network
│   │   ├── SparCC.Rmd
│   │   └── SparCC.nb.html
│   ├── 07.RandomForest
│   │   ├── 01.ExprSetDivid.Rmd
│   │   ├── 01.ExprSetDivid.nb.html
│   │   ├── 02.Difference.Rmd
│   │   ├── 02.Difference.nb.html
│   │   ├── 03.RandomForest.Rmd
│   │   ├── 03.RandomForest.html
│   │   ├── 03.RandomForest.nb.html
│   │   ├── 04.Biomarker_visualization.Rmd
│   │   ├── 04.Biomarker_visualization.nb.html
│   │   └── README.md
│   ├── 08.SupportVectorMachine
│   │   ├── SVM.Rmd
│   │   └── SVM.nb.html
│   └── 09.MaAslin2
│       ├── MaAslin2.Rmd
│       └── MaAslin2.nb.html
├── README.md
├── Result
│   ├── Biomarker
│   │   └── RF_model
│   ├── Differential
│   │   ├── CRC_HC_DEA.csv
│   │   ├── CRC_HC_DEA_limma.csv
│   │   └── CRC_HC_DEA_wilcox.csv
│   ├── MaAsLin2
│   │   └── species
│   ├── Network
│   │   └── species_SparCC.RDS
│   ├── Phenotype
│   │   └── phenotype.csv
│   └── Profile
│       ├── genus_profile.RDS
│       ├── genus_profile.tsv
│       ├── genus_profile_TSE.RDS
│       ├── phylum_profile.RDS
│       ├── phylum_profile.tsv
│       ├── phylum_profile_TSE.RDS
│       ├── species_profile.RDS
│       ├── species_profile.tsv
│       └── species_profile_TSE.RDS
└── Study
    └── curatedMetagenomicData
        ├── CRC_marker_abundance_Origin.RDS
        ├── CRC_marker_presence_Origin.RDS
        ├── CRC_pathway_abundance_Origin.RDS
        └── CRC_relative_abundance_Origin.RDS
```



### Contributors

1. [Hua Zou](zouhua1@outlook.com)

   