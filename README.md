% cat README.md 
# seminar-c-test%      
 
% vi README.md 

% cat README.md 
## seminar-c-test
This is a test repo for Seminar C

% git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

% git add README.md 

% git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md

% git commit -m 'Edit README.md'
[main 187e639] Edit README.md
 1 file changed, 2 insertions(+), 1 deletion(-)
honda@KHs-MBP-16-2024-FFQ1FYDQPY seminar-c-test % git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

% git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:hondaki/seminar-c-test.git
   7443d39..187e639  main -> main

% git remote -v
origin	git@github.com:hondaki/seminar-c-test.git (fetch)
origin	git@github.com:hondaki/seminar-c-test.git (push)


% git pull
Already up to date.
