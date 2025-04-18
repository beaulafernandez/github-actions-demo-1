PERSONAL STUDY GUIDE

Workflow - Event - Job - Runner - steps

Trigger a Workflow - Events - Activity Type

Examples:
  push commit
  pull request - types [opened, reopened] - branches/ branches-ignore [/feature**]
  branch-protection-rule -types [created, deleted]
  workflow_call - called by another workflow
  workflow_dispatch - manual
  workflow_run - based on conclusion of another workflow
  repository_dispatch - events outside github

Jobs | Steps | Runners
  Context - Contexual information
  Dependent Jobs
  Condition - if expressions in job

Matrix Strategy

Environment Varibales | Inputs | Outputs
  $GITHUB_ENV
  echo "env_name=value" >> "$GITHUB_ENV"
  echo "$env_name" 


Actions 
  Adding an action (Github marketplace, repo - public, repo - same, repo - other)
    Examples:
      {owner}/{repo}@{ref}  
      ./path-to-dir 
      docker://{image}:{tag}
  
  Create an action [ inputs, file-path , outputs, results-file]






