---
title: "Git Blame in Action"
author:  "Skills4EOSC T4.2"
tags: 
    - FAIR-by-Design Learning Materials
    - Git
    - Version Management
---

# Git Blame in Action

This activity introduces the participants to the basic concepts of the Git blame feature, allowing them to investigate in detail who made what changes and when to specific files of interest.

## Activity Duration

15 minutes

## Number of People that it can be Performed With

Any

## Goal of Activity

The goal of this activity is to have the participants access the already prepared demo repository and analyze the changes made to two specific files of interest - `01_raw_data/20240813_1_state_transition_projection_algo1.csv` and `02_scripts/02_visualize.py`. At the end, it should be possible for the participants to state whether there has been manual data manipulation of one of the raw data files.
 
## Materials

- View access to the [https://github.com/Task-4-2/librarian-git-exercise](https://github.com/Task-4-2/librarian-git-exercise) repository on GitHub, hosting the source files for this activity.
- A GitHub account is not mandatory, but can be nice-to-have. A GitHub account would allow each participant to fork the repository and continue experimenting, if so desired.

## Instructions

### Scenario Setup

A paper that you have been reading has linked to a GitHub repository where the authors have deposited all of the raw data, code, intermediary results, and visualizations. You are interested to see how the raw data has been uploaded and if it has been manually modified after its upload.

### Tasks Assigned to Participants

Your task is to analyze the version history of the following files:

- `01_raw_data/20240813_1_state_transition_projection_algo1.csv`
- `02_scripts/02_visualize.py`

1. Has there been manual data manipulation in the `20240813_1_state_transition_projection_algo1.csv` file?

    - If yes, who performed it and when?
    - If yes, what was the original value, before the change?
    - Tip: Analyse the history of line 32 in the CSV file.

2. Analyze the file `02_scripts/02_visualize.py`. The following expression controls the rotation of the text on the x-axis of the generated visualizations. [An example](https://github.com/Task-4-2/librarian-git-exercise/blob/main/03_graphics/20240813_4_state_transition_projection_algo4.png) is available in the `03_graphics` folder.

    ```python
    plt.xticks(rotation=90, ha='right')
    ```

    - Analyze the history and determine the GitHub username of the user that altered the visualization generation code.
    - What was the previous rotation value?

### Trainer Guidance

The activity can be completed just by viewing the files, as the repository is public. The participants do not require their own GitHub account. Optionally, some participants might want to clone the repository locally and analyze the Git version history using third party tools. While this is certainly possible, trainers should encourage users to use the web interface of GitHub instead, as to be able to provide help in case of any issues.

## Tips and Tricks

The activity can be done by the participants either in their own time or live. If the activity is done live, the trainers should make sure that all participants complete the activity in the allocated time. First time users are expected to have questions about the various ways of navigating the GitHub interface, so trainers should be prepared to help and explain.

In case it is done offline, the results can be checked either manually by the trainers, once the participants have submitted their answers, or if the learning platform allows it, automated checking of answers can be put in place as well. As the answers to the questions are simple and not dependant on a wider context, such automated checking should not be a challenge to implement. 

Trainers are free to fork the repository and alter any additional files in case they want to customize the scenario.

## Related sources
- [Viewing a File - GitHub Docs](https://docs.github.com/en/repositories/working-with-files/using-files/viewing-a-file)

## Comments
- how did it go
- supporting the co-creation process
