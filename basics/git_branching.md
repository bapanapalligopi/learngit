# Branches
Folder=> (.git) =>master default branch => created when commit happens
![image](https://github.com/user-attachments/assets/adbb481d-1d62-4fb9-ab86-589bfc9b0b74)

The master branch is created locally

Whenever you want to work in isolation for the master branch, create a copy of the master by creating a new branch
# git branch name
Wherever the head is pointing, a branch will be created from the head
![image](https://github.com/user-attachments/assets/29f71db1-1b96-4bd5-bc7c-3b5e1c1f0281)
![image](https://github.com/user-attachments/assets/edc9d081-0a4c-4816-a977-9f2c6a55e027)
#git branch 
give info about local branches
![image](https://github.com/user-attachments/assets/b432f2d1-8ab0-48e0-8080-d62209cfa8e1)
#git branch jatin
![image](https://github.com/user-attachments/assets/5423d061-893c-4dce-9220-8183ba5538eb)
head is at main and jatin , they sink each other
# git checkout branchname
# git checkout jatin
![image](https://github.com/user-attachments/assets/30566056-9cf5-4038-8325-1292fdcf8358)
same files from main or master will avaialable in jatin branch
![image](https://github.com/user-attachments/assets/13894e58-e6b9-4608-9184-3eefba291b38)
added a new thing in a file in Jatin branch, so
jatin branch is one head of master branch
![image](https://github.com/user-attachments/assets/9ccfd3f4-fe1c-4d6e-9ee0-91f0a5bf6473)
main does not reflect the jatin branch
![image](https://github.com/user-attachments/assets/c5bfd420-bb8c-4b3d-8162-7bee838489e7)
![image](https://github.com/user-attachments/assets/7f01834a-de91-42ac-8f47-9795286ff632)
# git switch name same as checkout
# delete a branch
# git branch -d name
![image](https://github.com/user-attachments/assets/a37e5b25-c226-444f-ae97-42c44b10fc09)
# to sink branches
![image](https://github.com/user-attachments/assets/c87d7b9f-13fc-4499-877d-5fa6760e6cc1)
The main branch is one commit behind the Jatin branch
The Jatin branch is one head of main branch
# git merge
One branch commit can combine with another branch
Check out which branch you want to sync with the 
main branch is behind one commit of Jatin, so
Switch to main
![image](https://github.com/user-attachments/assets/eca8bf79-beb8-44fe-8917-3f394274cb29)
![image](https://github.com/user-attachments/assets/77b0c428-f7cd-4e02-9ebd-d5af5b4b42a8)
example2 Switch to master
![image](https://github.com/user-attachments/assets/50bba09f-0635-42cd-a47a-b1d61f58f948)
![image](https://github.com/user-attachments/assets/3fac7c62-8e03-4d41-ad77-5cb59865f1f5)
![image](https://github.com/user-attachments/assets/c708c783-946c-41f3-8978-97a6f4266a4f)
![image](https://github.com/user-attachments/assets/28e8c99d-78fa-4e75-a90e-b7872b81e0a1)
HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice    
$ git status
fatal: not a git repository (or any of the parent directories): .git

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice    
$ git init
Initialized empty Git repository in B:/springSecurityWorkspace/gitpractice/.git/

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git  add .
warning: in the working copy of '.gitattributes', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.mvn/wrapper/maven-wrapper.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mvnw.cmd', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pom.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/java/com/example/demo/GitpracticeApplication.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/resources/application.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/test/java/com/example/demo/GitpracticeApplicationTests.java', LF will be replaced by CRLF the next time Git touches it     

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git commit -m "f1 f2 f3"
[master (root-commit) c923d5c] f1 f2 f3
 12 files changed, 587 insertions(+)
 create mode 100644 .gitattributes
 create mode 100644 .gitignore
 create mode 100644 .mvn/wrapper/maven-wrapper.properties
 create mode 100644 mvnw
 create mode 100644 mvnw.cmd
 create mode 100644 pom.xml
 create mode 100644 src/main/java/com/example/controler/F1.java
 create mode 100644 src/main/java/com/example/controler/F2.java
 create mode 100644 src/main/java/com/example/controler/F3.java
 create mode 100644 src/main/java/com/example/demo/GitpracticeApplication.java  
 create mode 100644 src/main/resources/application.properties
 create mode 100644 src/test/java/com/example/demo/GitpracticeApplicationTests.java

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git branch feature1

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git branch feature2

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git branch -a
  feature1
  feature2
* master

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git checkout feature1
Switched to branch 'feature1'

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ ls
HELP.md  mvnw*  mvnw.cmd  pom.xml  src/  target/

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ git status
On branch feature1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        src/main/java/com/example/controler/Feature1.java

nothing added to commit but untracked files present (use "git add" to track)    

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ git add .

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ git commit -m "feature1"
[feature1 a6f1c40] feature1
 1 file changed, 5 insertions(+)
 create mode 100644 src/main/java/com/example/controler/Feature1.java

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ git log
commit a6f1c40edcb7252fc0e07cd48b68ad02d9df8bf1 (HEAD -> feature1)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:31:03 2025 +0530

    feature1

commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3 (master, feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature1)
$ git checkout master
Switched to branch 'master'

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git log
commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3 (HEAD -> master, feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git merge feature1
Updating c923d5c..a6f1c40
Fast-forward
 src/main/java/com/example/controler/Feature1.java | 5 +++++
 1 file changed, 5 insertions(+)
 create mode 100644 src/main/java/com/example/controler/Feature1.java

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git log
commit a6f1c40edcb7252fc0e07cd48b68ad02d9df8bf1 (HEAD -> master, feature1)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:31:03 2025 +0530

    feature1

commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3 (feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git checkout feature2
Switched to branch 'feature2'

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ ls
HELP.md  mvnw*  mvnw.cmd  pom.xml  src/  target/

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ git status
On branch feature2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        src/main/java/Feature2.java

nothing added to commit but untracked files present (use "git add" to track)    

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ git add .

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ git commit -m "feature2"
[feature2 d9d5795] feature2
 1 file changed, 4 insertions(+)
 create mode 100644 src/main/java/Feature2.java

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ git log
commit d9d5795572b3c00917bdf1b2a13b86b63f83d965 (HEAD -> feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:32:43 2025 +0530

    feature2

commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (feature2)
$ git checkout master
Switched to branch 'master'

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git log
commit a6f1c40edcb7252fc0e07cd48b68ad02d9df8bf1 (HEAD -> master, feature1)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:31:03 2025 +0530

    feature1

commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git merge feature2
Merge made by the 'ort' strategy.
 src/main/java/Feature2.java | 4 ++++
 1 file changed, 4 insertions(+)
 create mode 100644 src/main/java/Feature2.java

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
$ git log
commit 2ae216b42aede184c0d8b82a844f311858accda5 (HEAD -> master)
Merge: a6f1c40 d9d5795
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:33:21 2025 +0530

    Merge branch 'feature2'

commit d9d5795572b3c00917bdf1b2a13b86b63f83d965 (feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:32:43 2025 +0530

    feature2

commit a6f1c40edcb7252fc0e07cd48b68ad02d9df8bf1 (feature1)
commit 2ae216b42aede184c0d8b82a844f311858accda5 (HEAD -> master)
Merge: a6f1c40 d9d5795
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:33:21 2025 +0530

    Merge branch 'feature2'

commit d9d5795572b3c00917bdf1b2a13b86b63f83d965 (feature2)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:32:43 2025 +0530

    feature2
commit a6f1c40edcb7252fc0e07cd48b68ad02d9df8bf1 (feature1)
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:31:03 2025 +0530

    feature1

commit c923d5cd755667d46f416d5e3a6b84a43aeb59c3
Author: Gopi17-Developer <abdabd1703@gmail.com>
Date:   Fri May 9 07:29:34 2025 +0530

    f1 f2 f3

HEMANTH@Bapanapallis-Laptop-17 MINGW64 /b/springSecurityWorkspace/gitpractice (master)
