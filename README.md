# Tutorial
This tutorial aims to help you setup develop environments for CS 4804 programming assignments.

## Python Installation
* Python for [Windows](https://www.python.org/downloads/windows/)
* Python for [Linux/UNIX](https://www.python.org/downloads/source/)
* Python for [Mac OS X](https://www.python.org/downloads/mac-osx/)
* [Anaconda Individual Edition](https://www.anaconda.com/products/individual)

ps. Please use Python 3.6 for class assignments

## Setup Python env using Docker

```
docker search continuumio
docker pull continuumio/miniconda3
docker run -t -i continuumio/miniconda3 /bin/bash
docker run -ti -v /Path/tutorial:/tutorial continuumio/miniconda3 /bin/bash

conda create --name cs4804 python=3.7
conda activate cs4804
conda deactivate
conda info --envs

conda search beautifulsoup4
conda install beautifulsoup4
conda list | grep beaut

```