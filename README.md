# **UT 🇪🇪 - Master's Thesis - Mirlind, 2021 🎓**

### This repository is part of my Master's Thesis and contains all of the (external) files and scripts that were used for the analysis purpose of the study.

- Student: **Mirlind Murati**
- Supervisor(s): **Ezequiel Scott**
- Thesis Topic: **Conformance Checking of ScrumPractices: A Study of 10 Open-SourceProjects**
- Institute of Computer Science - Software Engineering
- University of Tartu & TalTech, Estonia (August 2021)


Thesis can be accessed as a PDF: [Conformance Checking of ScrumPractices: A Study of 10 Open-SourceProjects](https://github.com/mirlindm/MasterThesis-Mirlind-2021)

## Thesis Objective 🎯
- The main aim of this thesis is to reveal the type of development data that is needed to perform conformance checking techniques and achieve satisfactory results. Furthermore, this study aims to check and verify how compliant has the development process of the ten open-source studied projects been against the Scrum Agile Framework. 
- In simpler words, it aims to check whether the development teams were actually sticking to Scrum, and if yes, to what extent they were doing so.

## How 🤔? 
- With a set of defined Scrum Rules **(Scrum Rules Table (Results for RQ1).pdf)** applied over the development Jira data traces of ten open-source projects (more information over the projects can be found in the thesis PDF file), I have conducted a study analysis to check the compliance of these development teams towards the Scrum framework as defined by the [Scrum Guide](https://www.scrum.org/resources/scrum-guide).


## This GitHub repository contains the analysis part of this thesis:
- All of the datasets included in my study can be found within the directory: **Datasets (Before Cleaning), Datasets (After Cleaning) and Changelogs Datasets (After Cleaning)**.
- All of the Python scripts and notebooks used to carry the different parts of the analysis, such as data cleaning and pre-processing **(Notebook for cleaning and exporting projects data to own datasets.ipynb)**, implementation of the pre-defined Scrum rules through the Python scripts **(Scrum Rules Implementation.ipynb)**, can be found in the directory: **Notebooks - Coding Scripts**.

## Clarification
- I have used the **Notebook for cleaning and exporting projects data to own datasets.ipynb** notebook as a general file to perform initial exploration of the data and to further separate the data of the different projects in separate datasets. 
- Thereafter, for each dataset, I have created the Scrum rules implementation notebook, in order to carry out the analysis of each project in isolation.
- The results are reported altogether in the **RQ2-RQ3 Results** folder.

## Usage
- Download or clone this repository to your local machine: 
```
git clone https://github.com/mirlindm/MasterThesis-Mirlind-2021
``` 
- Upload the Python notebooks in your preferred computational notebook tool or app, such as Jupyter Notebook, Google Colab, etc.
- For each notebook, upload the corresponding dataset (csv file) of the respective open-source project, such as Nexus, XD, etc.
- Run all of the code cells within the notebook **Scrum Rules Implementation.ipynb**.
- Check the outputs and verify the results. 🥳


## Contributing
Pull requests are warmly welcome! 😊 


## Contact  📞
@: mirlindmurati777@gmail.com <br/>
@: murati@ut.com
