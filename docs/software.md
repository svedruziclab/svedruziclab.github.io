# Software

Research work in BioSFGroup relies on computer software, with a strong preference towards the usage of [free and open-source software](https://opensource.com/article/17/11/open-source-or-free-software), starting from the operating system. Our workstations and laptops run [Ubuntu LTS](https://ubuntu.com/download/desktop), while [our supercomputer Bura](https://cnrm.uniri.hr/bura/) runs [Red Hat Enterprise Linux](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux).

The reasons for the preference towards the usage of free and open-source software are the limited use conditions, limited extensibility, and license cost of proprietary software, which limit the science that we can do. The developments that we do can be found on [our GitHub organization](https://github.com/svedruziclab).

The list below is limited to the software we use; for a more comprehensive list of available free and open-source software for molecular modeling, see:

- [Pirhadi, S.](https://sums.ac.ir/page-EnmncrcMegaMenu/en/298/form/pId47531), [Sunseri, J.](https://pitt.edu/~jss97/), and [Koes, D. R.](https://bits.csb.pitt.edu/) [Open source molecular modeling.](https://doi.org/10.1016/j.jmgm.2016.07.008) Journal of Molecular Graphics and Modelling 69, 127–143 (2016); [the updateable list of software on GitHub Pages](https://opensourcemolecularmodeling.github.io/), [the repository on GitHub](https://github.com/OpenSourceMolecularModeling/OpenSourceMolecularModeling.github.io)
- [ABC of cheminformatics](https://github.com/filipsPL/ABChemoinformatics) by [Filip Stefaniak](https://filipspl.github.io/)
- [Directory of computer-aided Drug Design tools](https://www.click2drug.org/) by [Swiss Institute of Bioinformatics](https://www.sib.swiss/)

## Structure visualization, analysis, and editing

### PyMOL

**PyMOL** ([homepage](https://pymol.org/), [Wikipedia](https://en.wikipedia.org/wiki/PyMOL)) is free and open source molecular visualization system, maintained by [Schrödinger](https://www.schrodinger.com/).

PyMOL is available as a package in [Arch Linux](https://www.archlinux.org/packages/community/x86_64/pymol/), [Debian](https://tracker.debian.org/pkg/pymol), and [Fedora](https://apps.fedoraproject.org/packages/pymol).

Specific uses:

- [Visual approach to the construction of &QMMM section of CP2K input file](https://github.com/pmamonov/pymol-cp2k-qmmm)

### VMD

**VMD** ([homepage](https://www.ks.uiuc.edu/Research/vmd/), [Wikipedia](https://en.wikipedia.org/wiki/Visual_Molecular_Dynamics)) is a freely available molecular visualization system used for the displaying and animation of biomolecular systems. VMD stands for *Visual Molecular Dynamics*, and it is maintained by [Theoretical and Computational Biophysics Group](https://www.ks.uiuc.edu/) at [the University of Illinois at Urbana-Champaign](https://illinois.edu/). VMD is distributed with source code under [VMD License](https://www.ks.uiuc.edu/Research/vmd/current/LICENSE.html), and it is not free and open-source software.

VMD is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/vmd/), but not in Debian and Fedora.

Specific uses:

- [VMD psfgen Plugin](https://www.ks.uiuc.edu/Research/vmd/plugins/psfgen/)
- [DynamicBonds](https://www.ks.uiuc.edu/Research/vmd/current/ug/node58.html)

### UCSF Chimera

**UCSF Chimera** ([homepage](https://www.cgl.ucsf.edu/chimera/), [Wikipedia](https://en.wikipedia.org/wiki/UCSF_Chimera)) is a freely available visualization and analysis software. Chimera works with single molecules as well as supramolecular assemblies, sequence alignments, results of docking, and molecular dynamics trajectories. Chimera is distributed in a binary form under [UCSF Chimera Non-Commercial Software License Agreement](https://www.cgl.ucsf.edu/chimera/license.html), and it is not free and open-source software.

UCSF Chimera is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/ucsf-chimera/), but not in Debian and Fedora.

Specific uses:

- [Dock Prep](https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/dockprep/dockprep.html), [AutoDock Vina](https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/vina/vina.html), and [ViewDock](https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/viewdock/viewdock.html)
- [Add Charge](https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/addcharge/addcharge.html)
- [MD Movie](https://www.cgl.ucsf.edu/chimera/docs/ContributedSoftware/movie/movie.html)

### wxMacMolPlt

**wxMacMolPlt** ([homepage](https://brettbode.github.io/wxmacmolplt/), [Wikipedia](https://en.wikipedia.org/wiki/WxMacMolPlt)) is a free and open-source graphical user interface for preparation and visualization of the input and output files for the GAMESS quantum chemistry package.

wxMacMolPlt is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/wxmacmolplt/) and [Fedora](https://apps.fedoraproject.org/packages/wxmacmolplt), but not in Debian.

### MODELLER

**MODELLER** ([homepage](https://salilab.org/modeller/), [Wikipedia](https://en.wikipedia.org/wiki/MODELLER)) is a proprietary software for modelling of tertiary structures of proteins.

MODELLER is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/modeller/), but not in Debian and Fedora.

### Avogadro

**Avogadro** ([homepage](https://avogadro.cc/), [Wikipedia](https://en.wikipedia.org/wiki/Avogadro_%28software%29)) is a free and open-source molecule editor. It is maintained by [Kitware](https://www.kitware.com/). Avogadro comes in two versions: orange Avogadro, and blue [Avogadro 2](https://www.openchemistry.org/projects/avogadro2/).

Avogadro (first version, the orange one) is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/avogadro/), [Debian](https://tracker.debian.org/pkg/avogadro), and [Fedora](https://apps.fedoraproject.org/packages/avogadro). Avogadro 2 (the blue one) is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/avogadro2-git/) and [Fedora](https://apps.fedoraproject.org/packages/avogadro2), but not in Debian.

### ChemAxon Marvin

**ChemAxon Marvin** ([homepage](https://chemaxon.com/products/marvin), [Wikipedia](https://en.wikipedia.org/wiki/ChemAxon)) is a freely available software for drawing and visualization of molecules. Marvin is distributed in binary form under [ChemAxon EULA](https://docs.chemaxon.com/display/docs/End+User+License+Agreement), and it is not free and open-source software.

Marvin is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/marvin/), but not in Debian and Fedora.

### Cresset

**Torch** ([homepage](https://www.cresset-group.com/products/torch/)) is a proprietary software.

Torch is not available as a package in Arch Linux, Debian, and Fedora.

**Spark** ([homepage](https://www.cresset-group.com/products/spark/)) is a proprietary software.

Spark is not available as a package in Arch Linux, Debian, and Fedora.

**Forge** ([homepage](https://www.cresset-group.com/products/forge/)) is a proprietary software.

Forge is not available as a package in Arch Linux, Debian, and Fedora.

## Electrostatic calculation, protein-ligand docking, and molecular simulation

### APBS and PDB2PQR

**APBS** ([homepage](https://www.poissonboltzmann.org/), [Wikipedia](https://en.wikipedia.org/wiki/APBS_%28software%29)) is a free and open-source software for computing the numerical solution of the Poisson-Boltzmann equation that describes electrostatic interactions between molecular solutes.

APBS is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/apbs/), [Debian](https://tracker.debian.org/pkg/apbs), and [Fedora](https://apps.fedoraproject.org/packages/apbs).

**PDB2PQR** ([homepage](https://www.poissonboltzmann.org/), [Wikipedia](https://en.wikipedia.org/wiki/PDB2PQR)) is a free and open-source software for preparation of molecular structures for electrostatic calculation.

PDB2PQR is available in [Arch User Repository](https://aur.archlinux.org/packages/pdb2pqr/) and [Debian](https://tracker.debian.org/pkg/pdb2pqr), but not in Fedora.

### AutoDock and AutoDock Vina

**AutoDock** ([homepage](https://autodock.scripps.edu/), [Wikipedia](https://en.wikipedia.org/wiki/AutoDock)) and **AutoDock Vina** ([homepage](https://vina.scripps.edu/), [Wikipedia](https://en.wikipedia.org/wiki/AutoDock_Vina)) are free and open source protein-ligand docking software packages.

AutoDock is available as a package in [Debian](https://tracker.debian.org/pkg/autodocksuite) and [Fedora](https://apps.fedoraproject.org/packages/autodocksuite), but not in Arch Linux. AudoDock Vina is available in [Arch User Repository](https://aur.archlinux.org/packages/autodock-vina/) and [Debian](https://tracker.debian.org/pkg/autodock-vina), but not in Fedora.

### rDock and RxDock

**rDock** ([homepage](https://rdock.gitlab.io/), [Wikipedia](https://en.wikipedia.org/wiki/RDock)) and **RxDock** ([homepage](https://rxdock.gitlab.io/), [Wikipedia](https://en.wikipedia.org/wiki/RxDock)) are free and open source protein-ligand docking software packages designed for high throughput virtual screening.

rDock and RxDock are not available as packages in Arch Linux, Debian, and Fedora.

### GROMACS

**GROMACS** ([homepage](https://www.gromacs.org/), [Wikipedia](https://en.wikipedia.org/wiki/GROMACS)) is a free and open-source molecular dynamics package. It supports classical molecular mechanics and provides an interface to a number of quantum mechanics software packages.

GROMACS is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/gromacs/), [Debian](https://tracker.debian.org/pkg/gromacs), and [Fedora](https://apps.fedoraproject.org/packages/gromacs).

Specific uses:

- [Protein-Ligand Complex](http://www.mdtutorials.com/gmx/complex/)
- [Free Enegy Calculation](https://group.miletic.net/en/tutorials/gromacs/4-methane-fe/)
- [Umbrella Sampling](http://www.mdtutorials.com/gmx/umbrella/)
- [Coarse Grained](http://cgmartini.nl/) (proteins in lipid bilayers, protein-protein interactions, protein kinases)

### NAMD

**NAMD** ([homepage](https://www.ks.uiuc.edu/Research/namd/), [Wikipedia](https://en.wikipedia.org/wiki/NAMD)) is a freely available molecular dynamics package.

NAMD is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/namd/), but not in Debian and Fedora.

### PLUMED

**PLUMED** ([homepage](https://www.plumed.org/), [Wikipedia](https://en.wikipedia.org/wiki/PLUMED)) is a a free and open source library for free energy calculations in molecular systems.

PLUMED is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/plumed/), but not in Debian and Fedora.

### CP2K

**CP2K** ([homepage](https://www.cp2k.org/), [Wikipedia](https://en.wikipedia.org/wiki/CP2K)) is a free and open-source molecular dynamics package. It supports both quantum and classical molecular mechanics and allows using both of them in the same simulation with QM/MM.

CP2K is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/cp2k/), [Debian](https://tracker.debian.org/pkg/cp2k), and [Fedora](https://apps.fedoraproject.org/packages/cp2k).

Specific uses:

- [Nudged Elastic Band](https://www.cp2k.org/exercises:2015_ethz_mmm:nudged_elastic_band)
- [QM/MM](https://www.cp2k.org/exercises:2015_uzh_molsim:chp_cu111)

### NWChem

**NWChem** ([homepage](https://nwchemgit.github.io/), [Wikipedia](https://en.wikipedia.org/wiki/NWChem)) is a free and open source molecular dynamics package.

NWChem is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/nwchem/), [Debian](https://tracker.debian.org/pkg/nwchem), and [Fedora](https://apps.fedoraproject.org/packages/nwchem).

### GAMESS (US)

**GAMESS (US)** ([homepage](https://www.msg.chem.iastate.edu/gamess/), [Wikipedia](https://en.wikipedia.org/wiki/GAMESS_%28US%29)) is a freely available quantum chemistry software.

GAMESS (US) is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/gamess/), but not in Debian and Fedora.

## Topology generation and file format conversion

### AmberTools and acpype

**AmberTools**, a part of **Amber** molecular dynamics package ([homepage](https://ambermd.org/), [Wikipedia](https://en.wikipedia.org/wiki/AMBER)), is a freely available set of tools for preparation and analysis of molecular dynamics simulations. Many of the tools are free and open-source software.

AmberTools is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/ambertools), but not in Debian and Fedora (there is [an effort to package AmberTools for Fedora](https://fedoraproject.org/wiki/AmberTools)).

**ACPYPE** ([homepage](https://github.com/t-/acpype), [Google Code archive](https://code.google.com/archive/p/acpype/)) is a free and open-source software for generation of molecular topologies. It uses [Antechamber and GAFF](https://ambermd.org/antechamber/antechamber.html) from AmberTools.

ACPYPE is not available as a package in Arch Linux, Debian, and Fedora.

### Open Babel

**Open Babel** ([homepage](https://openbabel.org/), [Wikipedia](https://en.wikipedia.org/wiki/Open_Babel)) is free and open-source software for conversion between different chemical file formats. It provides both command line and graphical user interfaces.

Open Babel is available as a package in [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/openbabel/), [Debian](https://tracker.debian.org/pkg/openbabel), and [Fedora](https://apps.fedoraproject.org/packages/openbabel).

## Chemical kinetics simulation and quantitative molecular interactions

### KinTek Explorer

**KinTek Explorer** ([homepage](https://kintekcorp.com/overview/)) is proprietary software for chemical kinetic data analysis.

KinTek Explorer is not available as a package Arch Linux, Debian, and Fedora.

### COPASI

**COPASI** ([homepage](http://copasi.org/), [Wikipedia](https://en.wikipedia.org/wiki/COPASI)) is a free and open-source software for simulation and analysis of biochemical networks and their dynamics.

COPASI is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/copasi/) and [Fedora](https://apps.fedoraproject.org/packages/COPASI), but not in Debian.

### Tenua

**Tenua** ([homepage](http://bililite.com/tenua/), [Wikipedia](https://en.wikipedia.org/wiki/Tenua)) is a free and open-source software for chemical kinetics simulation.

Tenua is not available as a package in Arch Linux, Debian, and Fedora.

## Data processing and visualization

### R and Bio3D

**R** ([homepage](https://www.r-project.org/), [Wikipedia](https://en.wikipedia.org/wiki/R_%28programming_language%29)) is a free and open-source software environment and a programming language for statistical computing.

R is available as a package in, [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/r/), [Debian](https://tracker.debian.org/pkg/r-base), and [Fedora](https://apps.fedoraproject.org/packages/R).

**Bio3D** ([homepage](http://thegrantlab.org/bio3d/)) is an R package for analyzing the protein sequence, structure, and trajectory data.

Bio3D is available as a package in [Debian](https://tracker.debian.org/pkg/r-cran-bio3d), but not in Arch Linux and Fedora.

### Maxima

**Maxima** ([homepage](https://maxima.sourceforge.io/), [Wikipedia](https://en.wikipedia.org/wiki/Maxima_%28software%29)) is a free and open source computer algebra system.

Maxima is available as a package in [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/maxima/), [Debian](https://tracker.debian.org/pkg/maxima), and [Fedora](https://apps.fedoraproject.org/packages/maxima).

### LibreOffice Calc

**LibreOffice** ([homepage](https://www.libreoffice.org/), [Wikipedia](https://en.wikipedia.org/wiki/LibreOffice)) is a free and open source office suite. The spreadsheet component is called [Calc](https://www.libreoffice.org/discover/calc/).

LibreOffice is available as a package in [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/libreoffice-fresh/) ([still branch](https://www.archlinux.org/packages/extra/x86_64/libreoffice-still/)), [Debian](https://tracker.debian.org/pkg/libreoffice), and [Fedora](https://apps.fedoraproject.org/packages/libreoffice).

### gnuplot

**gnuplot** ([homepage](http://www.gnuplot.info/), [Wikipedia](https://en.wikipedia.org/wiki/Gnuplot)) is a free and open source graphing software.

Gnuplot is available as a package in, [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/gnuplot/), [Debian](https://tracker.debian.org/pkg/gnuplot), and [Fedora](https://apps.fedoraproject.org/packages/gnuplot).

### SciDAVis

**SciDAVis** ([homepage](http://scidavis.sourceforge.net/), [Wikipedia](https://en.wikipedia.org/wiki/SciDAVis)) is a free and open source visualization software.

SciDAVis is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/scidavis/), [Debian](https://tracker.debian.org/pkg/scidavis), and [Fedora](https://apps.fedoraproject.org/packages/scidavis).

## Laboratory protocols, methods, notes, and other documentation

### Docutils and Sphinx

**Docutils** ([homepage](https://docutils.sourceforge.io/), [Wikipedia](https://en.wikipedia.org/wiki/ReStructuredText)) is a free and open source text processing software for converting plaintext-like [reStructuredText](https://docutils.sourceforge.io/rst.html) into LaTeX/PDF and HTML.

Docutils are available as a package in [Arch Linux](https://www.archlinux.org/packages/community/any/python-docutils/), [Debian](https://tracker.debian.org/pkg/python-docutils), and [Fedora](https://apps.fedoraproject.org/packages/python-docutils).

**Sphinx** ([homepage](https://www.sphinx-doc.org/), [Wikipedia](https://en.wikipedia.org/wiki/Sphinx_%28documentation_generator%29)) is a free and open-source documentation generator that builds on top of Docutils and makes it easy to create beautiful documentation.

Sphinx is available as a package in [Arch Linux](https://www.archlinux.org/packages/community/any/python-sphinx/), [Debian](https://tracker.debian.org/pkg/sphinx), and [Fedora](https://apps.fedoraproject.org/packages/python-sphinx).

### Pandoc

**Pandoc** ([homepage](https://pandoc.org/), [Wikipedia](https://en.wikipedia.org/wiki/Pandoc)) is a free and open source document converter between different markup formats.

Pandoc is available as a package in [Arch Linux](https://www.archlinux.org/packages/community/x86_64/pandoc/), [Debian](https://tracker.debian.org/pkg/pandoc), and [Fedora](https://apps.fedoraproject.org/packages/pandoc).

### LibreOffice Writer

**LibreOffice** ([homepage](https://www.libreoffice.org/), [Wikipedia](https://en.wikipedia.org/wiki/LibreOffice)) is a free and open source office suite. The word processor component is called [Writer](https://www.libreoffice.org/discover/writer/).

LibreOffice is available as a package in [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/libreoffice-fresh/) ([still branch](https://www.archlinux.org/packages/extra/x86_64/libreoffice-still/)), [Debian](https://tracker.debian.org/pkg/libreoffice), and [Fedora](https://apps.fedoraproject.org/packages/libreoffice).

### Graphviz

**Graphviz** ([homepage](https://www.graphviz.org/), [Wikipedia](https://en.wikipedia.org/wiki/Graphviz)) is a free and open source graph visualization software initially developed by [AT&T Labs](https://about.att.com/innovation/labs).

Graphviz is available as a package in [Arch Linux](https://www.archlinux.org/packages/extra/x86_64/graphviz/), [Debian](https://tracker.debian.org/pkg/graphviz), and [Fedora](https://apps.fedoraproject.org/packages/graphviz).

### Font Awesome

**Font Awesome** ([homepage](https://fontawesome.com/), [Wikipedia](https://en.wikipedia.org/wiki/Font_Awesome)) is a free and open source set of icons [licensed under the terms of Creative Commons Attribution 4.0 license](https://fontawesome.com/license).

Font Awesome is available as a package in [Arch](https://www.archlinux.org/packages/community/any/ttf-font-awesome/) [Linux](https://www.archlinux.org/packages/community/any/otf-font-awesome/), [Debian](https://tracker.debian.org/pkg/fonts-font-awesome), and [Fedora](https://apps.fedoraproject.org/packages/fontawesome-fonts).

## Software development

### Visual Studio Code

**Visual Studio Code** ([homepage](https://code.visualstudio.com/), [Wikipedia](https://en.wikipedia.org/wiki/Visual_Studio_Code)) is a proprietary source-code editor built on a number of free and open-source software projects. Notable extensions are [Python for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [C/C++ for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools).

Visual Studio Code is available as a package in [Arch User Repository](https://aur.archlinux.org/packages/visual-studio-code-bin/), but not in Debian and Fedora. Official binaries for Debian and Fedora (among others) are [provided by Microsoft](https://code.visualstudio.com/Download).
