# Working with remote repositories - 2

Last lesson, you created an account on __GitHub__ and pushed a commit to your remote repository.  You are now a proud owner of a __GitHub__ account, giving you access to thousands of projects being built online. 

In this lesson, we will be taking a tour of __GitHub__, looking at the features that make it a social coding site. We will learn how collaboration works on __GitHub__, and at the end of this lesson, we will make our first contribution to a __GitHub__ project.

## Working with __GitHub__
> ### __IMPORTANT__
> The lesson notes for this series are hosted on my __GitHub__ profile on a repo (_Git-Intro_).  
For this lesson, I have created a file called ROLLCALL.md on this repository for you to make a contribution later on. 

Sign in to [__GitHub__](https://github.com)  . You should see a screen with a dark menu bar at the top. On the left, just beside the GitHub logo is a search field you can use to find other __GitHub__ users, repositories, commits, etc. 
> Tip: You can hit forward-slash(/) on your keyboard to access the search field.

Beside the search field are links to let you access pull requests, issues, and the marketplace. We will look at these later on. Clicking _Explore_ will let you view popular repositories on __GitHub__.

![__Git__ Status](./images/54-MenuBar.png)  

On the right side, there's a notification icon (it looks like a bell) where you can check notifications. You will get a notification if another user follows you, sends you a pull request, etc. 

To its right is a __+__ symbol that produces a drop-down menu when clicked. It lets you do stuff like create new repositories, gists and much more.  

Your profile picture is displayed by the __+__. Click it to access a menu that lets you configure profile and account settings.

You will get more familiar with the menu as your contributions on __GitHub__ grows. Below the top menu, the screen is broken into three sections. 

![__Git__ Status](./images/61-BelowMenu.png) 

A list of the repositories on your account is displayed on the left side. In the middle, you will see updates from other users or projects you might be following. It will also display what you do on __GitHub__. On the right side are links to other repositories you might be interested in... think 'repo suggestions'... 

## Finding other users
The Search field is how you find a host of things on __GitHub__. Enter "Kachi Awaji" to find me 😊 on __GitHub__. 

![__Git__ Status](./images/55-SearchResult.png)  

The search results are divided into various categories: repositories, code, commits, issues, marketplace, wikis, and users. You are looking for a user, so scroll down and click on _Users_ to show users that fit the search entry. This will show you two results.

![__Git__ Status](./images/56-PickUser.png)  

The first account is an account I created when learning __Git__. I don't use it much these days, but there are a few repositories on there you might find helpful.

The second is my main account. Click the __profile picture__ or __user name__ to view my [__profile__](https://github.com/Kachi-Awaji).

![__Git__ Status](./images/52-MyGitHub.png)

Links to popular repositories on my profile are shown on the right. 
You can also click the _Repositories_ tab on the right of my profile picture to view all repositories on my profile. 

You will be making a contribution to the __Git-Intro__ repository. Click on the repository to view the files it contains. 

![Repository Screenshot](./images/57-GitIntro.png)

At the top, the name of the user(Kachi-Awaji) and the repo name(Git-Intro) is shown to identify the repository. You can always take a quick look at this if you get lost when going through __GitHub__ repositories.

![Repository Screenshot](./images/58-GitIntroTop.png)
On the right are three buttons that let you interact with the repository:
- Click on _Watch_ if you want to be notified of changes to this repository. 
- If you really love a repository, click _Star_ to make it easy to find it again later. You can see all the repositories you have starred by going to your stars page. (find your star page by going to your profile and clicking on the _stars_ tab on the right).
- The _Fork_ button lets you make a copy of the repository on your profile. We will talk more on this soon.

Just below are six tabs : _Code_, _Issues_, _Pull request_, _Projects_, _Wiki_ and _Settings_. 

The _Code_ tab is open by default and displays the contents of the repository below. 

![Repository Screenshot](./images/59-RepositoryContent.png)

There's a brief description of the repository, and below it a few stats (number of commits on the repository, branches, releases, and contributors)

Below that are buttons that are two buttons. The one on the left lets you select a branch to work on. The other is for making pull requests. You will learn about these soon.

On the other side are three buttons that let you create a new file, upload a file to the repository, or find a file on the repository.  The green button at the end lets you clone or download the repository.

You _clone_ a repository when you want to make a copy of it to your system. The 'download as zip' option saves the project files in a zip folder for download. This might be helpful for those who do not have __Git__ installed on their system. 

We will talk about cloning in a later part of this lesson. 

Next, just before the list of files and folders and repos are displayed, details about the latest commits to the repository are displayed. You can tell from the profile picture displayed that I made the last commit on the repository, and the commit message is displayed beside my picture.

Our project files and folders are displayed below. The images folder contains all the screenshots used in this tutorial. The repo also contains the lesson files, a Readme.md file, and a Rollcall.md.

Files with .md extensions indicate that they are written in Markdown. Markdown is markup language for quickly formatting documents published on the web. 

There's a README file whose content is displayed automaticaly below your repository by __GitHub__. Use a README file to give users a bit of information about your repository. 

![Repository Screenshot](./images/60-ReadMe.png)

That's a lot we have learnt so far. To make contributions to repositories, you need to have a copy of the repository to work with. There are ways to do this.

## Getting a copy of a remote repository
You can get a copy of a repository in two ways  
1. Clone the repository.
2. Fork the repository.

To clone a repository, _git bash_ into any folder on your system. For this example, I am using the "Documents" folder on my system.

On the command line, type `git clone repolink`. Remember, you can get the repository link by going to the repository page. Click the _Clone/download_ button to reveal the link.

![Repository Screenshot](./images/62-CloneDownload.png)



<!-- #
The remote repository takes the most recent commit, and uses that to create the files on the server. 


When you created your new repository, you initialized it with a README file. README files are a great place to describe your project in more detail, or add some documentation such as how to install or use your project. The contents of your README file are automatically shown on the front page of your repository.

Let's commit a change to the README file.

In your repository's list of files, click README.md.

Readme file in file list
Above the file's content, click .

On the Edit file tab, type some information about yourself.

New content in file
Above the new content, click Preview changes.

File preview button
Review the changes you made to the file. You'll see the new content in green.

File preview view
At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message. For more information, see "Creating a commit with multiple co-authors."

Commit message for your change
Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is master, you should choose to create a new branch for your commit and then create a pull request.

Commit branch options
Click Propose file change.

Propose file change button
Celebrate
Congratulations! You have now created a repository, including a README file, and created your first commit on GitHub. What do you want to do next?

"Set up Git"
Create a repository
"Fork a repository"
"Be social"

 -->
