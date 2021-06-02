---
layout: page
title: About
---
<div style="display:flex;"> 

<img src="/assets/images/avator.jpg" alt="avator" style="width:150px; margin:10px" />
<table class="tg">
<thead> <tr> <th class="tg-0pky"></th> <th class="tg-0pky"></th> </tr></thead>
<tbody>
  <tr>
    <td class="tg-0pky">Name:</td>
    <td class="tg-0pky">Yichao Xu</td>
  </tr>
  <tr>
    <td class="tg-0pky">Phone:</td>
    <td class="tg-0pky">+44 (0) 75 2239 2643</td>
  </tr>
  <tr>
    <td class="tg-0pky">Email: </td>
    <td class="tg-0pky">yichao.xu.application@outlook.com</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:normal;font-style:normal;text-decoration:none">Curriculum Vitae</span>: </td>
    <td class="tg-0pky"> <a href="\assets\pdfs\resume.pdf"> Download </a>
</td>
  </tr>
</tbody>
</table>
</div>

## 1. Introduction

I am Yichao Xu, a postgraduate in Software Engineering. I am looking forwarding PhD opportunity in computer sciences, especially computer security aspects. I summaries the following three points to prove my competitiveness, and I organise the page from the three aspects: 
* Firstly, a solid academic background to CS,
* Secondly, various industrial projects experiences,
* Finally, similar research project experiences about the signature of the functions

## 2. Academic Background

### 2.1 JOHNS HOPKINS UNIVERSITY

| Duration | Major | Degree |
| - | - | - | 
| 2021 - 2022 | Security Informatics (Research and Technique) | Master of Sciences|

In this fall, I will start my second master education at JHU focusing on the research topics about computer security. 

### 2.2 UNIVERSITY COLLEGE LONDON

| Duration | Major | Degree | GPA |
| - | - | - | - |
| 2019 - 2020 | System Software Engineering | MSc with Distinction | Over 3.9 |

In UCL, I obtained my master's degree with distinction at UCL, and the major is system software engineering. The core courses include software architecture design, software testing & verifying and development tools (Git, DIFF and PATCH)

### 2.3 UNIVERSITY OF LIVERPOOL

| Duration | Major | Degree | GPA |
| - | - | - | - |
| 2017 - 2019 | Software Development | BSc with First Honour | Over 3.9 |

In Liverpool, I obtained my first honour degree in software development and ICS. My courses were about the basic computer sciences, such as algorithm, data structure, operation system, databases, various programming languages, etc. 

## 3. Campus Practices

### 3.1 Data Mining (Python)

| Duration | Project | Role |
| - | - | - | 
| 2020.03-2020.06 | A tools for GitHub repository Mining based on Python | Developer | 

In that project, I implemented a terminal tool based on Python, and there are about five thousands lines of codes. It can identify each commit's changes from the Github repositori es and then analyse co-changed relationships between the functions and tests.  
I used the following techniques and frameworks in the tool: Pyriller (Mining the Githubr epositories), GumTree and Subprocess module Invoking the Java program for classifying changes in commits) Python's data analysis modules (Handling the CSV file, analysing and visualising data), APRIORI algorithm (finding out the association between tests and functions).  
I used the tool to evaluate the tests maintenance approach in six GitHub repositories.I optimise the CoEv strategy for establishing "test-to-code tracebility links according to the results of experiments. The precision of the strategy increased to 30%. The tool can be fo unded from the link "https://github.com/aooXu/comp0110_project_tools"

### 3.2 Android Package (Kotlin)

| Duration | Project | Role |
| - | - | - | 
| 2019.11-2020.04 | Android package to predict the health status | Android Developer | 

In that project, I used Kotlin to implement an Android framework, and I contributed about ten thousands lines of codes. The framework can upload sensitive data for training the global model and download the model for health score predicting.
I used the following techniques and frameworks: Kotlin and MVVM (Ensuring the usability of the framework), Retrofit2 and WorkerManager (Uploading data and scheduling the upload), Tensorflow-Lite (Implementing the local machine learning), SQLite (Storing the machine learning model and sensitive data), Asynchronous encryption and data noise (Avoid the data abusing and eavesdropping).
I did the code review with "CarefulAI", A software development company from the UK. They accepted all functionalities, and the framework may be used in the NHSX project in the future.
The codes of the framework can be founded from the link "https://github.com/aunroel/nhs_app/tree/android_branch/Android"


## 4. Work Experience

### 4.1 Research Intern

| Duration | Institution | Role |
| - | - | - | 
| 2020.11-2021.02 | China Academy of Industrial Internet | Research Intern | 

In CAII, I worked with Dr He on a project about commercial explosives. I mainly focused on the framework design for a platform that makes the government be able to monitor the manufacture, usage and distribution of explosives.
In the design, I imported the Hyperledge Fabric to make all data immutable and used the private data set to protect the business secret.
The CAII accepted the my system design.

## 5. Research Experience

### 5.1 Mining repositories to establish the test-to-code links

| Duration | Place | Role |
| - | - | - | 
| 2020.03-2020.06 | London | Researcher | 

In the project, I mined GitHub repositories of six open-source Java projects. The results demonstrated the tests maintenance approaches of the developers.
Based on these data, I optimised the classical CoEv strategy by the cocreation and coevolution relationship between the tests and functions codes.
After that, I evaluated its precision on the other three java repositories, and the final result showed that the optimisations improve the precision by thirty per-cent.

### 5.2 Analysing the DoS attacks to IoT system

| Duration | Place | Role |
| - | - | - | 
| 2017.07-2017.09 | Suzhou | Researcher | 

In the project, I worked with the teammates to test an IoT system's performance under three different DoS attacks.
I used pressure test tools such as Ping3 and Hunk to launch the DoS attacks and modified the sources codes of the LOIC to customise the frequency and size of the attack packages. The results were collected by a Python program and Wireshark automatically.
We released a paper, "A Denial of Services Attack for IoT system", on the Sciences and Wealth.
