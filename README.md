# Identifying-GitHub-Expertise-Using-NLP
## Note: 
This is a reproduction project as part of the MSR course 2022 at UniKo, CS department, SoftLang Team
## Name of the team: 
Whiskey
## Student names: 
- Aneesa Sulthana Jagaraspalli
- Irshad Hussain Mohammed
- Pavan Kumar Tokachichu

## Objective of Reproduction
### Description : 
Training Microsoft LUIS with utterances of different technologies using NLP and  testing the acquired code chunks from github repositories  on the trained LUIS to find Precision, Recall and F-measure.
### Input data:  
Used GitHub REST API version 3, https://developer.github.com/v3/ to fetch input data(commit data) for testing LUIS 
Paper Code Repo: https://github.com/melkor54248/RepoSkillMiner

### Output data: 
Evaluate Precision, Recall and F-measures for the derived technologies, by conducting a test in LUIS and reporting the results.

## Implementation of Reproduction
### Hardware Requirements :
- x86 64-bit CPU (Intel / AMD architecture)
- 4 GB RAM
- 1 GB free Disk space

### Software Requirements :
- Windows 7 or 10
- Mac OS X 10.11 or higher, 64-bit
- Linux: RHEL 6/7, 64-bit (almost all libraries also work in Ubuntu)
- Browser to access Microsoft Azure (Chrome, Bing, Firefox, Safari)

### Validation :
The Technologies used by the authors produced more accurate results than the technologies chosen by us. We have chosen Pyspark and Sql to train LUIS and the reason to chose these two technologies is because these two technologies have a lot of similarities in their syntaxes. We wanted to check if the paper is biased with the technologies chosen by authors. As a result of our Reproduction, we found out that the metrics like Precision, Recall, F-measure were less for model differntiating SQL and Pyspark.This is because there were complex ines of code especially when provided by a Pyspark line of code internally having sql command.

### Data :
#### Input   :
#### Output  :
