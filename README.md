![CF](https://i.imgur.com/7v5ASc8.png)  Lab 07: Functional Programming
=======
[![Build Status](https://travis-ci.org/codefellows-seattle-301d4/07-functional-programming.svg?branch=master)](https://travis-ci.org/codefellows-seattle-301d4/07-functional-programming) [![GitHub issues](https://img.shields.io/badge/Issues%3F-Ask%20for%20Help!-orange.svg)](https://github.com/codefellows/seattle-301d4/issues/new)

The concepts of functional programming have significantly shaped Computer Science from the early days.

Apply some "FP" concepts to the MVC Blog!

We'll make an "admin" page, which will show some stats on how authors on the blog are doing. In the end, it will looks [something like this](https://cf-mvc-blog--class07.aerobatic.io/admin.html).

Today there are many TODO items, but they are (mostly) smaller bites.

## TODOs: MVP
1. Start by looking over what's new in the codebase. There is now an admin.html page! There are some `// DONE` comments! There are some new functions in articleView.js. Practice those code-reading skills. :smiley:
1. Let's make sure each one of our scripts are properly enclosed. Wrap the contents of article.js in an IIFE, just like articleView.js has been. Set up your IIFE so it receives a parameter to which it can attach behavior.
1. For both `index.html` and `admin.html`, we'll want access to the `Article.all` data...but we'll have different view functions to set up each of those pages. Help complete the `fetchAll` function so that it calls a `next` parameter: a function to call when it's work is done.
1. Ensure both the index page and the admin page call `fetchAll` in a way that properly triggers the appropriate page setup methods.
1. Use chained map/reduce calls to transform the data into what you need it to be.


# User Stories: Stretch Goals
- What statistical analysis would be of interest to you with this data set? Code it up!  



## Write code together!

Find those `TODO` items in the code, and tackle one of them.

1. Driver: In your terminal, ensure that:
   - you are on a branch with you and your partner's namesake.
   - you are currently within the directory also with you and your partner's namesake in the `submissions` folder.

1. Type `atom .` to open this folder as a project in Atom.
1. Use the Atom "Find in Project" (command shift "f" if on a Mac) to locate all the TODO items.
1. Work through one or two TODO items (or one hour, whichever arrives first), testing your code as you go, until you are happy with how it's working.
1. In your terminal type `git status` to view the files that you have changed. You should only see the files that you have worked on.
1. Type `git add file1 file2` where file1, file2, etc. are the files that you have changed.
1. Type `git status` to view the files that have been added to your commit. You should only see the files that you worked on.
1. Type `git diff --staged` to view the differences between the previous version and the staged version of your file.
1. Type `git commit -m "some meaningful message"` where Some meaningful message is a message that explains your commit.
1. Type `git status` to make sure there is nothing to commit.
1. Type `git push origin your-name-partner-name` to push this branch to your forked repo on GitHub.
2. **Reminder: No Pull Requests until the assignment is finished, or time runs out**
2. On GitHub, Add your navigator as a collaborator (go to settings -> collaborators).
3. Slack your partner the repo link for them to clone down.

## Switch roles

1. Navigator (AKA new Driver): You can now clone the driver's fork, to your own local dev environment. If you haven't already:
2. `mkdir 301/` that will be the parent directory for your own forked repo
3. `cd 301/`
4. `mkdir navigator` within this main "301" directory - **not your class repo directory** - this will now contain your partner's repo, and future partner repos when you initially start out as navigator and later switch as a driver). Since you are now a collaborator, you can `pull` and `push` changes to and from `orgin`.

The new driver (original navigator):  
1. `git clone` the repo your patner Slacked you into your navigator folder.  
2. `git fetch origin` branch-name  
2. Now open the code in Atom. It's your turn to have the hands on the keyboard!  

## Submit your assignment

When you are finished with your work (or if time runs out), then submit your work. To do this, you'll create a "Pull Request" (aka: "PR") to the upstream repo with your changes, and submit that PR link in Canvas.

1. Ensure that all your local changes are committed, and pushed to your `origin` repo.
2. Visit the origin repo on github.com.
1. Create a new PR.
1. Carefully review the PR to ensure the branches look correct.
1. Write a good descriptive summary of your changes:
  - Be sure to include how much time you spent on it, and who you worked with.
  - Briefly reflect on and summarize your process.
1. When you create the PR, it will have a unique URL. Copy this link, and paste it into the assignment submission form in Canvas. Both the driver and the navigator will submit the same PR link.

