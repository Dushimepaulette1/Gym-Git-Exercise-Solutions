# Git Exercise 1

# Gym Git Exercise Solutions

## BUNDLE 1 Exercise 1

```bash
mkdir git-exercise-1
cd git-exercise-1
git init
echo "# Git Exercise 1" > README.md
echo "<h1>Git Exercise 1</h1>" > index.html
git add .
git commit -m "Initial commit with README and index.html"
git branch -m master main
git remote add origin https://github.com/Dushimepaulette1/git-exercise-1.git
git push -u origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
git push origin main
git push origin dev
```

## BUNDLE 1 Exercise 2

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\home.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git adPS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git adPS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\home.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added home.html"
[dev 928e93b] added home.html
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\about.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added about.html"
[dev 3e1cfd7] added about.html
 1 file changed, 11 insertions(+)
 create mode 100644 about.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>git add .\team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "add team.html"
[dev d19df2b] add team.html
 1 file changed, 11 insertions(+)
 create mode 100644 team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash
No local changes to save
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash pop
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash apply
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash list
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git reset --hard
>>
HEAD is now at d19df2b add team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add home.html about.html team.html
>>
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add home.html about.html team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Add initial HTML pages"
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash pop
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash show -p | git apply
>>
No stash entries found.
error: No valid patches in input (allow with "--allow-empty")
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git stash apply
No stash entries found.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
>>
On branch dev
Your branch is ahead of 'origin/dev' by 3 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> ls


    Directory: C:\Users\Green
    Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l        12/18/2024   3:10 PM            243 about.html
-a---l        12/18/2024   3:09 PM            242 home.html
-a---l        12/18/2024   2:36 PM             52 index.html
-a---l        12/18/2024   3:06 PM           1080 README.md
-a---l        12/18/2024   3:11 PM            242 team.html


PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 938 bytes | 156.00 KiB/s, done.
Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   b2013b6..d19df2b  dev -> dev
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git satus
git: 'satus' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>

```

## BUNDLE 2 EXERCISE 2

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout main
>>
Switched to branch 'main'
Your branch is behind 'origin/main' by 6 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git pull origin main
From github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Updating d611daa..6eeea5d
Fast-forward
 README.md  | Bin 38 -> 11342 bytes
 about.html |  11 +++++++++++
 home.html  |  11 +++++++++++
 team.html  |  11 +++++++++++
 4 files changed, 33 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout -b ft/service-redesign
>>
Switched to a new branch 'ft/service-redesign'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\services.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "made chnages in services.html"
[ft/service-redesign 4532efc] made chnages in services.html
 1 file changed, 15 insertions(+)
 create mode 100644 services.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 508 bytes | 254.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\services.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "different chnages in services"
[main a2cdb9f] different chnages in services
 1 file changed, 15 insertions(+)
 create mode 100644 services.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 522 bytes | 130.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   6eeea5d..a2cdb9f  main -> main
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git diff main
diff --git a/services.html b/services.html
index 50f0b4f..2fbe8a1 100644
--- a/services.html
+++ b/services.html
@@ -9,7 +9,7 @@
     <h1>Services</h1>
     <p>
       Our services are very customer friendly and we are willing and happy to
-      have you!!! Welcome!!!!!!!!!!!!!!
+      have you
     </p>
   </body>
 </html>
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git merge main
Auto-merging services.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "resolved merge conflicts"
[ft/service-redesign b61c852] resolved merge conflicts
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 384 bytes | 192.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   4532efc..b61c852  ft/service-redesign -> ft/service-redesign
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```
