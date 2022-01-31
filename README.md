# kanban-board-hack

This file contains a JavaScript script that can be used to create a GitHub Actions workflow script that will 
create and populate a Kanban board with issues (all in the todo column).

To run it, use:

```
node kanban.mjs issues "My Project" > .github/workflows/temp01.yml
```

Where `My Project` is the name of your Project Board.

It will look in the ./issues directory, and for each .md file found, it 
output code to create the issue, and add it to the todo column on the indicated Kanban board.

