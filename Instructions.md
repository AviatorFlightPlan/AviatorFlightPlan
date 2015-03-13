Greetings, we would like to welcome everyone to the Aviator Flight Plan Team. 
If you are looking at this page, you must be new to the team or to GitHub.
Here, we will provide instructions on how to use GitHub as well as a link to a video version of the tutorial, if you get stuck on the text version.
We are committed to keeping this experience as close to how a workplace would be as possible,
so keep your work professional.


Good Luck!

Project Managers,

Ben Cohen and Griffin Ramsey

#Directions for github:

__Please read the entire tutorial, even if you use the video tutorials to help you along with pieces of it if you are stuck (which is great, that is what they are for), the text will give you the most information about what you need to do. We know there is quite a bit of text, but all of it is important and videos have been made to help you along with the process.__

* If you have not already, create a GitHub account. There should be a link somewhere at the top right of GitHub.com.
* Next, unless you've already done so, ask a project manager for access to the files.

####Now you are ready to download GitHub.
* First, install GitHub to your computer. Choose the correct link for your system.
* Windows: https://windows.github.com/
* Mac: https://mac.github.com/
* __Linux: This is a bit complicated if you're used to using a non-linux machine.__
  * Open the terminal (For most versions of linux, the hotkey is Ctrl + Alt + T).
  * In the terminal, type sudo apt-get install git
  * Press enter and now type git config --global user.name "YOUR NAME"
  * Press enter again and also type git config --global user.email "YOUR EMAIL ADDRESS"
  
Video Tutorial: https://www.youtube.com/watch?v=8XDR137mZK4

####Now we can start learning how to use GitHub
* Go back to the repository page on the GitHub website (https://github.com/AviatorFlightPlan/AviatorFlightPlan) and go to the top right corner where it says "fork"
* Click that and then click on the square that appears for your username.
* _This will create a version just for you so you dont have to worry about ruining the original._
* Now go to the bottom right corner and click "clone in desktop"
* __Sometimes the above step does not work, if this is the case, follow these steps:__
    * Open the GitHub program you installed earlier (not the command line, the other one)
    * Click the + in the top right.
    * Click on your username on the right.
    * Click clone at the top, then select AviatorFlightPlan.
    * Click the check at the bottom and save it to your GitHub folder. If you have no GitHub folder, make one.
    * Copy this folder path for later.

* Now that you have GitHub installed and cloned the files, look for a program that should have installed with GitHub called Git Shell, or something similar.
* Once that opens, find your folder that you just cloned. Mine was located at C:\Users\MYNAME\Documents\GitHub\AviatorFlightPlan
* Copy the location you found your folder in and go into the Git Shell you opened earlier.
* Now type cd FOLDER_LOCATION_YOU_JUST_COPIED
* _Note: often in command line programs, you need to right click to be able to paste text._
* _What that just did was allow the program to know where to look when editing your files._
* If you did not press enter, please press enter, and from now on, always just assume to press enter after typing something into this program.
* Next, type git init
* _This initializes your repository so that you can work with it._
* Once you do that, type git remote add origin https://github.com/YOUR_USER/AviatorFlightPlan
* _This allows you to upload changes to your personal online copy of the repository._

Video Tutorial: http://youtu.be/f3ZWImsfXO4

####Now to pull updates from the master file without losing your personal edits:
* Type git pull https://github.com/AviatorFlightPlan/AviatorFlightPlan
* __Note, this only takes the file and puts it in local storage, you will still have to use a "git push" to add this to your personal online version.__

Video Tutorial included in the above video tutorial.

####You now have GitHub set up and you can now begin to push/pull/change files.

##***At the start of each session, you must do these:
* Type git init
* Make sure you are in the correct directory. If you are not sure, just type cd FOLDER_LOCATION (Mine is C:\Users\MYNAME\Documents\GitHub\AviatorFlightPlan) I've also found just typing cd AviatorFlightPlan works.
* Make sure you are in the branch you want to be working on. For more info about branches keep reading.
* Type git pull https://github.com/AviatorFlightPlan/AviatorFlightPlan/
* _This will allow you to have all the current changes people have uploaded and initialize your files for the session._

Video Tutorial: http://youtu.be/NwcWxw3zZTc

##Useful Commands
* To add a new file to the repository, put the file in the folder location you specified a few steps above, then type git add FILE_NAME.EXTENSION (Example: git add myfile.txt)
  * Or: to add every file in your folder, type git add *
  * If your file has spaces in the name, use "FILE_NAME.EXTENSION" (Example: git add "my file is very long.txt")
* __After adding a file you should type git status to make sure the file is being tracked.__
    * If it isn't check your spelling and try adding it again, capitalization does matter.
* To check if your file has been made ready to upload, type git status
  * _Files that are not uploaded will be listed._
* To save a changelog, type git commit -m "TYPE_CHANGES_HERE"
  * Or: if you have a longer message type, git commit
* _This will bring up a long message. Just start typing your message and then just close and save the box that appeared when you are done._
  * Also, if you want to commit all changes you've made recently, type git commit -a
* __*You must do a commit command before you can upload online.*__
* __To push your changes to your personal online copy, type git push__
* To get files from your personal online repository (_NOT_ the master original version, but your personal copy), type git pull
* To delete uncommitted changes you do not want to keep, type git reset --hard
* To switch branches, type git checkout NAME_OF_BRANCH
* _Be careful because once you switch, all changes will be made to that new branch you switched to._
* To see what branches exist locally, type git branch
* To merge the currently viewed branch and another, type git merge BRANCH_NAME
* __Tip: For this to work correctly, switch to viewing the branch you want to have data merged to, then use the above command with the BRANCH_NAME being the branch that you want give data to the other branch.__
* To push your local branch online, type git push origin BRANCH_NAME
* __If you don't know what a branch is, basically it is a version of a program stored in a separate place than the original version so you don't corrupt files, or so you can try out features without ruining the original.__
   
Video Tutorial: http://youtu.be/ygA731k1vPw
 
##**Once you push an update online, you are not done.
* By using the push command using the setting you set up through this tutorial, you are only pushing changes to your personal online copy.
* Now you need to push it to the main copy which is controlled by the project managers.
* To do this, go to the website (github/YOUR_USER/AviatorFlightPlan) and look towards the center right of the screen for the link "pull request"
* At the new screen, make sure the box at the top right says AviatorFlightPlan/AviatorFlightPlan, and the box next to it says YOUR_USER_NAME/AviatorFlightPlan
* Now you can use this page to create a request for a manager to add your changes to the official version.

Video Tutorial is included in the video totorial above.

####Hopefully this gives you a great start, and for more commands you may use, I suggest going here: https://confluence.atlassian.com/display/STASH/Basic+Git+commands
    
To ensure that you have read this and completed the steps, upload any file that is not a .txt to your fork, and request it to be pushed to the main version. We will not allow you to begin any projects until you complete this.
    
##Troubleshooting:
A command not working? Here are some common reasons why:
* Can't push/pull files?
    * You might have unsaved changes.
    * Try typing git commit -a
* Can't add files? Or change files to be tracked?
    * You may have spelled the file wrong (capitalization matters)
    * You may be in the wrong directory, to reset it, type cd FOLDER_PATH
