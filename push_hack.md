Github Past PUSH Hack.
Useful for recording offline activity days.

While the question "How do I make a Git commit in the past?" explains how to amend the commit author date:

git commit --amend --no-edit --date="Fri Nov 6 20:00:00 2015 -0600" 
Run that after a commit to amend the last commit with the timestamp noted.
The --no-edit will leave the message as-is.

The OP asks:

That question does not specify the GitHub result... would it work in the same way?

Yes: multiple projects exist allowing you to generate and push commits "done in the past", in order to update your contribution chart.

See for instance contribution.io, github-contribution, or gitgardener.

All you need to do, is to push those amended commit on the master branch of your GitHub repo, as I mention here.




example:

1. git add *
2. git commit -m "github hack test"
3. git commit --amend --no-edit --date="Tue Dec 21 20:00:00 2020 -0600" 
4. git push