# Introduction to Python - Please read!

Hello dear participant! Thank you for choosing to be a part of this amazing event! We are thrilled to have you on board. 
This page will provide you with detailed instructions on how to set up all the necessary pre-requisites for the workshop.

but first......

We understand that some of these concepts and tools may be new to you. That's perfectly okay! We will guide you through each step and explain everything gradually. It's important to know that you don't have to grasp everything immediately, and you are not expected to become a professional software developer after this workshop.
(However, it is important to mention, that we held a similar workshop last year, and as a result of the workshop, some participants were able to start pursuing a career in tech! so.. eveverything is possible!)

This day is just meant to give you a glimpse at what it means to build tech products, and to show you it is not as scary as it may seem.
You don't need to understand every aspect in fine detail.
Sometimes, following the instructions without fully understanding them and progressing to the next step is perfectly fine. In fact, even experienced developers often solve problems in this way!

Please, don't be afraid to ask questions, thera are no bad questions. 

Remember to *believe in yourself* and approach this day with a mindset of getting the most out of it.

We strongly believe that we need more women in tech. Diversity (of any sort) brings more perspectives and ideas, and more perspectives and ideas mean better solutions, and better solutions means a better industry.

If you're having problems, in any of the steps, please do not hesitate to contact your assigned mentor, she or he will be delighted to help!
(btw, experienced developers, need to be independent as possible, and each of the following steps has plenty of information online, so you can also of course, try to Google the solution yourself,
but only if you're feeling adventurous 🙂)

Now let's get this show on the road! 

### Install PyCharm Community version
https://www.jetbrains.com/pycharm/download/#section=mac

PyCharm is an IDE, what is an IDE you ask? good question.
An IDE is a software program that helps people write and edit code more easily. It has tools to catch mistakes, make coding faster, and helps with organizing and testing your code. Essentially, it's a helpful tool for people learning or working with coding.

### Install Python
https://www.python.org/downloads/

What is Python you ask? good question.
Python is a popular programming language known for its simplicity and versatility. It is used for web development, data analysis, AI, and more, and is beginner-friendly with a clean and readable syntax.
(Of course Python is the writer's of this document favourite progmramming language, and I do expect it to be your favourite as well! Joking 😅)


#### What is pip?
Python installation will also install PIP.
What is PIP you ask? good question.
PIP is the standard package manager for Python. It helps users easily install, manage, and uninstall Python libraries and packages from the Python Package Index (PyPI).

What is a Python package you ask? even better question
A Python package is a way to organize and distribute Python code. It is a collection of code files, that someone already written for us, that can be easily imported and used in other Python programs.
Basically meant to not re-invent the wheel everytime we create a new Python program.

https://pip.pypa.io/en/stable/installation/


# Test your Python installation
After you installed Python, and all the needed software to execute Python code on your laptop, let's see if it works!

If you have an Apple Mac Laptop:

Can you run the commands below without errors?
- Open Terminal

What is Terminal?
The Terminal application on a Mac is a command-line interface that allows users to interact with the operating system and execute commands using text-based input.

- Execute ``python3 --version``

With this command, we're checking if Python was installed, and if it was, then what is the version of Python which was installed - this is the best indiciation whether Python was installed properly.

Do you see the output?  
>Python 3.N.N
- Execute `python3 -m pip --version`

With this command, we're checking if PIP was installed, and if it was, then what is the version of PIP which was installed - this is the best indiciation whether PIP was installed properly.

Do you see the output?  
>pip x.x.x from ....

If you see the outputs above, then you have successfully installed Python! It is time to install Jupyter Notebooks!

### Install Jupyter Notebook

What is Jupyter Notebook? yet another good question,

Jupyter Notebook is a web-based tool where you can write and run code in a variety of languages (like Python, R, and Julia), visualize data, and create shareable documents. It's great for data cleaning, data visualization, prototyping, and sharing results.
We will use Jupyter Notebook in the first part of the workshop, to run and test basic Python commands.

https://jupyter.org/install

Again, on Terminal, please run,
This command will use PIP, to install the Jupyter Notebook.

>pip install notebook


# Test it

Let's test if the Jupyter Notebook was indeed installed.

Start the notebook server from the Terminal app:
`jupyter notebook`
You should see the web page of the Notebook open in your browser.


That's it, you're all set and ready for the workshop! good job!


