### Coding Guidelines

Branches representing a new features must have as parent branch the `develop` branch and have a wrike taks associated to it.

![Write Task ID](/.github/DOCS/wrike_task_ID.png?raw=true "Optional Title")

- Branches follow the strategy:
  - `feature/projetcName-wrikeTaskID` - for the implementation of a new feature based on a wrike task
    - example: `feature/workshop-592699324`
  - `bugfix/projectName-wrikeTaskID` - for the fixing of a bug exi[s]ting within a wrike task
    - example: `bugfix/workshop-592699324`
  - `hotfix/projectName-wrikeTaskID` - for the fixing of a bug exi[s]ting within a wrike task
    - example: `hotfix/workshop-592699324`
  - `release/version` - for the closing a release of exi[s]ting within a wrike task
    - example: `release/0.1.0`
  - `tag` - for the tagging a version of a exi[s]ting within a wrike task
    - example: `v0.1.0`
  

- Commits follow the strategy:
  - `projectName-taskID #time duration description` - for a commit relative to a wrike task
  - the `duration` especification must comply to the following format: `1w 2d 4h 30m`
  - example: `workshop-592699324 #time 15m added code documentation`
