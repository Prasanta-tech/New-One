# New-One
starting of disaster
<br>
This is cool

 <!-- this is the update inside the local device so it is appear in the yellow color with M symbol  -->
 <!-- and shows https://github.com/Prasanta-tech/New-One.git inide the terminal  -->

 <!-- there are 4 types of files when there are something update in the local -->
 <!-- untracked - create the new file
 modified - change something insdide the file olny
 unmodifed - 
 staged - do add but no the commit  -->

 <!-- so we have to do the add then commit  -->

 <!-- git add file name ( for the single file )
 git add. ( all file add) -->

 <!-- for commit
 git commit -m"meaningful message "  -->

<!-- 
 for push to remote 
 git push origin main -->
<!-- where origin refers to the repos name and main is the branch name -->

<!-- from the local to remote 
lets create one directory so come out from the cd that is cd .. then create new one by mkdir name
to delete rm -rf file name
we hv to add the git into the terminal so use the init that is 
then u can check by ls -a , there is .git command 
then add all these files 
make a repos inside the git hub
then introduce that remote repos to the local by 
git remote add origin<link of that repo>
then u can check the current repos by git remote -v
git branch ( to check the branch) - by default the master will come - we hv to rename the brach by main and will changes here only by
git branch -M
then push it  -->

<!-- Git branches  -->
<!-- ----------------
there are 2 devlopers who works independely on the same repo and lastly that 2 features are merge with the main branch  -->

<!-- git branch - check the current branch
git branch -M main - to rename the current to the main brach
git checkout -b feature1 - to create a new branch 
git checkout feature1 - switch tho the feature1 branch
git push origin feature1 - to push not chnge in the main -->

<!-- to compare bet braches , files , repos 
git diff main - compare with the main with the current things may be the brach or something like that
to merge
go to github - pull repos - create a pull request (PR) - it goes to the admin or owner - then he will compare with the main section if everything is write then he accept it - it changes in remote not in the local- to change from the remote to the local -
git pull origin filename(main)

merge conflicts 
it happens when there are diff changes for the same line of code but for the diff branches- this can be check by git merge filename()
it will give some error then we can just change the line of code as per our need , then just pull request  -->

<!-- 
git reset  - if do the add , but want to undo 
git reset HEAD~1 - want to reset the latest commit - it comes before the add mode 
git reset hashlink( available in terminal) -->
<!-- 
to copy a entire repo from other's repo - go to that repo - do fork- which will create the same repo inside your repos profile  -->