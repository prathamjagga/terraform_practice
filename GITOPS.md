Gitops is when you use git to manage your IAC code.
As for the ops part,we usually set up a pipeline using some tool, probably github actions which trigger deployment or perform "terraform apply" after getting changes committed to the main branch.
You can see the image below for understanding:

image.png

the git repository might also be connected to terrform cloud to track the changes
.
