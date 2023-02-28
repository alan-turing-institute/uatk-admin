# The Science of Cities and Regions - Admin and planning
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## About this Repository

Welcome to the Science of Cities and Regions admin repository. The Science of Cities and Regions is an Alan Turing Institute project, aiming to produce a step change in the science of cities by the application of next generation AI and data science to address major challenges and opportunities for society, the economy and underpinning infrastructure. The project comprises four missions:
- Urban Mobility
- Land Use Planning
- Spatial inequalities and sustainability
- Digital Twins

A core part of the project is the **Urban Analytics Technology Platform (UATP)**, an ecosystem of software tools, data products and documentation.

This repository contains high-level planning and governance information for the project, onboarding information for new members of the team, and other admin and random information. It also contains high level information about the UATP ecosystem and links to the UATP repositories, data and documentation.

This repository follows the recommendations and guidance provided in *[The Turing Way](https://the-turing-way.netlify.app/welcome)* handbook to data science and was generated based on the [Turing Way's reproducible project template](https://github.com/alan-turing-institute/reproducible-project-template).

## Getting started

Please read:
- [Code of conduct](CODE_OF_CONDUCT.md) 
- [Contribution Guide](CONTRIBUTING.md)

## Communication within the project

Since we're a distributed team, we aim to document everything so that it's visible to everyone in the project. 

### Regular meetings

There is an overview of regular meetings at [`uatk-admin/meetings.md`](https://github.com/alan-turing-institute/uatk-admin/blob/main/meetings.md). Please edit if anything is missing or incorrect.

### Communication channels

- [Slack #ua-confidential channel](https://join.slack.com/share/enQtNDg3Nzc4MTI0MTIwMS0wYzhiOTdjOGRlODE2MmNjYzA3YmM2ZDBmZDQ3OTI2MzJkYjE3MGE0YWMzY2U5MWZiNDk3NjdiYmU2ZGJkZGE4) is for informal communication between team members.
- [Slack #urbananalytics channel](https://join.slack.com/share/enQtNDg2NTAzOTYwMTY2Ny1mNmFhNjNlMjk0OTZkNTYxNWExMWE1NDU2ZmEwNjYzYmVmMzAyMWQxYmRkNWMyOTA2NTg0NWM2ZjA1NTNlNmYy) is an all-Turing channel where we post about UA activity.
- Technical discussion should happen in issues on the relevant project's Github repo or in this repo for more high-level topics.

## Repo Structure

Inspired by [Cookie Cutter Data Science](https://github.com/drivendata/cookiecutter-data-science)

```
├── LICENSE
├── README.md          <- The top-level README for users of this project.
├── CODE_OF_CONDUCT.md <- Guidelines for users and contributors of the project.
├── CONTRIBUTING.md    <- Information on how to contribute to the project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── project_management <- Meeting notes and other project planning resources
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualisation  <- Scripts to create exploratory and results oriented visualisations
│       └── visualise.py
└──
```

**Maintainers**

This repository is jointly developed and maintained by the Science of Cities and Regions team at The Alan Turing Institute.

🎯 Roadmap
---

### Checklist for setting an online repository 

- [x] Add a README file
- [x] Add a [CONTRIBUTING](CONTRIBUTING.md) file
- [ ] Add a [LICENSE](LICENSE.md)
- [x] Add a [Code of Conduct](CODE_OF_CONDUCT.md)
- [ ] Install [all-contributors](https://allcontributors.org/) bot
- [x] .gitignore file (choose from a template)
- [ ] Issue templates
    - [ ] Optionally Install [Welcome/behavior](https://github.com/behaviorbot/welcome) bot (see The Turing Way [config](https://github.com/alan-turing-institute/the-turing-way/blob/main/.github/config.yml))
- [ ] Create a directory with files for project management (meetings, report, proposals)
- [ ] Create a directory with files for communications
- [ ] Create a directory for research analysis
- [ ] Create a directory for research results/outcome to share (?)
- [ ] Create a directory for ethics approval and project policies
- [ ] Create a directory with files for stakeholders info and nature of engagement
- [ ] Connect repo with Zenodo
- [ ] Add cff file for citation
- [ ] Add badges
- [x] Add some issues for short/long term work
- [ ] Add org chart
- [ ] Add UATP and projects/apps conceptual diagram
- [ ] Add wiki with descriptions and links to repos/projects/datasets


📫 Contact
---

For any queries or concerns, you can directly reach out to Grigorios Mingas by emailing [gmingas@turing.ac.uk](mailto:gmingas@turing.ac.uk).
