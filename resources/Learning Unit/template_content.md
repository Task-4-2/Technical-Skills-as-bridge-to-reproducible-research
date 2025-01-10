---
title: "Content of the Learning Path"
author: "Skills4EOSC T4.2"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - FAIR Learning Unit Template
---
# Introduction
In this document, you will find a short description of the three units that make up the learning path.

## Target Audience
- Data Librarians and other data curious

# Learning Unit 1: Reproducibility and Replicability in Scientific Research

This unit focuses on reproducibility and replicability in scientific research. It is the first unit in the learning path title "Technical skills are the bridge to reproducible research: An introduction for data librarians".
In this unit we discuss what reproducibility is, the barriers there are to reproducibility and the benefits of reproducibility.

## Learning Objectives
After completing this unit, you will be able to:

* Define reproducibility and replicability in scientific research
* Explain how reproducibility and replicability are related but also different
* Describe benefits of reproducibiliy to researchers
* Describe common barriers to reproducibility

## Duration
- 60 mins

## Prerequisites
- None

## Learning Tools
- None
- The content is designed to be taught online, therefore a virtual teaching platform with breakout rooms is used to facilitate the content and activities.

## Learning Content Topic
The unit discusses the difference between an original research study and a replication study. Both play an important role in the scientific process. But how do we go from science to knowledge? Or from a single scientific result to reliable knowledge and understanding of some phenomenon or topic? 
Step one in the scientific method is to formulate a research question or hypothesis. 
Step two is to design a research study to answer that question or test that hypothesis, using appropriate research methods. For instance, we may want to conduct an experiment, which means manipulating an independent variable and measuring a dependent variable to determine cause-and-effect. Once we decide on the appropriate study design, step three is data collection and step four is data analysis. 
In step five, after we analyze all the data, we get our results – we get the answer to our research question or the test of our hypothesis.

However, one research study and one result can be very exciting and can give us a hint of how something works, but it is not reliable enough. We could get lucky and get a great result purely by chance. Or the phenomenon we study could be very complex and the data could be messy. There are lots of reasons why a single research result is only the start of the scientific investigation, not the end of it.  

This unit introduces the learner to what reproducibility is and how it benefits science. In conclusion, the unit addresses the barriers to reproducibility, which are described as:

 1. Cultural Barriers:
·	Researchers are rewarded for producing high-impact, novel results, not for making their work reproducible.
·	The ‘publish or perish’ culture pressures them to prioritize speed over careful validation.
·	Success is often measured by quantity and impact, not quality or reproducibility.
2. Publishing Barriers:
·	Journals favor new findings over replication studies.
·	Many journals don’t require authors to share data, code, or methods, and peer reviewers don’t often have the time or expertise to verify reproducibility.
3. Technical Barriers:
·	(Lack of Standardization) Different fields often use their own methods, tools, and protocols, which makes it harder to reproduce work across studies. 
·	(Data and Software Availability) Outdated or unavailable software can make it impossible to reproduce results.
·	(Lack of Infrastructure) Some fields don’t have reliable platforms to store and share large datasets, and reproducing complex simulations can require resources that not everyone has. 
·	(Collaboration and Data Integration Challenges) Interdisciplinary work can face unique problems, like differences in data formats, methods, or terminology. Large datasets also come with logistical and technical challenges.


The content of the unit is described in more detail in this document where each slide used in the training is enriched with speaker notes: [Unit1_InstructorNotes](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/blob/59f6fd436090a06e6f0225714777763dece2fb29/resources/Learning%20Unit/attachments/Unit%201%20instructor%20notes%20DRAFT.docx)


### Related Learning Materials
Follow the link to find activities. Activities 1 and 2 are used in this unit. [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Learning%20Unit/Activities)

## Summary
Reproducibility means getting the same results with the same data, while replicability means getting the same results with new data. 
Reproducibility is the first step toward replicability, and replicating results is how we build scientific knowledge.
Reproducibility benefits researchers directly, not just the broader scientific community. It takes time and effort, but that investment pays off in the long run!


## Suggested Reading

