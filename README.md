# Guide to Using GitHub

Welcome to the Learning Analytics and Conversational Agent Collaborative Task! In this guide, you will learn how to effectively use GitHub, particularly focusing on installing Git and cloning repositories. GitHub is a platform for version control and collaboration that allows you to efficiently manage projects and work together with others. Let's start with the basics.

## Installing Git

Before you can start using GitHub, you need to install Git on your computer. Git is the version control system that powers GitHub.

1. **Download Git**: Go to the [official Git website](https://git-scm.com) and download the latest version for your operating system.
2. **Install Git**: Follow the installation instructions on the website. Make sure to choose the default options during the installation to ensure a smooth setup.
3. **Configure Git**: After installation, you need to configure Git with your name and email address. This information will be used in your commits. Open your command line interface (CLI) and run the following commands:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

For a detailed installation guide, you can refer to the [Git installation tutorial](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## Cloning a Repository

Once Git is installed, the next step is to clone a repository. Cloning allows you to get a local copy of a remote repository on GitHub onto your computer.

1. **Find the Repository URL**: Go to the GitHub page of the repository you want to clone. Click on the "Code" button and copy the URL under "Clone with HTTPS".
2. **Clone the Repository**: Open your command line interface and run the following command:
   ```bash
   git clone [URL of the repository]
   ```
   Replace `[URL of the repository]` with the actual URL you copied.

3. **Navigate to the Repository**: After cloning, a new directory will be created with the same name as the repository. Use the `cd` command to change your current directory to this new directory:
   ```bash
   cd [repository-name]
   ```

## Helpful Resources

- **Git and GitHub for Beginners**: For a step-by-step video tutorial on how to install Git and clone a repository, check out this [beginner’s tutorial on YouTube](https://www.youtube.com/watch?v=SWYqp7iY_Tc). It’s great for visual learners and covers the basics in an easily understandable format.

- **GitHub Documentation**: For more in-depth information, the [GitHub Docs](https://docs.github.com/en) provide detailed guides on various aspects of using GitHub, from beginner to advanced levels.

This introduction has covered the essential steps to get started with GitHub, focusing on installing Git and cloning repositories. There are many more features and tools within GitHub to explore, such as branches, pull requests, and GitHub Actions for CI/CD. Good luck with your project, and enjoy your journey into the world of GitHub!



To ensure you are well-equipped to tackle the tasks at hand, we recommend installing Jupyter Notebook. This powerful tool will allow you to work on assignments directly within an interactive environment, which is particularly useful for Python programming and data analysis tasks.

## [Installing Jupyter Notebook](https://www.youtube.com/watch?v=HLD-Ll_-IT4)

Follow these steps to install Jupyter Notebook and set up your environment:

1. **Install Python**: Jupyter requires Python to be installed on your system. If you don't have Python installed, download and install it from the [official Python website](https://www.python.org/downloads/). Ensure you add Python to your system's PATH.

2. **Install Jupyter via PIP**: Open your command line interface (CLI) and install Jupyter using Python’s package manager PIP:
   ```bash
   pip install notebook
   ```

3. **Launch Jupyter Notebook**: Once installed, you can start Jupyter Notebook by running the following command in your CLI:
   ```bash
   jupyter notebook
   ```
   This command will open Jupyter in your default web browser.

## Accessing the Git Repository Folder

To work on your project files, you need to navigate to the folder containing the cloned Git repository.

1. **Navigate to Your Repository**: Use the `cd` command to change directories to your repository where the Jupyter notebook file is located. For example:
   ```bash
   cd path/to/your/repository
   ```

2. **Open the Jupyter Notebook File**: Within the repository, locate the file named `oer.ipynb`. You can open this file directly from the Jupyter Notebook interface in your browser. It should be listed in the directory structure displayed by Jupyter.

3. **Ready to Edit**: With the `oer.ipynb` file open in Jupyter Notebook, you are now ready to begin editing and executing the code as per the task requirements. Jupyter Notebooks make it easy to edit and run Python code in chunks (cells), which can be executed independently.

By following these instructions, you will have a functional setup to efficiently work through the tasks using GitHub and Jupyter Notebook. This setup not only helps in managing and sharing your work but also in documenting your progress interactively.
