---
## Lesson 

"Getting started with R"
- Teaching: 15 mins
- Exercises: 1
- Question: How do you open a notebook and what do you do when you get there?
- Objectives: Open a notebook then use markdown and R to perform basic tasks
- Activity: With a group, work on a calculation and have a go at changing some of the code to produce different results.
- Keypoints: Get started, be fearless!

---
## Getting started

Follow these step-by-step instructions to get started with Jupyter Notebooks using Python:

1. Open CloudStor: https://cloudstor.aarnet.edu.au/
2. Select the SWAN service (Jupyter notebooks are integrated) and "spawn" a notebook.     


![SWAN](https://github.com/ingridbmason/Intro-to-Jupyter-for-Research-Support/blob/master/images/swan_logo.png) 

3. Open workshop list of commands in separate window: https://github.com/ingridbmason/Intro-to-Jupyter/blob/master/Worksheet_R.txt
4. Open a new notebook from the top righthand dropdown menu: Click on 'New' and then select R. 

![New](https://github.com/ingridbmason/Intro-to-Jupyter-for-Research-Support/blob/master/images/new_notebook.png)


5. Select 'File' at the top left hand side of the screen and select 'Save As'. Name your notebook 'Intro to Jupyter Notebooks'.

## Let's go for dip with R

Using the workshop list of commands - saved in the repository as **Worksheet_R.txt** we can now start with some basic markdown. Remember that [markdown](https://en.wikipedia.org/wiki/Markdown) is how you can make rich (or formatted) text in a plain text editor.

- First let's splash around in markdown!
  - Markdown is for writing down comments outside of the code cells, so you can describe what you are doing as you go.
  - In computer programming a 'string' is sequence of alphanumerical characters
  - Type 
  
  **# this is a string** 
  
     into the cell, making sure you select 'Markdown' from the dropdown menu above where it shows 'Code' as the default. Already here you can see how notebooks are flexible, as you can choose what kind of cell you are writing in (and toggle it at any time!)
  
  ![markdown](https://user-images.githubusercontent.com/48195568/56338527-89484580-61e9-11e9-965c-3726d8fd7fbb.png)

  - Click on 'Run' or use the shortcut **Shift+Enter** to execute the cell. 
  - You have just created a heading in your notebook! Hooray!
 
  ![STRING](https://user-images.githubusercontent.com/48195568/56339085-dcbb9300-61eb-11e9-88c9-60034e797b68.JPG)
 
  - Now let's try italics. In a new cell type 
  
  **\_this is a string\_**
  
  and select 'Markdown' from the dropdown menu again.
  
  - Click on 'Run' or use the  shortcut **Shift+Enter** to execute the cell.
  - Voila! _Italics!_
   
  ![italics](https://user-images.githubusercontent.com/48195568/56340380-ea274c00-61f0-11e9-8580-f471417719d9.JPG)

If you want to know more about markdown, take a look at these pages: 

- https://guides.github.com/features/mastering-markdown/
- http://www.gastonsanchez.com/r4strings/formatting.html


### Mini-activity

Following the same steps as above but selecting 'Code' from the dropdown menu for the next fields, try typing this: 

  **print ("this is a string")**
    
Now let's try to print out a calculation using 'x':

  **x<- "this is a string"**
  **print (x)**

Let's see what happens when we add this:

  **print(x, quote = false)**
  
What happens? What is going on here? Speak in small groups about these instructions, markdown and what you've just learned. It can feel a little strange, as you already know how to do formatting in programs like Word. However, what we are doing here is 'speaking' directly to the computer, with a different kind of interface so you can also perform calcuations, visualisations and use computational methods.


![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
