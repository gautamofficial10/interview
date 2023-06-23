# interview
This repository is for github practice and interview .


#### Clone the repository

````shell
$ git clone https://github.com/gautamofficial10/interview.git
Cloning into 'interview'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

````

```shell
macos-C1QG65WXMY:interview gkumar6$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.idea/

no changes added to commit (use "git add" and/or "git commit -a")
```


```shell
macos-C1QG65WXMY:interview gkumar6$ git diff README.md
diff --git a/README.md b/README.md
index efa42fd..7c1edc7 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,33 @@
 # interview
-This repository is for github practice and interview prepration .
+This repository is for github practice and interview .
+
+
+#### Clone the repository
+
+````shell
+$ git clone https://github.com/gautamofficial10/interview.git
+Cloning into 'interview'...
+remote: Enumerating objects: 6, done.
+remote: Counting objects: 100% (6/6), done.
+remote: Compressing objects: 100% (3/3), done.
+remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
+Receiving objects: 100% (6/6), done.
+
+````
+
+```shell
+macos-C1QG65WXMY:interview gkumar6$ git status
+On branch main
+Your branch is up to date with 'origin/main'.
+
+Changes not staged for commit:
+  (use "git add <file>..." to update what will be committed)
+  (use "git restore <file>..." to discard changes in working directory)
+       modified:   README.md
+
+Untracked files:
+  (use "git add <file>..." to include in what will be committed)
+       .idea/
+
+no changes added to commit (use "git add" and/or "git commit -a")
+```
```


#### How to push the code to github ?
```shell
macos-C1QG65WXMY:interview gkumar6$ git add .
```

```shell

macos-C1QG65WXMY:interview gkumar6$ git commit -m "Updating Readme File"
[main 7f353bd] Updating Readme File
 8 files changed, 135 insertions(+), 1 deletion(-)
 create mode 100644 .idea/.gitignore
 create mode 100644 .idea/inspectionProfiles/Project_Default.xml
 create mode 100644 .idea/inspectionProfiles/profiles_settings.xml
 create mode 100644 .idea/interview.iml
 create mode 100644 .idea/misc.xml
 create mode 100644 .idea/modules.xml
 create mode 100644 .idea/vcs.xml
macos-C1QG65WXMY:interview gkumar6$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

```


```shell
macos-C1QG65WXMY:interview gkumar6$ git push
Username for 'https://github.com': gautamofficial10@gmail.com
Password for 'https://gautamofficial10@gmail.com@github.com':
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 10 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 2.43 KiB | 497.00 KiB/s, done.
Total 12 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/gautamofficial10/interview.git
   ffac43d..7f353bd  main -> main
```