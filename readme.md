# How to chain deployment and release in two different repositories
This project walks through release deployment in Repo A https://github.com/durrello/github-cross-repo-reployment-repo-a then release in Repo B https://github.com/durrello/github-cross-repo-reployment-repo-b once it is successful in A

## Create the workflow files
### Repository A
This is the source repository that is going to triger build in the second repository(Repository B)

### Repository B 
This repo is triggered after Repository A has successfully built.