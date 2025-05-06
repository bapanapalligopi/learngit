# git init
the default branch will get create is master branch
there will be two areas Non-Staging and Staging
if you commit anything that will be there in Object folrdwe inside .git
remove .git folder (Delete local git repository)
## rm -rf .git/
To change the default branch name by init
## git init --intial-branch=main
![image](https://github.com/user-attachments/assets/6a92f951-e586-4f1b-91bc-6fcb4b00472b)
do not use nested .git folders
# git status
NSA=Non Staging Area
SA=Staging area
To check whether the folder it is in NSA or SA
git does  not track the empty folders
there should at least one file inside a folder to track that folder by git
whenever you do crud ipeartion any file that file info there in NSA
![image](https://github.com/user-attachments/assets/95ecb072-5063-450b-abaa-78cf13c6be05)
## git status -V
-V verbose
verbose detailed info about folder
![image](https://github.com/user-attachments/assets/5a840863-ac03-4abe-be41-caef4d06fffa)
## git status -s
-s short hand info
?? details not aware of perticular folder
![image](https://github.com/user-attachments/assets/6a3bb52d-43bf-4257-8afb-688ea12b2c71)
# git add files
To move NS area files to S area files
## git add index.html
![image](https://github.com/user-attachments/assets/050a8f64-03cb-4e2f-9b70-671167065cb1)
Add multiple files to the staging area
## git add .
All non-empty directories will move to the S area.
![image](https://github.com/user-attachments/assets/3f4df67f-56d6-4e43-a2b5-64968f608d9a)
## git add file1 file2
![image](https://github.com/user-attachments/assets/8d415811-ae56-4282-94e5-215d427779bf)
Undo Files From S to NS
Undo of git add for specific files
## git rm --cached file1 file2 ..
![image](https://github.com/user-attachments/assets/526e38e6-1c10-426a-ab88-a529cc9a90f6)
# git commit
To track all files in the Staging area 
## git commit -m "created files"
![image](https://github.com/user-attachments/assets/d7c7f4a2-8166-4d93-879d-7fbde3323507)
![image](https://github.com/user-attachments/assets/ec330d69-0a7a-4660-8622-0d8a8a6f0b53)
![image](https://github.com/user-attachments/assets/81bda05b-3d8a-4707-a3d4-72469cd49d28)
A commit object will be created with the following details
Who did the commit (user name)
When was the commit done (time)
Commit message
Snapshots of files in the staging area
![image](https://github.com/user-attachments/assets/36436383-6a76-44df-8f2e-3300391833fc)
Snapchat contains all the info about a particular time of that file using the commit ID
A commit object of Snapchat will be created by =using the SHA-1 algorithm 
The moment you do commit, a branch will be created.
![image](https://github.com/user-attachments/assets/3c88a29c-026d-4a70-96f5-e63bbce0738e)
HEAD => pointing to the latest commit
You can change the position of HEAD
If you do another commit, the commit object is again created with reference to previous object
It always goes to the previous commit
and now head point to the latest commit c2
![image](https://github.com/user-attachments/assets/45cb6634-9b36-440c-a909-b3e2b4badd2e)
![image](https://github.com/user-attachments/assets/3eb714b0-702b-43b7-b791-b3e88532f7a1)
![image](https://github.com/user-attachments/assets/db89d0dc-fac0-4cbb-b8e7-c9017ad72070)
To see commit object
Never ever edit commit objects
![image](https://github.com/user-attachments/assets/923d9422-a04e-48df-86ed-128ba5626378)
![image](https://github.com/user-attachments/assets/2dd2949c-17e4-453b-850e-02c0dda22140)

