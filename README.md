https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

…or create a new repository on the command line
echo "# CSRAgent-Template" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/carlos-isc/CSRAgent-Template.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/carlos-isc/CSRAgent-Template.git
git push -u origin master

