…or create a new repository on the command line
```shell
echo "# gcr.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/just-do1/gcr.io.git
git push -u origin main
```
                
…or push an existing repository from the command line
```shell
git remote add origin https://github.com/just-do1/gcr.io.git
git branch -M main
git push -u origin main
```
