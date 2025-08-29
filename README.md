# MGVI Molecular Docking Workshop

Welcome to the **workshop on "Introduction to AlphaFold3 and Molecular Docking"**. This comprehensive 3-day workshop will guide you through the fundamentals of protein structure analysis, AlphaFold3 usage, and molecular docking techniques using HIV-1 protease as our primary case study.

## 🎯 Workshop Overview

This hands-on workshop combines theoretical knowledge with practical skills, covering everything from basic protein structure concepts to advanced molecular docking simulations. You'll learn to use industry-standard tools like ChimeraX, AutoDock Vina, and AlphaFold3 to understand protein-ligand interactions.

## 📋 Prerequisites & Setup

### System Requirements

- **Operating System**: Windows 10/11, macOS 10.14+, or Linux (e.g.,Ubuntu 22.04)
- **RAM**: Minimum 8GB, recommended 16GB
- **Storage**: At least 5GB free space
- **Internet**: Stable connection for downloading software and databases

### Step 1: Install Conda (Miniconda/Anaconda)

**If you already have Conda installed, skip to Step 2.** Please note the installation process below is only for MacOS and Linux systems.

#### For macOS

1. Download Miniconda from: <https://docs.conda.io/en/latest/miniconda.html>
2. Download the "Miniconda3 macOS 64-bit pkg" installer
3. Run the installer and follow the prompts
4. Open **Terminal** application
5. Verify installation by typing: `conda --version`

#### For Linux

1. Download Miniconda from: <https://docs.conda.io/en/latest/miniconda.html>
2. Download the "Miniconda3 Linux 64-bit" script
3. Open terminal and navigate to download directory
4. Run: `bash Miniconda3-latest-Linux-x86_64.sh`
5. Follow the prompts and restart your terminal

### Step 2: Clone the Repository

1. **Clone this repository** to your local machine:

```bash
git clone https://github.com/AnubhavKafle/MGVI_workshop.git
cd MGVI_workshop
```

### Step 3: Create the Workshop Environment

1. **Open your terminal/command prompt**:

2. **Create the conda environment** from the YAML file present in the folder (workshop.yml):

```bash
conda env create -f workshop.yml
```

3.**Activate the environment**:

```bash
conda activate mgvi_docking
```

### Step 4: Verify the installation

**Test your setup** by running these commands in your activated environment:

```bash
conda info
```

You should see the environment name `mgvi_docking` in the output.

### Step 5: Test Jupyter

**Test Jupyter** by running:

```bash
jupyter --version
```

You should see the version number in the output.

**Test ChimeraX** by opening the application from your desktop/applications folder.

### Troubleshooting

**Environment creation problems**:

```bash
conda env create -f workshop.yml
```

**Environment activation problems**:

```bash
conda activate mgvi_docking
```

**Jupyter problems**:

```bash
jupyter --version
```

**ChimeraX problems**:

```bash
chimerax --version
```

**ChimeraX installation problems**:

```bash
chimerax --version
``` 

**AutoDock Vina(conda package) problems**:
The pdbqt files in the folder cannot be overwritten. So, if the error message says that the file already exists, you can delete the file and try again with the python notebook.

The docking workflow is in the "Molecular-Docking-Ligand-Protein-workflow.ipynb" file. Make sure the code can access pdb files in **your local directory**.

## 📅 Daily Schedule

### Day 1: Foundations

- **Protein Structure 101** - *Led by Mothar*
- **Understanding AlphaFold**: Capabilities and limitations
- **Hands-on**: AlphaFold3 server familiarization
- **Lab Setup**: Environment testing and tool verification

### Day 2: Target Analysis

- **Case Study**: HIV-1 protease structure and function
- **Mutation Analysis**: Understanding structural variants
- **Visualization Skills**: Advanced ChimeraX techniques
- **Ligand Chemistry**: Binding patterns and interactions
- **Measurement Tools**: Distance analysis in ChimeraX

### Day 3: Molecular Docking

- **Docking Theory**: Principles and algorithms
- **Structure Preparation**: Protein and ligand processing
- **Binding Site Definition**: Search space optimization
- **Simulation Execution**: Running AutoDock Vina
- **Results Analysis**: Interpretation and visualization

## 🛠️ Tools & Software

| Tool | Purpose | Installation |
|------|---------|--------------|
| **ChimeraX** | Molecular visualization | Separate download |
| **AutoDock Vina** | Molecular docking | Conda package |
| **AlphaFold3 Server** | Structure prediction | Web-based |
| **RDKit** | Chemical informatics | Conda package |
| **OpenBabel** | Chemical file conversion | Conda package |
| **Jupyter Notebook** | Interactive analysis | Conda package |

## 📚 Essential Resources

### Documentation & Tutorials

- [ChimeraX User Guide](https://www.rbvi.ucsf.edu/chimerax/docs/user/index.html)
- [AutoDock Vina Documentation](https://autodock-vina.readthedocs.io/en/latest/)
- [RDKit Documentation](https://www.rdkit.org/docs/)

### Databases & Servers

- [AlphaFold Structure Database](https://alphafold.ebi.ac.uk/)
- [AlphaFold3 Server](https://deepmind.google/science/alphafold/)
- [Fold Seek Structure Search](https://search.foldseek.com/)
- [Protein Data Bank (PDB)](https://www.rcsb.org/)

### Additional Tools

- [OpenMM Molecular Dynamics](https://openmm.org/)
- [PDBFixer Structure Cleanup](https://github.com/openmm/pdbfixer)

## 📧 Contact Information

**Workshop Organizer**: Anubhav Kaphle  
**Institution**: AEHRC, CSIRO  
**Email**: [anubhav.kaphle@csiro.au](mailto:anubhav.kaphle@csiro.au)

---

## ⚡ Quick Start Checklist

Before the workshop begins, ensure you have:

- [ ] Conda installed and working
- [ ] Repository cloned to your local machine
- [ ] `mgvi_docking` environment created from YAML file
- [ ] Environment activated successfully
- [ ] All required packages installed (verified with test commands)
- [ ] ChimeraX downloaded and installed
- [ ] Jupyter Notebook can launch
- [ ] Stable internet connection

