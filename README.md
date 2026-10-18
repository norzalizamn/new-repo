# new-repo

…or create a new repository on the command line
<code>
echo "# test-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/norzalizamn/test-repo.git
git push -u origin main
</code>

…or push an existing repository from the command line
<code>
git remote add origin https://github.com/norzalizamn/test-repo.git
git branch -M main
git push -u origin main
</code>
