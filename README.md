# Git Exercise 1

# Gym Git Exercise Solutions

## Exercise 1

```bash
mkdir git-exercise-1
cd git-exercise-1
git init
echo "# Git Exercise 1" > README.md
echo "<h1>Git Exercise 1</h1>" > index.html
git add .
git commit -m "Initial commit with README and index.html"
git branch -m master main
git remote add origin https://github.com/<your-username>/git-exercise-1.git
git push -u origin main
git checkout -b dev
git checkout -b test
git checkout dev
git branch -d test
git push origin main
git push origin dev
```

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
PS C:\Users\Green Way\OneDrive\Desktop\Gym-Git-Exercise-Solutions>



                                                                   git add .\team.html
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

## BUNDLE 6 EXERCISE 1

```bash
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git commit -m "chnaged to restaurant"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git add .
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git commit -m "chnaged to restaurant"
[main 3e30bed] chnaged to restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 344 bytes | 344.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Dushimepaulette1/git-cafe-exercise
   d1d3f9c..3e30bed  main -> main
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git checkout git-cafe-exercise
error: pathspec 'git-cafe-exercise' did not match any file(s) known to git
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git branch
* main
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git checkout -b ft/menu
Switched to a new branch 'ft/menu'
@Dushimepaulette1 ➜ /workspaces/git-cafe-e
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git add menu.html
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git commit -m "Add Menu page with restaurant menu items"
[ft/menu 2b1e6df] Add Menu page with restaurant menu items
 1 file changed, 7 insertions(+)
 create mode 100644 menu.html
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git push origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 428 bytes | 428.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/Dushimepaulette1/git-cafe-exercise
 * [new branch]      ft/menu -> ft/menu
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
        status
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git status
On branch ft/menu
nothing to commit, working tree clean
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git push --set-upstream origin ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.
Everything up-to-date
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git push origin main
Everything up-to-date
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
        status
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git status
On branch ft/menu
Your branch is up to date with 'origin/ft/menu'.

nothing to commit, working tree clean
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git status
On branch ft/menu
Your branch is up to date with 'origin/ft/menu'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   menu.html

no changes added to commit (use "git add" and/or "git commit -a")
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git add .
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git commit -m "modified menu.html"
[ft/menu 1296af2] modified menu.html
 1 file changed, 1 insertion(+), 1 deletion(-)
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Dushimepaulette1/git-cafe-exercise
   2b1e6df..1296af2  ft/menu -> ft/menu
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $
```

## BUNDLE 6 EXERCISE 2

```bash
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git chceckout main
git: 'chceckout' is not a git command. See 'git --help'.

The most similar command is
        checkout
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (ft/menu) $ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (main) $ git checkout -b bugfix/contact
Switched to a new branch 'bugfix/contact'
@Dushimepaulette1 ➜ /workspaces/git-cafe-e
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (bugfix/contact) $ git add index-4.html
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (bugfix/contact) $ git commit -m "Update title to Contact on index-4.html"
[bugfix/contact bd44e58] Update title to Contact on index-4.html
 1 file changed, 1 insertion(+), 1 deletion(-)
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (bugfix/contact) $ git push origin bugfix/contact
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 342 bytes | 342.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bugfix/contact' on GitHub by visiting:
remote:      https://github.com/Dushimepaulette1/git-cafe-exercise/pull/new/bugfix/contact
remote:
To https://github.com/Dushimepaulette1/git-cafe-exercise
 * [new branch]      bugfix/contact -> bugfix/contact
@Dushimepaulette1 ➜ /workspaces/git-cafe-exercise (bugfix/contact) $
```
