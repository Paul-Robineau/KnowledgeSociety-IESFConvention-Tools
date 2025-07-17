# KnowledgeSociety IESFConvention Tools

This work has been done in the context of the organization of the IESF (*Ingénieurs et Scientifiques de France*) Scientific Convention named "From knowledge construction to its reception by the civil society", which will follow the model  of the Citizen Conventions - More information available [here](https://conventions.iesf.fr/convention-connaissances/home) (in French).

## Objective

This repository stores the Jupyter Notebooks developped to manage: 
1. Drawing lots to create a list of convention participants respecting: 
  - the representativeness criteria selected by the convention steering committee 
2. Drawing lots to create thematic working groups respecting:
  - the preferences expressed by the convention participants' majority judgments
  - minimizing gender disparities within the groups

## Notes on advancement

2025/07/17 

>For now, only the Jupyter Notebook for the **Objective 2** is available. Furthermore, its internal documentation is only available in French. The FR/ENG Jupyter Notebooks for the **Objective 1** & **Objective 2** will be available in the near future.

## Structure

The Jupyter Notebooks use data stored as `csv` files in the `data` folder.

Each of them incorporates a bloc of code that can generate an adequate random sample for testing purposes.

## Requirements

### Python environment manager

We suggest you to use Miniconda:

> Miniconda is a free, miniature installation of Anaconda Distribution that includes only conda, Python, the packages they both depend on, and a small number of other useful packages.

[Miniconda Installation Guide](https://www.anaconda.com/docs/getting-started/miniconda/main)

### Setting up the environment

Within your Python environment manager console (like miniconda console, or anything that suits you):

Create a new Conda environment with all required libraries (in this example named `da` for "data analysis"):

```
conda create  -n da -c conda-forge pandas numpy pulp random math tdqm matplotlib seaborn jupyterlab
```

Or, create the Conda environment only:

```
conda create -n da -c conda-forge
```

And install the libraries afterwards, after activating the environment:

```
conda activate da
```

```
conda install pandas numpy pulp random math tdqm matplotlib seaborn jupyterlab
```

Some libraries may require you to use  the `pip` manager instead of conda. In that case, use the command:

```
pip install name_of_library
```

## Use the Jupyter Notebooks

2.  Activate the environment:

```
conda activate da
```

3. Launch Jupyter Lab:

```
jupyter-lab
```
You can select the Notebook you want to use by navigating in the directory where you downloaded the Notebooks.

They are thoroughly documented to allow you to understand what does each bloc of code.
