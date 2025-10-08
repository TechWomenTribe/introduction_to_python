# Introduction to Python - Please read! 🙂

Hello dear participant! Thank you for choosing to be a part of this amazing event! We are thrilled to have you on board.
This page will provide you with detailed instructions on how to set up all the necessary pre-requisites for the workshop.

But first...

We understand that some of these concepts and tools may be new to you. That's perfectly okay! We will guide you through each step and explain everything gradually. It's important to know that you don't have to grasp everything immediately, and you are not expected to become a professional software developer after this workshop.
(However, it is important to mention that we held a similar workshop last year, and as a result, some participants were able to start pursuing a career in tech! So... anything is possible really! 🚀)

This day is mostly meant to give you a glimpse at what it means to build tech products, and to show you it is not as scary as it may seem.
You don't need to understand every aspect in fine detail.
Sometimes, following the instructions without fully understanding them and progressing to the next step is perfectly fine. In fact, even experienced developers often solve problems in this way!

Please, don't be afraid to ask questions, there are no bad questions.

Remember to **believe in yourself** and approach this day with a mindset of getting the most out of it.

We strongly believe that we need more women in tech. Diversity (of any sort) brings more perspectives and ideas, and more perspectives and ideas mean better solutions, and better solutions mean a better industry.

If you're having problems in any of the steps, please do not hesitate to contact your assigned mentor—she or he will be delighted to help!
(By the way, experienced developers need to be as independent as possible, and each of the following steps has plenty of information online, so you can also, of course, try to Google the solution yourself, but only if you're feeling adventurous 🙂)

**Note:** Before starting, make sure you have admin rights on your computer :) We need to install certain tools & technologies throughout this tutorial. If you do not have admin rights, unfortunately it is not possible to follow this course.

Now let's get this show on the road!

---

## What Will You Learn?

- What Python is and why it’s awesome
- How to install Python and essential tools (Windows & Mac)
- Using Git and GitHub to manage your code
- Writing and running your first Python code
- Exploring Jupyter Notebook for interactive coding

---

## Prerequisites

**Before you start:**  
Make sure you have administrator rights on your computer. You will need these to install software.

---

## 1. Install Git

Git is a version control system that helps you manage and share your code.

### Windows

1. Download Git from: https://git-scm.com/download/win
2. Run the installer and follow the prompts (default options are fine).

### Mac

1. Open Terminal (find it in Launchpad or Applications > Utilities).
2. Install Homebrew (if you don't have it):
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
3. Install Git:
   ```sh
   brew install git
   ```

---

## 2. Create a GitHub Account

Sign up at: https://github.com/join

---

## 3. Clone the Workshop Repository

Open Terminal (Mac) or Command Prompt (Windows) and run:

```sh
git clone https://github.com/TechWomenTribe/introduction_to_python.git
```

---

## 4. Install PyCharm Community Edition

PyCharm is an IDE that makes coding easier.

- **Windows:** https://www.jetbrains.com/pycharm/download/?section=windows
- **Mac:** https://www.jetbrains.com/pycharm/download/?section=mac

Download and install the Community Edition.

---

## 5. Install Python

### Windows

1. Download Python from: https://www.python.org/downloads/windows/
2. Run the installer.
   **Important:** Check the box that says "Add Python to PATH" before clicking "Install Now".

### Mac

1. Download Python from: https://www.python.org/downloads/macos/
2. Open the downloaded `.pkg` file and follow the instructions.

---

## 6. Verify Python and pip Installation

Open Terminal (Mac) or Command Prompt (Windows) and run:

```sh
python --version
```
or
```sh
python3 --version
```

You should see something like `Python 3.x.x`.

Check pip (Python's package manager):

```sh
pip --version
```
or
```sh
python3 -m pip --version
```

---

## 7. Install Jupyter Notebook

Jupyter Notebook is a web-based tool where you can write and run code in a variety of languages (like Python, R, and Julia), visualize data, and create shareable documents. It's great for data cleaning, data visualization, prototyping, and sharing results.
We will use Jupyter Notebook in the first part of the workshop, to run and test basic Python commands.

Install it using pip:

```sh
pip install notebook
```
or
```sh
python3 -m pip install notebook
```

---

## 8. Test Jupyter Notebook

Start Jupyter Notebook:

```sh
jupyter notebook
```

A browser window should open. To stop Jupyter, go back to Terminal/Command Prompt and press `CTRL + C`.

---

You're all set! You're ready to start coding in Python. Good luck and have fun!
