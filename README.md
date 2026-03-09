# EuVSOP use case using pyBIS

## Overview
This repository consists of Python script and required data ([Excel files](20260309_EuVSOP_excel_files), [datasets](20260203_EuVSOP_datasets), etc.) to implement the EuVSOP use case in BAM Data Store ([main](https://main.datastore.bam.de/), [training](https://training.datastore.bam.de/), [playground](https://playground.datastore.bam.de/), [demo](https://demo.datastore.bam.de/)) instances. This script is meant to be used by **DSSt(s)**.

More detailed description of the script structure and used functions can be found in the [Wiki](https://datastore.bam.de/en/pyBIS). More information about the EuVSOP use case and corresponding publication can be found [here](https://datastore.bam.de/en/use_cases/EuVSOP).

## Prerequisites and installations
* **BAM username** and **password** are required to [log in to the instance](https://datastore.bam.de/en/openBIS_v20-10-12-2/How_to_guides/How_to_log_in). To execute some cells, [Project Admin rights](https://datastore.bam.de/en/concepts/roles_and_rights) are required; therefore, **only DSSt(s)** can run this script to its full extent.

* [Python for Windows](https://gist.github.com/ibresslerBAM/b638c55b4af5810fed47fcd7788fddd5#pythonminiforgejupyterlab-install-and-update-guide-for-windows) 
<!---or this link https://bamresearch.github.io/bam-pybis-workshop/#setting-up-vscode-with-python-in-windows --->
* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)

```python
pip install jupyter
pip install jupyterlab
```

* [VS Code](https://code.visualstudio.com/) (optional)

* [pyBIS](https://pypi.org/project/PyBIS/)

```python
pip install pybis
```
or 

```python
pip install --upgrade pybis
```

## Results

![Hierarchy Graph of Experimental Step: EuVSOP HEE Treatment with the  research workflow of the EuVSOP use case is visualized.](20260309_figures_for_README\20260309_EuVSOP_Results_hierarchical_graph.png)

20260309_figures_for_README/20260309_EuVSOP_Results_hierarchical_graph.png
