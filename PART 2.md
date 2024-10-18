# gitgud
 
List three major version control software for software engineering.
- github
- gitlab
- beanstalk

What are the main advantages to using Git in your software development, and how is it useful for game developers.
Some of the main advantages are much easier collaboration, collaboration over distances, various branches are possible giving more control in development and due to the reliability of git over hard drives there is a significantly smaller possibility progress will be lost. These all streamline and improve the development process for game developers.

Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merges
- branch - a branch is code deriving from a parent piece of code that retains the parent piece allowing editing of the parent code as well as further branches as to not interfere with the original code and allow concurrent development of code.
- pull - pull is to download a specific branch/version of a git repository.
- push - push is to upload a piece of code to a repository or update code held within an existing repository. you may also push new  branching code into a repository.

If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
The companys policys and procedures may focus on efficiency and collaboration all of which are improved by using a version control system similar to Git. The company may specifically focus on DevOps in which case version control systems are almost a neccesity.

Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
P4Merge, KDiff3, Araxis Merge, Tortoise SVN, Tortoise Git
running "git mergetool --tool-help" will also provide a list of inbuilt git merge tools

In a merged source code file, how does Git let you know there is a conflict?
git will provide markers surrounding the conflicting area like this
<<<<<<< HEAD
(old code)
=======
(conflicting code)
>>>>>>> name of commit

What are the steps you can take to resolve Git conflicts?
once you have located the problematic code using $ git status you can open the code and repair any conflicts then push the code again.

What does git revert do, and how can you use it?
git revert reverts a commit to the prior commit. this is useful if you have pushed a commit that you want reverted, especially if the changes are difficult to be undone manually.

What does git reset do, and how can you use it? 
git resets deletes all following commits after the chosen commit, bringing the commit to the chosen commit.

What is the difference between git revert and git reset?
git revert is used for undoing committed changes whilst git reset is used for undoing uncommitted changes

True or False: It is okay to commit broken code to the main branch.
broken code, whilst able to be worked around, should generally be committed to a working/development branch.

True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
false - disregarding strenuating circumstances, related and concurrent changes should be committed in one individual commit to avoid clutter and confusion.

Describe what is DevOps, how is it useful for game developers?
DevOps is philosophy, process and set of practices that are meant to help automate and support collaboration and development between software development and IT teams. DevOps was originally created out of concern regarding the disjointed collaboration of developers and operations supporting the code. DevOps allows for faster, higher quality and less issue prone development through increased collaboration, planning and communication. 

List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Docker - through utilizing packages of software required to run a specific program, docker allows you to better deploy and test applications quickly.
GitHub - through repositories GitHub allows you to share and alter applications for better collaboration.
Jira - Jira is a DevOps program that focuses on bug tracking, issue tracking and agile project management.

What is CI/CD and how can it be used to automate the game development process?
CI/CD is continuous integration and continuous delivery/deployment, this is a development process that allows for much easier and efficient development through use of communication and collaboration.