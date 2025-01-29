---
title: "Learning Unit 2: Reproducibility Crisis and Remedies"
author: "Skills4EOSC T4.2"
tags: 
    - FAIR-by-Design Learning Materials
    - FAIR Learning Objects
    - Reproducibility crisis
---

# Learning Unit 2: Reproducibility Crisis and Remedies

## Learning Objectives

- Explain what reproducible research looks like in practice
- Explain the barriers to reproducibility and how to overcome them

## Target Audience

- Data Librarians and other data curious

## Duration

- 60 mins

## Prerequisites

- Please read the two cases ([Activity 3a](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/blob/main/resources/Unit%2002%20%E2%80%93%20Reproducibility%20Crisis/Activities/03a-Definition%20of%20Research%20Misconduct.md) and [Activity 3b](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/blob/main/resources/Unit%2002%20%E2%80%93%20Reproducibility%20Crisis/Activities/03b-The%20case%20of%20Brian%20Wansink%20-%20P%20Hacking.pdf))

## Learning Tools

- Training BBB room
- Browser

The content is designed to be taught online, therefore a virtual teaching platform with breakout rooms is used to facilitate the content and activities.

## Reproducibility Crisis and Remedies

This unit introduces the Reproducibility Crisis, what it is and actions that can be taken to implement reproducible workflows to counter this crisis.

## What is the Reproducibility Crisis?

