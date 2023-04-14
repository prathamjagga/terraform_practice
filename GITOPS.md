Gitops is when you use git to manage your IAC code.
As for the ops part,we usually set up a pipeline using some tool, probably github actions which trigger deployment or perform "terraform apply" after getting changes committed to the main branch.
You can see the image below for understanding:

![image](https://user-images.githubusercontent.com/30550632/232118588-415e41da-dbe6-4928-81a9-818d3f509455.png)


the git repository might also be connected to terrform cloud to track the changes
.
