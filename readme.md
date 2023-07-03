# Creating a nanoGPT version to train on specific dataset to do specific tasks.
### We use Anaconda to mananged the packages, below are some useful commands:
1. Exporting conda venv to remote runner for cicd.
`conda env export > environment.yml`
2. Creating the conda venv in remote runner.
`conda env create -f environment.yml`
