---
title: "Learning Unit 3: Technical Aspects"
author: "Skills4EOSC T4.2"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Git
    - Jupyter Notebooks
    - Reproducibility
    - Data Backups
    - File Naming Conventions
---

# Learning Unit 3: Technical Aspects

The goal of this unit is to showcase concrete ways on how to put into practice the various topics and recommendations regarding reproducible research discussed during the previous training session.

The unit covers 4 main aspects, starting with providing a bridge between theoretical aspects discussed so far and technical aspects which are the main focus of this presentation. Then, the outline the common challenges that arise when it comes to research data management and how data longevity can be ensured across wide timespans. Finally, a discussion on collaboration tools that can also aid the reproducibility aspects of the research, introducing Jupyter notebooks as the means to do so.

## Learning Objectives

After completing this unit, you will be able to:

* Describe the challenges related to data management
* Use Git as a file versioning tool
* Explain different data back-up methodologies and select the optimal one
* Discover the concept of virtual notebooks and their relation to reproducibility

## Target Audience

- Data Librarians and other data curious

## Duration

- 120 mins

## Prerequisites

The technical aspects is an introductory unit in which the concepts of file naming schemes, file versioning, Git, and lab notebooks are introduced. As the unit is targeted at the beginner level, no explicit preparation is needed before attending the session. However, accounts on the following platforms will be useful for conducting the exercises:

GitHub. Details about account creation are available on the [GitHub docs page](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)

