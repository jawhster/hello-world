# hello-world
Using GitHub guide to create hello-world repository

I'm learning so can share between LaTeX, overleaf, and git.

# helpful reference document on using git to clone to local directory, git pull, make changes, commit, and git push

http://latextrack.sourceforge.net/github-tutorial/github-tutorial.pdf

# notes

Repository = organize a single project (folders/files,images,videos,spreadsheets,datasets, etc). Best practice to include README file

Branching = way to work on different versions of a repository at one time

  > By default, repository has one branch named master (definitive branch)
  > When branch off the master branch, we're making a copy, or snapshot, of master at that point in time
  > If someone else made changes to master while working on our branch, you can pull in those updates
  > Bug fixes & features separate from master (production) branch
  > When a change is ready, they merge their branch into master
  
Pull request = when open a pull request, proposing your changes & requesting someone review (@mention system) & pull in your contribution & merge them into their branch
  > Pull requests are the heart of Github collaboration
  > Now that we have changes off of master branch, we can open a pull request
  > Pull requests show diffs, or differences, of the content from both branches
  > As soon as make a commit, can open pull request & start discussion (even before code is finished)
  
Best practice: master branch is always deployable so it is extremely important that your new branch is created off of master when working on a feature or fix
