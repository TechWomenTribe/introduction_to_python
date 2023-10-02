# Introduction to Python - Please read! 🙂

Hello dear participant! Thank you for choosing to be a part of this amazing event! We are thrilled to have you on board. 
This page will provide you with detailed instructions on how to set up all the necessary pre-requisites for the workshop.

but first......

We understand that some of these concepts and tools may be new to you. That's perfectly okay! We will guide you through each step and explain everything gradually. It's important to know that you don't have to grasp everything immediately, and you are not expected to become a professional software developer after this workshop.
(However, it is important to mention, that we held a similar workshop last year, and as a result of the workshop, some participants were able to start pursuing a career in tech! so.. anything is possible really! 🚀)

This day is mostly meant to give you a glimpse at what it means to build tech products, and to show you it is not as scary as it may seem.
You don't need to understand every aspect in fine detail.
Sometimes, following the instructions without fully understanding them and progressing to the next step is perfectly fine. In fact, even experienced developers often solve problems in this way!

Please, don't be afraid to ask questions, thera are no bad questions. 

Remember to **believe in yourself** and approach this day with a mindset of getting the most out of it.

We strongly believe that we need more women in tech. Diversity (of any sort) brings more perspectives and ideas, and more perspectives and ideas mean better solutions, and better solutions means a better industry.

If you're having problems, in any of the steps, please do not hesitate to contact your assigned mentor, she or he will be delighted to help!
(btw, experienced developers, need to be independent as possible, and each of the following steps has plenty of information online, so you can also of course, try to Google the solution yourself,
but only if you're feeling adventurous 🙂)

Note before starting everything, make sure you have the admin rights on your computer :) We need to install certain tools & technologies throughout this tutorial. If you do not have the admin rights, unfortunately it is not possible to follow this course.

Now let's get this show on the road! 

### Install Git

First things first, we need to install `Git` to start working with code repositories. What is Git? Git is a distributed version control system that tracks the changes on the projects and helps to collaborate between members when working together with a team. For now, you can think of where we keep our codebase🙂

**If you have a Windows Laptop:**  
    Download and install the latest of git from: https://git-scm.com/download/win -> Press "Click here to download" link


**If you have an Apple laptop:**
1. Open your terminal by clicking the Launchpad in the Dock, type Terminal in the search field, then click Terminal.
2. Execute the command to install brew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
3. Now time to install git. Execute from your terminal `brew install git`
4. Great! You installed git on your computer :) Now time to create a Git account by following the instructions on this page: https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account
5. After you have a username and password for git, let's clone this repository to our local machine by executing the command below.
    `git clone https://github.com/TechWomenTribe/introduction_to_python.git`

### Install PyCharm Community version

**If you have a Windows Laptop:**
https://www.jetbrains.com/pycharm/download/?section=windows

**If you have an Apple laptop:**
https://www.jetbrains.com/pycharm/download/#section=mac

PyCharm is an IDE, what is an IDE you ask? good question.
An IDE is a software program that helps people write and edit code more easily. It has tools to catch mistakes, make coding faster, and helps with organizing and testing your code. Essentially, it's a helpful tool for people learning or working with coding.

### Install Python

What is Python you ask? good question.
Python is a popular programming language known for its simplicity and versatility. It is used for web development, data analysis, AI, and more, and is beginner-friendly with a clean and readable syntax.
(Of course Python is the writer's of this document favourite progmramming language, and we do expect it to be your favourite as well! Joking 😅)


First check whether your computer is running a 32-bit version or a 64-bit version of Windows, on the "System type" line of the System Info page. To reach this page, try one of these methods:

**If you have a Windows Laptop:**

Press the Windows key and Pause/Break key at the same time
Open your Control Panel from the Windows menu, then navigate to System & Security, then System
Press the Windows button, then navigate to Settings > System > About
Search the Windows Start menu for "System Information". To do that, click the Start button or press the Windows key, then begin to type System Information. It will start making suggestions as soon as you type. You can select the entry once it shows up.
You can download Python for Windows from the website https://www.python.org/downloads/windows/. Click on the "Latest Python 3 Release - Python x.x.x" link. If your computer is running a 64-bit version of Windows, download the Windows x86-64 executable installer. Otherwise, download the Windows x86 executable installer. After downloading the installer, you should run it (double-click on it) and follow the instructions there.

One thing to watch out for: During the installation, you will notice a window marked "Setup". Make sure you tick the "Add Python 3.8 to PATH" or 'Add Python to your environment variables" checkbox and click on "Install Now".

**If you have an Apple laptop:**

> Note Before you install Python on OS X, you should ensure your Mac settings allow installing packages that aren't from the App Store. Go to System Preferences (it's in the Applications folder), click "Security & Privacy," and then the "General" tab. If your "Allow apps downloaded from:" is set to "Mac App Store," change it to "Mac App Store and identified developers."

