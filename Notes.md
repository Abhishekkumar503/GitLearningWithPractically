*In this repo I will go throught all practical GIT command*

For creating fature branches use : **git branch branchName**


for Checking the logs use : **git log** ( for oneLine use : **git log --oneline**)
Example :
abhishekkumar~$git log
commit 8dfd91dd711401e325bd781abdb990b822a35d89 (HEAD -> main, origin/main, RebaseBranch)
Author: Abhishekkumar503 <ak204479@gmail.com>
Date:   Wed Sep 30 23:35:25 2026 +0530

     Add few file to Main Branch
abhishekkumar~$


Adding some files to **RebaseBranch**
Step 1 : Checkout to RebaseBranch 
    Examples
    abhishekkumar~$**git checkout RebaseBranch**
M       Notes.md
Switched to branch 'RebaseBranch'
abhishekkumar~$

Step 2 : Add file  
    Example : abhishekkumar~$**touch rebase.txt**

Step 3 : Adding 1 more commit to ReabaseBranch

Step 4 :



============================================

Error while pushing code to main without orgin to Git ( currently code is avaialbe in local not in origin)
Example :
    abhishekkumar~$git push 
fatal: The current branch RebaseBranch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin RebaseBranch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

To fix this use **git push -u origin RebaseBranch**

After this new Branch will create in origin also
Example : 
abhishekkumar~$git push -u origin RebaseBranch
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 10 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 764 bytes | 764.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'RebaseBranch' on GitHub by visiting:
remote:      https://github.com/Abhishekkumar503/GitLearningWithPractically/pull/new/RebaseBranch
remote: 
To https://github.com/Abhishekkumar503/GitLearningWithPractically.git
 * [new branch]      RebaseBranch -> RebaseBranch
branch 'RebaseBranch' set up to track 'origin/RebaseBranch'.
abhishekkumar~$


