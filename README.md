# CSIQ
CSIQ: A Synthesized Dataset of Code Smells, Issues and Quality related Artifacts from Open Source Repositories


The dataset contains synthesized code smells, issues, quality, and source code metrics information of 60 versions under 10 different repositories. The dataset is extracted into 3 levels: (1) Class (2) Method (3) Package. The dataset is created upon analyzing 9,420,246 lines of code and 173,237 classes.  The provided dataset contains following folders: code smells, issues, quality attributes, synthesized and four associated Comma Separated Values (CSV) files: repositories.csv, versions.csv, codesmells.csv and attribute − details.csv. The first file (repositories.csv) contains general information (repository name, URL, number of commits, stars, forks, etc.) to understand the size, popularity, and maintainability.   File versions.csv contains general information (version unique ID, number of classes, packages, external classes, external packages, version repository link) to provide an overview of versions and how over time the repository continues to grow. File  attribute-details.csv  contains detailed information  (attribute name,  attribute short form, category, and description) about extracted static analysis metrics and code quality attributes.  The short form is used in the real dataset as a unique identifier to show value for packages, classes, and methods. File codesmells.csv provides the information (Rule, Code Smell, Rule Description) of code smells analyzed from each version.

Your Github repo should have documentation files explaining how to obtain the artifact package, how to unpack the artifact, how to get started, and how to use the artifacts in sufficient detail. The artifact submission must describe only the technicalities of the artifacts and uses of the artifact that are not already described in the paper. The submission should contain the following documents (in markdown plain text format).

## how to obtain the artifact package
Identify the repositories and their link from Github that you want to mine issues
For example: I will mine the following repositories
1. https://github.com/spring-projects/spring-framework
2. https://github.com/junit-team/junit5
.....


###Issue Mining
Follow the steps for each repository. For example I want to it my no 1 repository: spring-framework
Step 1: Visit the following URL https://www.smreza.com/projects/modelmine/issues.php 
Step 2: paste the repository URL in the GitHub Link box



## how to unpack the artifact




A README.md main file describing what the artifact does and where it can be obtained (with hidden links and access password if necessary).
A LICENSE.md file describing the distribution rights. Note that to score “available” or higher, then that license needs to be some form of open source license.
An INSTALL.md file with installation instructions. These instructions should include notes illustrating a very basic usage example or a method to test the installation. This could be, for instance, information on what output to expect that confirms that the code is installed and working; and that the code is doing something interesting and useful. IMPORTANT, there should be a clear description of how to reproduce the results presented in the paper.
A copy of the accepted paper in pdf format.
