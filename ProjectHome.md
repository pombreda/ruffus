# Project Documentation #
Project documentation is available here:
http://www.ruffus.org.uk

Ruffus is a Computation Pipeline library for python. It is open-sourced, powerful and user-friendly, and widely used in bioinformatics for managing dependencies in parallel workflows.

# The _Ruffus_ provides automatic support for #
  * Managing dependencies
  * Parallel jobs
  * Re-starting from arbitrary points, especially after errors
  * Display of the pipeline as a flowchart
  * Reporting


Computational pipelines are often conceptually quite simple, especially if we breakdown the process into simple stages, or separate **tasks**.

Each stage or **task** in a computational pipeline is represented by a python function.

Each python function can be called in parallel to run multiple **jobs**.

It was originally written for scientific research (bioinformatics/genome analysis pipelines).

# Design goals #
> (In order)
  * Elegance
  * Lightweight
  * Unintrusiveness
  * Flexible
  * Practical (i.e. powerful)

There is no hidden magic so _Ruffus_ is completely customisable.

# Installation #
```
sudo pip install ruffus --upgrade
```
or
```
easy_install -U ruffus
```

# Latest Source Code #
The latest (unreleased) source code **in development** can be downloaded from the Google repository here
```
git clone https://bunbun68@code.google.com/p/ruffus/ 
```
or from the git hub repository:
```
git clone https://github.com/bunbun/ruffus.git
git clone git@github.com:bunbun/ruffus.git
```

The git hub code tracks the day to day development of Ruffus while the Google repository is slightly more stable.

# Tutorial #
An simple tutorial is available here:
http://www.ruffus.org.uk/tutorials/new_tutorial/introduction.html

# Cylindrophis ruffus #
Is the name of the red-tailed pipe snake from Hong Kong where the author comes from
http://www.ruffus.org.uk/why_ruffus.html#why-ruffus





























