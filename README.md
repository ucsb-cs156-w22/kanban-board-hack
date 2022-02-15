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

That code then needs to be pasted into a GitHub Actions script.

Surely, there is a better way to structure this; this was a quick hack
when I was under the gun and pressed for time.  

Please SOMEONE, whether me or someone else, refactor this into a more sensible workflow. :-)



