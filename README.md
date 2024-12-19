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

## BUNDLE 3 EXERCISE 1

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git branch
  dev
  ft/bundle-2
  ft/service-redesign
* ft/team-page
  main
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\team.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "updates on team.html"
[ft/team-page a144391] updates on team.html
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin ft/team-page
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.89 KiB | 386.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout ft/team-page
Switched to branch 'ft/team-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git log --oneline
a144391 (HEAD -> ft/team-page, origin/ft/team-page) updates on team.html
77f2fa8 (ft/service-redesign) updates on readme
b61c852 (origin/ft/service-redesign) resolved merge conflicts
a2cdb9f (origin/main, main, ft/contact-page) different chnages in services
4532efc made chnages in services.html
6eeea5d Merge pull request #1 from Dushimepaulette1/dev
2e1dcc8 (origin/dev, dev) updates on readme.md
d19df2b add team.html
3e1cfd7 added about.html
928e93b added home.html
b2013b6 updated README.md
d611daa created a readme and index.html file
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git cherry-pick <commit-hash>
At line:1 char:17
+ git cherry-pick <commit-hash>
+                 ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>




 git cherry-pick a144391
[ft/contact-page e611aff] updates on team.html
 Date: Wed Dec 18 16:09:33 2024 +0200
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout ft/contact-page
Already on 'ft/contact-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git cherry-pick a144391
On branch ft/contact-page
You are currently cherry-picking commit a144391.
  (all conflicts fixed: run "git cherry-pick --continue")

nothing to commit, working tree clean
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>



PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added contact.html"
[ft/contact-page 0db6519] added contact.html
 Date: Wed Dec 18 16:09:33 2024 +0200
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 contact.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>git push origin ft/contact-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 706 bytes | 176.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git status
On branch ft/contact-page
nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout ft/contact-page
Already on 'ft/contact-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> echo "<!DOCTYPE html><html><head><title>FAQ Page</title></head><body><h1>Frequently Asked Questions</h1></body></html>" > faq.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .\faq.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "added faq.html"
[ft/faq-page 1368769] added faq.html
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 faq.html
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 399 bytes | 79.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout ft/team-page
Switched to branch 'ft/team-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert <commit-hash>
At line:1 char:12
+ git revert <commit-hash>
+            ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
+ git revert <commit-hash>
+            ~
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
The '<' operator is reserved for future use.
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.
   sErrorRecordException
    + FullyQualifiedErrorId : RedirectionNotSupported

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.

PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git revert a144391
[ft/team-page 29adb91] Revert "updates on team.html"
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 345 bytes | 69.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   a144391..29adb91  ft/team-page -> ft/team-page
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```

## BUNDLE 3 exercise 2

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> echo "Updated main branch content" >> main_file.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add main_file.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Update: Changes made to main branch"
[main 6a524a6] Update: Changes made to main branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 main_file.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 342 bytes | 171.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   a2cdb9f..6a524a6  main -> main
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git add resolved_file.txt
fatal: pathspec 'resolved_file.txt' did not match any files
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 echo "Redesigned home page content" >> home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git add home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git add home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Feature: Redesign home page"
[ft/home-page-redesign 9a288bf] Feature: Redesign home page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin ft/home-page-redesign
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 8 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.22 KiB | 418.00 KiB/s, done.
Total 12 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```

## BUNDLE 4 EXERCISE 1

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git remote add git-copy https://github.com/Dushimepaulette1/project-copy.git
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> echo "Updated home page content" >> home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Update: Made changes to the home page"
[main ed33a45] Update: Made changes to the home page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 home_page.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   6a524a6..ed33a45  main -> main
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push git-copy main
remote: Permission to Dushimepaulette1/project-copy.git denied to paulette920.
fatal: unable to access 'https://github.com/Dushimepaulette1/project-copy.git/': The requested URL returned error: 403
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git remote set-url git-copy git@github.com:Dushimepaulette1/project-copy.git
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push git-copy main
Enumerating objects: 29, done.
Counting objects: 100% (29/29), done.
Delta compression using up to 8 threads
Compressing objects: 100% (28/28), done.
Writing objects: 100% (29/29), 4.98 KiB | 1.24 MiB/s, done.
Total 29 (delta 10), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (10/10), done.
To github.com:Dushimepaulette1/project-copy.git
 * [new branch]      main -> main
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```

## BUNDLE 4 EXERCISE 2

```bash
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git add .
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Add initial footer changes"
On branch ft/footer
nothing to commit, working tree clean
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git push origin ft/footer
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout -b ft/footer
fatal: a branch named 'ft/footer' already exists
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 echo "Footer version 1" > footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git add footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Add initial footer implementation"
[ft/footer 2d3fa86] Add initial footer implementation
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 echo "Footer version 2 updates" >> footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git add footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "Update footer with additional details"
[ft/footer d9ccad1] Update footer with additional details
 1 file changed, 0 insertions(+), 0 deletions(-)
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 628 bytes | 314.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
   ed33a45..d9ccad1  ft/footer -> ft/footer
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 # Merge with squash option
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git merge --squash ft/footer
Updating ed33a45..d9ccad1
Fast-forward
Squash commit -- not updating HEAD
 footer.txt | Bin 0 -> 90 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions> git commit -m "footer changes squashing"
[ft/squashing cf1a7c9] footer changes squashing
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 footer.txt
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
 git push origin ft/squashing
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 329 bytes | 329.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/Gym-Git-Exercise-Solutions/pull/new/ft/squashing
remote:
To github.com:Dushimepaulette1/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/squashing -> ft/squashing
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>
```
