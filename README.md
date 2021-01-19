[![Azure Notebooks](https://notebooks.azure.com/launch.svg)](https://notebooks.azure.com/Microsoft/libraries/samples)

# End of life for the Azure Notebooks preview
The Azure Notebooks preview has ended as of *January 15th, 2021* as we focus on building great Jupyter notebooks experiences across our products, including Visual Studio Code, Azure, GitHub, Codespaces. Please visit [our site](https://aka.ms/aznb-notebooks-at-msft) to find information on these experiences as well as instructions for downloading any content you currently have on the Azure Notebooks site.

We deeply value the Azure Notebooks community and all that was created over the past 4 years. This has our team all the more excited to share our latest notebooks experiences with you.


# Azure Notebooks

Azure Notebooks is a hosted service for [Jupyter Notebooks](#jupyter) that
requires no installation.  It enables you to get started quickly on
prototyping, data science, academic research, or learning to program Python or
R.  You can combine code, markdown, images, videos, graphs, all in one format
and easily share with partners.

Documentation for Azure Notebooks is found on
[https://docs.microsoft.com/azure/notebooks](https://docs.microsoft.com/azure/notebooks).

## Interesting samples

In addition to the notebooks in this repository, which you can also find on the
[Azure Notebooks samples library](https://notebooks.azure.com/Microsoft/projects/samples),
there are some good external resources as well:

- [Intro to Jupyter notebooks](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)
- [Intro to Data Science](https://github.com/jakevdp/PythonDataScienceHandbook) by Jake Vanderplas
- See the Sample notebooks on the
  [Azure Notebooks](https://notebooks.azure.com/) front page
- A [curated list of interesting Jupyter notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)

## Data sources

There are many interesting sources of data to use in notebooks.  A couple of
good resources are:

- [List of public data sources fit for machine learning](https://blog.bigml.com/list-of-public-data-sources-fit-for-machine-learning/)
- [35 Brilliant and Free Data Sources](http://www.forbes.com/sites/bernardmarr/2016/02/12/big-data-35-brilliant-and-free-data-sources-for-2016/#469939567961)

Note that data must be accessible to the service — you can use Github, Dropbox,
OneDrive, Azure blobs, SQLAzure, and more.

## Jupyter resources

- [Jupyter.org docs](http://jupyter.org)
- [Jupyter on YouTube](https://www.youtube.com/results?search_query=jupyter+notebook+tutorial)
  - [Cell magics](https://youtu.be/zxkdO07L29Q)
  - [Making slide shows with executable code](https://youtu.be/EOpcxy0RA1A)
  - [All about Jupyter](https://www.youtube.com/watch?v=GMKZD1Ohlzk)

## [Filing issues](https://github.com/Microsoft/AzureNotebooks/issues/new)

Knowing the context of your issue will help us solve it faster.  Please include
as much of the following as you can when creating a issue:

* Whether the issue is related to Jupyter Notebooks or the Project feature.
* The Jupyter Kernel (`python36`, `python2`, `python3`, `R`, etc) in case of
  problems with a Jupyter Notebook.
* Time of occurrence.
* Web browser the issue occurred in.
* If the issue occurred once or can be reproduced (with steps to repro it).
* Project ID and Notebook Name.
* Logs (`!cat .nb.log` or: New > Terminal, `$ cat .nb.log`).
* Usage scenario: teaching a class, doing homework, evaluating results for
  research.
* Add template to root.

## Short FAQ

### What is Jupyter?

Jupyter (formerly IPython), is a multi-lingual REPL on steroids.  Azure
notebooks is a free service that provides Jupyter notebooks along with
supporting libraries as a service.  It means you can just login and use it, no
installation or setup is necessary.  Instructors can also use the service by
easily sharing a notebook.  Students get their own private copies that they can
run.  The service is provided by the Python team @ Microsoft, which is part of
the Data Group.