- Chiarelli, A., Loffreda, L., & Johnson, R. (2021). The Art of Publishing Reproducible Research Outputs: Supporting emerging practices through cultural and technological innovation. Zenodo. https://doi.org/10.5281/zenodo.5521077
- National Academies of Sciences, Engineering, and Medicine, Reproducibility and Replicability in Science. Washington, DC: The National Academies Press (2019). DOI: 10.17226/25303.
- The Turing Way Community. (2022). The Turing Way: A handbook for reproducible, ethical and collaborative research (1.0.2). Zenodo. https://doi.org/10.5281/zenodo.7625728
- Why is Reproducibility so Important to Scientists: Guide for 2022. https://genemod.net/blog/why-is-reproducibility-so-important-to-scientists


  

# Learning Unit 2: Reproducibility Crisis and Remedies

## Learning Objectives

* Explain what reproducible research looks like in practice
* Explain the barriers to reproducibility and how to overcome them


## Duration

- 60 mins

## Prerequisites
- Please read the two cases (Activity 3 and 3a), which can be downloaded here: [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Learning%20Unit/Activities)

## Learning Tools
- None

## Learning Content Topic
This unit introduces the Reproducibility Crisis, what it is and actions that can be taken to implement reproducible workflows to counter this crisis.

### What is the Reproducibility Crisis?
[Nature](https://www.nature.com/articles/533452a) did a rather extensive survey a few years ago on reproducibility. It showed that 90 % of the survey participants – the researchers - thinks that a reproducibility crisis is a fact - either slightly or significantly (1,576 scientist in sample).

* More than 70 % of researchers have failed to reproduce another scientist’s experiments. More than half have failed to reproduce their own experiments. Publishing replicated positive studies did not feel very motivating (24 %) and journals are reluctant towards publishing negative replication results (13 %)
* More than 60 % experienced failure in reproducibility due to pressure to publish and selective reporting. Adding to the difficulties to comply to reproducibility practices were also competition for grants and growing amount of bureaucracy demands
* Almost 90 % felt that a more robust experimental design and improved statistics and mentorship could help to solve the reproducibility crisis. Also enhanced practices and journal checklists were ranked high
* 80 % think that research funders and publishers should do much more to address this issue
Another analysis by [Macleod](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(13)62329-6/abstract) estimates that 85% of biomedical research efforts are wasted

In summary, lack of reproducibility has a negative impact on public trust in the conclusions of science. Trust and confidence are important for science, but have different meanings for scientists, citizens and policy-makers. The aim is to make science reproducible. Reproducible science is where all information relevant to the  work, including, but not limited to, text, data and code, is made available, such that an independent researcher can reproduce the results.

The overarching categories of factors that impact reproducibility in research are:

* **Technical Factors:** Issues related to tools, processes, and materials that can introduce variability or error.
* **Human Factors:** Behavioral and procedural issues, such as errors or poor practices in data recording or sharing.
* **Study Design & Statistics:** Problems with the planning and execution of research studies, including misuse of statistical methods.
* **Rewards & Incentives:** Structural pressures in academia that encourage practices undermining reproducibility, such as prioritizing novelty over rigor.

Reproducibility is one of the principle at the core of open science - Both focus on transparency and this principle is particularly important to reinforce the rigor of scientific results

### A reproducible research lifecycle
The more of the research cycle is available and accessible, the more reproducible and verifiable the work. A paper only presents the output, but a format that is gaining more and more traction is the research compendium. This combines data and code with (information about the) environment, as well as usage information and a license. A research compendium can be made executable as well, allowing full reproduction of the project at the click of a button.

Why code? A proper basic understanding of programming is incredibly useful to find, store, utilize, document and interpret data. It is the first step towards making research reproducible. Large datasets, or the option to use specifically developed tools, can also be reasons a researcher will need to use a programming language like R, or Python.

Unfortunately, having access to data and a script does not guarantee that a project can be faithfully reproduced. Also, attaching code as supplementary material does not allow software to stand as a research product in its own right. Making science reproducible requires an open, adequate combination of data and software.

Good version control is essential, and requires its own tools. Also, unlike a paper, software is not stand-alone, and requires extra work to ensure it can function faithfully on another machine, or in another time. Challenging, and there is a need to consider how to license software and how to cite used software (and what platform to use for publishing it).

### How to improve reproducibility
Data can be FAIR but if they are of poor quality or the methods of collection and analysis are biased or poorly described, the research will not necessarily be reproducible.
It is necessary that experimental protocols, analysis methods, source codes and software used are also shared in a complete and detailed manner. These aspects are not always covered by FAIR.

There are different levels of reproducibility.  the gold standard being that the code, all documentation and installation instructions are available as well as access to a virtual environment, such as a jupyter notebook, where you can re-run the analysis. Basically sharing data and code alone is not enough.

#### Care about data
To care about data we have to keep in mind that it is important to:

- Submit your datasets to a trustworthy repository​
- Provide accurate metadata​
- Choose the right licence (ODBL, CCBY, …)​
- When collecting data:​
- Use standards (units/measurement tools, reference documents​) and the right formats (open, sustainable, machine-readable) 
- When processing​ data:
- Do not modify the raw data​
- Favor the command line: simple, clear, generic, sober programs with naming rules for example​
- Work in a structured, shared and backed-up environment

#### Care about Code
To care about code we have to keep in mind that it is important to:

- Describe, comment on your codes and their sequences using flowcharts, notebook​
- Use development standards: framework (Django, Symfony), common programming languages, free (R, Python) 
- Work in a shared and protected environment ​
- Choose the right licenses: Apache, GNU GPLv3, MIT  ​
- Work with version management tools -> software forge (a forge is a web-based collaborative software platform for developing and sharing computer applications),  continuous integration
- Archive your code (Software Heritage)​
- Publish your code/software in open journals

#### Care about Environment
To care about environment  we have to keep in mind that it is important to:

- Describe well and prepare to open ​the environment, the underlying conditions of the experiment the tools (hardware, software, languages) used for processing, for calculation ​
- Describe the trace and version its progress in the data management plan/software of the project ​tools: Opidor, Data Stewardship, ARGOS (MA) ​
- Describe all research products to electronic laboratory notebooks (ElabFTW, LabGuru) with time stamping or TMS (time management system)​
- Facilitate the reuse of "digital objects" by depositing your data and codes in environments (repositories) indexed (PID), accessible, open, saved... ​
- Work in an open environment, shared with collaborators and saved (task management system, shared spaces,...) ​
- Link data, code and results to computational documents (Jupyter, Rstudio NoteBook) ​
- Index objects: by a controlled vocabulary (list, taxonomy, thesaurus, ontology) to classify, reason ​
- Publish in open journals: its results, data papers,​
​
And despite this, the reproducibility of the execution environment is not obvious.​

## Reproducibility at the institutional level
This recently published report and related self-assessment worksheet, below, assists research institutions in understanding how reproducibility can be scaled up internally and supports scaling up of practices to the majority of the research community. It furthermore helps to create an understanding of what types of practices are helpful.

Worth noting, that this report is focused on how well organised an organisation is at scaling up reproducibility practices (i.e., access and coordination). It is not about the maturity of reproducibility practices and how well they adhere to what is commonly understood to be best practice in reproducibility.

- Barker, M., & ChueHong, N. (2024). Framework for scaling up reproducibility practices in research organisations. Zenodo. 
- Barker, M., & ChueHong, N. (2024). Assessment worksheet. Zenodo.

## How can we move forward?
* **Build communities** – elevating trust requires shared risk and reward : Use  of narrow metrics, e.g., pub count, impact factor, leads to poor  results – need a community to improve practices - Risky for single team  to invest heavily​
* **Collaborate with stakeholders** (publishers and funders) to raise expectations  : transparent results, common terminology, elevated expectation, high quality software​
* **Invest in software ecosystems** – easier to improve quality & share investments:  high quality ecosystems, investement in software skills, new software tools and methodologies​
* **Transform software research into science** – and capture science fundings: scientific software needs a research focus  - improve scientific software using science​

## Summary
1. Reproducibility has to be thought of as a long-term goal, where concepts and terminologies are to be discussed among different communities to make sure that there is a coherent terminologyin place thatall communities can understand. According to the literature review and interviews done, these types of engagement are more and more starting to occur

2. There is a need for a bottom-up approach to shape policies that support reproducible research practices. This due to the fact that there are naturally huge differences between the different communities in terms of e.g. standards and methods used. This image shows exactly at which stages this policy development work is to take place in order to be correctly understood and supported by key stakeholders, such as research performing organisations, funders, publishers and service providers. Currently, very very few (NWO only exception) do not support nor require reproducibility, and publishers are afraid to include reproducibility requirements as they fear it might affect the submission rates in a negative manner. But we can see some progress here as well, where some publishers are adding some reproducibility requirements.

3. There is a need to bake in the reproducibility aspects into the everyday research process and for it to thus become the norm – the way things are done within science. But these efforts are currently seen as time-consuming and efforts that adds on top of the ordinary research practices, so incentives are needed. Here the dis-incentives are mentioned, which are well-known challenges – the H-index and Impact Factors and the time preassures put on researchers.

4. It is, however, not easy to change things in this respect, as being reproducibility compliant requires good data management practices. These skills are preferrably to be developed early on in the research career, which also helps in taking reproducible aspect into account during all stages of the research life cycle. Here is where especially the FAIR principles comes into play.

5. There are lots of tools and infrastructures available to support good research data management practices and researchers are aware of these, but that is not really the problem in the end. The problem is that the interoperability between systems is not at an advanced stage just yet and thus hinders reproducible research workflows.

## Key Takeaways

* Lack of reproducibility has a negative impact on public trust in the conclusions of science!
* Data reproducibility is key to Open Science, but FAIR principles alone don't guarantee it
* Proper management of data and code, combined with well-documented computational environments, is essential for ensuring the reproducibility of research results
* Data reproducibility practices must be supported by institutional policies that establish a strong regulatory framework to enforce and maintain them over time

### Learning Activity
This unit has a learning activity about scientific misconduct and is described here: [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Learning%20Unit/Activities)

To understand why research integrity matters, this activity examines what happens when such integrity is absent – research misconduct.


## Suggested Reading
- If you want to know more about reproducible research practices, you can look at more cases studies on http://www.practicereproducibleresearch.org/ 

- If you want to know more about reproducibility of scientific results in Europe : 
* [Reproducibility of scientific results in the EU](https://op.europa.eu/en/publication-detail/-/publication/6bc538ad-344f-11eb-b27b-01aa75ed71a1)
* [Assessing the reproducibility of research results in EU Framework Programmes for Research](https://op.europa.eu/en/publication-detail/-/publication/36fa41a8-dbd5-11ec-a534-01aa75ed71a1/language-en)                                               




# Learning Unit 3: Technical Aspects

The goal of this unit is to showcase concrete ways on how to put into practice the various topics and recommendations regarding reproducible research discussed during the previous training session.

The unit covers 4 main aspects, starting with providing a bridge between theoretical aspects discussed so far and technical aspects which are the main focus of this presentation. Then, the outline the common challenges that arise when it comes to research data management and how data longevity can be ensured across wide timespans. Finally, a discussion on collaboration tools that can also aid the reproducibility aspects of the research, introducing Jupyter noteooks as the means to do so.

## Learning Objectives
After completing this unit, you will be able to:

* Describe the challenges related to data management
* Use Git as a file versioning tool
* Explain different data back-up methodologies and select the optimal one
* Discover the concept of virtual notebooks and their relation to reproducibility

## Duration
- 150 mins

## Prerequisites
The technical aspects is an introductory unit in which the concepts of file naming schemes, file versioning, Git, and lab notebooks are introduced. As the unit is targeted at the beginner level, no explicit preparation is needed before attending the session. However, accounts on the following platforms will be useful for conducting the exercises:

GitHub. Details about account creation are available on the [GitHub docs page](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)

Google Colab (if you plan to use Google Colab instead of Binder for testing out the lab notebooks). A free Google account is enough for accessing the Colab service. More information is also available on the [official page](https://colab.google/).

No additional software apart from a web browser is required for taking part in the training or for conducting the exercises. 

## Learning Tools
- See Prerequisites
- The content is designed to be taught online, therefore a virtual teaching platform with breakout rooms is used to facilitate the content and activities.

## Learning Content Topic

### From Theory to Practice
Data management plans can be abstract in nature and there is a need to discuss ways of how different aspects can be implemented in practice. This section focuses on topics such as:

* Securely storing research data
* Describing the stored data so that others can easily make sense of it and reuse it
* Optimizing the storage and presentation of the data to facilitate collaboration
* Ways in which research data can be made persistently available, ensuring its longevity

A common problem which everyone has experienced is having to deal with multiple versions of the same file, named seemingly in an arbitrary fashion. When multiple versions of the same file are available, clear indication to which one is the most recent and up-to-date one is needed. Furthermore, if unsuitable naming convention adopted, there is also no clear indication on how these versions differ between each other and what changes have been introduced when. Some potential options that can be used for organizing research files are:

* Using search tools (should be avoided, discussed in more details on the next slide)
* Defining a consistent and descriptive file naming strategy and applying it to individual files
* Using more advanced file versioning tools which can also act as collaboration enablers, discussed in more details later in the presentation

Using advanced searching tools to find a given file, without adopting a more systematic approach is usually just a “local” solution, that will work on a given workstation. Different operating systems have different features when it comes to file searching, and what works on a given machine might not work on others. Additionally, this limits the platforms where the files can be hosted, since different online services have vastly different text searching capabilities. As a result, this option should be avoided if possible. It should be stressed that in this unit we do not make any recommendations on “how” the naming scheme should be structured, just that it should be well defined and consistently applied across all files. The adopted naming scheme should be as descriptive as possible, incorporating elements that are useful for the given type of files, such as the creation date, a brief description, incremental version number, etc... The ordering in which elements are added to the naming scheme is also very important, since it has an impact on the lexicographical sorting of the files

### Filenaming recommendations
No golden rule. Different conventions for different file groups are possible.

Think about what is important:

* The date
* The format
* Description
* Version
*Keep in mind that operating systems sort files in a lexicographical order. Put important information first.*

* Include metadata, use abbreviations
* Decide what information to include in the file name
* Different environments have different file name length limits 
* Keep full directory length less than 255 characters to avoid problems
* Use ISO 8601 for data formats (YYYYMMDD). Lexicographical sorting will sort the files correctly based on date in this case.
* Use fixed length numbers: 001, 017, 153 instead of 1, 17, 153

A common pitfall with lexicographical sorting is the sorting of numbers. To avoid this, fixed length numbers should be used, along with ISO 8601 notation for any dates in the file name. Another point to make is that even though modern devices might support long file names, for backwards compatibility it is better to limit file paths to no more than 255 characters.

* Include file extensions in the name. Some operating systems do not require an extension, but it is a good practice (e.g., image1.jpg, image2.png, README.md)
* Avoid special characters and spaces in file names
* Different operating systems have different policies regarding special characters (:, /, \, ?, |, <, > are all problematic)
* Spaces make it difficult to type the name on the command line. Use _, -, or character casing to separate metadata: my_file.txt; my-file.txt; MyFile.txt
* Do not use the same name with changed casing: image1.png and Image1.png

Proper filenaming examples: 

* [investigator]_[method]_[subject]_[YYYYMMDD]_[version].[ext]
* [project #]_[method]_[version]_[YYYYMMDD].[ext]
* [YYYYMMDD]_[version]_[subject]_[datacollector].[ext]
* [type of file]_[author]_[date].[ext]

### Tips to applying filenaming conventions
Dealing with an existing set of files which have not adopted a consistent naming scheme previously can be tedious and error prone, should the renaming process be manually conducted. An alternative is to use automated bulk renaming tools:
Microsoft Windows: [BulkRenameUtility](https://www.bulkrenameutility.co.uk/), [PowerToys PowerRename](https://learn.microsoft.com/en-us/windows/powertoys/powerrename)
MacOS: built-in bulk renaming, [Transomino](https://www.transnomino.com/)
GNU/Linux: [rename](https://man7.org/linux/man-pages/man1/rename.1.html)


### More advanced file versioning with Git
Git is the most popular file versioning tool today, available as open-source software for all popular computing platforms. Main benefit of adopting Git is the fact that it can efficiently track the complete history of a given file, allow reverting to previous file versions and deal with (conflicting) changes made by multiple users. 


### Git features and terminology

*Repository* – analogy to a folder with enabled file versioning features.
*Clone* – local copy of a remote repository with its full version history and file contents.
*Commit* – a record of changes to a file or a set of files. Described by a commit message.
*Push* – upload of local commit(s) to a remote repository (online).
*Pull* – download of remote commit(s) to a local repository.
*Fork* – a 1:1 copy of an existing repository. Forks share the same history as the parent but diverge by adding unique changes.

Care should be taken to clearly describe the difference between the clone and pull actions to users that have not used Git before. Cloning is done once at the repository level, downloading all files within it, along with the complete history for each file. In a nutshell, cloning allows a remote repository to be downloaded locally.

Pulling revers to downloading remote changes that have been uploaded to the online hosted Git repository in the meantime, thus reconciling the remote changes with the local changes. To pull remote changes to a given repository, the repository must already be available locally, meaning that the clone action has been executed previously. 

In most cases, the most popular free Git hosting services will be sufficient for most research groups. Depending on the subject area, there might be specialized Git hosting services available as well. Users should also check if their institution already offers a hosted Git service. 

### Git feature spotlight
Repository visibility options are:

*Private* – only designated people have access and not visible to search engines
*Public* – anyone can view the repository, indexed by search engines

Branches are a very useful tool when collaborating with others. Each new set of changes can be developed on a separate branch, until ready to be made part of the original content, by merging that branch to the primary branch. 
Potentially disruptive changes to the files can also be made on separate branches and if they are successful, merged into the main branch. If unsuccessful, the branch can simply be discarded, without any effect to the main branch’s content. 

*Git blame* – check by whom a given change was made and when
*Git branch* – parallel version of a single repository. Changes to it do not affect the “primary branch” or live version. Parallel branches can eventually be merged to the primary branch if desired. Branches allow multiple people to work in parallel, without disturbing each other. Once the work on the subbranch has been finished (new experiment, new chapter...), it can be merged to the main branch. Should merge conflicts arise (conflicting changes have been introduced), they can be manually reconciled.

### Git and README files
Good practice is to add a README.md file in each directory. The README.md file in the top of the repository serves as a general description
including description of subdirectory contents and file naming schemes and is shown prominently on the web

### More ways to use Git
Git itself is free and open-source software and there are multiple ways to interact with Git repositories:

* Official command line application – git
* Dedicated desktop applications
* GitHub Desktop
* Sourcetree (BitBucket)
* Sublime Merge
  
Find a [Step-by-step guide](https://fair-by-design-methodology.github.io/FAIR-by-Design_ToT/latest/Stage%204%20%E2%80%93%20Produce/08-Development%20Tools/08-Introduction%20to%20Markdown%20and%20Git/#version-management) on getting started with a desktop client as part of the FAIR-by-Design ToT Development Tools learning unit.

### Tracking the lifecycle of a file with Git
Git does not track only the file contents. It also helps with adding, removing, and renaming files. Part of the summary information about the changes introduced in the commit. An important point to make is that Git does not only version the content of the files, but also their location and name. This makes it easy to track the complete lifecycle of a given file not only as its content is changed, but also as it is moved between subdirectories and/or renamed. This is especially important for long living repositories, where the file naming schemes might have evolved over time. Note also that this versioning of the file names also provides an additional safety net when using bulk rename utilities. Undoing a botched bulk rename is just a matter of reverting the corresponding commit where the changes have been introduced.

### Ensuring data longevity
Data is the basis of research. Data recovery upon loss might be expensive, slow, or even impossible. Therefore, reliable backups are an important part of data management. When keeping a single copy of data, it is not a matter of if the data will be lost, but when it will be lost, as it is just a matter of time. To prevent this, a robust backup strategy should be implemented. Mitigation against:
* Hardware failure
* Software failure
* Silent corruption
* Human errors
* Device theft/loss

  Do not store data in a single local copy - Storing locally and on an external medium + in the cloud (three copies)
This is also known as the 3-2-1 backup method: 3 copies of data (1 production and 2 backups); 2 different media; 1 copy off-site.

### Github and backup aspects
Question: If I use an online Git service to host my repositories, do I have to implement any additional backup solutions?
Answer: Yes

It is good practice to apply the same backup strategy as used for the rest of your files. For additional safety repository mirrors can be set up, where the repository content is mirrored across different Git hosts (e.g., GitHub and GitLab). Using a single online hosting Git service is not backup, since the account can be disabled, the service can go out of business or can suffer unrecoverable data corruption/loss.

### Final points about backup aspects
Careful consideration when choosing a cloud storage service:

* Security aspects
* Privacy policy (Privacy aspects should be taken into careful consideration when choosing online storage services. It is advised to carefully read both the privacy and terms of use policies).
* Data mining
* Data ownership
* Terms of use
* Guaranteed service & data availability

## Tools for collaboration and reproducibility
If I meticulously manage my data and describe it in detail while publishing it in a Git repository, isn’t that enough? The answert is NO.

### Electronic Lab Notebooks
Electronic Lab Note books can assist in online and offline searching, output in different formats, sharing your data, embedding different media to make content more interactive and improving accessibility. Depending on the scientific discipline, different tools are used, but Jupyter is among the most popular ones today. It should be stressed that Jupyter is not limited only to the use of the Python programming language and that other programming languages are supported as well through the introduction of different “kernels”.

### Setting up a Jupyter environment
Local installation

* pip install jupyterlab
* jupyterlab notebook
The local installation instructions assume that the user already has a Python environment setup.

Hosted Jupyter environments available at many institutions. But there are also free services
[Binder](https://mybinder.org/)
[Google Colab](https://colab.research.google.com/)
Google Colab is a popular electronic lab notebooks service compatible with Jupyter Notebooks. It provides both a free and a paid option. The paid option includes higher resource limits and the code is executed on more performant hardware. Both Binder and Google Colab support a direct Git integration, where a Git repository can be immediately opened in the respective environment just by providing a link to it.

### Jupyter and Git
Jupyter and Git are commonly used in tandem. Git for storing the data, and Jupyter for analyzing and visualizing the data.
Jupyter can be connected directly to a Git repository. All files are available in the Jupyter environment.It is possible to create permanent links which instantiate a new Jupyter environment from a Git repository upon a click. 
Note, that many Git hosts offer a dedicated read-only view for Jupyter notebooks

### Do's and Don't's with Jupyter Notebooks

* ✅ Do serialize or cache the intermediate outputs of long-running steps.
* ✅ Do take care to execute the steps serially, one after the other, before publishing the notebook.
* ❌ Don’t ever edit your raw data, especially not manually. This includes changing file formats or fixing errors by hand.
* ❌ Don’t overwrite your raw data with a newly processed or cleaned version. Notebooks should be as idempotent as possible.
* ❌ Don’t save multiple versions of the raw data.

### Zenodo and Github integration
The step-by-step instructions on how to achieve the Git<->Zenodo integration are out of scope of this presentation and participants are invited to have a look at [Referencing and citing content guide from GitHub](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
The Git repository can be seen as a “living organism” to which changes can be made at any point, whereas Zenodo deposits are point-in-time freezes of the content of the repository, created on the repository owner’s demand

### Key Takeaways
The challenge of putting data management plans into practice
* Practicing good data hygiene
* Hierarchical file structure
* File naming conventions
* The importance of data backups

File versioning
* Collaboration enabler
* Integration with third-party (research) infrastructures (e.g., Zenodo)

Improving reproducibility by providing a snapshot of the compute environment
* Electronic lab notebooks
* Integration with file versioning
* Free vs. paid hosting options

Comparison of electronic lab notebook documents



### Learning Activity
This unit has two learning activities.

**Activity 1** 
The learner practices using the Git blame feature, Activity 5 [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Learning%20Unit/Activities)

The activity uses this [demo repository](https://github.com/Task-4-2/librarian-git-exercise)

**Activity 2**
The learner practices using Jupyter Notebooks, Activity 6 [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Learning%20Unit/Activities)

This activity can be conducted on any online Jupyter service that offers the possibility to clone a remote public Git repository. The links towards Binder and Google Colab are direct links, meaning that they will open a new browser window with the corresponding Git repository already cloned and a Jupyter notebook ready to be used. In case one of the links does not work, the other can freely be used as an alternative.

## Suggested Reading
* Learn more about Jupyter notebooks by following the [Zero-to-Binder guides](https://book.the-turing-way.org/communication/binder/zero-to-binder.html).
* Learn more about Git branching and how it works using the interactive ["Learn Git Branching" tool](https://learngitbranching.js.org/).
* Markdown is a useful tool to format text-based cells when using Jupyter notebooks. Learn more about Markdown by following the [FAIR-by-Design Markdown guide](https://fair-by-design-methodology.github.io/FAIR-by-Design_ToT/latest/Stage%204%20%E2%80%93%20Produce/09-Content%20Development/09-Markdown%20Syntax/)
* Be wary of common pitfalls when using Jupyter notebooks by reading the ["Reproducibility"](https://ml-science-book.com/reproducibility.html) section of the Supervised Machine Learning for Science Git Book. The part about ordering of executed cells is especially important.
* Use [Cookiecutterbased](https://github.com/cookiecutter/cookiecutter) templates such as the one for [data science by DrivenData](https://cookiecutter-data-science.drivendata.org/) for easy initialization of new coding environments.

