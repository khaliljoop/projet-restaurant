…or create a new repository on the command line
echo "# projet-restaurant" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/khaliljoop/projet-restaurant.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/khaliljoop/projet-restaurant.git
git branch -M master
git push -u origin master