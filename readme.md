Explores DVC, Pachyderm, Domino, and a self-made Read the [blog post]() for more information on motivations.

Files that are common to all/most of the tools are in the root directory.
Tool-specific configurations are 

# Getting started.
1. Log in to Kaggle. 
2. `git clone 
I chose a small dataset that is also interesting and popular. 
[here](https://www.kaggle.com/datasnaek/youtube-new)

# Toy Workflow
I came up with this toy workflow before I started working on this project. It is
meant to have a decent number of forking paths to keep things interesting and the
environment is meant to be non-trivial. 

- Data Cleaning -- Two different subsets of the data
- GPU environment + custom library code
- Feature Engineering
- Two different models to save and reproduce
- One Jupyter Notebook for model validation under two different models. 

# What is the self-made solution?
The self-made solution relies on tools that 

- Maintain the *environment* with Docker 
- Mantain the *code* with Git and Github
- Maintain the *data* via Git LFS. 

# What aren't we concerned about?

