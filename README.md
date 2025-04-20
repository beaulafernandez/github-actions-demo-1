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
  continue-on-error

  Passing information between jobs 
  - map steps output to job output

  Matrix Strategy
  Caching
  Artifacts

Environment Varibales | Inputs | Outputs
  $GITHUB_ENV , GITHUB_OUTPUT
  echo "{name}={value}" >> "$GITHUB_ENV"
  echo "{name}={value}" >> "$GITHUB_OUTPUT"

Actions 
  Adding an action (Github marketplace, repo - public, repo - same, repo - other)
    Examples:
      {owner}/{repo}@{ref}  
      ./path-to-dir 
      docker://{image}:{tag}
  3
  Create an action [ inputs, file-path , outputs, results-file]

Secrets





