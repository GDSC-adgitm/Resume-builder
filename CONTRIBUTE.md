![image](https://user-images.githubusercontent.com/110708865/195105442-212ad0c0-1d6c-41d4-8388-0b8450f4aa7b.png)

### STEPS FOR CONTRIBUTION 💥
### 0. Star the Repo 💡
Star the repo by pressing the topmost-right button to start your wonderful journey.
 
### 1. Fork it 🍴	
You can get your own fork/copy of Hacktoberfest 2022 by using the "fork" button.
### 2. Clone the repository ⚡
--> You first need to create a local copy of this repository after you have forked it to be able to contribute to the same. Copy the following command and paste it in your terminal.

✅ git clone https://github.com/username/HacktoberFest.git
This makes a local copy of the repositry in your machine.

Please ensure that you add YOUR username in the command and do this after Forking the Repository.

### 3. Create a New Branch ⚡
 After successfully cloning the repository, you need to now create a separate branch for yourself to not disturb the workflow of the repository. If you aren't already inside the main folder copy this command in terminal and press enter.

✅ cd HacktoberFest

 Now that you are inside the main folder, use this command to create a new branch for yourself.

✅ git branch (name of your branch)

Please ensure that the name of your branch is your username.

### 4. Switch to your New Branch ⚡
✅ To start working and to push code from your own branch, please execute the following command in the Terminal.

✅ git checkout (name of your branch)

You should receive a notification which will state that you have switched to your newly created branch.

### 5. ADD YOUR FAVORITE PIECE OF CODE WHICH CAN HELP BUDDING DEVELOPERS GROW!

### 6. Sync all Updates ✨
The part you have been waiting for. If you are sure that you are following the guidelines that you can find here, proceed further and execute the following command in your terminal.

✅ git add .

This will add all the files in your local repository. After this execute

✅ git commit -m "ADD YOUR MESSAGE HERE (PREFERABLY THE NAME OF YOUR PROJECT)"

Note that it is mandatory for you to add a Commit Message for others to understand what you are trying to add here. Now finally to push updates to the new branch, execute the following:

✅ git push --set-upstream origin (name of your branch)

While you are at it, also execute the following command which will specify a new remote upstream repository (the cone you are looking at).

git remote add upstream  https://github.com/GDSC-adgitm/Resume-builder

### 7. Keep your Repository in Sync 

You need to use the following commands to help you sync all the branches with their respective commits associated with this repository and stay in loop. Copy these commands and execute:

✅ git fetch upstream

✅ git checkout master

Post this you simply need to merge all the changes you made.

git merge upstream/master

### 8. Creating PUll REQUEST ✨
Create a Pull Request (The Part you have been waiting for) Now that you are done with the most complex parts of the process, you can just go to your forked repository and Click on New Pull Request towards the left hand side of the page and You're Done! Congratulations on successfully creating a Pull Request there!
What are the most important Git Commands that I am going to need?
Some important commands that you are going to need are listed below:

✅ git checkout "(name of your branch)" <br>
✅ git checkout dev <br>
✅ git pull (Really !Important to merge updates) <br>
✅ git rebase dev <br>
The most important commands now are as below:

✅ git add . or git add -A <br>
✅ git commit -m "MESSAGE" <br>
✅ git push origin (name of your branch) <br>
Finally go to your repositry in the browser and click on compare and pull requests. Then add a title and description to your pull request that explains your precious effort.

