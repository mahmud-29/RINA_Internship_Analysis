# RINA Crop Science Internship Analysis

## Project Overview

This repository contains the Python codes, processed outputs, tables, figures and analysis workflows completed during my Data Science internship project with RINA Crop Science at Charles Darwin University.

The project focuses on analysing seed germination and early seedling growth using RGB and multispectral imagery under different treatments and environmental conditions.

## Experimental Trials

### First Trial

The first trial established the initial dataset organisation, image-processing workflow, feature extraction and trial-level analysis.

### Second Trial

The second trial expanded the analysis with additional samples, diagnostic outputs, processed tables and comparison figures.

### Third Trial

The third trial analysed 12 experimental trays under:

- Microbe and non-microbe treatments
- Ideal growing conditions
- Heat-stress conditions
- Moisture-stress conditions
- Indoor and outdoor environments

## Analysis Workflow

1. Dataset organisation and validation
2. Image manifest creation
3. Missing-band and duplicate-file checking
4. RGB and multispectral image processing
5. Vegetation-index calculation
6. Plot-level feature extraction
7. Tray-level data aggregation
8. Treatment and environmental comparisons
9. Statistical summaries
10. Figure and table generation

## Features Analysed

- NDVI
- GNDVI
- NDRE
- SAVI
- RGB green fraction
- Canopy coverage
- Growth score
- Germination proxy measurements

## Repository Structure

```text
RINA_Internship_Analysis/
├── codes/
│   ├── 01_first_trial_analysis.ipynb
│   ├── 02_second_trial_analysis.ipynb
│   └── 03_third_trial_analysis.ipynb
├── outputs/
│   ├── First Trial/
│   ├── Second Trial/
│   └── Third Trial/
├── README.md
├── requirements.txt
└── .gitignore