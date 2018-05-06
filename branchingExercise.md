# Git Branching, Merging and Tagging Practice

1. Make a new directory call `branchingPractice`
2. In that new directory, create a file called `index.html`
3. In that new directory create 2 new sub-directories `css` and `js`
4. In the `css` directory, create a new file called `styles.css` and in the `js` directory, create a file called `main.js`
5. Initialize this directory as a new Git repository
6. Add all these new files and directories to the staging index and commit these files with a thoughtful commit message
7. Create a new branch off the `master` branch called `feature1`
8. Checkout the `feature1` branch and add some basic boilerplate HTML markup to `index.html`
9. Add and commit these changes
10. Checkout the `master` branch
11. Take a look at the contents of the `index.html` file. What do you notice? Why do you think it's like that?
12. Create another new branch off the `master` branch called `feature2`
13. Checkout the `feature2` branch and add the following content to `index.html` - 'Hi, there!'
14. Add and commit these changes
15. Checkout the `master` branch
16. Again, take a look at the contents of the `index.html` file. What do you notice? 
17. Merge the branch `feature2` into the branch `master`
18. Again, take a look at the contents of the `index.html` file. What does it look like now?
19. Now, try merging the `feature1` branch into the branch `master`.
20. Resolve this conflict. Put the `Hi, there!` string inside the body of the HTML. Consider that the resolution of the merge conflict.
21. Add and commit these changes.
21. Delete both the `feature1` and `feature2` branches.
22. Tag this commit as `version-1.0`
23. Check to see which branches are left.
