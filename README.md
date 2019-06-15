# Herako

## Herako installation

The herako installation requires all information to be on github. To do so we have to create the structure in Visual Studio. Make use to open three terminals: powershell, gitbash and python. In gitbash all the git work can be done. In python the script can be created and powershell can be used as normal terminal. 

## Git

In order to create git files the following procedures has be undertaken: 

step 1: create files in visual studio. 

step 2: create new file in visual studio: .gitignore

step 3: open .gitignore and write all files and folders you do not want to include like:
	
	__pycache__/ 
	
	*.pyc                      (compiled python code)  
	
	.DS_Store

step 4: git init in terminal

step 5: git status to see the status

step 6: git add * to add everything

step 7: git add .gitignore to add explicitely this file

step 8: git commit -m "message to be included to later understand the change"

step 9: git remote add origin git@github.com:kkw12/<name-of-repository>.git

step 10:git push -u origin master (to push the masterbranch)


## README file

In gitbash write vim README.md, vim will be opened. press i insert file will be opened. writing can begin # is title, ## header please beaware of the space in between. To insert code do 

```
pip install Flask
python app.py
```

When finished press ECS and write :wq To proceed after do in gitbash: 

git status 

git add README.md 

git commit -m "Added readme"

git push




