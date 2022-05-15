# fake
 A fake repo to play with....
 
 # Experiment 2
 
 In this experiment i want to explore at what point do changes in the PR are visible to me on the local machine
 
 On the PR at the remote I will make a suggestion and place some comments....
 Then I want to be able to see them on the local machine.
 Do i have to check them in.  Specifically
 0. Push the README branch: issue2 to the REMOTE
 
 1158  git switch issue2
 1159  git branch
 1162  git status
 1163  git add README.md
 1164  git commit -m "issue2 starts"
 1165  git remote
 1166  git push -u origin issue2
 
 At this point the we have issue2 on the remote
 The remote offers to make a pull request.
 
 
 1. I will place a comment on the PR
 2. I will place a suggestion on the PR
 - here is the suggestion. Now lets see when I can see them on the local machine.  What do I have to do to make them visible on the remote?
 - first I notice that it asks me to commit the suggestion.
 - btw I can also edit it (as I am doing now)
 3. I will then fetch/pull the PR to see what i can see on the local machine
 1172  git fetch
 1173  git diff issue2 origing/issue2
 1174  git diff
 1175  git merge
 I did a fetch and tried to see what changes but that didn't work....
 The merged updated this file with these comments.
 
 4. I will then push a change from local to the remote
After doing a push I can see the how the round trip is working.
You can make a suggestion on the PR, commit it and on the local you can pull down the changes. 
# Specifically

- learning about PRs

- making sure it all works from CLI

# Publishing a Repo to Github using CLI


Declare the remote

`git remote add origin  https://github.com/avilior/fake`

git push -u origin main

Notes on GIT


Play with GitHub pull requests.

Create a branch on local machine

`git branch issue1`
`git checkout issue1`

~or~
`git checkout -b issue1`

What is the difference between:
git switch issue1 vs git checkout issue1?


We need to push issue1 branch to remote.

`git push -u origin issue1`


Now create a pull request on GitHub

- On Github we have Compare & pull requests
- Or new pull request

This is a public repo:
So lets see if I can see it without logging in

PR was made. And I made a change…..

BTW: once I made a change I was given an option to make a single change or “Start a Review”. What is “Start a Review”

Now back on my local machine….
Can I see anything that happened on the remote?

I did a diff but I didn’t see the changes 
Maybe I should have done a git fetch then a diff????

I pulled the changes down from remote by doing

`git pull`


