gitexquis
=========

Exquisite corpse for octocat animations

esquisse : sketch in french

exquis : exquisite, beautiful, lovely in french

This repo is a collaborative animation tool to design new costumes for octocat in the spirit of version control.
There are a lot of these [octocat designs](http://octodex.github.com/). What if you could create a series of octocat costume proposals via composites of component illustrations from 3 users (VCS #rahrahrah)?
So in the echo of VC and the surrealist practice of [exquisite corpse illustrations](http://en.wikipedia.org/wiki/Exquisite_corpse), this repo crowdsources octocat illustrations in 3 parts, and then squashes tripartite cats to one composite cat. Not all of the procedures of Git are suited to this concept, so some of the workflows are awk/nonstandard, but the basic idea of VC illustrations and collaboration fit with git.

General Idea
---------------------
Octocats will be split into 3 parts. you select a portion of the octocat 1/3, 2/3, or 3/3 to illustrate, and you push your design component to a remote branch, and await "squashing" your component part with 2 others for a complete cat.


How it might work
---------------------
### Clone the repo and initiate an illustration
Illustrations will tag to your username and others can then branch from and rebase on your animation.
> git clone git@github.com/auremoser/gitexquis.git
> git checkout -b Your_Username octocat

### View and contribute to illustrations
> git branch -a
> git fetch 

To fetch all changes from remote branches so you can rebase your illustration addition on the existing octocat (split into 3 parts).

Add your octocat with a commit comment that states what # in the series of 3 your commit contributes to, so, if you contribute the second of a 3 part octocat illustration, create a meaningful commit message to that end.

> git rm octocat.md
> git add Your-Username.md
> git commit -m "Octocat addition #/#"

### How to illustrate
Create a photoshop illustration or draw one and photograph it. Specify in markdown what your octocat design is in one sentence and then link to an illustration on imgur or another URL host.
Pull to collect animations ideas from a branch / push to add them to the components folder. 

### How to complete a cat
Rebase and squash to create a composite from 3 illustrations, or append yours to an existing branch in the components folder, and submit it for consideration. Push your complete octocat image after combining all three parts to the composite folder for consideration. Approved cats will get pushed for posting to the Octodex based on admin discretion.

![yes we code](https://raw.github.com/auremoser/gitexquis/master/imgs/codercat.jpeg)

