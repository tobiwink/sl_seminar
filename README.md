# Statistical Learning Seminar

This Github repository contains the material for the first presentation of the [Statistical Learning Seminar](https://na.uni-tuebingen.de/ex/seminar_statistisches_lernen_ss23/) at the University of Tübingen. The seminar is organized by Prof. Dr. Andreas Prohl and [Dr. Abhishek Chaudhary](https://na.uni-tuebingen.de/~chaudhary/) and takes place in the summer semester 2023.

## Content

The manuscript and the presentation slides are available in the root folder, the Overleaf project is in the `latex` folder.
To run the code, you need to install the packages listed in the `requirements.txt` file with Python 3.8.5.

If you use an Anaconda environment, you can create a new environment called `sl_seminar` that has the requirements, using the following command:

```bash
conda env create -f environment.yml
```

Then, you can activate the environment with:

```bash
conda activate sl_seminar
```

and run the notebook with:

```bash
jupyter notebook
```