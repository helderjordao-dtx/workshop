### Coding Guidelines

Branches representing a new features must have as parent branch the `develop` branch and have a wrike taks associated to it.

![Write Task ID](/.github/DOCS/wrike_task_ID.png?raw=true "Optional Title")

- Branches follow the strategy:
  - `feature/projetcName-wrikeTaskID` - for the implementation of a new feature based on a wrike task
  - `bugfix/projectName-wrikeTaskID` - for the fixing of a bug exi[s]ting within a wrike task
  - example: `feature/workshop-592699324`

- Commits follow the strategy:
  - `projectName-taskID #time duration description` - for a commit relative to a wrike task
  - the `duration` especification must comply to the following format: `1w 2d 4h 30m`
  - example: `workshop-592699324 #time 15m added code documentation`
