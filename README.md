# Introduction to Python

Welcome to **Introduction to Python**! Python is one of the most popular and powerful programming languages. It is used extensively in computational and data science, and you will use it in almost all modules during your MSc studies. This self-guided course will help you to learn the basics of Python.

This course consists of 5 compulsory lectures (1, 2, 3, 4, and 5) and one optional (lecture 6). We strongly recommend completing them in that order.

## How to run this course

There are three possibilities for how you can learn Python with this self-guided course. **JupyterHub** and **Binder** options allow you to run tutorials in the cloud - you do not need to install anything, and no files will be created on your machine. All you need is a web browser and internet connection. However, you ***must remember to download Jupyter notebooks** you worked in to ensure your work is not lost at the end of each session. The third option is to create a Python environment and run all tutorials on your machine. There is no difference in what you will learn, and we give you complete freedom to choose how you want to run the tutorials.

### 1. JupyterHub (ESE students)

1. **Create a GitHub account**. In the email you received, we sent you your unique username. Create a GitHub account and make sure your GitHub account uses that username.

2. **Login to JupyterHub**. By clicking the following badge, you can access our JupyterHub server and log in using the GitHub account you just created:

[![JupyterHub](https://img.shields.io/badge/JupyterHub-ese--msc-orange)](https://ese-jhub-pre-sess.westeurope.cloudapp.azure.com/pre-sess/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fese-msc%2Fintroduction-to-python&urlpath=lab%2Ftree%2Fintroduction-to-python%2F&branch=main)

After login, it may take some time for JupyterHub to start for the first time, so please be patient.

**IMPORTANT:** Please note that we do not guarantee your work is backed up. Therefore, we strongly recommend downloading the notebook at the end of each session.

### 2. Binder

You can access Binder by clicking on the *Binder badge*:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ese-msc/introduction-to-python/HEAD?labpath=index.ipynb)

**IMPORTANT:** Please note that after the Binder session ends, all your work is deleted. Therefore, please download the notebook you worked in at the end of each session.

### 3. On your machine

1. **Install Git**. Please follow installation instructions for your operating system on the [Git webpage](https://git-scm.com/).

2. **Clone the repository**. In Terminal (Linux and macOS) or Command Prompt (Windows), navigate to the location where you want the course files to be and run
```console
$ git clone https://github.com/ese-msc/introduction-to-python
$ cd introduction-to-python
```
3. **Set up a Python environment**. You can use either **conda** or **uv** - pick whichever you prefer.

   **Option A: conda**. If you do not already have it installed, download [Anaconda](https://www.anaconda.com/products/individual) Python 3 for your operating system and follow the instructions to install it. After the installation is complete, in Terminal (Linux and macOS) or Anaconda Prompt (Windows), navigate to the course directory, create a new conda environment, and activate it:
   ```console
   $ conda env create -f environment.yml
   $ conda activate introduction-to-python
   ```

   **Option B: uv**. [uv](https://docs.astral.sh/uv/) is a fast Python package and project manager. Follow the [installation instructions](https://docs.astral.sh/uv/getting-started/installation/) for your operating system, then, from the course directory, run:
   ```console
   $ uv sync
   ```
   This creates a virtual environment in `.venv` and installs all the dependencies needed for the course.

4. **Open Jupyter Notebook**.
   * If you used conda, make sure the `introduction-to-python` environment is activated, then run:
     ```console
     $ jupyter notebook &
     ```
   * If you used uv, run:
     ```console
     $ uv run jupyter notebook &
     ```

## Testing

After (almost) each exercise in the compulsory part of the course, there is a cell containing `assert` statements that validate your solution. If a cell runs without raising an error, your solution is correct; if it raises an `AssertionError`, revisit your solution and try again.

It is important to follow the instructions for each exercise exactly and not change the names of variables, functions, or classes, so that these tests can check your code correctly. Please also avoid changing the content of any testing cell.

## Support

**We encourage questions!** If you require support, have questions, want to report a bug, or want to suggest an improvement, please raise an issue in the [course repository](https://github.com/ese-msc/introduction-to-python).

> **Q:** I don't know where to ask my question. It might be related to something else, but I'm unsure. What should I do?  
> **A:** Open an issue in this repository. This is a safe, respectful space to ask questions and open issues.

> **Q:** I've never opened an issue. How do I do it?  
> **A:** Click the `Issues` tab next to the top of the page, then click the green `New Issue` button. Ask your question in the title and comment fields, then click  `Submit new issue`. Congratulations, you submitted your question! We will try to get back to you shortly.

> **Q:** How can I see if somebody else had the same or similar question?  
> **A:** When you click the `Issues` tab next to the top of the page, you can see all issues that are currently open and are being addressed. In addition to them, you can also check the issues that have been resolved in [closed issues](https://github.com/ese-msc/introduction-to-python/issues?q=is%3Aissue+is%3Aclosed).

Are you a community member that enjoys sharing your knowledge and helping others solve problems? We encourage you to respond to these issues.