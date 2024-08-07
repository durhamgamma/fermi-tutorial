# fermi-tutorial
Tutorial to conduct fermi analysis including fermitools and fermipy

## Installation Instructions

Simply clone this repo into a new directory called "fermi-tutorial" e.g.

```git clone https://github.com/durhamgamma/fermi-tutorial.git fermi-tutorial```

## Running the tutorials

Navigate into your newly created directory called "fermi-tutorial", and then into the approprate tutorial folder e.g. tutorial1-fermidata. From there you can run the tutorials by simply opening your chosen tutorial number using Jupyter e.g.

```jupyter notebook tutorial-1-fermidata.ipynb```


Once you have the tutorial notebook open just follow the instructions and complete the learning exercises as required.

## Dependecies
To run this tutorial you need [Fermitools](https://github.com/fermi-lat/Fermitools-conda/wiki) v2.2.0 and [Fermipy](https://fermipy.readthedocs.io/en/latest/index.html) v1.2.2 installed.

> [!IMPORTANT]
> We have included Fermi data files in this repo so you will need to use Git LFS otherwise the data files will be corrupted on download. Follow GitHub's [installation instructions for the Git Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage?platform=mac)

Tutorial 2 requires you to run both the jupyter notebook as well as running fermitools from the command line.

Whilst these tutorials can be run using your own installation of the fermitools and fermipy, they were really designed to be run inside Durham's fermi tutorial docker image. You can build the one provided in the [fermi-tutorial-docker](https://github.com/durhamgamma/fermi-tutorial-docker) repo.

More instructions about running the tutorial using the docker container can be found in the README of the [fermi-tutorial-docker](https://github.com/durhamgamma/fermi-tutorial-docker) repo.

If you do run these tutorials using your own installation of the fermitools and fermipy, then you may need to adjust any paths accordingly to the requirements of your system.
