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

### Tools

The project will rely on the following technologies:
 * fmri prep, to preprocessing the frmi data.
 * Markdown, to structure the text.
 * Python, with nilearn packages to analyze functional connectivity.
 * Jupyter notebook, to present the result. 
 * Adding the project to the website relies on github, through pull requests.

### Data
The [OpenNeuro website](https://openneuro.org/datasets/ds004144/versions/1.0.2) which provided the sample data in BIDS forms.

### Deliverables

At the end of this project, we will have:
 - The current jupyter document, completed and revised.
 - A github website about the project.

## Results

### Progress overview

I did the functional connectivity using seed-based analysis. I mainly focus on six regions in "pain matrix". The output would be a correlation matrix indicating the relationships between these regions. 

### Tools I learned during this project

 * **Python** Nilearn package is a useful tool for functional connectivity.
 * **Jupytor notebook** I leanred how to utilize this tool to function as powerpoint.
 * **Github workflow-** I learned how to use VSCode to pull things into my repository.

### Results

#### Deliverable 1: report correlation matrix

The final result shows the significant correlation (p<.05) between 6 brain regions. 
As can be seen in the figure, compared to the healthy control, patients with fibromyalgia exhibit lower connectivity within these regions. Connectivity between right Insula and Postcnetral lobe as an example. The later step is to interpret these results and use stricker threshold to do comparisons (eg. Bofferini correction). 

## Conclusion and acknowledgement
This is a tight project that should be done within a short period of time. 
Thank you very much for all the TAs, especially Amenda and Yu-Shiang Su, they helped me a lot since I'm still a beginner to python.

