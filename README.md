…or create a new repository on the command line
echo "# dominion" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/devops40team2-dominion/dominion.git
git push -u origin main
