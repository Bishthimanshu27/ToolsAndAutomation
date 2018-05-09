# Git Exercise
To be done with a partner.

Your goal is to complete all the steps below and do your best to solve any issues that arise.

### On Computer 1
0. One person should create a new Github repository for this project. They should invite their colleague to join as a colloborator.
1. Make a new directory call `gitPractice`
2. In that new directory, create a file called `index.html`
3. In that new directory create 2 new sub-directories `css` and `js`
4. In the `css` directory, create a new file called `styles.css` and in the `js` directory, create a file called `main.js`
5. Initialize this directory as a new Git repository
6. Add all these new files and directories to the staging index and commit these files with a thoughtful commit message.
7. Create a new directory called `log`
8. Add a `.gitignore` file that ignore all files in the `log` directory that end with `.log`.
9. Commit both the `.gitignore` file and the `log` directory. (Remember empty directories cannot be committed)
10. Set this repository to use to Github repository as a remote.
11. Push the master branch to the Github origin master
12. Create a new branch called layoutUpdate
13. Switch to that branch and make the background color of the HTML page green.
14. Connect the Javascript and CSS files to the HTML with appropriate markup.
15. Log your name to the browser developer console in the JS file.
16. Add and commit these changes and
17. Add another file called links.html
18. Amend your previous commit to include this file
19. Add an `a href` link tag in the `index.html` file that with the `src="links.html"`
20. Add and commit this file.
21. Add another file called whoops.html
22. Add and commit this file.
23. Add another file called whoopsAgain.html
24. Add and commit this file.
25. Using `git reset` get rid of these 2 files and bring it back to the state it was right before you added them. You can stick them in the trash.

### Computer 2
0. Clone the repository
1. Create a branch called jsUpdate
2. Switch to that branch and add some HTML boilerplate code to the `index.html` file.
4. Write a javascript function in the `main.js` file that pops up an alert on the page everytime some clicks anywhere on your page.
5. Add and commit these changes
6. Add a few more changes to the bottom of the `index.html` - put your names and email addresses.
7. Add and commit these changes
8. Add another file to the `js` directory called `functions.js`
9. Add and commit these changes
10. Revert the commit that added your names and email addresses to the bottom of the `index.html` file.
11. Merge your branch into master and push your changes

### Computer 1
1. Merge the branch `layoutUpdate` into `master` and push to Github - you may run into problems.
2. Pull the most recent changes from Github, resolve any conflicts the way you and your partner see fit.
3. Add and commit these changes and push the resolution.


