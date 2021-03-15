# PSG 2 (2020/21) Showcase Project
This is a project example for the course PSG 2 of year 2020-21.

![Project columns](https://github.com/governify/showcase-psg2-2021/blob/main/project.PNG?raw=true)

## Guarantees
The three correlations present in the TPA are the following:

### New branch - In progress issue (GH Projects)
 - Teams must move the issue to the "In progress" column and create a branch including the issue number inside the branch name.
 - The system will look for the issue to be in the "In progress" column each time a branch is created. 

### Open PR - In review issue (GH Projects)
 - Teams must move the issue to the column named "In review" and open the PR related to the branch of the issue.
 - The system will look for the issue to be in the "In review" column each time a PR is opened. 

### Merge PR - Done issue (GH Projects)
 - Teams must move the issue to the column named "Done" and merge the PR related to the branch of the issue.
 - The system will look for the issue to be in the "Done" column each time a PR is merged. 


## Things to take in mind
 - The guarantees are computed every 5 minutes. Students should take a while each flow step (New branch-Open PR-Merge PR) for the system to properly obtain the metrics.
 - The issues/cards should be moved before working with the branches/PR as it is possible to miss some information doing the workflow in reverse.
 - The columns must be called exactly "In progress", "In review" and "Done" (case sensitive).
