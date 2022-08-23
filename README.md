
# Git and Github - Lab

## Introduction

So far we've seen how Git can be an incredibly useful tool for keeping track of changes, allowing you to test features or branches, and then go back to earlier versions if you'd like. But that is only one use for Git, it can also be a very helpful tool when collaborating with other data scientists. Hopefully by now you have been set up with **Github** which is a website that hosts Git repos in the clould. This lab will have you practicing creating repos in Github, cloning repos from Github, pushing changes to Github, and finally, how to deal with Git conflicts that might arise not just from your own coding, but from the collaboration process itself. Additionally, we'll test the functionality of .gitignore. All of these skill will be important as you move through the projects here at Flatiron.  
                                       

## Objectives

You will be able to:

- Create a repo through the Github interface
- Use .gitignore to prevent a file from being uploaded to the cloud
- Push specific branches to Github
- Create new Jupyter Notebooks with which to work in
- Invite collaborators to your Github repo
- Identify and fix merge conflicts when merging branches on the Github platform

## Creating a Repo

First, we'll want to practice creating a new repo in Github. You can also do this from your terminal, but doing it from the Github site lets you set some handy defaults as we go.  

From the homepage, you should see in the upper left a green button that says "New"

(Alterntively, in the upper right you can click the plus sign that will show you a drop down with several options, including 'New Repository')

<new repo image>

From there, you'll see this screen:

<new repo menu image>

There are many options here. We'll go through them in order.

 1. For now, ignore the template option. Some organizations might create ready made templates for you to use, but we're just working with the basic repo.
 
 2. If you see an option to select an owner, go ahead and select yourself. Again, if your Github profile is linked to a larger organization (like, say, if you were an instructor at Flatiron School) you might have the option to set that organization as the owner of the repo. But we'll keep this one personal.
 
 3. Now we can name the repo. Choose something descriptive, but unique. Also, in general, we want to avoid putting spaces in titles for files and folders. I went with dsc-github-practice-repo here, just as an example. You can also add a description if you'd like. I put "This repo is for practicing git commands and using cloud repos," but you can put in anything you'd like. 
 
 4. Since we want to practice collaborating, let's set this repo to public. This means that anyone with the link could theoretically take a peek at the repo. Keep this in mind, we don't want to upload any personal or sensitive information to this repo. 
 
 5. Next, check the box to add a README. Github is offering to create a README file for us, since every good repo should have a README. It'll be a blank document at first, but ticking this box saves us the step of creating that README manually.
 
 6. Finally, we're given the option to choose a .gitignore template. If we don't select anything here, we'll have to create the .gitignore manually. Since we mostly use Python in our bootcamp, let's select the Python .gitignore, which will automatically populate the file with many useful defaults. We can always edit the .gitignore later to suit our needs. 
 
 7. Ignore the license for now.

All of these options can be adjusted later, but this sets us up well for a good collaborative repo.

Once you're all set **go ahead and create the repo.** It should look like this:

<repo created image>

If you've been following these steps, the README file and the .gitignore will have been already added to the repo. 

## Clone to local

Now that you've got your very own repo in Github, we need to get this down to our local computer to work on it. You can copy and paste the url at the top or click the green "Code" button to get the url. Then, we'll want to open up our terminal, and navigate to an appropriate folder. Hopefully you have a folder for your Flatiron materials already created, and you've probably cloned at least a few labs into it already. This might be the first time you clone your own repo into your computer though! Very exciting. Make sure you're not cloning this repo into another repo though! That can sometimes cause conflicts later down the line.

Once you've navigated to the right folder, we'll use the command 

> git clone <your-url-here>

This should create a folder in your local machine that is a copy of the repo in the cloud. 

## Creating a main notebook

Now that we've cloned down this repo, let's cd into it, and hit ls to look around. You should see the README file, and nothing else. The .gitignore is hidden by default. See the .gitignore module for more on how to intract with it, but for now let's just... ignore it. 

We want to create a jupyter notebook in here as if we were about to start a project! Go ahead and type 

> jupyter notebook

into your terminal. This will open up a new tab with a local host of your folder. In the upper right, you'll see a drop down under "New". Click that, and select the Python (learn-env) option. You'll be taken to a blank, unnamed notebook.

### Further exploration 
 

## Additional Resources


## Summary
