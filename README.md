# CSIQ
CSIQ: A Synthesized Dataset of Code Smells, Issues and Quality related Artifacts from Open Source Repositories


The dataset contains synthesized code smells, issues, quality, and source code metrics information of 60 versions under 10 different repositories. The dataset is extracted into 3 levels: (1) Class (2) Method (3) Package. The dataset is created upon analyzing 9,420,246 lines of code and 173,237 classes.  The provided dataset contains following folders: code smells, issues, quality attributes, synthesized and four associated Comma Separated Values (CSV) files: repositories.csv, versions.csv, codesmells.csv and attribute − details.csv. The first file (repositories.csv) contains general information (repository name, URL, number of commits, stars, forks, etc.) to understand the size, popularity, and maintainability.   File versions.csv contains general information (version unique ID, number of classes, packages, external classes, external packages, version repository link) to provide an overview of versions and how over time the repository continues to grow. File  attribute-details.csv  contains detailed information  (attribute name,  attribute short form, category, and description) about extracted static analysis metrics and code quality attributes.  The short form is used in the real dataset as a unique identifier to show value for packages, classes, and methods. File codesmells.csv provides the information (Rule, Code Smell, Rule Description) of code smells analyzed from each version.

Here  I shared the documentation explaining how to obtain the artifact package, how to unpack the artifact. 

## How to obtain the artifact package
Identify the repositories and their link from Github that you want to mine issues
For example: I will mine the following repositories
1. https://github.com/spring-projects/spring-framework
2. https://github.com/junit-team/junit5
...


### Issue Mining
Follow the steps for each repository. For example I want to it my no 1 repository: spring-framework
Step 1: Visit the following URL https://www.smreza.com/projects/modelmine/issues.php 
Step 2: paste the repository URL in the GitHub Link box
Step 3: Choose State from the selection. Issue state is either All, Open or closed.
Step 4: Choose Start issue no and how many issue. Bu Default start issue  is 1 and no of issue is 1000 meaning it will mine issues from the beginning and mine first 1000 issue.
Step 5: Choose the motive. Motive is either export or analysis. In case of obtaining issue artifact, please choose export. 
Step 6: You can go to step 2 and put another repository and repeat step 3-6 to obtain artifacts for selected repositories. 


## How to unpack the artifact

Follow the steps for each repository. For example I want to it my no 1 repository: spring-framework
Step 1: Download the zip of this repository or visit https://doi.org/10.17632/77p6rzb73n to download the data
Step 2: extract the zip file and locate the dataset folder.
Step 3: Use this dataset folder as artifcat dataset in your programming in python or any other language.
Step 4: Read all the csv files under issue folder. Asample code is provided in the following link: https://www.kaggle.com/code/saifuddinmahmud/git-issue

## Where Issue dataset can be obtained 
-  Download the zip of this repository from this link https://github.com/sayedmohsinreza/CSIQ/ or visit mendeley data https://doi.org/10.17632/77p6rzb73n to download the data
-  No password is neccessary
-  No Installation needed

