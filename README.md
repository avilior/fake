# fake
 A fake repo to play with....
 
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


