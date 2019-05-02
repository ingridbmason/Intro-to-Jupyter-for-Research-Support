@title[Introduction]
### Intro to Jupyter Notebooks
<p style="color:gray">For Research Support Specialists</p>
<p style="font-size:0.6em; color:gray">C3DIS 2019</p> 


Note: 

A first look at notebooks, why they are useful and how to use them. Then some time working with a notebook.     

---
@title[Agenda]
### Agenda 
- What is a Jupyter notebook and how does it function. *30 mins*
- Where does a Jupyter notebook fit in different researcher toolkits. *45 mins*
- Why use Jupyter notebook on a desktop and why use it in the cloud. *30 mins*
- Basic Python programming using a Jupyter notebook. *30 mins*
- Wrap up. *10 mins*

Note:  

If we have time, we can have a go at using R too, with some basic commands.  

---
@title[Notebook Function]
### Notebook Function 

- Notebooks may or may not be useful for researchers! 
- Notebooks could accelerate research or just improve a few processes to make life less tedious. :)

Note:

- Objective: Understand what notebooks are capable of. 
- Activity: How could you see a notebook being useful to researchers?

---
@title[Notebook Description]
### Overview

<p style="font-size:0.6em; color:gray">Jupyter Notebooks offer a hybrid environment in which you can perform computational tasks while also using text to annotate or describe what you and your code blocks are doing. It is like a mix between working in a command line interface, writing arguments in a programming language, and working in a word processor application, writing up documentation.</p> 

---
@title[Notebook Overview]
### What can Jupyter Notebooks do?

<p style="font-size:0.6em; color:gray">“The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualisations and explanatory text. Uses include: data cleaning and transformation, numerical simulation, statistical modelling, machine learning and much more.”</p>

