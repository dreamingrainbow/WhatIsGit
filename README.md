# WhatIsGit
A little help on git! A short walk through on what git is and how to use it!

### What is Git / Version Control and Why do I need this as a developer ?

Hello, everyone, I am Michael, AKA DreamingRainbow, today I'd like to talk about version control. Now a day's every developer should know about version control.
As a developer and even someone who writes regularly, you have probably writen something, later changed a paragraph or function, just to come back to want the 
original version. In steps  ->> Git, Mercurial, SVN. Version Control systems that allow you to keep track of your changes, but wait they are like super hero's
with special powers! These wonderful tools allow you to work hand in hand with other, not only that it's almost like magic more than one person can work on the 
same thing at the same time and end up with a working version in the end. The power of Merge! We will get into that later. Let's for now dive into the power's of
version control.

Enter the Super Hero GIT from the wonderful World of Version Control!
By now you have heard of GIT, or git or github even. All about the git you could say.  Although there are many version control systems to choose from we will focus
our discussion on the version control system (super hero) "GIT". Some others to try are Bitbucket.org/Mercurial and SVN. Check those out after this! 

Now, by now you should now why you would want to use a version control system so we will talk about GIT, as it is one of the most popular at the time of this writing.
Enters our super hero GIT --> I have powers!!

Let's talk about these "powers" (functions/commands)!

Where do we start? The chicken or the egg? Well, guess that depends on what your hungry for, I say cook um both I'm hungry! So, lets start with what cooks the fastest egg!

Egg? Fork me!! What? git fork? uhh, your loosing me.. Ok so really lets start with the Fork! We need a fork to eat with? lol, No we need a to Fork the repo! Why ? What is fork
the repo?

## Fork!
Forking the repo(repo=repository) is the process of making a copy of the original repo in to a new repo under a new owner/repo. In other words your making a copy 
so you can do what you want with it? Yup, git fork is the power to copy someone else's work. This allows you to make all the changes you want to your new copy.

So what if I dont want to copy someone else work, and want to be original? Great question, and exactly why I made the chicken or the egg reference, but in the world of
Version Control there are even more than the Chicken or Eggs you also have another choice. Let's talk about these other two now. Let's start with creating a new repository
for you fresh or existing code. Enters the power of Init!

## Init!
git init get a diretory ready to begin storing versions of the files with in it. Have some code not in a repo? You will need to init the repo to start the process. This
just lets the world of Version Control know you are down to play! Poof your done! No not really. Now is time to build your project, and discover other super powers! 

Of course we all can't be original, and sometime recreating the wheel just does't make since. So, we make a clone! What its the clone wars? Hahaha No! Not yet atleast!

## Clone!
You have discovered yet another super power of the super hero git! Git clone allows you to download a copy of an existing repo to a local source. You can have your very own copy of the
current code right on your desktop like magic even! Hahaha! SO! Clone it! Once you have you are now ready to begin your changes to the code base!

Wow we already have three super powers can we take much more power than that? I say give me more!! So, git responds with even more powers! Once we have a repo to work with and bring it to 
our local source we can start working with the code base. Make our awesome changes, and the extra salt and pepper to the steak ya know! Great so all that just to make our changes??
Well, we have more powers though! Let's dive into them next!

## Status!
We first use another super power status. "git status" lets us see what has changed compared to the repo source. Before anyone else can see changes we have to add them but we should know what
has changed. git status will let us see the file's changed and we can then add those changes to our local git repo.

## Add!
After making our awesome changes, we added a few files, and some images, we need to save our changes. So we use the power of add! What we gotta do math now? Nooo. Just time to user the power
of git add! Ok git add --> Ooops Not so quick! we got to tell git what to add! Yes you could just "git add ." but let's not! Who know's who's been in this directory adding files to it. We use 
the power of status to tell us what has changed and add those files to the repository with "git add filepath/filename". Add just creates a record of the changes. Now at this point you have your files
staged to be commited. What we are sending our code to the asylum? HAHAHA! No! We make the record of our changes but we haven't stored that record yet. Time to commit it!

## Commit!
At this point your local copy has recorded the additions to the repository but it needs more! You will have to commit it to memory! Enters yet another power commit! This is the time you can remind yourself
what you did in the changes you are commiting. With the simple command git commit -m "Your message here" you tell git to remember this set of changes. Of course change "Your message here" to discribe your changes.

Great we now have our very own copy of our changes, but wait what about the source, where are my changes they are not there! Nope, we have only stored our changes localally. We have to tell
the git source of our changes. Does that mean we have more powers? Yup! just a few more! What a few more?? Yea, but you will get a hang of them quick! So, you want to know what they are huh?

## Push!
Wait, stop! Don't push! Oh wait that's the power you are suposed to be using. Let us not push each other let us push our changes!!! So we user the power of git push to push or changes back to the git source. 
Once we have them there others can see and interact with them.

What else can git do? 
So, we talked about a few of the git commands(super powers) but there are a few more to consider. Lets take for example branch! Sometimes we will be working on a project have an idea and want to test it out. 
We create a branch which allows us to create a seperate version of the code base at the time of branch but later allows us to bring them all together later. Which brings me to pull and merge!

## Pull and Merge!
While working on your project someone else finishes a potion of the project and tells you to pull his changes, but his changes where made to the file you have just finished commiting. Oh no what to do!
No worries we have more supper powers to use! First, we will git pull the remote changes, and then we will need to git merge the changes into our local copy. This process can get overwhelming, and there are many tools to help you with merging.
I will not be discussing that in this help document! Once you have merged all the changes you will need to add, commit, push the final changes back to the remote source that you cloned originally!

Sweet, we did it! We now have mastered our super hero git and all of the super powers that are lent to us via our Version Control System! I hope this help's you out on your journey to version control. 
Best wished and Good Luck!
