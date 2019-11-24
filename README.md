# Python-Tutorial
Python materials and tasks for my students

# About me:
Hi, I'm [Mateusz Dorobek](www.mateuszdorobek.pl). I'm student of Data Science at Warsaw University of Technology. I'm Python programmer, and I like to teach people, so why is this repository ;). I'm using Python in my everyday work as a tool for Machine Learning and Neural Networks. My biggest passion is Jazz Music, and I have created [Music Generator](https://github.com/SaxMan96/Music-Generator) using Python. Checkout other Python projects on my GitHub.

If you want to be my student contact me via my [LinkedIn](https://www.linkedin.com/in/mateuszdorobek/) profile or visit my profile on [E-korepetycje](e-korepetycje.net/mateuszdorobek)

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

- [**Lesson 1** - Introduction](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%202%20-%20Containers%20Part%20I%20-%20Lists%20%26%20Tuples.ipynb)
- [**Lesson 2** - Containers Part I - Lists & Tuples](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%202%20-%20Containers%20Part%20I%20-%20Lists%20%26%20Tuples.ipynb)
- [**Lesson 3** - Conditional Instructions & Operators](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%203%20-%20Conditional%20Instructions%20%26%20Operators.ipynb)
- [**Lesson 4** - Loops](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%204%20-%20Loops.ipynb)
- [**Lesson 5** - Containers Part II - Dictionary & Set](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%205%20-%20Containers%20Part%20II%20-%20Dictionary%20%26%20Set.ipynb)
- [**Lesson 6** - String Formatting](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%206%20-%20String%20Formatting.ipynb)
- [**Lesson 7** - Functions](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%207%20-%20Functions.ipynb)
- [**Lesson 8** - Lambdas](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%208%20-%20Lambdas.ipynb)
- [**Lesson 9** - Classes](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%209%20-%20Classes.ipynb)
- [**Lesson 10** - Inheritance](https://github.com/SaxMan96/Python-Tutorial/blob/master/lessons/Lesson%2010%20-%20Inheritance.ipynb)

# Sources

- [GIT](https://git-scm.com/downloads) - installation file
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) - installation file
- [W3Schools](www.w3schools.com/python) - some of examples
- [Tutorialspoint](www.tutorialspoint.com/python) - some of examples
- [Learnpython](www.learnpython.org) - some of examples
