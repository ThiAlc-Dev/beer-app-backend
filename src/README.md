***create a new repository on the command line***
echo "# beer-app-backend" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M "you_branch_name"
git remote add origin https://github.com/ThiAlc-Dev/beer-app-backend.git
git push -u origin "you_branch_name"

***push an existing repository from the command line***
git remote add origin https://github.com/ThiAlc-Dev/beer-app-backend.git
git branch -M "you_branch_name"
git push -u origin "you_branch_name"