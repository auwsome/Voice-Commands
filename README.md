# Voice-Commands

This project will serve to collect the most common speech recognition and voice commands. Each collision can be resolved by GitPoll.

Create an issue for each collision.
Vote on the issue by adding "+1" or "-1" as a comment, OR by accessing the GitPoll for each issue at:<br>
"http://poll.gitrun.com/auwsome/Voice-Commands/issues/" plus the issue number such as:<br>
http://poll.gitrun.com/auwsome/Voice-Commands/issues/1

GitPoll doesn't work on PRs. ZenHub is free for OS projects and does work on PRs, but only shows +1s for each comment which should represent individual alternatives. 

Collaborators are able to create pull requests back to the master branch. These include the collisions resolved through the top voted issues.

Finally, a consensus list of the most common speech recognition and voice commands will be available to add to your favorite application's configuration file(s). 

The best way to handle custom selections per command is to start from the consensus master list and add or delete items or groups of items. Each deletion or addition can be referenced by a commit ID and merged to your own branch or fork by using the Git cherry-pick command. Unfortunately, there is currently no way to search for the commit ID of an indiviual item, unless the item was added to the commit comments and "git log grep <item>" is used. Conceivably, one could use a utility like BeyondCompare or another 'diff' tool to selectively merge lines. Hopefully, individual variations from the consensus list will initiate creation of a pull request which should have their own commit ID and can be searched.

In the future, the application file integration may be automated by a small downloadable profile app that notifies users of new additions and allows acceptance or rejection of individual changes, along with subscription to indiviual forks or author collections. Application usage and user data will be available for reference as well. This project could have much wider application as a model for consensus and custom settings integration.. for applications, OSs and even organizations.
