---
title: Professional work
layout: single
classes: wide
---

Here you can find the professional work I have done. This page focuses on projects I've been a part of that were not directly related to my MPhil or PhD projects. Teaching related work can be found [here](/teaching/).

## Research assistant

Over most of 2021 and into 2022 I worked as a research assistant on a couple projects relating to COVID-19. 

- COVID-19 federal forecasting
  - Running weekly forecasts for COVID-19 cases, maintaining, and improving the codebase, and implementing novel developments for inclusion of vaccination data and handling of co-circulating strains.
  - Worked with teams all around Australia to produce weekly forecasts of COVID-19 cases for the Australian federal government.
  - Took on a mature codebase that has been worked on by multiple collaborators and has been consistently updated since March 2020 as the pandemic has progressed.
  - Extensive updates to the Stan model and the simulation model.
    - I developed approximations for the forward simulation method that allowed for a 10-20x speedup in that component of the model.
  - Code is available [here](https://github.com/djmorris7/covid19-forecasting-aus) (note that this cannot be run as data-sources are no longer available and this repository acts as an archive now).
  - The details of our model (the Probabilistic model) is available in the series of Technical Reports available here:
    - [Technical Report March 2021](https://www.doherty.edu.au/uploads/content_doc/Technical_Report_15_March_2021_RELEASED_VERSION.pdf)
    - [Model updates May 2022](https://mspgh.unimelb.edu.au/__data/assets/pdf_file/0003/4256103/2022-05-22-Technical-report-public-release.pdf)
- First Few X (FFX) COVID-19
  - Assessed the assumptions of a final size based epidemic model. This model used a particle filter with importance sampling to infer $R_0$ and model parameters related to the mixing of individuals.
  - Translated the codebase I inherited from MATLAB to Julia to obtain around a 50x improvement in runtimes.
  - The publication arising from this work is available at [doi:10.1016/j.lanwpc.2022.100573](https://www.thelancet.com/journals/lanwpc/article/PIIS2666-6065(22)00188-2/fulltext).

## Workshops and outreach

In 2022 I helped to develop a **Data Science Coffee Club** at the University of Adelaide for post-graduate students in Mathematics. We developed a series of sessions for giving a crash course into the following LaTeX, Git and Github, code practices, debugging, plotting, note-taking practices and more. In 2023 we refined this session and rebranded as **HDR Skills Workshop**. This was a more streamlined version of the sessions with an emphasis on encouraging collaboration and development of incoming students.
