README mixnotes

logs

create on github a void repo

create in local RStudio, a Quarto Project blog with 

> quarto create blog mixnotes

Setup GIT as below

output_dir: docs in _quarto.yml

github enable Pages for publishing /docs

… OK or create a new repository on the command line

echo "# mixnotes" >> README.md

git init 

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/fischerpj/goodrock.git

git push -u origin main