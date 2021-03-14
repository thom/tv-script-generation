# Udacity Deep Learning Nanodegree Program - Project: Generate TV Scripts

This project generates Seinfeld TV scripts using RNNs. It uses a Seinfeld
dataset of scripts from 9 seasons. The Neural Network will generate a new,
"fake" TV script.

## Setup Instructions

Clone the repository and navigate to the downloaded folder:

```bash
git clone https://github.com/thom/tv-script-generation.git
cd tv-script-generation
```

Install [anaconda](https://www.anaconda.com/products/individual) or
[miniconda](https://docs.conda.io/en/latest/miniconda.html) and create a new
conda environment:

```bash
conda create --name deep-learning python=3
```

Enter your new environment:

```bash
conda activate deep-learning
```

Make sure you have already installed the necessary Python packages:

```bash
conda install pytorch torchvision -c pytorch
```

Run the following to open up the Jupyter lab server:

```bash
jupyter lab
```

In your browser, open ```dlnd_tv_script_generation.ipynb```. Follow the
instructions in the notebook; they will lead you through the project.

## Requirements

Graded according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2260/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Thomas Weibel](https://github.com/thom).
