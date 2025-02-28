---
layout: page
title: Recommended reading
tagline: Madeleine J. Zurowski
permalink: /recommended_reading
ref: reading
order: 5
---

This page is a collection of papers and resources I have found helpful in building up my physics knowledge (many of which I still refer to regularly). There are also some interesting thoughts on research as a student and a supervisor in [this](https://mjzurowski.github.io/files/psg.pdf) chapter of a postgraduate survival guide I helped to write many moons ago.

# Contents
1. [Technical papers](#papers)
2. [Software and computing resources](#software)
3. [Plots and presentation](#style)

# Technical papers<a name="papers"></a>

## Dark matter as a concept
* [PDG DM review](https://pdg.lbl.gov/2024/web/viewer.html?file=../reviews/rpp2024-rev-dark-matter.pdf) (Baudis and Profumo): general overview of the motivation for DM and various test methods (direct, indirect, collider)
* [History of Dark Matter](https://arxiv.org/abs/1605.04909) (Bertone and Hooper): overview of the historical perspective/evolution of the fields' understanding of DM

## Building and testing DM observables
* [Lewin and Smith](https://www.sciencedirect.com/science/article/abs/pii/S0927650596000473): basic derivation of direct detection DM rates.
* [The Effective Field Theory of Dark Matter Direct Detection](https://arxiv.org/abs/1203.3542): a more detailed theoretical formalism for general DM interactions.
* [A Refinement of the Standard Halo Model for Dark Matter Searches](https://arxiv.org/pdf/1810.11468): refinement of the standard velocity distribution assumptions. Good description of how this is calculated and included in DM rates.
* [Chapter of my thesis](https://mjzurowski.github.io/files/rate_calcs.pdf): combines the EFT formalism and more general velocity distribution (without worrying too much how either are derived) with experimental effects to get the observation rate (similar to Lewin and Smith with a more detailed interaction model).
* [Recommended conventions for reporting results from direct dark matter searches](https://arxiv.org/pdf/2105.00599): generally good conventions put together by members of a range of different DM direct detection experiments. Also provides a baseline DM model to make sure comparisons between experiments are in an “apples to apples regime”.
* [Direct Detection of sub-GeV Dark Matter with Semiconductor Targets](https://arxiv.org/pdf/1509.01598): similarly to the EFT paper, this lays out a theoretical formalism for sub-GeV DM scattering with electron.
* [Migdal Effect in Dark Matter Direct Detection Experiments](https://arxiv.org/abs/1707.07258): original paper that explores the concept of the Migdal effect and derives the relevant parameters
* [Directly detecting sub-GeV dark matter with electrons from nuclear scattering](https://arxiv.org/pdf/1711.09906): a great example of the application of the Migdal effect to experimental limits

## Statistics
* [Statistics for Nuclear and Particle Physics](https://www.cambridge.org/highereducation/books/statistics-for-nuclear-and-particle-physicists/9544B39F3244D9457BEC324CD34F1571#overview) (Lyons)
* [Statistical Data Analysis](https://www.sherrytowers.com/cowan_statistical_data_analysis.pdf) (Cowan)
* [PDG statistics review](https://pdg.lbl.gov/2020/reviews/rpp2020-rev-statistics.pdf) (Cowan)
* [Asymptotic formulae for likelihood-base tests of new physics](https://arxiv.org/abs/1007.1727) (Cowan, Cranmer, Gross and Vitells)

## Detector concepts
* [Radiation Detection and Measurement](https://indico-tdli.sjtu.edu.cn/event/171/contributions/2123/attachments/982/1592/Knoll4thEdition.pdf) (Knoll)
* [Introduction to Solid State Physics](http://metal.elte.hu/~groma/Anyagtudomany/kittel.pdf) (Kittel)
* [The Art of Electronics](https://kolegite.com/EE_library/books_and_lectures/%D0%95%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%B8%D0%BA%D0%B0/_The%20Art%20of%20Electronics%203rd%20ed%20%5B2015%5D.pdf) (Horowitz and Hill)

### SuperCDMS
* [Snowmass Contribution](https://arxiv.org/abs/2203.08463)
* [Superconducting detectors for particle physics](https://arxiv.org/abs/2111.08875)
* [Transition edge sensors](https://link.springer.com/chapter/10.1007/10933596_3) (Irwin and Hilton)

### SABRE
* [Technical design review](https://arxiv.org/abs/2411.13889)
* [Background simulation and sensitivity projection](https://arxiv.org/abs/2205.13849)

# Software and computing resources<a name="software"></a>
* [Installing python](https://realpython.com/installing-python/)
* [Slurm user guide](https://slurm.schedmd.com/quickstart.html)
* [git user guide](https://github.com/git-guides)

## Latex
* Guides to getting started: [1](https://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/), [2](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
* [Cloud use](https://www.overleaf.com/project) (overleaf) - this is the recommended user interface for Latex
* Local installation guides;
    * [MiKTeX](https://miktex.org/download) (Windows, Mac, Linux)
    * [Mac only install guide](https://sourabhbajaj.com/mac-setup/LaTeX/)

## Geant4
* [Main documentation](https://geant4.web.cern.ch/docs/) - this includes generic installation guide
* [Tutorials from past workshops](https://geant4.web.cern.ch/docs/tutorials?past)
    * These generally link to an Indico page - if you go to timetable you should be able to access the material via the attachment for each session
    * Another recommended option is to try editing the Geant4 examples that the software download comes with (e.g., adjusting geometry shapes, adding additional physics lists etc.)

## ROOT
* [ROOT manual](https://root.cern/manual/)
* [RooFit introduction](https://root.cern/download/roofit-strasbourg-v10.pdf)
* [RooFit tutorials](https://root.cern/doc/v628/group__tutorial__roofit.html) (available in both C and python)
* [RooStats introduction](https://indico.cern.ch/event/72320/contributions/2082590/attachments/1037204/1478053/schott_2009.11.26_roostats_tutorials.pdf)
* [RooStats tutorials](https://root.cern/doc/v630/group__tutorial__roostats.html) (note not all of these are available in python)

# Plots and presentation<a name="style"></a>
* [How to visually present data](https://github.com/cajohare/HowToMakeAPlot) (O’Hare)
* [Craft of Scientific Presentations](https://sharif.edu/~namvar/index_files/Scientific-Presentation.pdf) (Alley)
* [Writing Mathematics](https://entropiesschool.sciencesconf.org/data/How_to_Write_Mathematics.pdf) (Halmos)
* [Elements of Style](https://www.nature.com/articles/nphys724) (Nature)
* [Coloring for Colorblindness](https://davidmathlogic.com/colorblind/): site that lets you generate and test colour scheme comptability with different types of colourblindness.
