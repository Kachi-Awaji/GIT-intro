# Lesson 4: Commiting your work 

In the last lesson, we created our first repository by initializing Git in our project folder.

In this lesson, we will explore Git some more, learning a few more commands along the way. We will start working on our project files, and learn how to save the changes to git. 

We will talk about the index (staging area), and end the lesson by making our first commit.

## Checking the status of your repository

After you intialize GIT in a repository, the GIT program starts watching your folder. Git can 'see' your folder.. think of him like an invisible partner working with you in the background.

Let's begin by finding out some information about the repository. In the command line, type `git status`

[git status screenshot]

The git status prints a message that will be very confusing at first, like reading Chinese. Let's go through it line-by-line. 

The first line of the message says 
` On branch master `

We will talk about branches in more detail in a future lesson. But for now, note that all git projects begin on a branch called master.

The next line says 
`no commits yet`

Saving changes to your project on Git is called 'commiting' the changes. This messages shows we haven't made any commits to our repository yet. When we do make our commit, this will be updated.

Next, there's a heading
`Untracked files: `
A short message follows it. That will be explained soon. For now, notice the three files in our project folder are shown in red.

When you intialize Git, you also have to tell Git what files to monitor in your project folder. Files that you ask Git to watch in your project folder are called __TRACKED FILES__.

We haven't begun tracking any files in our project. To begin tracking files in our project, we use the `git add` command.

[last line of screenshot.. highlight to track]

Imagine GIT has a list. On this list, he has the names of files in your project that you have asked him to 'track'. 

This list is empty when the repository is initialized. To add files to this list, you use the 'git add' command.

Alright, less talking. Let's do an example.

In our project folder, let's tell Git to track changes to our index.html and main.css files.

[git add 2 files screenshot]



Initializing Git causes Git to start monitoring your project folder. It doesn't begin watching the files in the folder immediately.

So, Git, after initialization, can see all the files in your folder. 