echo "# flaskdemo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ginnb/cheatsheets.git
git remote add origin https://github.com/ginnb/flaskdemo.git
#git remote remove origin
git push -u origin main
