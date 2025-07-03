# Inputs-data-
Supporting input files for my published article on MLIP development for the codes used e.g. FHI-Aims, Gulp, MACE janus

# Inputs-data

This repository contains input and supporting data files used in our recently submitted article to PCCP involving "Modelling Silica using MACE-MP Machine Learnt Interatomic Potentials" for zeolite and silica materials modelling.

These files are provided to ensure **transparency**, **reproducibility**, and to meet the journal's requirements for open data.

## 🔧 Included Directories and Files

### `FHI-Aims/`
This folder contains input files used for density functional theory (DFT) calculations with the [FHI-aims](https://fhi-aims.org/) code.

**Contents may include:**
- `control.in` – Calculation settings
- `geometry.in` – Atomic structure
- `output/` – Results and logs (if included)

### `GULP/`
Contains input data related to classical force field simulations with [GULP (General Utility Lattice Program)](https://gulp.curtin.edu.au/).

**Typical files:**
- `.gin` – GULP input file
- `.gout` – Output or log files (optional)

### `MACE-MLIP/` (Janus MLIP)
This directory includes model files, configuration data, and training/validation structures used with the **Janus MACE MLIP** framework (https://github.com/ACEsuit/mace-foundations).

**May contain:**
- `cif file`,  – That is used for optimisation
- `config.yaml` – Model or training configuration
- `models` – all three trained models used in this study

## 📄 Article Reference

**Article title**: *"Modelling Silica using MACE-MP Machine Learnt Interatomic Potentials "*  
**Authors**: Jamal Abdul Nasir, Jingcheng Guan, Woongkyu Jee, Scott M. Woodley, Alexey A. Sokol, C, Richard A. Catlow* Alin-Marin Elena*  
**Journal**: Physical Chemistry Chemical Physics 
**DOI**: `DOI or link` **

## 📜 License

This data is made publicly available for academic use. Please cite the related publication if you use any of the files.

---

Feel free to open an issue if you have questions about the files or wish to request additional data.

