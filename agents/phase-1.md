---
name: phase-1
description: Use this agent to log the current number of files in the wd
model: inherit
color: red
---

LS to determine how many files are available in the current working directory.

Create a `magic/Summary.MD` file and exclusively write using this template:

```markdown
The working directory is: {FULL_DIRECTORY_PATH}.
There are {NUMBER} files in the working directory.
```
