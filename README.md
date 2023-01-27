# *Tech201-git-github*
Basic practice of creating and editing a markdown file. 

## Creating the Markdown file
-*These steps have been added from the local host.*-

- Step 1: Open Git Bash 
- Step 2: `mkdir` + name of the directory you wish to create
- Step 3: `cd` + name of the directory you have just created
- Step 4: `pwd` = shows current directory which you are navigating. 
- Step 5: `git clone` + https URL in GitHub of the repository you want to clone in your local environment
- Step 6: `ls` = listing files and directories
- Step 7: `cd` + name of the file or directory you want to navigate
- Step 8: `ls` = to see the files in the directory (in this case to see the README.md file that you are about to edit)
- Step 9: `pwd` = to confirm which file or directory you are currently navigating
- Step 10: `nano` + README.md = make changed to the README.md file (documentation file)
- Step 11: Add the changes that you want to make; once finished press CTRL+X
- Step 12: Confirm the changes you made by pressing Y and Enter
- Step 13: `git add .` = add the changes made in your local environment
- Step 14: `git status` = to confirm that the changes have been added to your local environment
- Step 15: `git commit -m "concise message"` = commit the changes you have made
- Step 16: `git push -u origin main` = push the changes made in the local environment to the online environment
- Step 17: check the online environment for the changes you have just made.
- Great! You have successfully created and made changes to a Markdown file! 

### Adding pictures to the Markdown file.
![](Git-PUSH-pULL.png)
- step 1: Go into the local environment cloning the online one.
- Step 2: Download the picture that you wish to add to the environment.
- Step 3: Save the picture in the same folder as the README.md file. 
- Step 4: Now, in Pycharm or Bash, you should be able to code the following:
- Step 5: `![](name_of_the_image.png)`
- Step 6: On the right hand side, in the Preview side, you should be able to see the picture.
- Step 7: Now that we have the picture in the local environment, let`s push it in the online one.
- Step 8: `git add .` = add the changes (in this cade the picture) to the Markdown file.
- Step 9: `git status` = to make sure the changes have been sent. 
- Step 10: `git commit -m "concise message"` = commit the change.
- Step 11: `git push -u origin main` = push the change on the online environment.
- Step 12: Go on GitHub and check that the picture has been successfully added. 
- Weehey! You have successfully added a picture to your Markdown file! 

