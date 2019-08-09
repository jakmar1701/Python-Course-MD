# Python-Tutorial
Python materials and tasks for my students

# Environment

Installation of python environment is way easier when doing it with virtual environment manager such as MiniConda.  For proper installation follow these steps:

1. Install MiniConda from [here ](https://docs.conda.io/en/latest/miniconda.html) (choose version for Python 3.7)

2. After installation press "Win" button and type "Anaconda prompt". In Anaconda command line type:

   ```bash
   $ conda -V
   ```

3. Make  sure that you have the newest version of conda, otherwise, update conda using:

   ```bash
   $ conda update conda
   ```


# Git

Our tutorial requires you to install [GIT](https://git-scm.com/downloads). Select **Git Bash** during installation and use this command line when using GIT. At first use there will be pop up to enter your GitHub login data.

After you install GIT, follow these steps:

1. **Clone** repository to your local machine using:

   ```bash
   $ git clone https://github.com/SaxMan96/Python-Tutorial.git
   ```
   
2. **Pull** the changes from upstream. Your master needs to be up to date.

   ```bash
   $ git pull origin master
   ```

3. Create the **branch** on your local machine and switch in this branch (use name like john_smith):

   ```bash
   $ git checkout -b [name_of_your_new_branch]
   ```

4. **Push** the branch on Github:

   ```bash
   $ git push origin [name_of_your_new_branch]
   ```

    Please remember to work only on your branch, to check what branch you are currently on type:

    ```bash
   $ git branch -a
    ```



If you configured your git branch properly, you can start working on tasks. 

1. After you've changed some files you have to add it to your staging area using:
    ```bash
    $ git add [file]  
    ```
    
2. When you add all wanted files, you can save added file to your local repository with:
    ```bash
    $ git commit -m “[ Type in the commit message]”  
    ```
    
3. If you want to send changes to GitHub repository use ```$ git push``` as mentioned above.

4. If you want to start working with new task use ```$ git pull origin master``` command to make sure you have recent version of repository on your local machine.

# Integrated Development Environment - IDE

For our tutorial we will use **Jupyter Notebook** as our IDE, but there are a lot of alternatives such as Pycharm, Spyder, Visual Studio Code etc.

To open Jupyter Notebook file (such as *Introduction.ipynb*):

1. Open Anaconda Prompt, it should look like this:

   ```bash
   (base) C:\Users\John>
   ```

   (base) - means that you have active *base* environment.

2. Go to your file location e.g.:

   ```
   cd C:\Users\John\Desktop\Python-Tutorial
   ```

3. Then type:

   ```
   jupyter notebook
   ```

\* click help tab and learn shortcuts to work with Jupyter faster.

# Lessons

- **Lesson 1** - Introduction
- **Lesson 2** - Containers Part I - Lists & Tuples
- **Lesson 3** - Conditional Instructions & Operators
- **Lesson 4** - Loops
- **Lesson 5** - Containers Part II - Dictionary & Set
- **Lesson 5** - String Formatting
- **Lesson 7** - Functions
- **Lesson 8** - Lambdas
- **Lesson 9** - Classes
- **Lesson 10** - Inheritance

# Sources

- [GIT](https://git-scm.com/downloads) - installation file
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - installation file
- [W3Schools](www.w3schools.com/python) - some of examples
- [Tutorialspoint](www.tutorialspoint.com/python) - some of examples
- [Learnpython](www.learnpython.org) - some of examples