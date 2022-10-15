# Store GitLab Build Statusses
This repo contains the build status results from the GitLab CI, and stores the
accompanying build status badges (svg).

## Structure
There are two lists:
 - `evaluated_commits.txt` - contains all commit sha's that were evaluated.
 - `evaluated_commits_with_ci.txt` - contains all commit sha's of GitHub 
 repositories that contained a GitLab CI yaml.
 
 Furthermore, the build statusses are stored according to folder structure:
 ```
 <organisation/username>/<repo_name>/<branch>/commit_sha.txt
 ```
