a.)
checkout - look at desired status of repository(like branches or files)

working copy - a version that allows for changes to be made without actually replacing the original

branch - movable pointer to a commit

update - make the version the most recent added

commit - records changes to repository

push - updates remote references along with associated objects

pull - fetch and merge changes on remote server to working directory

clone - fetch a repository from the git server

b.)
Similarities - Both are used to work on files.

Differences - In SVN you are working with the central repository while in Git you are working with a clone rather than the original.

c.) The git command to update a working copy to the repository is git commit. The subversion command is svn update.

d.) Conflict is a problem that occurs in a repository.  Conflict can be caused by simultaneously making changes at the same exact time to the same exact repository that are different from each other. To resolve this you can merge or choose one of the changes. For an example lets say that the teacher and TA were both working on the exam and committed changes and one puts the date but not the score and the other does the date but not the score. This results in a conflict. In order to fix this they would merge the two together in order to resolve the conflict.