–description from [Project Jupyter](https://jupyter.org/)

---
@title[Data Cleaning]
#### Data cleaning

<p style="font-size:0.6em; color:gray">Data cleaning is about finding and correcting (or removing) inaccuracies from a dataset, a table, or a database. The process involves identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting them.</p>

Note:

In Jupyter Notebooks you can preview and analyse a limited number of columns and rows of data at a time, so you can see if there are blanks or repeated errors or inaccuracies. In addition, working directly with a large dataset without having to download it can save a lot of time.

---
@title[Data Transformation]
#### Data transformation

<p style="font-size:0.6em; color:gray">Data transformation is the process of converting data values from one source format or structure to another so they become consistent or intelligbible to a target structure or system. A typical scenario where information needs to be shared involves the extraction of the data from the source application or data custodian, the transformation of that data into another format, and finally loading the transformed data into the target location.</p>

---
@title[Numerical Simulation]
#### Numerical Simulation
Simulation can be used to trace waves e.g. seismic or shock waves.   

<a title="Nick Rogers [CC BY 3.0 (https://creativecommons.org/licenses/by/3.0)], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Inviscid_Burgers_Equation_in_Two_Dimensions.gif"><img width="256" alt="Inviscid Burgers Equation in Two Dimensions" src="https://upload.wikimedia.org/wikipedia/commons/0/02/Inviscid_Burgers_Equation_in_Two_Dimensions.gif"></a>

---
@title[Statistical Modelling]
#### Statistical Modelling
Linear regression: is a type of statistical model used to reveal a relationship between two variables.

<a title="Oleg Alexandrov [Public domain], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Linear_least_squares_example2.png"><img width="256" alt="Linear least squares example2" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Linear_least_squares_example2.png/256px-Linear_least_squares_example2.png"></a>

---
@title[Data Visualisation]
#### Data Visualisation
Network analysis: is a form of data visualisation of nodes of different sizes connected in a network.  

<a title="Martin Grandjean [CC BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0)], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Social_Network_Analysis_Visualization.png"><img width="512" alt="Social Network Analysis Visualization" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/Social_Network_Analysis_Visualization.png/512px-Social_Network_Analysis_Visualization.png"></a>

---
@title[Programming Languages]
### Programming Languages

Jupyter Notebooks can be used with a variety of different programming languages. Initially the notebookes were for *Julia*, *Python* and *R* but now they support many more languages. 

<p style="font-size:0.6em; color:gray">If you don't know the languages and packages researchers use, it might be helpful to think about the types of tasks they want to perform. Python is currently the most popular language used in Jupyter Notebooks as well as R, you can also consider what is commonly used in different fields of research.</p>

Note:

- Objective: Understand languages (and packages) that are suited to different research tasks. 
- Activity: In pairs, talk about which programming language might make the most sense for you and why. When you are ready, think about how you would recommend Python or R to someone else in your field. Share this with the group.

---
@title[Technical Overview]
## Technical Overview

You don't need anything special to run a notebook - just a browser will do!

<p style="font-size:0.6em; color:gray">Jupyter Notebooks don't need much to get going. They are editable and viewable in a web browser. You can also run them on a local machine with no internet or a remote machine with internet. They are very flexible and free!</p>

Note: 

- Objective: Understand how notebooks run and how they are different to the command line
- Activity: Look at an example on GitHub

---
@title[Technical Breakdown]
### Technical Breakdown

- Used to capture documentation and executable code 
- An editable document with input and output “cells” (text strings) 
- Document files e.g. *yourfilename.ipynb*

Note:   

Human-readable documents containing: analysis description and the results (figures, tables, etc..) and executable documents which can be run to perform data analysis. 

---
@title[Notebook Operation]
### Notebook Operation

- Editable and viewable in a web browser
- Can run on local machine with no internet
- Can run on remote machine with internet

---
@title[Notebook Kernels]
### Notebook Kernels

<p style="font-size:0.6em; color:gray">Jupyter Notebooks use a “kernel”, which is kind of like an interpreter. This is what turns a programming language into instructions the computer understands so it can do the work.</p> 
<p style="font-size:0.6em; color:gray">In regular computers a kernel connects the application software to the computer hardware. In the case of Jupyter Notebooks, this application permits displaying, editing and running program commands via a web browser.</p>
<p style="font-size:0.6em; color:gray">Notebooks use blocks of code to perform computational processes resulting in outputs, or results.</p>

Note: 

Different kernels can be installed for different types and versions of programming languages. The kernel in the notebook is a program that runs code written in a specific programming language.

---
@title[Code and Markdown]
#### Code and Markdown

<p style="font-size:0.6em; color:gray">**Code**: "Running code" means making the computer do what you are telling it to do. "Executing code" is the same thing.</p>
<p style="font-size:0.6em; color:gray">**Output**: In Jupyter Notebooks "output" is the result of the computational process, such as a visualisation, graph, model, equation and so on.</p>
<p style="font-size:0.6em; color:gray">**Markdown**: "Markdown" is formatted text you want to include such as headings, italics, quotes and other types of styling. It might be a description, a note, a question (as context).</p> 
<p style="font-size:0.6em; color:gray">**Cells**: Jupyter notebooks are a series of “cells” containing *executable code*, *outputs*, or *markdown*.</p> 

<p style="font-size:0.4em; color:gray">Cells might contain code executed (through the kernel) or markdown formatted text (including [LaTeX](https://www.latex-project.org/)) to embed the description of the work process next to the code.</p>

---
@title[Command Line]
#### Compared to Command Line

<p style="font-size:0.6em; color:gray">Command line does not include notes. In Jupyter Notebooks you can also go back and delete or change code or text as you go, which you cannot do using the command line.</p> 
<p style="font-size:0.6em; color:gray">Notebooks present markdown and visualisations inline - meaning you can see the both at the same time and the parts that aren't code do not interfere with the code. It results in a highly flexibly but user-friendly environment that can perform complicated tasks very quickly.</p>



---
@title[JSON]
<p style="font-size:0.4em; color:gray">Jupyter Notebooks are saved as a JSON (JavaScript Object Notation) file with an **.ipynb** extension.</p> 
<img src="images/notebook_json.png" width="500">

---
@title[Summary]
#### Summary

A notebook:
- Runs on your desktop with no internet or on a remote server via the internet 
- Requires a kernel (computational engine) to execute code e.g. Python or R
- Runs and stores the code and output, with markdown notes
- Is an editable document with input and output cells 

---
@title[Hands On]
## Hands On

- Look at an example of a Jupyter Notebook [in GitHub](https://github.com/ingridbmason/Intro-to-Jupyter/blob/master/AARNet_Intro_Jupyter.ipynb)
- Identify the cells, what is input and what is output, and what is markdown. Discuss the types of output. 
- Examine the code. Different colours are used. Have you seen that before? Why do you think different colours are used?

Note: 

If you have seen or used the command line before, can you think of any reasons why Notebooks might be easier to use? Discuss your ideas and experiences with the group. If you haven't used the command line before, have a think about why notebooks could be less daunting for beginners.

---


