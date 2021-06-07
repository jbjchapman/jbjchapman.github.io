---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- 2017 Eng.D, Univeristy College London & National Physical Laboratory
  * Winner of Stoneham-Marshall Prize for Outstanding Research in Condensed Matter Theory
- 2014 MRes, Molecular Modelling and Materials Science, UCL
  * Distinction
- 2013 MPhys, Theoretical Physics, Univeristy of York
  * Starred 1st Class with Distinction (average test score 86 %)

## Work experience

- 2017-Present: Postdoctoral Research Scientist, United Kingdom Atomic Energy Authority, Culham Centre for Fusion Energy
  * Developing scalable models and interdisciplinary design solutions for radiation resistant materials for fusion reactors.
  * Leading the design, integration and testing of new functionality into SPILADY simulation package.
  * Successfully written grants to secure over 15 million core-hours on national HPC facilities for high-throughput big-data calculations.
  * Constructed high-dimensional dataset maintained in a relational database (SQLite) to standardise varied longitudinal simulation data.
  * Built python based tools to train supervised machine learned interatomic potentials (including numpy, scipy, scikit-learn, sqlite3 and pandas packages).
  * Developed an artifical neural network (ANN) suitable for modelling magnetic materials with spin degrees of freedom.
  * Performed exploratory data analysis supporting CCFE’s successful Athena Swan Bronze Award as a member of the Diversity Panel.

- 2013-2017: Doctoral Research, Joint Enterprise with University College London and the National Physical Laboratory
  * Thesis: "Improving the Functional Control of Ferroelectrics using Insights from Atomistic Modelling". Supervised by Prof. D. M. Duffy & Dr A. V. Kimmel.
  * Supervised successful MSc project
  * Instigated international collaborations with Queens University Belfast and Carnegie Institute of Science to combine simulation results with experimental data.
  * Developed new models and analysis software to characterise properties of perovskite ferroelectric materials and built tools, algorithms and software hierarchy to achieve research aims. Software used by institutions in UK, Germany and USA.
  * Applied advanced analytic and mathematical competency to take large and complex data sets and extract meaningful quantitative information.
  * Demonstrable project management skills handling several innovative concurrent projects, completing deliverables and meeting deadlines, factoring available resources, constraints and slippages
 
- 2009-2013: Undergraduate, University of York
  * Dissertation: "Time-Dependent Quantum Dynamics of Interacting Electrons - The Role Correlation". Supervised by Prof. R. W. Godby.
  * Project designed to improve exchange-correlation energy functionals used in time-dependent density functional theory.
  * Optimised pre-existing software (iDEA code) in an unfamiliar language. Achieved a 28-fold improvement in speed and a reduced memory requirement, extending the scope and impact of the project. Enabled the reverse engineering of exact Kohn-Sham potentials for strongly correlated materials.
  * Selected by the Department of Physics and secured funding through the Nuffield Foundation.
  * Formulated new methods to numerically model the exact behaviour of fully interacting electrons subject to time dependent potentials and applied novel correlation measures to illuminate features in quantum dynamics neglected in local and adiabatic approximations.
  * Mentor for the Physics Undergraduate Consultancy Service (2011-2013). Voluntary advisor and tutor the Physics Department walk-in consultancy service.
  * Department of Physics Ambassador (2011-2013) - Our team won the "Vice Chancellor Silver Award for Outstanding Achievement"
  * Elected Physics Society Sports Sectretary (2011-2012)
  * Elected Physics Society Social Sectretary (2010-2011)

## Skills

- Numerical modelling, data manipulation and visualisation on Windows and Unix environments: 
  * Languages: Python, C++, Fortran, C, Latex, Bash (shell scipt)
  * Tools: Numpy, Scipy, Scikit-Learn, Pandas, Multiprocessing, OpenMP, Jupyter Notebooks, matplotlib, gnuplot, Microsoft Office
  * Databases: SQLite, Excel
  * Version Control: Git, GitHub, GitLab
- Scalable Scientific Computing:
  * Density Functional Theory calculations (VASP, CASTEP, OPENMX, CP2K, iDEA). Including:
    * Exchange-correlation functional development for Time Dependent Density Functional Theory (TDDFT);
    * Phonon calculations using Density Functional Perturbation Theory (DFPT);
    * Non-collinear calculations using Constraint Functional DFT.
  * Molecular Dynamics simulations (SPILADY, DLPOLY,LAMMPS)
    * Interatomic Potential development: EAM, Finnis-Sinclair, Buckingham, Linear, Artificial Neural Network
  * Spin Lattice Dynamics (SPILADY) including longitudinal fluctuations.
  * Experience on national supercomputing facilities including Archer and Archer2, UK and Marconi-FUSION, Italy.
- Mentoring
  * Physics Undergraduate Consultancy Service
  * Supervised MSc project
  * Physics Department Ambassador for prospective students
- Communication
  * Lead author of publications in high-impact journals.
  * Presented talks, posters and lead discussions regarding innovative research at dozens of international conferences, seminars, workshops and meetings.
  * Team player instigating successful international collaborations

## Awards and Grants
* 15 million core-hours granted for use on Marconi-FUSION supercomputer (2019-Present)
* Marshal Stoneham Award for Outstanding Research in Condensed Matter Physics (2018)
* IEEE ISAF-IWATMD-PFM conference student paper finalist (2017)
* Best Computational Research Poster - UCL Chemistry Department (2016)
* Condensed Matter Theory Grant for use on the ARCHER supercomputer (2014-2017)
* IEEE Ultrasonics, Ferroelectrics and Frequency Control Society Student Grant (2015)
* Joint recipient of the Vice Chancellor Silver Award for Outstanding Achievement (2012)
* Nuffield Foundation Bursary for summer scholarship in the University of York Condensed Matter Theory Group (2012)
* Joint recipient of Engineering Education Scheme Grant (2007) 

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Posters
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

