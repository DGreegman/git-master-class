# git-master-class

## Explain Version Control
Version control is a system that allows you to track changes in your files over time. It enables multiple people to work on a project simultaneously, keeping a historical record of changes made to the code or files. Version control systems help manage collaboration, track modifications, and provide a way to revert to previous states if needed.

## Explain difference between git and github

### Git
Git is a distributed version control system that allows you to track changes in your codebase. It operates locally on your computer and provides commands for committing, branching, merging, and more.

### Github
GitHub, on the other hand, is a web-based platform that uses Git for version control. It adds a graphical interface and collaboration features on top of Git. GitHub hosts repositories in the cloud, making it easy for multiple people to collaborate on a project.

## List 3 other github alternatives

### GitLab: 
Similar to GitHub, GitLab provides a web-based platform for hosting and managing Git repositories. It offers features for continuous integration, code review, and more.

### Bitbucket
Bitbucket is a Git repository management solution that also supports Mercurial. It provides a platform for code collaboration, continuous integration, and deployment

### SourceForge: 
SourceForge is an older platform that supports version control systems like Git, Mercurial, and SVN. It provides tools for collaboration and project management.


##  Explain the difference between git fetch and git pull

### Git Fetch: 
Fetching retrieves changes from a remote repository to your local repository, but it does not automatically merge them into your working branch. It's useful for seeing what changes are available before deciding to merge.

### Git Pull: 
Pull, on the other hand, not only fetches changes but also merges them into your current working branch. It's a combination of git fetch and git merge.

## Git Rebase:
Git rebase is a command used to integrate changes from one branch into another by moving or combining a sequence of commits to a new base commit. This helps create a linear, cleaner commit history. In simple terms, it's like taking your changes and putting them on top of the latest changes from another branch.

    Command: git rebase <base_branch>

## Explain in simple terms git cherry-pick and the command for it 

### Git Cherry-pick:
Git cherry-pick is a command that allows you to apply a specific commit from one branch to another. It's useful when you want to pick and choose individual commits and apply them to a different branch.

    Command: git cherry-pick <commit_sha>
