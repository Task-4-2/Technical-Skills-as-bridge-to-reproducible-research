---
title: "First Steps with Jupyter Notebooks"
author:  "Skills4EOSC T4.2"
tags: 
    - FAIR-by-Design Learning Materials
    - Jupyter Notebooks
    - Virtual Lab Notebooks
---

# First Steps with Jupyter Notebooks

This activity introduces the participants to the basic concepts of the Jupyter notebooks, one of the most popular virtual lab notebook formats today. It guides the participant through the process of using an online service to open an existing notebook, execute its code, and modify it according to set out requirements.

## Activity Duration

25 minutes

## Number of People that it can be Performed With

Any

## Goal of Activity

The goal of this activity is to have the participants access an already prepared Jupyter notebook, execute it, and then modify it, altering some of the content and description. 
 
## Materials

- The source code for the Jupyter notebook is hosted on GitHub, in a public repository - [https://github.com/Task-4-2/librarian-jupyter-notebook-example](https://github.com/Task-4-2/librarian-jupyter-notebook-example).
- Access to an online Jupyter notebook service such as Google Colab or Binder. Some participants might also have access to a Jupyter notebooks server hosted by their institution.

## Instructions

### Scenario Setup

A paper that you have been reading has linked to a GitHub repository where among other things a Jupyter notebook is included. Using this notebook the authors have analyzed the underlying raw data and drawn the conclusions outlined in the paper. You are interested to see if re-executing the Jupyter notebook indeed leads to the results discussed by the authors. You would also like to answer some additional questions, thus a slight altering of the notebook is also needed.

### Tasks Assigned to Participants

Open the [jupyter-example.ipynb](https://github.com/Task-4-2/librarian-jupyter-notebook-example/blob/master/jupyter-example.ipynb) notebook using one of the following ways:

- Using [Google Colab](https://colab.research.google.com/github/korvoj/jupyter-notebook-example/blob/master/jupyter-example.ipynb), free, but requires a Google Account
- Using [Binder](https://mybinder.org/v2/gh/korvoj/jupyter-notebook-example/HEAD?labpath=jupyter-example.ipynb), free, no sign up is required
- Using an institutional Jupyter notebook server or any other third-party service providing Jupyter notebook hosting

Execute all code cells of the notebook and try to understand what the Jupyter notebook is analyzing.

Modify the Jupyter notebook, so that instead of analyzing records related to `Reproducibility Crisis`, it analyzes records related to `open science` in general.

### Trainer Guidance

The activity can be conducted on any online Jupyter service that offers the possibility to clone a remote public Git repository. The links towards Binder and Google Colab are direct links, meaning that they will open a new browser window with the corresponding Git repository already cloned and a Jupyter notebook ready to be used. In case one of the links does not work, the other can freely be used as an alternative.

To complete the activity, at a minimum, the participants would need to change the query parameter sent in the request to the Zenodo API. The query parameters are set in the `params` dictionary. 

## Tips and Tricks

The activity can be done by the participants either in their own time or live. If the activity is done live, the trainers should make sure that all participants complete the activity in the allocated time. First time users are expected to have questions about running Jupyter notebooks in general and the user interface, so trainers should be prepared to answer accordingly. A major factor when organizing the exercise live is the chosen Jupyter notebook server. Trainers should test the amount of time required to start a new instance of the notebook, and if needed adjust the total time dedicated to the activity.

In case it is done offline, the results can be checked either manually by the trainers, or using a peer-review, where each participant will need to review the solutions of other participants, while also having their own solution reviewed. This might also be a further opportunity to learn new aspects of Jupyter notebooks, as each participant will not focus only on completing their own exercise, but see how others have done it as well.

Trainers are free to fork the repository and alter any additional files in case they want to customize the scenario.

## Related sources
- [Zenodo API Docs](https://developers.zenodo.org/)

## Comments
- how did it go
- supporting the co-creation process