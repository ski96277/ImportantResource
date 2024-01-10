# Important Resource

## Github

### add project to git
```Language
git add .
```

### add commit
```Language
git commit -m "write your commit here"
```

### push your commit 
```Language
git push origin branch_name
```

### remove a folder or file from git
```Language
git rm -r folder_or_file_name
```

### Show all branch name from remote git
```Language
git branch -r
```
### Check current branch name from  git
```Language
git branch 
```

## Dart Language

### fix Dart syntex
```Language
dart fix --apply
```
## Firebase Flutter website depoly

Firebase deployment flutter web app

Step1: Build web folder ( flutter build web )
Step2: Create New project on firebase
Step3: Register web app on firebase
Step4: Add Firebase sdk script on the build->web folder index.html before the body tag
Step5: Install firebase cli tools (npm install -g firebase-tools)
step6: Now deply the web using cmd
			1. firebase login " firebase login "
			2. firebase init hosting " firebase init "
			3.  Befire run the script go to the firebase.json inside the  web folder and change the public folder to build/web then run the cmd " firebase deploy --only hosting:imransk    "
