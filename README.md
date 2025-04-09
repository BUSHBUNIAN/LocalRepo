# LocalRepo
Commands: 
<br>
git init :- To initialize local repository as git repository
<br>
ls -a :- To check all files (Hidden & visible files). If '.git/' file is displayed then git is tracking the file.
<br>
git remote add origin <-link->. Prior running this command, create a repository on Github, then copy the link and use it in the command.
<br>
Now origin(default name of the repositiory on GitHub) is set. To Check what's set as origin, use the command- 'git remote -v'
<br>
We can check in which branch we are currently working on, use the command- 'git branch' . 'main' is set as default branch name on Github. In case, 'master' is set as deafult branch, you've to create a separate 'master' branch and make changes there. Best Alternative, Change the branch name from 'master' to 'main'. To execute this use command- 'git branch -M main'
<br>
Now, your code is ready to be published on GitHub. Use either of the commands- 1. 'git push origin main' 2. 'git push -u origin main' , '-u' flag is used to set the 'origin main' as upstream. Everything that we have to push in future will be pushed to this origin main. We don't have to rewrite 'origin main', we can just write 'git push'.