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
NS=Non Staging Area
S=Staging area
To check the folder whether it is in NS or S
git does  not track the empty folders
there should at least one file inside a folder to track that folder by git
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
Add mutliple files in staging area
## git add  .
All non empty directories will move to S area.
![image](https://github.com/user-attachments/assets/3f4df67f-56d6-4e43-a2b5-64968f608d9a)
## git add file1 file2
![image](https://github.com/user-attachments/assets/8d415811-ae56-4282-94e5-215d427779bf)
Undo Files From S to NS
Undo of git add for specific files
## git rm --cached file1 file2 ..
![image](https://github.com/user-attachments/assets/526e38e6-1c10-426a-ab88-a529cc9a90f6)


