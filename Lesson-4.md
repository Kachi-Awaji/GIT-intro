# Part 5: Commiting your work 

Last lesson, we created our first repository by initializing __Git__ in our project folder.

In this lesson, we will explore __Git__ some more, learning a few new commands along the way. We will start working on our project files, and learn how to save (or commit) our changes in __Git__. 

We will talk about the index (staging area), and end the lesson by making our first commit.


## Checking the status of your repository

The `git init` command creates a repository in your working directory (project folder).  

![__Git__ Status](./images/25-WorkingDirectory.png) 

`git init` creates a hidden folder - a __Git__ repository. This is __Git__'s home in your working folder. From here, it will monitor the files in the directory, and store information about changes they go through as the project progresses. 

Let's begin by getting some information about our repository. In the command line, type `git status`. You should get an output similar to the one below.

![__Git__ Status](./images/26-GitStatus.png)  

The `git status` command prints a message that will be very confusing at first; it will feel like reading Chinese. Let's go through the important lines.

 1. ` On branch master `

We will talk about branches in more detail in a future lesson.  All git projects begin on a branch called master.

 2. `no commits yet`

Saving changes to your project on __Git__ is called 'commiting' the changes. This messages shows we haven't made any commits to our repository yet. When we do make our commit, this will be updated.
 
 3. `Untracked files: `  
   
Notice the three files highlighted in red? Recognize them?

When you intialize __Git__, you also have to tell __Git__ what files to monitor in your project folder. Files that you ask __Git__ to watch in your project folder are called __TRACKED FILES__.

We haven't begun tracking any files in our project. To begin tracking files in our project, we use the `git add` command.

![__Git__ Status](./images/29-GitStatusHighlight.png)

Let's talk about this command a bit more... it is one of the most important Git commands to learn.

Imagine __Git__ has a list. On this list, it has the names of files in your project that you have asked it to 'track'. 

This list is empty when the repository is initialized. You will use the 'git add' command to include files on this list.

Alright, less talking. Let's do an example.

In our project folder, let's tell __Git__ to track changes to our index.html and main.css files.

![__Git__ Status](./images/27-GitAddCommand.png)

Check the status again.  

![__Git__ Status](./images/28-StatusAfterAdd.png)  

Notice the status has been updated.
 - No commits on the repository yet.
 - There are two lines of green text below the "Changes to be committed" heading. These are the files we have 'staged' to be committed. The 'new file:' in front of the filenames indicates this is the first time we will be adding the files to the repository.
- The 'git.png' file is not being tracked. It won't be added to our commit.  

We are now ready to make our first commit.

# __Git__ Commit
A commit is like a savepoint in your project. You are essentially saying "My files are this way now. They may go through some changes in the future. I want to be able to return to the way they are now."

To commit the files you staged (using the `git add` command is sometimes known as _staging changes_), type  

`git commit -m "Commit title"`  

Let's go through our new command.

The 'git commit' command saves our changes to the local repository - 'local repository' here meaning the hidden git folder on in your project.

Working with __Git__ is following three steps (mostly)  
1. Make changes to the files in the working directory.

2. Add the files to the index(stage changes you want to commit)  

3. Commit.  

This is the basic __Git__ workflow. Each git commit you make is a different version of the project... and __Git__ stores these versions so you can go back to them, if you need to. That's the beauty of version control with __Git__.

Every __Git__ commit should have a message attached, that describes what the commit is about -- a short description of the changes you have made. This is important, as you would be working on the project with other programmers. The descriptions you enter will give them a clear picture of your contributions.

Using only the 'git command' would open your text editor. This will let you type in your description before the commit is complete. This can be confusing sometimes. The -m option is an easier command to learn.

Using the `-m` option lets us type in our description at the end of the command. One thing is important though - the description must be in quotation marks ("").

Alright, let's make our first commit.

`git commit -m "My first commit"`  

![__Git__ Status](./images/30-FirstCommit.png)  

Congratulations. So far, so good. You've learnt how to use __Git__ as version control for your project, and you made your first commit.

In our next lesson, we will be learning about remote repositories. We will talk about Github, the online code-hosting site that runs on __Git__. See you soon.