Google Colab (if you plan to use Google Colab instead of Binder for testing out the lab notebooks). A free Google account is enough for accessing the Colab service. More information is also available on the [official page](https://colab.google/).

No additional software apart from a web browser is required for taking part in the training or for conducting the exercises.

## Learning Tools

- See [Prerequisites](#prerequisites)
- The content is designed to be taught online, therefore a virtual teaching platform with breakout rooms is used to facilitate the content and activities.

## From Theory to Practice

Data management plans can be abstract in nature and there is a need to discuss ways of how different aspects can be implemented in practice. This section focuses on topics such as:

- Securely storing research data
- Describing the stored data so that others can easily make sense of it and reuse it
- Optimizing the storage and presentation of the data to facilitate collaboration
- Ways in which research data can be made persistently available, ensuring its longevity

A common problem which everyone has experienced is having to deal with multiple versions of the same file, named seemingly in an arbitrary fashion. When multiple versions of the same file are available, clear indication to which one is the most recent and up-to-date one is needed. Furthermore, if unsuitable naming convention adopted, there is also no clear indication on how these versions differ between each other and what changes have been introduced when. Some potential options that can be used for organizing research files are:

- Using search tools (should be avoided, discussed in more details on the next slide)
- Defining a consistent and descriptive file naming strategy and applying it to individual files
- Using more advanced file versioning tools which can also act as collaboration enablers, discussed in more details later in the presentation

Using advanced searching tools to find a given file, without adopting a more systematic approach is usually just a “local” solution, that will work on a given workstation. Different operating systems have different features when it comes to file searching, and what works on a given machine might not work on others. Additionally, this limits the platforms where the files can be hosted, since different online services have vastly different text searching capabilities. As a result, this option should be avoided if possible. It should be stressed that in this unit we do not make any recommendations on “how” the naming scheme should be structured, just that it should be well defined and consistently applied across all files. The adopted naming scheme should be as descriptive as possible, incorporating elements that are useful for the given type of files, such as the creation date, a brief description, incremental version number, etc... The ordering in which elements are added to the naming scheme is also very important, since it has an impact on the lexicographical sorting of the files

## Filenaming recommendations

No golden rule. Different conventions for different file groups are possible.

Think about what is important:

- The date
- The format
- Description
- Version

*Keep in mind that operating systems sort files in a lexicographical order. Put important information first.*

- Include metadata, use abbreviations
- Decide what information to include in the file name
- Different environments have different file name length limits 
- Keep full directory length less than 255 characters to avoid problems
- Use [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) for data formats (YYYYMMDD). Lexicographical sorting will sort the files correctly based on date in this case.
- Use fixed length numbers: `001`, `017`, `153` instead of `1`, `17`, `153`

A common pitfall with lexicographical sorting is the sorting of numbers. To avoid this, fixed length numbers should be used, along with [ISO 8601](https://www.iso.org/iso-8601-date-and-time-format.html) notation for any dates in the file name. Another point to make is that even though modern devices might support long file names, for backwards compatibility it is better to limit file paths to no more than 255 characters.

- Include file extensions in the name. Some operating systems do not require an extension, but it is a good practice (e.g., `image1.jpg`, `image2.png`, `README.md`)
- Avoid special characters and spaces in file names
- Different operating systems have different policies regarding special characters (`:`, `/`, `\`, `?`, `|`, `<`, `>` are all problematic)
- Spaces make it difficult to type the name on the command line. Use `_`, `-`, or character casing to separate metadata: `my_file.txt`; `my-file.txt`; `MyFile.txt`
- Do not use the same name with changed casing: `image1.png` and `Image1.png`

Proper filenaming examples: 

- `[investigator]_[method]_[subject]_[YYYYMMDD]_[version].[ext]`
- `[project #]_[method]_[version]_[YYYYMMDD].[ext]`
- `[YYYYMMDD]_[version]_[subject]_[datacollector].[ext]`
- `[type of file]_[author]_[date].[ext]`

### Tips for applying filenaming conventions

Dealing with an existing set of files which have not adopted a consistent naming scheme previously can be tedious and error prone, should the renaming process be manually conducted. An alternative is to use automated bulk renaming tools:

- Microsoft Windows
    - [BulkRenameUtility](https://www.bulkrenameutility.co.uk/)
    - [PowerToys PowerRename](https://learn.microsoft.com/en-us/windows/powertoys/powerrename)

- MacOS
    - built-in bulk renaming
    - [Transomino](https://www.transnomino.com/)

- GNU/Linux
    - [rename](https://man7.org/linux/man-pages/man1/rename.1.html)

## More advanced file versioning with Git

[Git](https://git-scm.com/) is the most popular file versioning tool today, available as open-source software for all popular computing platforms. Main benefit of adopting Git is the fact that it can efficiently track the complete history of a given file, allow reverting to previous file versions and deal with (conflicting) changes made by multiple users.

### Git features and terminology

- **Repository** – analogy to a folder with enabled file versioning features.
- ***Clone** – local copy of a remote repository with its full version history and file contents.
- **Commit** – a record of changes to a file or a set of files. Described by a commit message.
- **Push** – upload of local commit(s) to a remote repository (online).
- **Pull** – download of remote commit(s) to a local repository.
- **Fork** – a 1:1 copy of an existing repository. Forks share the same history as the parent but diverge by adding unique changes.

Care should be taken to clearly describe the difference between the clone and pull actions to users that have not used Git before. Cloning is done once at the repository level, downloading all files within it, along with the complete history for each file. In a nutshell, cloning allows a remote repository to be downloaded locally.

Pulling revers to downloading remote changes that have been uploaded to the online hosted Git repository in the meantime, thus reconciling the remote changes with the local changes. To pull remote changes to a given repository, the repository must already be available locally, meaning that the clone action has been executed previously. 

In most cases, the most popular free Git hosting services will be sufficient for most research groups. Depending on the subject area, there might be specialized Git hosting services available as well. Users should also check if their institution already offers a hosted Git service.

### Git feature spotlight

Repository visibility options are:

- **Private** – only designated people have access and not visible to search engines
- **Public** – anyone can view the repository, indexed by search engines

Branches are a very useful tool when collaborating with others. Each new set of changes can be developed on a separate branch, until ready to be made part of the original content, by merging that branch to the primary branch. 
Potentially disruptive changes to the files can also be made on separate branches and if they are successful, merged into the main branch. If unsuccessful, the branch can simply be discarded, without any effect to the main branch’s content. 

- **Git blame** – check by whom a given change was made and when
- **Git branch** – parallel version of a single repository. Changes to it do not affect the “primary branch” or live version. Parallel branches can eventually be merged to the primary branch if desired. Branches allow multiple people to work in parallel, without disturbing each other. Once the work on the subbranch has been finished (new experiment, new chapter...), it can be merged to the main branch. Should merge conflicts arise (conflicting changes have been introduced), they can be manually reconciled.

### Git and README files

Good practice is to add a `README.md` file in each directory. The `README.md` file in the top of the repository serves as a general description including description of subdirectory contents and file naming schemes and is shown prominently on the web.

### More ways to use Git

Git itself is free and open-source software and there are multiple ways to interact with Git repositories:

- Official command line application – [git](https://git-scm.com/downloads)
- Dedicated desktop applications
    - [GitHub Desktop](https://desktop.github.com/download/)
    - [Sourcetree (BitBucket)](https://www.sourcetreeapp.com/)
    - [Sublime Merge](https://www.sublimemerge.com/)
  
Find a [step-by-step guide](https://fair-by-design-methodology.github.io/FAIR-by-Design_ToT/latest/Stage%204%20%E2%80%93%20Produce/08-Development%20Tools/08-Introduction%20to%20Markdown%20and%20Git/#version-management) on getting started with a desktop client as part of the FAIR-by-Design ToT Development Tools learning unit.

### Tracking the lifecycle of a file with Git

Git does not track only the file contents. It also helps with adding, removing, and renaming files. Part of the summary information about the changes introduced in the commit. An important point to make is that Git does not only version the content of the files, but also their location and name. This makes it easy to track the complete lifecycle of a given file not only as its content is changed, but also as it is moved between subdirectories and/or renamed. This is especially important for long living repositories, where the file naming schemes might have evolved over time. Note also that this versioning of the file names also provides an additional safety net when using bulk rename utilities. Undoing a botched bulk rename is just a matter of reverting the corresponding commit where the changes have been introduced.

## Ensuring data longevity

Data is the basis of research. Data recovery upon loss might be expensive, slow, or even impossible. Therefore, reliable backups are an important part of data management. When keeping a single copy of data, it is not a matter of if the data will be lost, but when it will be lost, as it is just a matter of time. To prevent this, a robust backup strategy should be implemented. This provides mitigation against:

- Hardware failure
- Software failure
- Silent corruption
- Human errors
- Device theft/loss

The recommended approach is not to store a single copy of your data, instead store multiple! The recommended approach is to store locally, on an external medium, and in the cloud (three copies). This is also known as the 3-2-1 backup method: 3 copies of data (1 production and 2 backups); 2 different media; 1 copy off-site.

### Github and Backup Aspects

**Question:** If I use an online Git service to host my repositories, do I have to implement any additional backup solutions?

***Answer: Yes***

It is good practice to apply the same backup strategy as used for the rest of your files. For additional safety repository mirrors can be set up, where the repository content is mirrored across different Git hosts (e.g., GitHub and GitLab). Using a single online hosting Git service is not backup, since the account can be disabled, the service can go out of business or can suffer unrecoverable data corruption/loss.

### Final Points About Backup Aspects

Careful consideration when choosing a cloud storage service:

- Security aspects
- Privacy policy (Privacy aspects should be taken into careful consideration when choosing online storage services. It is advised to carefully read both the privacy and terms of use policies).
- Data mining
- Data ownership
- Terms of use
- Guaranteed service & data availability

## Tools for collaboration and reproducibility

If I meticulously manage my data and describe it in detail while publishing it in a Git repository, isn’t that enough? The answer is ***NO***.

### Electronic Lab Notebooks

Electronic Lab Note books can assist in online and offline searching, output in different formats, sharing your data, embedding different media to make content more interactive and improving accessibility. Depending on the scientific discipline, different tools are used, but Jupyter is among the most popular ones today. It should be stressed that Jupyter is not limited only to the use of the Python programming language and that other programming languages are supported as well through the introduction of different “kernels”.

### Setting up a Jupyter Environment

Local installation:

```bash
pip install jupyterlab
jupyterlab notebook
```

The local installation instructions assume that the user already has a Python environment setup.

Hosted Jupyter environments available at many institutions. But there are also free services:

- [Binder](https://mybinder.org/)
- [Google Colab](https://colab.research.google.com/)

Google Colab is a popular electronic lab notebooks service compatible with Jupyter Notebooks. It provides both a free and a paid option. The paid option includes higher resource limits and the code is executed on more performant hardware. Both Binder and Google Colab support a direct Git integration, where a Git repository can be immediately opened in the respective environment just by providing a link to it.

### Jupyter and Git

Jupyter and Git are commonly used in tandem. Git for storing the data, and Jupyter for analyzing and visualizing the data.

Jupyter can be connected directly to a Git repository. All files are available in the Jupyter environment. It is possible to create permanent links which instantiate a new Jupyter environment from a Git repository upon a click. 

Note, that many Git hosts offer a dedicated read-only view for Jupyter notebooks

### Do's and Don't's with Jupyter Notebooks

- ✅ Do serialize or cache the intermediate outputs of long-running steps.
- ✅ Do take care to execute the steps serially, one after the other, before publishing the notebook.
- ❌ Don’t ever edit your raw data, especially not manually. This includes changing file formats or fixing errors by hand.
- ❌ Don’t overwrite your raw data with a newly processed or cleaned version. Notebooks should be as idempotent as possible.
- ❌ Don’t save multiple versions of the raw data.'

### Zenodo and Github integration

The step-by-step instructions on how to achieve the Git<->Zenodo integration are out of scope of this presentation and participants are invited to have a look at [Referencing and citing content guide from GitHub](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)

The Git repository can be seen as a “living organism” to which changes can be made at any point, whereas Zenodo deposits are point-in-time freezes of the content of the repository, created on the repository owner’s demand.

### Key Takeaways

The challenge of putting data management plans into practice:

- Practicing good data hygiene
- Hierarchical file structure
- File naming conventions
- The importance of data backups

File versioning:

- Collaboration enabler
- Integration with third-party (research) infrastructures (e.g., Zenodo)

Improving reproducibility by providing a snapshot of the compute environment:

- Electronic lab notebooks
- Integration with file versioning
- Free vs. paid hosting options

### Learning Activity
This unit has two learning activities.

- [Activity 1](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/blob/main/resources/Unit%2003%20-%20Technical%20Aspects/Activities/04-Git%20Blame%20in%20Action.md) - The learner practices using the Git blame feature. The activity uses the [Task-4-2/librarian-git-exercise](https://github.com/Task-4-2/librarian-git-exercise) repository as a demo repository.

- [Activity 2](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/blob/main/resources/Unit%2003%20-%20Technical%20Aspects/Activities/05-First%20Steps%20with%20Jupyter%20Notebooks.md) - 
The learner practices using Jupyter Notebooks. The activity uses the [Task-4-2/librarian-jupyter-notebook-example](https://github.com/Task-4-2/librarian-jupyter-notebook-example) repository as a demo repository.

This activity can be conducted on any online Jupyter service that offers the possibility to clone a remote public Git repository. The links towards Binder and Google Colab are direct links, meaning that they will open a new browser window with the corresponding Git repository already cloned and a Jupyter notebook ready to be used. In case one of the links does not work, the other can freely be used as an alternative.

## Suggested Reading

- Learn more about Jupyter notebooks by following the [Zero-to-Binder guides](https://book.the-turing-way.org/communication/binder/zero-to-binder.html).
- Learn more about Git branching and how it works using the interactive ["Learn Git Branching" tool](https://learngitbranching.js.org/).
- Markdown is a useful tool to format text-based cells when using Jupyter notebooks. Learn more about Markdown by following the [FAIR-by-Design Markdown guide](https://fair-by-design-methodology.github.io/FAIR-by-Design_ToT/latest/Stage%204%20%E2%80%93%20Produce/09-Content%20Development/09-Markdown%20Syntax/)
- Be wary of common pitfalls when using Jupyter notebooks by reading the ["Reproducibility"](https://ml-science-book.com/reproducibility.html) section of the Supervised Machine Learning for Science Git Book. The part about ordering of executed cells is especially important.
- Use [Cookiecutter](https://github.com/cookiecutter/cookiecutter) based templates such as the one for [data science by DrivenData](https://cookiecutter-data-science.drivendata.org/) for easy initialization of new coding environments.