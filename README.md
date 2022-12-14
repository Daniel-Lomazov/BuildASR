# Convert Video/Audio to Text using Python

As very quicly I was able to do more than a few things, lets start be creating a virtual environment and installing the 
required packages - I prefer, for the sake of simplicity, to install miniconda and create the virtual environment there.

## Setting up the environment

### Install Git
- Download and install git from [here](https://git-scm.com/downloads).

### Create your own project
- Create a folder for your project; keep the full path at hand.
- Open the command-line and navigate to the folder you just created
```
cd <path to your project folder>
``` 
- Clone this repository to you project folder
```
git clone https://github.com/<USERNAME>/<REPOSITORY>
```
### Install Miniconda
- Download Miniconda from [here](https://docs.conda.io/en/latest/miniconda.html) and install it.

### Set you virtual environment
- Search for the Anaconda prompt, open it and create a conda environment via ONE of the following methods:
```
conda env create -f environment.yml
```
---
```
conda create --name <env_name> --file requirements.txt
```
---
```
pip install -r requirements.txt
```

You can also use the `environment.tar.gz` file to create the environment on a different machine.

See you in the next post!