You need to go to the website https://www.python.org/downloads/mac-osx/ and download the latest Python installer:

* Download the Mac OS X 64-bit/32-bit installer file,
* Double click python-3.8.6-macosx10.9.pkg to run the installer.


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

**If you have a Windows laptop:**

Depending on your version of Windows and your keyboard, one of the following should open a command window (you may have to experiment a bit, but you don't have to try all of these suggestions):

* Go to the Start menu or screen, and enter "Command Prompt" in the search field.
* Go to Start menu → Windows System → Command Prompt.
* Go to Start menu → All Programs → Accessories → Command Prompt.
* Go to the Start screen, hover your mouse in the lower-left corner of the screen, and click the down arrow that appears (on a touch screen, instead flick up from the bottom of the screen). The Apps page should open. Click on Command Prompt in the Windows System section.
* Hold the special Windows key on your keyboard and press the "X" key. Choose "Command Prompt" from the pop-up menu.
* Hold the Windows key and press the "R" key to get a "Run" window. Type "cmd" in the box, and click the OK key.
ןכ
![image](https://github.com/TechGirlsTribe1/introduction_to_python/assets/6695760/17ba7471-8452-4a23-b96f-d1097655d811)

Try it now on your computer and see what happens!

**If you have an Apple laptop:**

- Open the Terminal application (It is already installed by default on an Apple laptop)

What is Terminal?
The Terminal application on a Mac is a command-line interface that allows users to interact with the operating system and execute commands using text-based input.

**Now, On Terminal if you have an Apple laptop, or on the Command Prompt if you have a Windows:**

- Type  `python3 --version`

With this command, we're checking if Python was installed, and if it was, then what is the version of Python which was installed - this is the best indication whether Python was installed properly.

Do you see the output?  
>Python 3.N.N

If you do not see any output, go ahead and try `python --version`, you should see the output above 🙂

- Type `python3 -m pip --version`

With this command, we're checking if PIP was installed, and if it was, then what is the version of PIP which was installed - this is the best indiciation whether PIP was installed properly.

Do you see the output?  
>pip x.x.x from ....

If you see the outputs above, then you have successfully installed Python! It is time to install Jupyter Notebooks!

### Install Jupyter Notebook

What is Jupyter Notebook? yet another good question,

Jupyter Notebook is a web-based tool where you can write and run code in a variety of languages (like Python, R, and Julia), visualize data, and create shareable documents. It's great for data cleaning, data visualization, prototyping, and sharing results.
We will use Jupyter Notebook in the first part of the workshop, to run and test basic Python commands.

Run this command which will use PIP to install the Jupyter Notebook:
- Type `pip install notebook`

More info can be found on: https://jupyter.org/install

# Test it

Let's test if the Jupyter Notebook was indeed installed.

**In order to start the Notebook, on Terminal if you have an Apple laptop, or on the Command Prompt if you have a Windows:**

- Type `jupyter notebook`
  
You should see the web page of the Notebook open in your browser, something like this:

<img width="1581" alt="image" src="https://github.com/TechGirlsTribe1/introduction_to_python/assets/6695760/5c94c58d-4183-4957-b0da-2fba037fc5f0">


In order to close this session, press `CTRL + C` from your terminal.  

That's it, you're all set and ready for the first part of the workshop! Good job! Now you can follow the instructions on `https://github.com/TechWomenTribe/my_weather_app/blob/main/README.md` to complete your preperation :)
