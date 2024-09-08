echo "# multi-page8hdu893h8u9jy78hju98j434s98yy7" >> README.md
//ACTIVATES SOURCE CONTROL
git init
git add README.md
git commit -m "first commit"

// RENAMES THE CURRENT BRANCH TO MAIN
git branch -M main

// ASSIGNS A URL TO THE ORIGIN VARIABLE
git remote add origin https://github.com/Shannareed/multi-page8hdu893h8u9jy78hju98j434s98yy7.git

//SYNC CHANGES TO GITHUB
git push -u origin main

//ADD CHANGES changes that were made to  THE README file
git add README.md

git config user.name "Shannareed"
git config user.email "shaylashaniya@yahoo.com"
//ADD CHANGES were made in OF ALL FILES and folders
git add .

//CREATE A SAVE POINT AND ATTACH A MEMO TO IT
git commit -m "added user info to read me"

//VIEW THE VALUE OF ORIGIN
git remote -v

//CHANGE THE VALUE OF THE ORIGIN VARIABLE
git remote set-url origin HTTPS://GITHUB.COM/SHANNAREED

//sync from github
git pull --set-upstream origin main

//  COPY THE FILES FROM GITHUB WITH DEFAULT PARAMETERS
git pull