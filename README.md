# FtrifloraEpichloe

```
The project is organized under the main directory FtrifloraEpichloe/, structured into two
major modules: Plant_host/ and Fungal_endophyte/. Each module contains data, scripts, and/or
outputs corresponding to specific stages of the analysis. Folder system as follows:

FtrifloraEpichloe/
│
├── Plant_host/
│   └── data/                                                                      
│       └── flow_cytometry_host.csv            # Genome size estimations via flow cytometry for the Fescues.
│                                              Variables: Host_sp (plant host species);
│                                              measurement_ID (measurement identification code);
│                                              nucleids (number of particles counted, sample); 
│                                              nucleids_ST (number of particles counted, standard); 
│                                              mean (arithmetic mean of the fluorescence intensities, sample); 
│                                              mean_ST (arithmetic mean of the fluorescence intensities, standard);
│                                              CV (coefficient of Variation, sample); 
│                                              CV_ST (coefficient of Variation, standard);
│                                              pg/2C (estimated genome size, sample); 
│                                              pg/2C_ST (known genome size, standard);
│
├── Fungal_endophyte/
│   ├── data/
│   │   ├── outputs_script_1/                  # Output files of the morphological analyses (from script_1.Rmd)
│   │   ├── outputs_script_2/                  # Phylogenetic trees and their support values files (from script_2.Rmd) 
│   │   ├── Phylogenetic_analysis/
│   │   │   │  
│   │   │   ├── MSA/                           # Multiple sequence alignments (FASTA format)
│   │   │   └── TREES/                         # Raw phylogenetic trees obtained from IQTREE and ASTRAL. 
│   │   │   
│   │   ├── culture_growth_dataset.csv         # Dataset for culture growth rate analysis (input script_1.Rmd).
│   │   │                                      This file is semicolon-delimited and uses a comma as the decimal separator.
│   │   │                                      Variables: IndID (measurement identification code);
│   │   │                                      Ind (short name for each isolate);
│   │   │                                      Rep (replicate code within each isolate);
│   │   │                                      Day (Day the measurement was made);
│   │   │                                      Diameter (diameter of the culture in mm)
│   │   │                                      Species (holobiont idntification code).
│   │   │ 
│   │   ├── spores_dataset.csv                 # Morphometric data of asexual reproductive structures (input in script_1.Rmd). 
│   │   │                                      This file is semicolon-delimited and uses a comma as the decimal separator.
│   │   │                                      Variables: Species (holobiont identification code);
│   │   │                                      SampleID (measurement identification code); 
│   │   │                                      Ind (short name for each isolate);   
│   │   │                                      conidL (conidial length in μm);
│   │   │                                      conidW (conidial width in μm); 
│   │   │                                      conidiogL (conidiogenous cell length in μm);
│   │   │                                      conidiogW (conidiogenous cell basal width in μm); 
│   │   │                                      conidA (conidial area in μm²). 
│   │   │
│   │   ├── alkaloids_PCR.xlsx                 # PCR results for the biosynthetic genes selected in the study
│   │   │
│   │   └── flow_cytometry_endophyte.csv       # Genome size estimations of Epichloë festucae via flow cytometry.
│   │                                          Variables: Host_sp (plant host species identification);
│   │                                          Endophyte_sp (endophyte species);
│   │                                          Measurement_ID (measurement identification code);
│   │                                          nucleids (number of particles counted, sample); 
│   │                                          nucleids_ST (number of particles counted, standard); 
│   │                                          mean (arithmetic mean of the fluorescence intensities, sample); 
│   │                                          mean_ST (arithmetic mean of the fluorescence intensities, standard);
│   │                                          CV (coefficient of Variation,sample); 
│   │                                          CV_ST (coefficient of Variation, standard);
│   │                                          pg/1C (estimated genome size, sample); 
│   │                                          pg/1C_ST (known genome size, standard);             
│   │
│   └── scripts/
│       ├── script_1.Rmd                       # RMarkdown: Morphological analysis of fungal endophytes.
│       ├── script_2.Rmd                       # Rmarkdown: Visualization and editing of phylogenetic trees (raw figures).
└

```
