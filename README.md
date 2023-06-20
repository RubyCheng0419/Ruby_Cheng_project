---
type: "project" # DON'T TOUCH THIS ! :)
date: "2020-06-04" # Date you first upload your project.
# Title of your project (we like creative title)
title: "Connect differently? Resting-state functional connectivity in patients with fibromyalgia (FM) syndrome"

# List the names of the collaborators within the [ ]. If alone, simple put your name within []
names: [Chia-Yu Cheng]

# Your project GitHub repository URL
github_repo: https://github.com/RubyCheng0419/Ruby_Cheng_project

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [Resting-state functional connectivity, fibromyalgia, chronic pain, pain matrix]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

Summary: "The aim of the study is to fully understand the mechanisms involved in FM pathology. To be more specific, we want to know the difference in endogenous pain modulation between FM patients and healthy control. We mainly focus on 6 brain regions included in pain matrix and investigates its connectivities."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: ""
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Project definition

### Background

As a graduate student, I was studying task-based fMRI analysis, digging into the deficiency of cognitive abilities in chronic pain patients. However, chronic pain patients not only exhibit cognitive deficiency, their brain also demonstrate impaired functional connectivity patterns. Thus, I decided to utilize the knowledge of what I've learned in Brainhack School and compared the difference of functional connecitiy bwteen chronic pain patients and healthy control. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTYs_JFKsHI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Tools

The project will rely on the following technologies:
 * fmri prep, to preprocessing the frmi data.
 * Markdown, to structure the text.
 * Python, with nilearn packages to analyze functional connectivity.
 * Jupyter notebook, to present the result. 
 * Adding the project to the website relies on github, through pull requests.

### Data
The [OpenNeuro website] (https://openneuro.org/datasets/ds004144/versions/1.0.2) which provided the sample data in BIDS forms.

Ultimately, the project template will be used by all BHS participants. Data on the different projects will be aggregareted on the (https://psy6983.brainhackmtl.org/project). This will serve as an additional example gallery in the years to come for future brainhack school students. Many reports from [BHS 2020](https://github.com/brainhack-school2020) already used this template.

### Deliverables

At the end of this project, we will have:
 - The current jupyter document, completed and revised.
 - A github website about the project.

## Results

### Progress overview

The project was swiftly initiated by P Bellec, based on the existing template created in 2019 by Tristan Glatard and improved by different students. It was really not that hard. Community feedback is expected to lead to rapid further improvements of this first version.

### Tools I learned during this project

 * **Meta-project** P Bellec learned how to do a meta project for the first time, which is developping a framework while using it at the same time. It felt really weird, but somehow quite fun as well.
 * **Github workflow-** The successful use of this template approach will demonstrate that it is possible to incorporate dozens of students presentation on a website collaboratively over a few weeks.
 * **Project content** Through the project reports generated using the template, it is possible to learn about what exactly the brainhack school students are working on.

### Results

#### Deliverable 1: report template

You are currently reading the report template! I will let you judge whether it is useful or not. If you think there is something that could be improved, please do not hesitate to open an issue [here](https://github.com/PSY6983-2021/project_template/issues/) and let us know.

#### Deliverable 2: project gallery

You can check out the [2020 BrainHack School project gallery](https://psy6983.brainhackmtl.org/project/)

##### ECG pupilometry pipeline by Marce Kauffmann

The repository of this project can be found [here](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann). The objective was to create a processing pipeline for ECG and pupillometry data. The motivation behind this task is that Marcel's lab (MIST Lab @ Polytechnique Montreal) was conducting a Human-Robot-Interaction user study. The repo features:
 * a [video introduction](http://www.youtube.com/watch/8ZVCNeX42_A) to the project.
 * a presentation [made in a jupyter notebook](https://github.com/mtl-brainhack-school-2019/ecg_pupillometry_pipeline_kaufmann/blob/master/BrainHackPresentation.ipynb) on the results of the project.
 * Notebooks for all analyses.
 * Detailed requirements files, making it easy for others to replicate the environment of the notebook.
 * An overview of the results in the markdown document.

##### Other projects
Here are other good examples of repositories:
- [Learning to manipulate biosignals with python](https://github.com/mtl-brainhack-school-2019/franclespinas-biosignals) by François Lespinasse
- [Run multivariate anaylysis to relate behavioral and electropyhysiological data](https://github.com/mtl-brainhack-school-2019/PLS_PV_Behaviour)
- [PET pipeline automation and structural MRI exploration](https://github.com/mtl-brainhack-school-2019/rwickens-sMRI-PET) by Rebekah Wickens
- [Working with PSG [EEG] data from Parkinson's patients](https://github.com/mtl-brainhack-school-2019/Soraya-sleep-data-in-PD-patients) by Cryomatrix
- [Exploring Brain Functional Activation in Adolescents Who Attempted Suicide](https://github.com/mtl-brainhack-school-2019/Anthony-Gifuni-repo) by Anthony Gifuni

#### Deliverable 3: Instructions

 To be made available soon.

## Conclusion and acknowledgement

The BHS team hope you will find this template helpful in documenting your project. Developping this template was a group effort, and benefitted from the feedback and ideas of all BHS students over the years.

You can also make submit your project to neurolibre https://neurolibre.org/. It is a preprint server for interactive data analyses. It is tailored for publishing interactive neuroscience notebooks that can seamlessly integrate data, text, code and figures.The submission instructions can be found here https://docs.neurolibre.org/en/latest/index.html and the jupyter book docs there https://jupyterbook.org/intro.html.
