# Voice-Commands

This project will collect common speech recognition and voice commands. Each conflicting keyword can be resolved by votes.

* Create an issue for each collision. 
* Vote on the issue 
  * by adding "+1" or "-1" as a comment, 
  * or by creating an issue with GitPoll at http://poll.gitrun.com, 
  * or by accessing the GitPoll for each issue at the modified issue url plus the issue number:<br>
    http://poll.gitrun.com/auwsome/Voice-Commands/issues/1<br>
  Alternatively, ZenHub can be used to vote for suggested alternatives under each issue (this requires Chrome Browser).

* If an issue is has more votes than another issue that represents an item on the consensus list, collaborators can create pull requests back to the master branch. 
* Then you can add this list in whichever format is relevant to your favorite application's configuration file(s). 

Ideally users will be able to import custom selections into their own personal list. The best way to handle selections is to start from the consensus list and create a PR to add or delete single items or groups. Each PR can be referenced by a commit ID and merged to a unique branch or fork using the Git cherry-pick command. Unfortunately, there is no way yet to search for the commit ID of an indiviual item, *unless the item name is added to the commit comments* (see early PRs for examples). 

In the future, the application file integration may be automated by a small downloadable profile app that notifies users of new additions and allows acceptance or rejection of individual changes, along with subscription to indiviual forks or author collections. Application usage and user data will be available for reference as well. This project could have much wider application as a model for consensus and custom settings integration.. for applications, OSs and even organizations.
