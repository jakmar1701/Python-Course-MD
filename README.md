# Python-Tutorial
Python materials and tasks for my students

# Git

Our tutorial requires you to install [GIT](https://git-scm.com/downloads). Select **Git Bash** during installation and use this command line when using GIT. At first use there will be pop up to enter your GitHub login data.

After you install GIT, follow these steps:

1. **Clone** repository to your local machine using:

   ```
   $ git clone https://github.com/SaxMan96/Python-Tutorial.git
   ```
   
2. **Pull** the changes from upstream. Your master needs to be up to date.

   ```
   $ git pull
   ```

3. Create the **branch** on your local machine and switch in this branch (use name like john_smith):

   ```
   $ git checkout -b [name_of_your_new_branch]
   ```

4. **Push** the branch on github :

   ```
   $ git push origin [name_of_your_new_branch]
   ```

If you configured your git branch properly, you can start working on tasks.









```
git clone
Usage: git clone [url]  

This command is used to obtain a repository from an existing URL.
```

```
git add
Usage: git add [file]  

This command adds a file to the staging area.
```

```
git commit
Usage: git commit -m “[ Type in the commit message]”  

This command records or snapshots the file permanently in the version history.
```

```
git status
Usage: git status  

This command lists all the files that have to be committed.
```

```
git pull
Usage: git pull [Repository Link]  

This command fetches and merges changes on the remote server to your working directory.
```



# Tasks

## Animals

**Topics**: Classes, Inheritance, Functions

**Content**: Create parent class Animal, and child classes Dog and Cat.
Create methods get_sound(), get_name(), 