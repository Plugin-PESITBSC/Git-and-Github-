# Git-and-Github-

FAQs


    What is the difference between Git and GitHub?

Git is a version control system; think of it as a series of snapshots (commits) of your code. You see a path of these snapshots, in which order they where created. You can make branches to experiment and come back to snapshots you took.

GitHub, is a web-page on which you can publish your Git repositories and collaborate with other people.


    Is Git saving every repository locally (in the user's machine) and in GitHub?

No, it's only local. You can decide to push (publish) some branches on GitHub.

    Can you use Git without GitHub? If yes, what would be the benefit for using GitHub?

Yes, Git runs local if you don't use GitHub. An alternative to using GitHub could be running Git on files hosted on Dropbox, but GitHub is a more streamlined service as it was made especially for Git.

    How does Git compare to a backup system such as Time Machine?

It's a different thing, Git lets you track changes and your development process. If you use Git with GitHub, it becomes effectively a backup. However usually you would not push all the time to GitHub, at which point you do not have a full backup if things go wrong. I use git in a folder that is synchronized with Dropbox.

    Is this a manual process, in other words if you don't commit you won't have a new version of the changes made?

Yes, committing and pushing are both manual.

    If are not collaborating and you are already using a backup system why would you use Git?

   
If you encounter an error between commits you can use the command git diff to see the differences between the current code and the last working commit, helping you to locate your error.
You can also just go back to the last working commit.
If you want to try a change, but are not sure that it will work. You create a branch to test you code change. If it works fine, you merge it to the main branch. If it does not you just throw the branch away and go back to the main branch.
 You did some debugging. Before you commit you always look at the changes from the last commit. You see your debug print statement that you forgot to delete.