[Nature](https://www.nature.com/articles/533452a) did a rather extensive survey a few years ago on reproducibility. It showed that 90 % of the survey participants – the researchers - thinks that a reproducibility crisis is a fact - either slightly or significantly (1,576 scientist in sample).


- More than 70 % of researchers have failed to reproduce another scientist’s experiments. More than half have failed to reproduce their own experiments. Publishing replicated positive studies did not feel very motivating (24 %) and journals are reluctant towards publishing negative replication results (13 %)
- More than 60 % experienced failure in reproducibility due to pressure to publish and selective reporting. Adding to the difficulties to comply to reproducibility practices were also competition for grants and growing amount of bureaucracy demands
- Almost 90 % felt that a more robust experimental design and improved statistics and mentorship could help to solve the reproducibility crisis. Also enhanced practices and journal checklists were ranked high
- 80 % think that research funders and publishers should do much more to address this issue

Another analysis by [Macleod](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(13)62329-6/abstract) estimates that 85% of biomedical research efforts are wasted

In summary, lack of reproducibility has a negative impact on public trust in the conclusions of science. Trust and confidence are important for science, but have different meanings for scientists, citizens and policy-makers. The aim is to make science reproducible. Reproducible science is where all information relevant to the  work, including, but not limited to, text, data and code, is made available, such that an independent researcher can reproduce the results.

The overarching categories of factors that impact reproducibility in research are:

- **Technical Factors:** Issues related to tools, processes, and materials that can introduce variability or error.
- **Human Factors:** Behavioral and procedural issues, such as errors or poor practices in data recording or sharing.
- **Study Design & Statistics:** Problems with the planning and execution of research studies, including misuse of statistical methods.
- **Rewards & Incentives:** Structural pressures in academia that encourage practices undermining reproducibility, such as prioritizing novelty over rigor.

Reproducibility is one of the principle at the core of open science - Both focus on transparency and this principle is particularly important to reinforce the rigor of scientific results

## A Reproducible Research Lifecycle

The more of the research cycle is available and accessible, the more reproducible and verifiable the work. A paper only presents the output, but a format that is gaining more and more traction is the research compendium. This combines data and code with (information about the) environment, as well as usage information and a license. A research compendium can be made executable as well, allowing full reproduction of the project at the click of a button.

Why code? A proper basic understanding of programming is incredibly useful to find, store, utilize, document and interpret data. It is the first step towards making research reproducible. Large datasets, or the option to use specifically developed tools, can also be reasons a researcher will need to use a programming language like R, or Python.

Unfortunately, having access to data and a script does not guarantee that a project can be faithfully reproduced. Also, attaching code as supplementary material does not allow software to stand as a research product in its own right. Making science reproducible requires an open, adequate combination of data and software.

Good version control is essential, and requires its own tools. Also, unlike a paper, software is not stand-alone, and requires extra work to ensure it can function faithfully on another machine, or in another time. Challenging, and there is a need to consider how to license software and how to cite used software (and what platform to use for publishing it).

## How to improve reproducibility

Data can be FAIR but if they are of poor quality or the methods of collection and analysis are biased or poorly described, the research will not necessarily be reproducible.
It is necessary that experimental protocols, analysis methods, source codes and software used are also shared in a complete and detailed manner. These aspects are not always covered by FAIR.

There are different levels of reproducibility.  the gold standard being that the code, all documentation and installation instructions are available as well as access to a virtual environment, such as a jupyter notebook, where you can re-run the analysis. Basically sharing data and code alone is not enough.

### Care about data

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

### Care about Code

To care about code we have to keep in mind that it is important to:

- Describe, comment on your codes and their sequences using flowcharts, notebook​
- Use development standards: framework (Django, Symfony), common programming languages, free (R, Python) 
- Work in a shared and protected environment ​
- Choose the right licenses: Apache, GNU GPLv3, MIT  ​
- Work with version management tools -> software forge (a forge is a web-based collaborative software platform for developing and sharing computer applications),  continuous integration
- Archive your code (Software Heritage)​
- Publish your code/software in open journals

### Care about Environment

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

- **Build communities** – elevating trust requires shared risk and reward : Use  of narrow metrics, e.g., pub count, impact factor, leads to poor  results – need a community to improve practices - Risky for single team  to invest heavily​
- **Collaborate with stakeholders** (publishers and funders) to raise expectations  : transparent results, common terminology, elevated expectation, high quality software​
- **Invest in software ecosystems** – easier to improve quality & share investments:  high quality ecosystems, investement in software skills, new software tools and methodologies​
- **Transform software research into science** – and capture science fundings: scientific software needs a research focus  - improve scientific software using science​

## Summary

1. Reproducibility has to be thought of as a long-term goal, where concepts and terminologies are to be discussed among different communities to make sure that there is a coherent terminologyin place thatall communities can understand. According to the literature review and interviews done, these types of engagement are more and more starting to occur

2. There is a need for a bottom-up approach to shape policies that support reproducible research practices. This due to the fact that there are naturally huge differences between the different communities in terms of e.g. standards and methods used. This image shows exactly at which stages this policy development work is to take place in order to be correctly understood and supported by key stakeholders, such as research performing organisations, funders, publishers and service providers. Currently, very very few (NWO only exception) do not support nor require reproducibility, and publishers are afraid to include reproducibility requirements as they fear it might affect the submission rates in a negative manner. But we can see some progress here as well, where some publishers are adding some reproducibility requirements.

3. There is a need to bake in the reproducibility aspects into the everyday research process and for it to thus become the norm – the way things are done within science. But these efforts are currently seen as time-consuming and efforts that adds on top of the ordinary research practices, so incentives are needed. Here the dis-incentives are mentioned, which are well-known challenges – the H-index and Impact Factors and the time preassures put on researchers.

4. It is, however, not easy to change things in this respect, as being reproducibility compliant requires good data management practices. These skills are preferrably to be developed early on in the research career, which also helps in taking reproducible aspect into account during all stages of the research life cycle. Here is where especially the FAIR principles comes into play.

5. There are lots of tools and infrastructures available to support good research data management practices and researchers are aware of these, but that is not really the problem in the end. The problem is that the interoperability between systems is not at an advanced stage just yet and thus hinders reproducible research workflows.

## Key Takeaways

- Lack of reproducibility has a negative impact on public trust in the conclusions of science!
- Data reproducibility is key to Open Science, but FAIR principles alone don't guarantee it
- Proper management of data and code, combined with well-documented computational environments, is essential for ensuring the reproducibility of research results
- Data reproducibility practices must be supported by institutional policies that establish a strong regulatory framework to enforce and maintain them over time

## Learning Activity

This unit has a learning activity about scientific misconduct and is described here: [Activities](https://github.com/Task-4-2/Technical-Skills-as-bridge-to-reproducible-research/tree/main/resources/Unit%2002%20%E2%80%93%20Reproducibility%20Crisis/Activities)

To understand why research integrity matters, this activity examines what happens when such integrity is absent – research misconduct.

## Suggested Reading

- If you want to know more about reproducible research practices, you can look at more cases studies on [http://www.practicereproducibleresearch.org/](http://www.practicereproducibleresearch.org/)

- If you want to know more about reproducibility of scientific results in Europe: 
    - [Reproducibility of scientific results in the EU](https://op.europa.eu/en/publication-detail/-/publication/6bc538ad-344f-11eb-b27b-01aa75ed71a1)
    - [Assessing the reproducibility of research results in EU Framework Programmes for Research](https://op.europa.eu/en/publication-detail/-/publication/36fa41a8-dbd5-11ec-a534-01aa75ed71a1/language-en)
